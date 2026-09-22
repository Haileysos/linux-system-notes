# 파일과 디렉토리  

<br>

### 파일의 종류
- 일반 파일 (ordinary file)
  > 데이터를 가지고 있으면서 디스크에 저장된다.
  > - 텍스트파일 : 파일내용이 문자들로 구성
  > - 이진파일 : 텍스트가 아닌 실행파일, 동영상, 이미지 등을 저장

- 디렉토리 또는 폴더 (directory or folder)
  > 파일들을 계층적으로 조직화하는데 사용되는 일종의 특수 파일
  > 디렉토리 내에 파일이나 서브디렉토리들이 존재한다

- 장치 파일 (device special file)
  > 주변장치를 나타내는 내부적인 표현
  > 키보드(stdin), 모니터(stdout), 프린터 등도 파일처럼 사용

- 심볼릭 링크 파일
  > 어떤 파일을 가리키는 또 하나의 경로명을 저장하는 파일

### 디렉토리 계층구조  
리눅스 디렉토리는 루트로부터 시작하여 트리형태의 계층구조를 이룬다.  
<img width="1456" height="816" alt="image" src="https://github.com/user-attachments/assets/77e51532-34fc-40f1-b493-4ec2ee469107" />  

### 홈 디렉토리  
각 사용자마다 할당된 기본 작업/저장 공간  
사용자가 로그인하면 홈 디렉토리에서 작업을 시작함  

### 경로명  
파일이나 디렉토리에 대한 정확한 이름  
- 절대 경로명 (absolute pathname)
  > 루트 디렉토리로부터 시작하여 경로 이름을 정확하게 적는 것

- 상대 경로명 (relative pathname)
  > 현재 작업 디렉토리부터 시작해서 경로 이름을 적는 것

<img width="937" height="681" alt="image" src="https://github.com/user-attachments/assets/61285617-71b5-43fb-b51c-1274927e550b" />  
cs1.txt의 절대 경로명 : /home/chang/test/cs1.txt  
cs1.txt의 상대 경로명 : cs1.txt










