# git-command

## 특정일 로그 찾기  

* git log --before="2022-04-27" (2022-04-27 이전의 커밋 조회)
* --since, --after (명시한 날짜 이후의 커밋만 검색)
* --until, --before (명시한 날짜 이전의 커밋만 조회)
 

## 특정파일의 로그 찾기 

* git log --all --full-history -- "**/img_prod03_1@2x.png" 
* git log --all --full-history -- "경로/파일명" 

 

 

## 커밋 취소 

* git reset --soft HEAD^ 


## 브랜치를 안따고 main에서 작업하는데 충돌남 

* git stash (임시저장) 
* git pull origin main (main 브랜치 pull받기) 
* git stash list  (stash 리스트 확인) 
* git stash apply (가장 최근꺼 적용하기) 
* git stash drop (가장 최근꺼 제거) 
* git stash pop (apply과 drop 동시에)
