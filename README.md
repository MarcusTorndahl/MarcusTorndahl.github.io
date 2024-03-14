# marcustorndahl.github.io

The scope of this blog is to primarily focus on software development.

## Linux

Find current working directory of a running process
```bash
$ pwdx <PID>

$ lsof -p <PID> | grep cwd

$ readlink -e /proc/<PID>/cwd
```

## WSL - Windows Subsystem for Linux

Find WSL directory from Windows Explorer
```cmd
$ dir \\wsl$\<distribution>
```

Open up the Windows Explorer with the current directory from WSL terminal
```bash
$ explorer.exe .
```

Change directory to host root dircetory from WSL terminal
```bash
$ cd /mnt/c
```
