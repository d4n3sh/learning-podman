## Running a simple nginx pod

1. Create and run a nginx server on port 8080.

```bash
# podman run -p 8080:80 docker.io/library/nginx:latest
...
...
2022/05/09 00:01:19 [notice] 1#1: built by gcc 10.2.1 20210110 (Debian 10.2.1-6)
2022/05/09 00:01:19 [notice] 1#1: OS: Linux 5.17.0-0.rc7.116.fc36.x86_64
2022/05/09 00:01:19 [notice] 1#1: getrlimit(RLIMIT_NOFILE): 524288:524288
2022/05/09 00:01:19 [notice] 1#1: start worker processes
2022/05/09 00:01:19 [notice] 1#1: start worker process 26
```

2. Verify nginx is running.

```bash
# curl 127.0.0.1:8080
<!DOCTYPE html>
<html>
<head>
<title>Welcome to nginx!</title>
<style>
html { color-scheme: light dark; }
body { width: 35em; margin: 0 auto;
font-family: Tahoma, Verdana, Arial, sans-serif; }
</style>
</head>
<body>
<h1>Welcome to nginx!</h1>
<p>If you see this page, the nginx web server is successfully installed and
working. Further configuration is required.</p>

<p>For online documentation and support please refer to
<a href="http://nginx.org/">nginx.org</a>.<br/>
Commercial support is available at
<a href="http://nginx.com/">nginx.com</a>.</p>

<p><em>Thank you for using nginx.</em></p>
</body>
</html>
```
