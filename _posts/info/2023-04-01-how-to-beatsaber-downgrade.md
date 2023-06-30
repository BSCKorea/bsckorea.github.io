---
title: 비트세이버 다운그레이드 하는법
tags: 정보
---

```
1.29.4 유니티 업데이트로 인한 필수 다운그레이드는 아래의 링크를 이용하는 것이 간편합니다.
```
### [외부 프로그램 없이 다운그레이드 하기](/2023/06/30/downgrade-steambeta.html)

준비물 : **백업본** & [**LegacyInstaller**](https://github.com/Goobwabber/LegacyInstaller/releases/download/1.1.4/LegacyInstaller.zip)

사용 방법

1. 아래 사진처럼 첫번째에 Beat Saber 설치 폴더를 지정해준다.
2. 두번째에 Steam 설치 폴더를 지정해준다.
3. 다운받고싶은 버전을 선택한다.
4. 인스톨을 누른다.
5. 다운로드가 다 되면 아래 두 번째 사진처럼 스팀 라이브러리에 Beat Saber (설치한 버전) 이 생성된다.
6. 이제 Beat Saber를 실행하면 된다.

위의 방법을 실행하고 모드 설치 방법

**세번째 사진을 참고하면 편하다.**
1. [ModAssistant](https://github.com/Assistant/ModAssistant/releases/download/v1.1.30/ModAssistant.exe)를 실행한다.
2. 왼쪽탭에서 [옵션]을 누른다.
3. Intall Folder 혹은 설치 폴더 아래 Select Folder 혹은 폴더 선택을 누른다.
4. C(D):/~/Steam/steamapps/common/Beat Saber (설치한 버전) 폴더를 선택한다.
5. 모드를 다운받는다.
6. 모드 설치 완료. 이제 Beat Saber를 실행하면 된다.

- 백업 방법
    1. 기존의 Beat Saber 폴더에서 Custom이름이 붙은 폴더들과 UserData, Playlists를 백업한다.
    2. Beat Saber_Data 폴더 안에 CustomLevels를 백업한다.
        - 매핑하는 사람은 CustomWIPLevels도 백업한다.
    3. 새로 설치한 폴더에 백업한 폴더들을 붙여넣는다.
        - 여기서 생기는 문제는 대부분 UserData에서 발생하는 문제다. 대부분 기록을 저장하거나, 로깅 파일들에서 문제가 자주 발생한다.
        - 그래서 문제가 생기면 위의 파일들을 삭제하고 다시 실행해보는 것을 추천한다.

![](/img/information/lir.png)
![](/img/information/steaml.png)
![](/img/information/bgma.png)