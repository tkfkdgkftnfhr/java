## == 와 equals의 차이

* 예를 들어 1과 2를 비교한다 했을 때, 1 == 2와 a.equals(b)의 차이는 뭘까? 바로 동등하다는 기준이 다르다는 것이다.  

  무슨말이냐면, 1 == 2의 경우는 두 정수 객체의 **참조 동등성을 보고(주소값)** a.equals(b)는 a와 b가 같은 객체이건 다른 객체이건 상관없이
  
  **두 객체가 서로 저장하고 있는 데이터의 동일여부**를 기준으로 비교한다.
