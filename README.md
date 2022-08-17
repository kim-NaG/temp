## 프로그래밍 정보 ##  
사용도메인    : www.petglet.com
사용 공인 IP  : 211.110.64.66
사무실 IP - 14.36.46.90(고정)  121.65.132.178(유동) 

유지보수를 위해 최대한 CI기본 구조를 유지하며 작업
MVC 패턴 유지. Model구조 유지.
내부적으로 사용하는 변수와 입력받는 데이타의 변수는 소문자(단, DB직접찾는 array는 대문자로 받는다.), MYSQL관련은 대문자
## 프로그래밍 정보 ##  



## 초기설정 시 ##
  .env url 수정
  /app/Config/App.php  : URL 수정
  /app/Config/Constants.php  : ENC_KEY_128, TOKEN_EXPIRED_DATE REFRESH_TOKEN_EXPIRED_DATE 관련 정보 수정
  /app/Config/Database.php  : DB접속 정보 수정
  /app/Config/Routes.php  : Routes 정보 수정
  /app/Config/Encryption.php : 26번째 줄  public $key 변경
  
  폴더 775 , 파일 755, write folder 707

## 초기설정 시 ### temp
