# docker-for-mongodb
몽고DB를 위한 기본 개발 환경 셋업

## Before
> 개발환경 세팅을 위한 사전 준비.
* [도커](https://docs.docker.com/get-docker/)와 [도커 컴포즈](https://docs.docker.com/compose/install/)를 설치합니다.
   > **Mac**과 **Windows**는 **Docker Desktop**을 설치했다면 **Docker Compose**도 함께 설치되므로 별도 설치할 필요 없습니다.
   1. 도커를 설치하려면 [여기](https://docs.docker.com/get-docker/)를 클릭해주세요.
   2. 도커 컴포즈를 설치하려면 [여기](https://docs.docker.com/compose/install/)를 클릭해주세요.

## Run
1. 저장소를 복제합니다.
   ```bash
   # 저장소 복제
   $ git clone https://github.com/woorim960/docker-for-mongodb

   # 저장소로 이동
   $ cd docker-for-mongodb
   ```
2. docker-compose를 이용하여 서버를 오픈합니다.
   ```bash
   $ docker-compose up
   ```

## Exit or Termination
> 도커 컨테이너를 종료합니다.
  * ```Ctrl + C```를 입력해도 동작중인 컨테이너가 종료됩니다. 다만, 종료된 상태로 메모리에 남게되므로 완전히 삭제시키고자 할 때는 아래 명령어를 사용합니다.
  ```bash
  $ docker-compose down
  ```
