# rv

#### 설 치
- http://www.tweaksoftware.com/downloads
- 위 사이트에서 RV를 다운로드 받으세요.
- 라이센스는 디지털아이디어의 IT팀 지원을 받아 설치해주세요.

#### OSX RV에서 Prores 코덱으로 인코딩된 mov 재생방법
- 아래 방법으로 안될 수 있다. 만약을 위해 사용자 애플 계정으로 Xcode를 설치하게 한다.
- 슈퍼바이져가 RV에서 Prores 코덱이 재생되지 않으면 아래 단계를 실행한다.
```
cd ~
git clone https://github.com/didev/rv.git
sh ~/rv/mio_ffmpeg.sh
```
- 만약 RV 실행후 mov 재생시 프로그램이 다운되면 해당시스템에서 필요한 파일을 컴파일 한다.
- 참고1 : 이 리포지터리에는 컴파일에 대한 이슈를 다루지 않습니다.
- 참고2 : 테스트환경 macOS Sierra 10.12.2
