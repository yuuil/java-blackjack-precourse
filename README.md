# 프리코스 3주차 블랙잭

## 기능구현목록

- [x]  플레이어 입력받기
- [x]  플레이어의 배팅 금액 입력받기
- [x]  카드의 숫자 계산은 카드 숫자 기반. (Ace는 1 / 11로 계산, King, Queen, Jack은 10으로 계산)
- [x]  게임 시작 시 플레이어에게 두 장의 카드 지급
- [x]  카드의 합이 21을 넘지 않는 경우 추가로 카드를 뽑을 수 있음.
- [x]  추가로 카드를 뽑아 합이 21을 넘는 경우 배팅 금액 모두 잃음.
- [ ]  처음 두 장의 카드의 합이 21인 경우 배팅금액의 1.5배를 딜러에게 받음.
- [ ]  딜러와 플레이어가 모두 블랙잭인 경우 플레이어는 배팅한 금액을 돌려받음.
- [x]  딜러의 첫 두 장의 카드의 합이 16 이하이면 추가로 카드 받음.
- [x]  딜러가 21을 초과하면 남아있는 플레이어 모두 승리 => 배팅금액을 받음.



## 프로그래밍 요구사항

### 1. Card 객체

- Card 기본 생성자 추가 불가
- 필드(인스턴스 변수)인 symbol과 type의 접근제어자 private 변경 불가
- Card에 필드(인스턴스 변수) 추가 불가

### 2. Player 객체

- Player 기본 생성자 추가 불가
- 필드(인스턴스 변수)인 name, bettingMoney, cards의 접근제어자 private 변경 불가
- Player에 필드(인스턴스 변수) 추가 불가

### 3. Dealer 객체

- Dealer 기본 생성자 이외 다른 생성자 추가 불가
- 필드(인스턴스 변수)인 cards의 접근제어자 private 변경 불가
- Dealer에 필드(인스턴스변수) 추가 불가



> ### 선택사항
>
> - Card, Player, Dealer 객체의 예외 처리
> - Player와 Dealer의 중복 코드 제거
>   - 자바의 상속을 활용