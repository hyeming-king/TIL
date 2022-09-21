# Today I Learned
------
깃의 기능을 꾸준히 사용해보기 위해 앞으로 **TIL**을 작성하기로 하였습니다.:fire:
- 그날의 기억할만한 내용을 가볍게 정리합니다.
- 적게 공부한 날이여도 무조건 1일 커밋 진행할 것!

<br>

 #### [TIL220921] - 리눅스, vim, git 기초 명령어
> **리눅스 커멘트라인 기초**
- `pwd` : 현재 저장소 위치 (print working)
- `cd` : 현재 저장소 위치를 변경하라 (change directory)
- `ls` : 디렉토리 안에 있는 내용을 확인한다. (list)
   - ls 뒤에는 -a, -l 옵션을 붙일 수 있음.
> **git 사용 명령어**
1) `git status` : 수정한 파일 확인가능
    commit 하지 않은 파일이 있는 지 확인하기 좋음
2) `git add FILENAME` : 커밋 대기 상태로 만듬
3) `git commit -m "VERSION"`: 실제로 커밋 버전을 만듬
4) `git log`: 제대로 커밋 되었는지 확인
3) `git push`: 저장소에 내용 업로드 하기