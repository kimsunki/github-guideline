# github-guideline

1. github 사이트
   https://desktop.github.com/
   -> 프로그래밍 이나 다른 여타의 작업을 한 후 저장할 수 있는 저장공간 서비스를 제공해 주는 사이트

2. Ubuntu에 git 설치하기
   sudo apt-get install git 
  
3. CentOS
   su
   yum install git

4. github 사용방법

   mkdir ~/workspace
   cd ~/workspace
   git status
   git init
   git status
   git config --global user.name [유저이름]
   git config --global user.email [이메일주소]
   git remote add origin https://github.com/kowonsik/raspberry.git
   git pull -u origin master     # 파일 다운로드
   git add [생성한파일]
   git status
   git commit -m "메세지"
   git status
   git push -u origin master
   
2.

