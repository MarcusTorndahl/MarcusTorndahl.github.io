# marcustorndahl.github.io

The scope of this blog is to primarily focus on software development.

## Linux

Find current working directory of a running process
```bash
$ pwdx <PID>

$ lsof -p <PID> | grep cwd

$ readlink -e /proc/<PID>/cwd
```
