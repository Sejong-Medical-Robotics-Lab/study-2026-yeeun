# Day1 3.7 challenge mission record

```bash
$ nano new_exp.sh
#아래 내용 작성
#mkdir -p ~/robot_study/experiments/$1/{data,logs,results}
#echo "# 실험 노트: $1 ($(date +%F))" > ~/robot_study/experiments/$1/README.md
#echo "실험 폴더 생성 완료: $1"
$ chmod +x new_exp.sh 
$ ./new_exp.sh go2_walk_test 
실험 폴더 생성 완료: go2_walk_test
$ ls -R ~/robot_study/experiments 
/home/yeeee/robot_study/experiments:
go2_walk_test

/home/yeeee/robot_study/experiments/go2_walk_test:
README.md  data  logs  results

/home/yeeee/robot_study/experiments/go2_walk_test/data:

/home/yeeee/robot_study/experiments/go2_walk_test/logs:

/home/yeeee/robot_study/experiments/go2_walk_test/results:
~/robot_study/week1$ 
