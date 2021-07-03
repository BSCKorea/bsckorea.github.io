---
title: 커스텀 아바타의 눈 깜박임 애니메이션 넣는 법
tags: 정보
---

## 커스텀 아바타에 눈깜박임 애니메이션을 넣는 방법입니다

※ 이 방법은 풀트래커이거나 블렌드쉐이프가 몸이랑 떨어져있는경우에 한해 설정해주시기 바랍니다

---

1. 애니메이션을 추가한다

![](/img/blink/blink1.png)

이름은 기본적으로 blink로 예시로 넣겟습니다

![](/img/blink/blink2.png)

---

2. Animation창에서 눈깜박임 애니메이션을 만든다

 위치는 개인차가 있을텐데

![](/img/blink/blink3.png)

이 창을 확인하시고 방금 만든 블링크를 드래그해서 Hierarchy에 있는 아바타에 넣습니다

![](/img/blink/blink4.png)

그리고 hierarchy의 아바타를 새로 클릭합니다

그러면 animation의 선택창들이 활성화됩니다

![](/img/blink/blink5.png)

Add Property를 클릭하면

![](/img/blink/blink6.png)

여러 선택창 이나오는데 그중에 표정을 설정할수있는 Skinned Mesh Renderer가 있는데 이것은 아바타마다 있는 장소가 다르기때문에 잘 알아보시기 바랍니다

상위 화면의 프로퍼티에서

![](/img/blink/blink7.png)

블링크의 +를 눌러 추가합니다

![](/img/blink/blink8.png)

시간입력란

![](/img/blink/blink9.png)

이곳에 60을 넣고 표정값

![](/img/blink/blink10.png)

여기다가 100을 넣습니다

![](/img/blink/blink11.png)

눈을감은것을 확인할수있습니다

추가로 시간입력란에 58을 입력하고 표정값에 0을 집어넣습니다

또 시간입력란에 62를 입력하고 표정값 0을 집어넣으면

![](/img/blink/blink12.png)

점이 이렇게 생기는데요

![](/img/blink/blink13.png)

이버튼으로 미리보기를 해보시면

1초에 한번 깜박이는걸 확인하실수있습니다

이제 만든 blink애니메이션 파일을 클릭하시고

![](/img/blink/blink14.png)

Inspector창에서

![](/img/blink/blink15.png)

loop time을 체크합니다

※표정을 설정하면

![](/img/blink/blink16.png)

자세가 이렇게 변형되기 때문에 일단 풀트래킹이이 아니다/블렌드쉐이프에 바디가 섞여있을경우에는 사용하지 마시기바랍니다

- 풀트래킹일경우 : 표정설정을 하기전에 풀트래킹 타겟설정이 끝나고 정상적으로 움직이는 상황이라면 인게임에서 트래커에 따라 아바타가 붇기때문에 문제없이 작동합니다
- 블렌드쉐이프가 바디에랑 섞여있지 않은경우 : 그냥 그대로 설정해주시면됩니다

해당 현상을 고치시려면 [https://deux-hibi.hatenablog.com/entry/2019/01/07/210437](https://deux-hibi.hatenablog.com/entry/2019/01/07/210437)

이쪽 사이트를 참조해주시기바랍니다