# github_connect

## 🌼 [Git 설치](https://git-scm.com/download/win) 🌼

### 한 번만 설정해도 되는 것
      
      📌git을 통해서 github과 연결할 수 있다.
      
     ▪️ git hub에 올려야 할 폴더에 가서 쉬+우클릭 하여 PowerShell 창열기
     ▪️ 해당 창에 git init 이라고 입력 -> .git 폴더📁가 생성된다
     
     
      📌git 설치 후 git bash 열기
    
    ![image](https://user-images.githubusercontent.com/129706765/235417931-2770a1eb-14f2-4b25-8da0-ad8d39670997.png)
     ▪️ git bash에 유저 이름 설정💁‍♀️-> git config --global user.name "naye"

     ▪️ 유저 이메일 설정📧 (git hub에 등록했던 이메일과 같아야한다) -> git config --global user.email "0849_yoonln@naver.com"
     
     ▪️ 본인 정보 확인 -> git config --list
     
     ⚠️연결이 잘 되었는지 확인하기
      
     ▪️ git remote -v
      


### git hub에 코드 업로드 하기
      
      📌초기화 작업
            ▪️ git init
            
      📌추가 할 파일 (폴더 안의 내용을 모두 올림/ .은 모든 파일을 의미)
            ▪️ git add .
      
      📌히스토리 만들기
            ▪️ git commit -m "first commit" / m은 메세지를 의미 "" 안에는 히스토리의 이름을 적음
      
      📌git hub에 repositories를 만들고 그 주소와 연결하기    
            ▪️ git remote add origin https://github.com/Nayeye/css_flex.git
            
      📌git hub에 올리기 
            ▪️ git push origin master
