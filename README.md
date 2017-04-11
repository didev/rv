# RV
- RV에서 Prores코덱 재생을 돕기 위한 저장소입니다.
- 영화 및 드라마 현장에서 고생하는 슈퍼바이저의 지원을 위해 github에서 작성되고 있습니다.

#### RV 설치
- http://www.tweaksoftware.com/downloads
- 위 사이트에서 RV 플레이어를 다운로드 받으세요.
- 라이센스는 디지털아이디어의 IT팀 지원을 받아 설치해주세요.

#### 설치전에..
- 설명하는 방법을 따라하더라도 Prores가 재생되지 않을 수 있습니다.
- 사용자의 OS버전, RV 버전에 따라서 오류가 있을 수 있습니다.
- 오류가 났을때는 컴파일이 필요하니 사용자 애플 계정을 이용해서 미리 Xcode를 설치합니다.

#### Prores 코덱 설치하기
- RV에서 Prores 코덱이 재생되지 않으면 터미널을 열고 아래 명령을 실행합니다.
- 테스트환경 macOS Sierra 10.12.2
```
cd ~
git clone https://github.com/didev/rv.git
sh ~/rv/mio_ffmpeg.sh
```
- 만약 RV 실행후 Prores코덱 mov 재생시 RV 프로그램이 다운되면 해당시스템에서 필요한 파일을 컴파일 합니다.
- 컴파일을 하기 위해서는 장비를 사내 R&D Pipeline Group으로 가지고 와주세요.
- 이 리포지터리에는 컴파일에 대한 이슈를 다루지 않습니다.
