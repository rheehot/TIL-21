# class와 id

## ID

* 고유한 속성으로 한 HTML 문서에 하나만 사용이 가능하다.
  * 한개 딱 고유한 속성 -> id 사용 . 클래스를 사용해도된다 이부분은 팀의 룰에 따르면 된다.
* 고유한 ID 값이 있으면 하나하나에 특별한 제어를 할 수 있으며 검색에도 용이하다.

## Class 

* 하나의 HTML문서 안에 중복해서 사용 가능합니다.
* 하나의 태그에 여러개의 다른 class이름을 공백을 기준으로 나열할 수가 있습니다.
* 홈페이지 전체적인 스타일을 일관성있게 지정하기 위해서는 class의 사용이 필수적입니다.



## data 속성과 aria 속성

두 속성은 동일하게 getAttribute() 메소드를 통해 접근할 수 있다.

### 두속성의 차이점

> 서로 스펙으로 추가된 목적 자체가 다르다.

* data-* 속성의 경우 커스텀 속성으로, 데이터 자체를 위함이다.
  * data 속성은 HTML 요소에 추가적으로 데이터를 저장할 수 있게 해준다.
  * id나 class는 의미 부여 data 속성은 데이터 자체를 저장한다는 목적.
* aria-* 속성의 경우는 웹 접근성을 위함이다.



결론적으로 모든 속성들은 그 목적에 맞게 사용하는 것이 좋다.







Reference

* https://www.edwith.org/boostcourse-web/lecture/16670/
* https://mygumi.tistory.com/341