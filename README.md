## portfolio_dodge

**목차**
1. 코드 설명
2. 시연 영상
3. 참고 서적
---
**1. 코드 설명**
* **Bullet.cs** : 총알의 스피드와, 총알과 플레이어가 부딪혔을 때 PlayerController의 Die 메서드를 실행합니다.
* **BulletSpawner.cs** : Instantiate 를 사용해 총알을 자동으로 생성, 방향을 플레이어에 조준해주는 컨트롤러입니다.
* **GameManager.cs** : 게임을 진행함에 따라 스코어를 저장, 상황에 맞는 텍스트를 표시해주는 스크립트 입니다.
* **PlayerController.cs** : 플레이어의 이동을 전반적으로 담당하고, Die 메서드를 사용해 플레이어가 죽었을 때
                    GameManager의 EndGame 메서드를 실행해 게임 종료 상황을 알려줍니다.
* **Rotator.cs** : 바닥을 회전시켜 게임을 더 어렵게 만들어 놓은 스크립트 입니다.
---
**2. 시연 영상** 

![Dodge_Game](https://user-images.githubusercontent.com/112876376/191914787-50c064f7-678c-4f81-868a-2d03894a22c8.gif)
---
**3. 참고 서적** </br>
레트로의 유니티 게임 프로그래밍 에센스
