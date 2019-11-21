# InfraEngingeer
인프라엔지니어의 교과서

1. 로그를 읽는 기술 <br>
  tail /var/log/nginx/access.log <br>
  tail /var/log/nginx/error.log <br>

  가. nginx 로그출력하기 <br>
    nginx 설정파일 확인 -  /etc/nginx/nginx.conf <br>
     39         # Logging Settings <br>
     40         ## <br>
     41     <br>
     42         access_log /var/log/nginx/access.log; <br>
    <b> 43         error_log /var/log/nginx/error.log; </b> <br>

