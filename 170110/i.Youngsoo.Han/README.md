1. RAM은 어떤 단어들의 약자이며, 왜 RAM이라고 부르게 되었을까?
----

> * Ram은 어떤것의 약자일까요?
 - Random Access Memory

> * 왜 RAM이라고 부르죠?
 - 어느 위치에 있는 데이터든지 접근하는 시간이 같아서 Random Acces라는 이름이 붙었습니다. 반면에 보조기억장치는 데이터에 접근하는 시간이 모두 다릅니다.


2. 한글을 표현할 수 있는 문자 인코딩 방식에는 무엇이 있을까? 각각의 장단점도 조사해 보세요
----

> * UTF-8  
 - 장점       
    * 모든 유니코드 문자를 표현 할 수 있습니다.  
    * 문자 조합형으로 추가되는 문자에 대한 부담이 없습니다.  
    * 인코딩에 간단한 연산만 사용하므로 효율적이다.  
    * 바이트 단위 문자열 검색 알고리즘을 사용 할 수 있다.  
 - 단점   
    * 한중일 문자들과 표의 문자를 제외한 거의 모든 기존 인코딩들은 한 문자에 1바이트를 사용하므로 문자열 처리가 간편한 반면, UTF-8은 그렇지 않다.  
    * 대부분의 UTF-8 문자열은 일반적으로 적당한 기존 인코딩으로 표현한 문자열보다 더 크다.  
    
> * EUC-KR  
 - 장점       
    * 한글,영어 전용 홈페이지에 적당합니다.  
    * UTF-8 방식에 비해 적은 메모리가 사용됩니다.    
 - 단점     
    * 캐릭터 완성형 방식으로 다국어를 표현하는데 제한이 있습니다.  
    
    
