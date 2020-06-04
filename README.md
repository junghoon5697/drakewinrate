# How do drakes affect Summoner's Rift?
In this page, we investigate the relationship between drakes and win rates in the popular video game League of Legends. A total of 800,000 game data has been collected between May 19th and May 24th, on patch 10.10.
The dragon system in Leauge are mainly divided into three types : elemental, soul and elder. Within this page, we discuss the effect that each type of drake has on winning a game.

이 프로젝트에서는 인기 게임 '리그 오브 레전드'에서 용의 승률에 대한 영향력을 분석해보고자 합니다. 패치 10.10 버전에서 5월 19일 부터 24일 까지 모은 약 80만건의 데이터를 사용합니다.
리그 오브 레전드의 드래곤 종류는 크게 원소, 영혼 그리고 장로 드래곤으로 분류됩니다. 이 프로젝트에서는 각 용의 종류가 게임 승률에 미치는 영향을 분석하고자 합니다. 

# Elemental Drakes
Here we analyze the impact of elemental drakes on Summoner's Rift. There are a total of four elemental drakes : Fire, Wind, Ocean and Mountain drakes. 
먼저 소환사 협곡 모드에서 원소 용의 영향을 분석하고자 합니다. 원소용은 화염, 바람, 바다, 그리고 대지용으로 총 4가지가 존재합니다. 각각의 용 효과는 아래와 같습니다.

(시간이 조금 더 있었으면 보고 싶은 내용 : 용 영혼 종류에 따른 협곡 변화가 이기는 팀한테 미치는 영향)

영혼 효과:

(바람) : 궁극기 재사용 대기시간 10/20/30/40% 감소, 재사용 대기시간 최대치 초과 가능

(화염) : 공격력 및 주문력 +4/8/12/16% 증가

(바다) : 매 5초마다 잃은 체력의 2.5/5/7.5/10% 회복

(대지) : 방어력 및 마법 저항력 +6/12/18/24%

## First Dragon Analysis
We discuss the effect the first drake has on winning a game. 
첫번째 드래곤이 게임 승리에 끼치는 영향은 아래와 같습니다.

### First Dragon Time Stats

Average 1st Drake Time : 9mins 10 seconds

1st Drake Time Median : 8mins 41 seconds

1st Drake Slain Time Distribution 

![GitHub Logo](https://github.com/junghoon5697/drakewinrate/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202020-06-04%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%206.56.33.png)

### First Dragon Time per Tier

IRON : 9min 16sec

BRONZE : 9min 19sec

SILVER : 9min 29sec

GOLD : 8min 58sec

PLATINUM : 8min 18sec

DIAMOND : 7min 41sec

MASTER + : 7min 20sec

### First Dragon Win Rate

First Dragon Win Rate= 64.88%

First drake Fire Drake winrate = 65.56%

First drake Water Drake winrate = 66.93%

First drake Air Drake winrate = 61.91%

First drake Mountain Drake winrate = 64.86%

첫 용을 보통 6-9분 쯤에 먹는 것으로 확인이 되었습니다. 전반적으로 용을 먹는다는 것 자체가 게임 초반에 주도권을 가지고 있다는 뜻이라서 그런지 첫번째 용을 챙기기만 할 수 있다면 승률이 60%를 상회하는 것을 확인 할 수 있었습니다. 역시나 스노우볼을 잘 굴리는 윗 티어 일 수록 이를 캐치하고 첫번째 용을 다른 티어들 보다는 좀 더 일찍 챙기고자 하는 모습이 드러나 있습니다.

역시나 원소용이 처음 등장했을 때부터 게임 극초반에 먹을 수만 있다면 기분이 좋다는 소리를 자주 듣던 바다용이 첫 번째 용으로 나왔을 떄 승률이 제일 좋습니다. 보통 초반에 용을 평균 6-9분 사이에 먹는데, 이 때는 한창 라인전이 진행중인 단계에서 잃은 체력의 2.5% 회복은 꽤나 의미있는 버프로, 이를 바탕으로 스노우볼을 굴려서 게임 승리로 좀 더 손쉽게 이어나가는 구도를 확인할 수 있습니다. 바람 드래곤이 다른 영혼에 비해 승률이 크게 떨어지는 것도 라인전 단계에서 아직 궁극기를 찍지 못한 챔피언들도 있어서 바람용을 적절하게 사용하기가 어려운 구도가 생겨서라고 유추해 볼 수 있습니다.


### First Dragon Time vs Win Rate
![GitHub Logo](https://github.com/junghoon5697/drakewinrate/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202020-06-03%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%207.49.39.png)

첫 번째 용 타이밍과 승률의 상관관계 그래프입니다. 사실 첫 번째 용을 10분안에 먹는 경우가 압도적으로 많지만, 신기하게도 10분대 이후에 첫번째 용이 먹히게 되면 승률이 굉장히 올라가는 것으로 확인할 수 있었습니다. 아마도 그만큼 첫번째 용을 먼저 치기가 어려울 정도로 게임이 팽팽한 상황에서 첫번째 용을 먼저 먹게 되는 것이 그 용을 챙기는 팀한테 굉장히 큰 의미를 가지게 되기 때문에 이러한 현상이 나타나는 것으로 추정됩니다. 

#시간 남으면 전령 분석도 하고 싶었으나...

# Dragon Soul

## Win Rate with Soul
Win rate with soul is : 89.47%

## Win Time After Soul

## Soul Type vs Win Rate
Win Rate with Wind Soul is : 89.03%

Win Rate with Fire Soul is : 89.14%

Win Rate with Mountain Soul is : 89.75%

Win Rate with Water Soul is : 90.13%

### Win Rate with Several Elemental Drakes
Win Rate with 2 Soul Elemental Drakes is : 90.68%

Win Rate with 3 Soul Elemental Drakes is : 86.72%

Win Rate with 4 Soul Elemental Drakes is : 84.05%


### Win Rate With 4 Elemental Drakes

Win Rate with 4 Wind Rakes : 81.71%

Win Rate with 4 Fire Rakes : 85.78%

Win Rate with 4 Wind Rakes : 86.13%

Win Rate with 4 Wind Rakes : 82.57%

# Elder Dragon

## Win Rate with Elder Buff
Win Rate with Elder Buff is : 85.93%

## Win Time with Elder Buff
![GitHub Logo](https://github.com/junghoon5697/drakewinrate/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202020-06-03%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%208.36.29.png)

## Win Rate with Soul and Elder

