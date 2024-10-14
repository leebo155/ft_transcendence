# ft_transcendence
Not about Johnny Depp's movie.

## Introduction
* 이번 프로젝트는 지금 까지 배워온 지식을 바탕으로 **Pong** 게임을 즐길 수 있는 웹사이트를 구현하는 것이 목표입니다.
* 게임은 로그인 후 즐길 수 있으며 기본적으로 등록한 메일로 12자리 무작위 코드를 보내 2차 인증을 합니다.
* 게임은 오프라인과 온라인으로 즐길 수 있으며, 온라인으로 플레이 할 경우 대기방에 접속하여 준비가 완료되면 게임이 시작됩니다.
* 구현된 웹 사이트는 외부 라이브러리의 도움없이 [Single Page Application](https://en.wikipedia.org/wiki/Single-page_application)을 경험할 수 있도록 만들었습니다.
* 모든 서비스는 도커 컨테이너로 구현되어 도커 컴포즈를 사용하여 간단하게 빌드 가능합니다.

### Used Technologies

  #### Front-End
  * Vanilla Javascript
  * Bootstrap toolkit
  * ThreeJs
  
  #### Back-End
  * NginX
  * Django
    - daphne
    - channels
    - rest-frame-work
    - simplejwt
  * PostgreSQL
  * Redis
    
### Simple flowchart of process




### Made by
|<img src="https://github.com/leebo155.png" width=240>|<img src="https://github.com/juhyeonlee134.png" width="240">|<img src="https://github.com/jmsmg.png" width=240>|
|:--:|:--:|:--:|
|[Bohyeong Lee](https://github.com/bohlee)|[juhyeonlee](https://github.com/juhyeonlee134)|[Seonggon, Cho](https://github.com/Jmsmg)|
|Back|Front|Back|

## Usage
### Makefile

| Rules | Description |
| ----- | ----------- |
| all | Create and run Docker containers and images. |
| stop | Stop running Docker containers. |
| start | Start stopped Docker containers. |
| clean | Terminate created Docker containers. |
| fclean | Remove all created Docker containers and images. |
| re | Recreate Docker containers and images after removing them. |

## Screenshots
