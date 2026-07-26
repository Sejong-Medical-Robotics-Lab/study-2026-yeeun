# Day1 3.7 mission3  Record

```bash
$cd ~/robot_study/week1
$ for i in $(seq 1 100); do echo "[INFO] step $i: joint state ok" >> robot.log; done
$ echo "[ERROR] step 41: motor 3 overheat" >> robot.log
$ echo "[WARN] step 77: battery low (18%)" >> robot.log
$ wc -l robot.log
102 robot.log
$ tail -n 5 robot.log
[INFO] step 98: joint state ok
[INFO] step 99: joint state ok
[INFO] step 100: joint state ok
[ERROR] step 41: motor 3 overheat
[WARN] step 77: battery low (18%)
$ grep ERROR robot.log
[ERROR] step 41: motor 3 overheat
$ grep -n "motor 3" robot.log
101:[ERROR] step 41: motor 3 overheat
