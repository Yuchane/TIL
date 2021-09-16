# Git

## -분산 버전 관리 시스템

- 코드의 히스토리(버전)을 관리하는 도구

- 개발 되어온 과정 파악 가능

- 이전 버전과의 변경 사항 비교 및 분석

### 깃은 변경 사항 만을 저장

- 용량부담 감소

- 속도가 조금 빠름

  

  ### 깃(분산 버전 관리 시스템) 과 깃허브(깃 기반의 저장소)는 서로 다름



# Git은 명령어를 통해서  사용

## CLI(Comand-Line Interface)  

ex)cmd 창

## <->GUI

# powershell

윈도우에서 Unix/Linux 명령어 일부 사용가능

# 간단한 Unix/Linux 명령어

>- 현재 위치의 폴더, 파일 목록보기 ls
>
>- 현재 위치 이동하기 cd<path> 
>
>- cd ../<path>/ 현재 위치에서 하나 상위 <path>로 이동하는 명령어
>
>- <path> .. 상위폴더로 이동
>
>- 폴더 생성하기  mkdir 폴더이름 
>
>- 파일 생성하기 touch 파일이름
>
>- 삭제하기 rm 이름 (파일만 삭제가능), rm -r 디렉토리이름(폴더삭제 가능)
>
>- 화면 지우기 clear
>
>  





# Repository

특정 디렉토리를 버전 관리하는 저장소

- git init 명령어로 로컬 저장소를 생성 /local Repository
- .git 디텍토리에 버전관리에 필요한 모든게 들어있음

특정 버전으로 남긴다 = "커밋(Commit)한다"

## Commit

> - Wroking Directory 내가 작업하고 있는 실제 디렉토리			.git 이 있는 디렉토리		
>
> - Staging Area 커밋(commit)으로 남기고 싶은, 
>
> ​					 특정 버전으로 관리하고 싶은 파일이 있는 곳                git add 를 이용해서 만듬
>
> - Repository	커밋(commit)들이 저장되는 곳				   
>
>     git commit을 이용해서 스테이징 에어리어에 있는 파일들을 레퍼지토리에 저장

## git status

> 깃이 관리하고 있는 파일들이 어떤 상태인지 보여줌

## git add.

> 한번에 스테이징 에어리어에 올려준다
>
> . 하나는 현재 폴더라는 의미

## git commit -m " "

> 커밋에 메세지 남기기
>
> 커밋에 메세지는 최대한 자세하게

## git config

## git config --global --list



## git log

> 내가 지금까지 남긴 커밋(commit)에 대한 히스토리를 보여줌



## git init 

> git 저장소 생성

## git diff (commit ID) (commit  ID)

>두 커밋 간에 차이를 보여줌
>
>앞에 아이디를 기준으로 설명
>
>커밋 아이디 앞에 4자리까지만 적으면 됌



# git hub

> Public : 누구나 다 내가 올린 소스를 이용가능. 올리는건 불가능
>
> Private : 나만 이용가능

## 깃허브 레퍼지토리와 로컬 레퍼지토리를 연결하기

> ## git remote add origin{remote_repo(주소)} : 
>
> > 리모트 레퍼지토리를 더해줌. 오리진 이라는 이름으로 리모트_레포를 더해줌

				## 		   git push -u origin master   : 

​							내 마스터에 있는 모든 커밋을 깃허브에 올림 

​			

### *파일을 올린다고 생각하면 안됨, commit 단위로 올리는 것임



## TIL

Today I learned 오늘 배운 내용 정리

-매일 내가 배운 것을 마크다운으로 정리해서 문서화 하는 것





