## Step 1. 폴더 만들기
- C:\ 로 이동
- 1Day SQL (Setup) 폴더 생성 후 해당 폴더로 이동
- 시스템 종류에 따라 Win32 또는 Win64 폴더 생성

## Step 2. 필수 프로그램 다운로드
- 다운로드 1. 오라클 XE 다운로드
  + URL: https://www.oracle.com/database/technologies/xe-prior-releases.html
  + 계정 생성 필요
    * ID: your_email
    * PW: your_password

- 다운로드 2. JDK 다운로드
  + URL: https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html
  + 위치: Java SE Development Kit 8u201
  + 파일: jdk-8u201-windows-i586.exe

-다운로드 3. SQL Developer
  + URL: https://www.oracle.com/tools/downloads/sqldev-v192-downloads.html
  + 위 프로그램들을 모두 C:\1Day SQL (Setup)\ 하단에 옮겨놓는다. 


## Step 3. 실습용 스크립트 파일 다운로드
- 다운로드 1. 실습용 스크립트 파일 다운로드
  + URL: http://gangchon.com/file/1DaySQL/1Day_SQL_Script.exe
- 옮겨 놓은 후에는 더블클릭으로 해당 파일을 실행하면, 자동으로 폴더 및 파일이 생성이 된다. 

## Step 4. 환경설정
- 오라클 XE 설치 및 환경설정
  + OracleXE 파일의 압축을 푼다. 
  + setup.exe 파일을 실행한다. 
  + 중간에 패스워드 입력창이 나오면 “oneday”를 입력한다. 
  + 중요: 시스템파일 중 host 파일을 수정해야 하는데, 이 때, [알약]-[환경설정]-[호스트] 파일 보호 해제
  + C:\Windonws\System32\drivers\etc 에서 127.0.0.1  localhost 주석 해제
  + Chrome에서 http://127.0.0.1:8080/apex/f?p=4950 접속하여 확인한다. 
