# Test2
"$waitTime=3"을 설정한다.

"$url01=http://www.google.com"을 설정한다.



;# 설명 : 브라우저를 실행 하고 종료함 [ IE, FireFox(FF), Safari(SA), CR(Chrome) ]



브라우저 CR를 생성한다.

"$i=1" 설정 하고, "$i=3" 까지 반복한다. {

 TestProject "$url01" 으로 접속한다. 

 $waitTime 초 대기한다.

}

브라우저를 종료한다.
[출처] 네이버 guitar : 웹 테스트 자동화 툴|작성자 윌링하트
