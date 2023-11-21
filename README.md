*git & github 순서 

초기 디렉터리 생성 시 순서 
1. git init 저장소 등록 
2. git branch -M main 으로 변경 
3. git remote add origin https 주소 붙여넣기

--------------------------------------------------

*<초기 디렉터리 생성 후 작업 진행 시 순서>

1. git add란? 
= 현재 디렉터리 안 모든 파일과 폴더를 뜻함 
2. git commit -m 'message' - > 가능하면 영어를 추천 짧게 키워드 적기 가능. 
현재 스테이징된 파일의 기록명을 작성 (영어, 한글 모두 가능)
짧게 작성하기 

ex) 쇼핑몰 상품 페이지를 만들었다면

git commit -m 'shp=product end'
git commit -m '쇼핑몰 남자옷 완성'

3. git push origin main 해석 
 origin == gitHub 주소 
 main == local 내 컴퓨터 위치 
해석 == github에 local 작업물을 push 하겠다.

-----------------------------------------------

*위 add - > commit -> push 순서 중간 중간 작업 확인 리눅스 명령어 

1. git status 
local 과 stageing 상태에서 작업물의 등록 상태 체크 
2. git log 
commit 과 push 상태에서 작업물의 commit 기록과 업로드 정보체크 
11월21일
----------------------------------------------------------------

