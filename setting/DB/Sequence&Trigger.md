## Sequence & Trigger
참고 사이트 : http://mcpicdtl.blogspot.com/2008/02/oracle-sequence-trigger-by-vins.html

#### Trigger 사용하는 Sequence
1. :new 연산자를 사용하여 Trigger생성
2. Insert 문 작성시 Sequence자리를 null로 하거나, Sequence자리를 비우고 데이터를 입력한다.


#### Trigger 사용하지 않는 Sequence
1. Sequence를 0부터 시작  
2. Insert 문 작성시 Sequence.nextval로 데이터를 입력한다.
