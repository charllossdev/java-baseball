# 숫자 야구 게임

## 기능 요구사항
* 1부터 9까지 서로 다른 수로 이루어진 3자리의 수를 맞추는 게임
* 같은 수가 같은 자리에 있으면 `STRIKE`, 다른 자리에 있으면 `BALL` 같은 수가 전혀 없으면 `NOTHING`
    + [Example](): 상대방(컴퓨터)의 수가 `425` 일 때, 
        - `123` 을 제시한 경우 : `1 STRIKE`
        - `456` 을 제시한 경우 : `1 STRIKE`, `1 BALL`
        - `789` 를 제시한 경우 : `NOTHING`
* 위 숫자 야구게임에서 상대방의 역할은 컴퓨터
    + 컴퓨터는 `1 ~ 9` 까지 서로 다른 임의의 수 3개를 선택
    + 게임 플레이어는 컴퓨터의 수를 예측하여 3개의 숫자를 입력하고, 컴퓨터는 입력한 숫자에 대한 결과 출력
    + 위 과정을 반복해 컴퓨터가 선택한 3개의 숫자를 모두 맞히면 `게임 종료`
  