# Media Server


## Features

- 정적 미디어 파일을 서빙해 줍니다
- 동영상의 경우 스트리밍 제공


## Installation

1. 레파지토리 클론받기기:
    ```bash
    git clone https://github.com/your-username/media-server.git
    ```
2. .env 파일을 수정 (원하는 포트, 프로젝트명 입력력)
    ```
    APPNAME=limelab_backend
    PORT=8899
    ```
3. 빌드 스크립트를 실행:
    ```bash
    ./build.sh
    ```
    혹은
    ```bash
    sh build.sh
    ```

4. 브라우저를 열고 `http://localhost:8899/media/`에 접속. 뒤에는 경로에 맞게 파일명을 입력.
    



논의 사항
- 기본 1주일인거 일단 3시간으로 쿠기에 저장해서 관리 <<기간, 정리법 논의 필요>>
- 로그 파일 관리(용량에 대해서 주기적으로 초기화 할지, 쭉 싸을지)