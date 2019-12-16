# 구현해야 할 내용

## card
- [ ] Ace는 1또는 11로 계산할 수 있다.
! 기본 생성자 추가 불가
! 필드의 접근 제어자 private 변경 불가
! 필드 추가 불가

## cardFactory
- [ ] 카드 더미에서 꺼낸 카드를 처리한다.

## game

- [ ] 카드의 합이 21이거나 가장 가까운 숫자를 가지는 쪽이 이긴다.
- [ ] 플레이어들에게 배팅 금액을 받는다.
- [ ] 카드 두 장을 지급한다.
- [ ] 지급한 카드 두 장의 합이 21일 경우 베팅 금액의 1.5배를 딜러에게 받는다.
플레이어와 딜러가 동시에 블랙잭인 경우, 플레이어는 베팅한 금액을 돌려받는다.
- [ ] 카드를 추가로 뽑아 21을 초과할 경우 배팅 금액을 모두 잃는다.

## table
- [ ] 플레이어들과 딜러가 들어있는 객체
- [ ] 플레이어들의 수익을 관리한다

## player
- [ ] 지급받은 카드를 리스트에 추가
- [ ] 카드리스트를 비우는 메소드 추가
! 기본 생성사 추가 불가
! 필드 접근 제어자 private 변경 불가
! 필드 추가 불가
 
## dealer
- [ ] 지급받은 카드를 리스트에 추가
- [ ] 카드리스트를 비우는 메소드 추가
! 기본 생성자 추가 불가
! 접근 제어자 private 변경 불가
! 필드 추가 불가
