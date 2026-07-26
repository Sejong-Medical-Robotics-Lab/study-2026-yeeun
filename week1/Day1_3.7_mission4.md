# Day1 3.7 mission 4 record

```bash
[Terminal 1]
$ sleep 600
Terminated  #중단

[Terminal 2]
$ ps aux | grep sleep
yeeee      29229  0.0  0.0   9684  2020 pts/1    S+   16:23   0:00 sleep 600
yeeee      29330  0.0  0.0  10392  2536 pts/2    S+   16:26   0:00 grep --color=auto sleep
$ kill 29229

