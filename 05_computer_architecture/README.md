1) ps -eaf
apdmg 739 /usr/bin/mintty (ответ: 739)


2) Значение текущего Shell-процесса: ps -p 
PID PPID PGID WINPID TTY   UID     STIME     COMMAND
740 739  740  7936   pty0  197609  11:07:43  /usr/bin/bash (ответ: 740)

3)ps -a --all
 PID    PPID    PGID     WINPID   TTY         UID    STIME COMMAND
 739       1     739       7180  ?         197609 11:07:43 /usr/bin/mintty
 740     739     740       7936  pty0      197609 11:07:43 /usr/bin/bash
 784     740     784       9936  pty0      197609 11:14:21 /usr/bin/ps
(ответ: 3)