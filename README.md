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
   git config --global user.email [이메일주소] // 해당 github 에 만든 name과 email에 접근 
   git remote add origin https://github.com/kimsunki/레파지토리명.git // 내가만든 github 레파지토리를 추가
   
   < url을 잘못입력 했을 경우 >
     git remote rm origin
     git remote rename origin origin_re
   
   git pull -u origin master     # 파일 다운로드 // 밀어넣는것임 
   git add [생성한파일]  
   git status
   git commit -m "메세지"
   git status
   git push -u origin master
   
   < url return error가 발생한 경우 >
     git remote set-url origin git@github.com:kowonsik/레포지터리이름.git
   
   < public key error가 발생한 경우 >
     ubuntu에서 github로 데이터 & 파일을 보낼경우 github로 데이터를 보낼수 있는 접근권한을 가지려면 ssh라고하는 암호화 과정을      거쳐야 하는데 이 과정이 되지 않을 것임

5.

