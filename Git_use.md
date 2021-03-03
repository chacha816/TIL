### Git bash 사용법 떠올리기

1) 원격 저장소(remote repository)와 로컬저장소 연결

* git clone : Github에 있던 저장소를 로컬로 복사

~~~
git clone "원격 저장소 URL"
git clone https://github.com/.....
~~~

* git status : 디렉토리 확인
* git remote -v : 로컬과 원격 저장소 연결

~~~
git remote add '별칭' '원격 저장소URL'
git remote add TIL https://github.com/.....
~~~



2) 로컬에서 원격으로 보내기

* MD or 파일 작성
* git status로 아직 commit 안된 파일이 있는지 확인(빨간색)
* git add  : 파일 추가

~~~
git add '파일이름'    # md,text 등
git add .     # 폴더에 있는 파일 전체 추가
git add README.md
~~~

* git commit : repository에 커밋

~~~
git commit -m '간단한 설명'
git commit -m 'week 1'
~~~

* git log : 커밋 내역 확인
* girt remote add '별칭' '원격 저장소URL'
* git remote -v

~~~
<원격저장소 삭제하는 방법>
git remote remove '별칭'
git remote remove origin
~~~

* git push

~~~
git push -u origin 'branches명'
git push -u origin master
git push -u origin main
~~~



* push 실행 후, Github 유저네임과 비번 입력하면 완료!

