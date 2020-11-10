# EECS201012(014)-C programming-ResearchAssistant-2020
: 2020년 2학기 동안 'C 프로그래밍과 실습' 수업에서 조교를 맡았습니다.  
실습 과제 답안을 작성하면서 공부한 코드와 학생들을 위해 작성한 설명안을 업로드 했습니다.


## 1. 변수와 자료형
### 1) 거스름돈 계산하기 (3주차 실습 문제 2번)
> 편의점에서 물건을 구입하고 만 원을 냈을 때, 거스름돈의 액수와 점원이 지급해야할 거스름돈 화폐와 동전 수를 계산하는 프로그램을 작성해보자.
> * 사용자로부터 물건값을 입력받는다. 물건 값은 100원 단위로 떨어진다고 가정한다.
> * 점원이 내어주어야 할 오천원권, 천원권, 오백원 짜리 동전, 백원짜리 동전 개수를 출력한다.  
  
### 2) 키를 피트와 인치로 변환하는 프로그램 (3주차 실습 문제 4번)
> cm로 표현된 키를 입력하여 피트와 인치로 변환하는 프로그램을 작성하라. 1피트 12인치이고 1인치는 2.54cm이다.

  
    
      

## 2. 반복문
### 1) 직각 삼각형 패턴 출력 (5주차 실습 문제 7번, 5주차 실습 패턴출력 예제 코드)
> 원하는 단 수를 입력받고 '*'로 이루어진 직각 삼각형, 상하 반전된 직각 삼각형, 상하좌우 반전된 직각 삼각형, 피라미드를 출력하시오.

### 2) 패턴 출력 방법 설명 (5주차 실습 패턴출력)


### 3) 계산기 만들기 (5주차 실습 문제 8번)
> 연산 메뉴(+, - , *, /)를 화면에 출력하고 사용자가 메뉴 중에서 하나를 선택할 때까지 반복을 계속한다. do~while 반복문을 사용하여 사용자가 적절한 선택을 했는지를 검사하도록 하라. 만약 사용자가 A, S, M, D, Q가 아닌 다른 문자를 입력하면 "연산을 선택하시오." 메시지를 계속해서 출력한다. 하나의 메뉴가 선택되면 해당되는 연산을 실행하고 다시 메뉴를 선택할 수 있도록 하라. 반복을 종료하는 메뉴인 Q는 break문을 이용하여 구현하도록 하라.  
### 4) 입력버퍼를 비우는 법 (5주차 실습 문제 8 답변)


## 3. 함수
### 1) 알파벳인지 판별 (6주차 실습 문제 6번)
> 전달된 문자가 알파벳 문자인지 아닌지를 검사하는 함수 check_alpha()를 작성하고 이것을 호출하여서 사용자가 입력한 문자가 알파벳('a'에서 'z'까지)인지를 판단하여 출력하는 프로그램을 작성하라.  
### 2) 난수 생성 (6주차 실습 문제 8번)
> 난수(random number)는 컴퓨터를 이용한 문제 해결에서 많이 사용된다. 특히 수학적인 분석이 너무 복잡한 경우에 시뮬레이션으르 사용하면 실제로 제품을 제작하지 않고서도 많은 실험을 할 수 있다. Visual Studio의 경우, rand()가 한번 호출될 때마다 0에서 32767까지의 정수를 같은 확률로 선택하여 반환한다. rand() 함수를 이용하여 0 또는 1 값을 무작위로 반환하는 함수 b_rand() 를 작성하고 5번 호출하여 보자.



## 4. 배열
### 1) 각 시험별 최고, 최저 점수 구하기 (8주차 실습 문제 3번)
> 학생들의 시험 점수를 통계 처리하는 프로그램을 작성하여 보라. 한 학급은 최대 10명까지의 학생들로 이루어진다. 각 학생들은 3번의 시험을 치른다. 학생들의 성적은 난수를 생성하여서 얻는다. 각 시험에 대하여 최대점수, 최저점수를 계산하여 출력한다.

### 2) transpose (8주차 실습 문제 4번, 8주차 실습 문제 4번 해설)
> 2차원 행렬에 대한 transpose(int a[][3], int b[][3]) 함수를 작성하고 테스트하여 보라. 행렬의 크기는 3x3으로 가정하라.

### 3) 10진수를 2진수로 변환 (8주차 실습 문제 5번)
> 10진수를 2진수로 변환하여 출력하는 프로그램을 작성하여 보자. 최대 32자리까지 변환이 가능하도록 하라. 변환된 자리수를 저장하는데 배열을 사용하라. 10진수를 2로 나누어서 생성된 나머지를 역순으로 나타내면 2진수로 표현할 수 있다.  


## 5. 문자와 문자열
### 1) 찾아 바꾸기 (10주차 실습 문제 5번, 10주차 실습 문제 5번 way2)
> 간단한 "찾아 바꾸기" 기능을 구현하여 보자. 첫 번째로 사용자에게 최대 80 문자의 문자열을 입력하도록 한다. 두번째로 찾을 문자열을 입력받는다. 세 번째로 바꿀 문자열을 입력받는다. 문자열을 찾아서 바꾼 후에 결과 문자열을 화면에 출력한다.





  
    
      
