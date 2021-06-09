

# 팀 소개
팀명 : 테슬라 4조  
팀원 : 박나현, 선혜연, 이새롬, 이하림(팀장), 장서현

<br>

# 프로젝트 목표

자바를 응용하여 프로그램을 구현할 수 있다. 여러 클래스 간의 연결과 객체 활용을 익힌다. API 도큐먼트를 적극 활용하여 수업 시간에 다루지 않은 새로운 기능을 구현한다. 

<br>

# 프로젝트 개요 및 기능 소개

뚜또 렌터카는 바쁜 현대사회에서 사용자들에게 즉각적인 실시간 차량 정보를 안내하고 편리한 비대면 대여서비스를 제공하여 시간 절약을 가능케하는 자판기이다. 

1. 프로그램을 실행하면 회원가입을 받는다. 회원가입을 하면 차량 대여가 가능한 상태가 된다.
2. 사용자로부터 원하는 대여 날짜/시간과 반납 날짜/시간을 입력 받는다.
3. 사용자가 입력한 기간에 대여가능한 자동차 리스트를 출력한다.
4. 사용자로부터 원하는 자동차를 선택 받고 보험 옵션을 선택 받는다.
5. 사용자의 선택에 따른 대여요금 총합을 계산한다. 현금 결제 시 잔돈 반환이 가능하다.
6. 선택된 자동차는 대여가능한 자동차 리스트에서 제거된다.


<br>

# 프로젝트 진행 시 사용 기술

1. 각 클래스들을 하나의 클래스(Start)에 객체화 하여 ‘뒤로 가기’ 구현.
2. ‘Thread sleep(ms)’을 활용하여 3초 지연 효과를 추가.
3. Calendar 클래스를 활용하여 현재 날짜/시간을 호출. 이를 활용하여 달력 출력.
4. Vector 자료구조를 활용하여 보유한 차량 중 대여 가능한 차랑만 리스트로 출력.
5. 객체화와 Vector 자료구조를 활용하여 예약된 차량을 다음 실행 시 가능한 차량 목록에서 제거.
6. Date 클래스와 HashMap 자료구조를 활용하여 로그인 시점에 조건에 맞는 쿠폰을 자동 발급한다. Array 정렬 기능을 활용하여 가장 할인율이 높은 쿠폰을 자동으로 적용시켜 총 금액을 계산한다.
7. Vector 자료구조를 활용하여 예약정보를 저장하고 사용자 요청 시 예약 확인서 출력.

<br>

# 작성한 소스

<실행 관련 파일> 

- Main **하림**
- Start **서현**, 하림
- Join **서현**, 하림, 새롬, 혜연
- Login **서현**, 하림, 새롬
- DateTime **서현**, 하림, 나현, 새롬
- Car **나현**, 혜연, 서현, 하림
- Insurance **혜연**, 나현, 하림
- CheckSelection **새롬**, 하림
- Payment **하림**, 서현
- Inquiry  **하림**, 새롬

---------------------------------------------------------------------- 

<데이터 관련 파일> 

- User **서현**, 하림
- UserData **하림**, 서현
- Card **하림**, 새롬, 나현
- DriversLicense  **서현**
- Reservation **서현**, 하림
- ReservationData **서현**, 하림

<br>



# 실행 결과

1. 시작 화면

	![1](https://user-images.githubusercontent.com/82256409/121389455-665beb00-c987-11eb-8ea0-d24fadc29ce4.png)

2. 회원가입

	![2](https://user-images.githubusercontent.com/82256409/121389460-678d1800-c987-11eb-8e69-2b86aabcaa6e.png)

3. 로그인

	![3](https://user-images.githubusercontent.com/82256409/121389473-6a880880-c987-11eb-8a75-d26918acb665.png)

4. 당월, 익월 달력 출력

	![4](https://user-images.githubusercontent.com/82256409/121389474-6b209f00-c987-11eb-9e62-6b029c9193c9.png)

5. 대여/반납 날짜 및 시간 입력

	![5](https://user-images.githubusercontent.com/82256409/121389477-6bb93580-c987-11eb-9325-fef630366169.png)

6. 대여 가능한 차량 목록 출력 및 차량 선택

	![6](https://user-images.githubusercontent.com/82256409/121389479-6c51cc00-c987-11eb-887b-5c523196d325.png)

7. 보험 옵션 선택 

	![7](https://user-images.githubusercontent.com/82256409/121389483-6eb42600-c987-11eb-9fb1-898b5895ee10.png)

8. 총 결제 금액 계산 및 예약 내용 확인

	![8](https://user-images.githubusercontent.com/82256409/121389485-6eb42600-c987-11eb-9a1c-ea6e81f72e63.png)

9. 쿠폰 적용 및 결제

	![9](https://user-images.githubusercontent.com/82256409/121389486-6f4cbc80-c987-11eb-90c9-76e248e5a666.png)

10. 결제 방식 선택 및 결제

	![10](https://user-images.githubusercontent.com/82256409/121389487-6f4cbc80-c987-11eb-9f17-b0cbc37bc82e.png)

11. 현금 결제 시 거스름 돈 출력

	![11](https://user-images.githubusercontent.com/82256409/121389489-6fe55300-c987-11eb-856e-beffa7c5a680.png)

12. 예약확인서 출력

	![12](https://user-images.githubusercontent.com/82256409/121389490-6fe55300-c987-11eb-9f52-3432bdd5f8b9.png)

13. 재로그인 시 예약 내역서 발급

	![13](https://user-images.githubusercontent.com/82256409/121389495-71168000-c987-11eb-8256-fcc2537a3948.png)

14. 관리자 모드  

	![14](https://user-images.githubusercontent.com/82256409/121389498-71af1680-c987-11eb-92aa-851fee85490b.png)

