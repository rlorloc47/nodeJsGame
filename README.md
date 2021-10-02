# nodejs를 이용하여 간단한 게임 제작

## 개발환경
+ vscode
+ MySQL
+ Python

### 메뉴명
1. 로그인 및 회원가입 페이지
+ 닉네임/비밀번호 방식으로 로그인 및 회원가입을 진행
+ 로그인을 하지 않으면 게임을 진행 할 수 없음 ('로그인이 필요합니다'라는 alert 이후 로그인 페이지로 이동됨)
+ ![로그인 회원가입 페이지](https://user-images.githubusercontent.com/89571328/135485393-2bf55646-ee20-47c0-9f48-383b18b95164.png)
+ ![로그아웃페이지](https://user-images.githubusercontent.com/89571328/135485334-627c89e4-3596-4fb7-95a1-241d3ef931a5.png)

2. 단어비게임
+ 새로운 단어가 지속적으로 상단에서 추가되면서 하단으로 밀려난 단어가 특정 위치에 닿으면 게임종료
+ 단어와 동일하게 타자를 입력하면 해당 단어 삭제됨.
+ 타자를 입력하면 현재까지의 등수를 우측에 표시해줌.
+ ![단어비 게임](https://user-images.githubusercontent.com/89571328/135485086-8e8d22b1-8b5f-4f87-a88c-822b12b64315.png)