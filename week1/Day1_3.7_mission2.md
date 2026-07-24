# Day1 3.7 mission2 record

```bash
$mkdir data backup$ touch data/exp_01.csv data/exp_02.csv data/exp_03.csv data/memo.txt
$ ls data
exp_01.csv  exp_02.csv  exp_03.csv  memo.txt
$ cp data/exp_*.csv backup/
$ mv data/memo.txt data/note.txt
$rm backup/exp_03.csv$ ls -al data backup
backup:
total 8
drwxrwxr-x 2 yeeee yeeee 4096  7월 24 21:30 .
drwxrwxr-x 7 yeeee yeeee 4096  7월 24 21:27 ..
-rw-rw-r-- 1 yeeee yeeee    0  7월 24 21:29 exp_01.csv
-rw-rw-r-- 1 yeeee yeeee    0  7월 24 21:29 exp_02.csv

data:
total 8
drwxrwxr-x 2 yeeee yeeee 4096  7월 24 21:30 .
drwxrwxr-x 7 yeeee yeeee 4096  7월 24 21:27 ..
-rw-rw-r-- 1 yeeee yeeee    0  7월 24 21:27 exp_01.csv
-rw-rw-r-- 1 yeeee yeeee    0  7월 24 21:27 exp_02.csv
-rw-rw-r-- 1 yeeee yeeee    0  7월 24 21:27 exp_03.csv
-rw-rw-r-- 1 yeeee yeeee    0  7월 24 21:27 note.txt
