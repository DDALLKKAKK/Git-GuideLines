# GuideLines

## Git을 설치해봅시다.  
### [ 나는 Window OS를 사용합니다. ]
1. ```terminal``` 또는 ```터미널```을 윈도우 검색창에 검색합니다.  
**(중요! powershell이 아닌 terminal로 실행해야 합니다!!!!!!)**
2. ```winget install --id Git.Git -e``` 입력
3. 모든 옵션 동의(```y``` 입력)
4. 다 설치가 되었다면 기존 터미널 종료 후, 새 터미널 실행  
**(중요! 기존 terminal이 아닌 꼭 새 terminal로 실행해야 합니다!!!!!)**
5. ```git --version```을 새 터미널에서 실행  
(만일 ```git version 2.47.0``` 출력 시 성공{꼭 해당 버전이 아니어도 됨.}, ```command not found``` 출력 시 터미널 재부팅)  
### [ 나는 Mac OS를 사용합니다. ]
1. ```spotlight```를 실행합니다.
2. ```xcode-select --install```를 입력합니다.
3. 모든 옵션 동의(```y``` 입력)
4. 다 설치가 되었다면 기존 spotlight 종료 후, 새 spotlight 실행  
**(중요! 기존 spotlight이 아닌 꼭 새 spotlight로 실행해야 합니다!!!!!)**
5. ```git --version```을 새 터미널에서 실행
(만일 ```git version 2.47.0``` 출력 시 성공{꼭 해당 버전이 아니어도 됨.}, ```command not found``` 출력 시 spotlight 재부팅)
---
## Git과 Github를 연결해봅시다.
### [ 나는 Window OS를 사용합니다. ]
1. ```terminal``` 또는 ```터미널```을 윈도우 검색창에 검색합니다.  
**(중요! powershell이 아닌 terminal로 실행해야 합니다!!!!!!)**
2. ```winget install --id Github.cli``` 입력
3. 모든 옵션 아래와 같이 설정하세요.  
<pre><code>? Where do you use GitHub?
  > GitHub.com
? Preferred protocol?
  > HTTPS
? How to authenticate?
  > Login with a web browser</code></pre>
3. ```gh auth login``` 입력
4. 다 완료되었다면 기존 터미널 종료 후, 새 터미널 실행  
**(중요! 기존 terminal이 아닌 꼭 새 terminal로 실행해야 합니다!!!!!)**
5. ```git --version```을 새 터미널에서 실행
### [ 나는 Mac OS를 사용합니다. ]
1. ```spotlight```를 실행합니다.
2. ```brew install gh```를 입력합니다.
3. 모든 옵션 아래와 같이 설정하세요.  
<pre><code>? Where do you use GitHub?
  > GitHub.com
? Preferred protocol?
  > HTTPS
? How to authenticate?
  > Login with a web browser</code></pre>
4. 다 완료되었다면 기존 spotlight 종료 후, 새 spotlight 실행  
**(중요! 기존 spotlight이 아닌 꼭 새 spotlight로 실행해야 합니다!!!!!)**
5.  ```git --version```을 새 터미널에서 실행
---
## Git 초기실행을 마쳐봅시다.
1. ```git config --global user.name "username"``` 입력
**(중요!, ```username```을 본인 github username으로 대체하세요. 쌍따옴표는 그대로 유지.)**
2. ```git config --global user.email "you@example.com"``` 입력  
**(중요!, ```you@example.com```을 회원가입을 진행한 이메일로 대체하세요. 쌍따옴표는 그대로 유지.)**
3. ```git config --global init.defaultBranch main``` 입력
4. ```git config --list``` 입력  
(해당 출력값에서 본인 입력값과 차이 확인할 것.)
