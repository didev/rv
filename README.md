# RV
- RV에서 Prores코덱 재생을 위한 리포지터리입니다.
- 외부 및 현장에서 고생하는 슈퍼바이저의 지원을 위해 이 리포지터리는 github에서 작성되고 있습니다.

#### RV 설치
- http://www.tweaksoftware.com/downloads
- 위 사이트에서 RV를 다운로드 받으세요.
- 라이센스는 디지털아이디어의 IT팀 지원을 받아 설치해주세요.

#### OSX RV에서 Prores 코덱으로 인코딩된 mov 재생방법
- 아래 방법을 따라하더라도 재생되지 않을 수 있습니다.
- 만약을 위해 사용자 애플 계정으로 Xcode를 설치합니다.
- 슈퍼바이져가 RV에서 Prores 코덱이 재생되지 않으면 아래 단계를 실행합니다.
```
cd ~
git clone https://github.com/didev/rv.git
sh ~/rv/mio_ffmpeg.sh
```
- 만약 RV 실행후 mov 재생시 RV 프로그램이 다운되면 해당시스템에서 필요한 파일을 컴파일 합니다.
- 컴파일을 위해서 노트북을 R&D Pipeline Group으로 가지고 와주세요.
- 참고1 : 이 리포지터리에는 컴파일에 대한 이슈를 다루지 않습니다.
- 참고2 : 테스트환경 macOS Sierra 10.12.2
