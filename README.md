# JWT 로그인 api 서버
실제 REST API 서버와 최대한 유사한 것을 한번 만들어보기 위해 도전해 보았습니다. JWT를 이용하여 로그인을 구현하였습니다. 

# 앞으로 해보면 좋을 것
현재 access token만을 이용하여 인증을 하였습니다. 하지만 보안 상의 이유로 access token의 유효시간을 굉장히 짧게 설정하는 것으로 알고 있습니다. 이에 따라 인증이 중간에 끊기지 않기 위한 유효기간이 더 긴 refresh 토큰 또한 access token과 함께 발급해야하므로 다음에는 조금 더 완전한 토큰 인증방식 로그인을 구현해봐야할 것 같습니다
