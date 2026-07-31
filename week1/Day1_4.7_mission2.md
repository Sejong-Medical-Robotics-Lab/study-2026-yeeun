# Day1 4.7 mission2 record

```bash
cd ~/robot_study/study-2026-gildong
git status # ① 깨끗한 상태 확인
mkdir week1 && cp ~/robot_study/week1/new_exp.sh week1/
echo "- 3장 Linux 실습 완료" >> README.md
git status # ② 빨간색: 아직 스테이지 전
git diff 
git add .
git status # ③ 초록색: 스테이지 완료
git commit -m "feat: add week1 shell script practice"
git log --oneline 
git push origin main
```

① 깨끗한 상태 : 수정되거나 추가된 파일이 없음
② 스테이지 전 : 새로 생성된 폴더와 수정된 파일이 추적되지 않아 빨간색 파일 목록으로 출력
③ 스테이지 완료 : 명령어로 커밋 대기 상태로 들어가 초록색 파일 목록으로 출력
