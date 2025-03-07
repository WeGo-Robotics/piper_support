# piper_support
PiPER를 사용하며 발생한 이슈 및 Q&amp;A를 모아놓은 저장소입니다.

1. 소스 코드 다운로드
터미널에 아래 명령어를 입력하여 소스 코드를 다운로드합니다.


```
git clone https://github.com/WeGo-Robotics/piper_ws.git
```

WeGo Robotics에서 제공하는 ID와 PW를 입력해야 합니다.

2. 다운로드한 폴더로 이동
다운로드 받은 piper_ws 폴더로 이동합니다.

```
cd piper_ws
```

3. 원클릭 셋팅 파일 권한 설정
터미널에 아래 명령어를 입력하여, 원클릭 셋팅 파일(setup_dependencies.sh)의 실행 권한을 부여합니다.

```
chmod +x setup_dependencies.sh  
```

4. 원클릭 셋팅 파일 실행
원클릭 셋팅 파일을 실행하여 필요한 의존성을 설치합니다.

```
./setup_dependencies.sh  
```

5. 빌드 및 실행 준비
필요한 의존성 설치가 완료되면, colcon build 명령어로 빌드를 실행하여 준비를 마칩니다.

```
colcon build
```
