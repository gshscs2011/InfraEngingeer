# InfraEngingeer
인프라엔지니어의 교과서

1. 로그를 읽는 기술 <br>
  tail /var/log/nginx/access.log <br>
  tail /var/log/nginx/error.log <br>

  가. nginx 로그출력하기
    nginx 설정파일 확인 -  /etc/nginx/nginx.conf
     39         # Logging Settings
     40         ##
     41 
     42         access_log /var/log/nginx/access.log;
    <b> 43         error_log /var/log/nginx/error.log; </b>

