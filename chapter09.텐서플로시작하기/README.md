## tensorflow설치 참고하기
- https://tensorflow.blog/%EC%9C%88%EB%8F%84%EC%9A%B0%EC%A6%88%EC%97%90-%EC%95%84%EB%82%98%EC%BD%98%EB%8B%A4-%ED%85%90%EC%84%9C%ED%94%8C%EB%A1%9C%EC%9A%B0-%EC%84%A4%EC%B9%98%ED%95%98%EA%B8%B0/
- 단, 위와 같이 conda에 설치했을 경우, anaconda prompt를 통해 jupyter에 접속해야 한다. local에서는 설치가 되지 않았기 때문에 접속이 되지 않을 수 있다. 

- 만일, conda 혹은 python과 tensorflow버전이 맞지 않으면 session을 지원하지 않는다. 이럴 경우는 pip --upgrade를 해줘야 한다. 

- 혹은 google colab을  사용하면 별도의 설치없이, 버전을 지정하고 import해주면 된다. 
```python
%tensorflow_version 2.x #버전지정
import tensorflow as tf #모듈 설치
print(tf.__version__)
```

- 기본 tensorflow문법 확인하기 : https://m.blog.naver.com/PostView.nhn?blogId=infoefficien&logNo=221085823517&proxyReferer=https%3A%2F%2Fwww.google.com%2F
(google colab으로 예제 문제 반드시 확인하기)
