# learning-podman

## Installing podman on Fedora 36

1. Install the `podman` package.

```bash
# sudo dnf list podman
# sudo dnf install podman
```

2. Verify podman is installed and functioning.

```bash
$ podman -v
podman version 4.1.0

# podman run hello-world
...
!... Hello Podman World ...!

         .--"--.
       / -     - \
      / (O)   (O) \
   ~~~| -=(,Y,)=- |
    .---. /`  \   |~~
 ~/  o  o \~~~~.----. ~~
  | =(X)= |~  / (O (O) \
   ~~~~~~~  ~| =(Y_)=-  |
  ~~~~    ~~~|   U      |~~

Project:   https://github.com/containers/podman
Website:   https://podman.io
Documents: https://docs.podman.io
Twitter:   @Podman_io
```
