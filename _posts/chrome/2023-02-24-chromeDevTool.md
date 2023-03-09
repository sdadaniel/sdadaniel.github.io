---
title: "Chrome Dev Tools"
categories: "chrome"
tag: "tools"
---

개발을 하면서 개발자 도구에서 매번 사용하는 부분만 보고 깊게 살펴볼 여유가 없었던 것 같습니다. 더 좋은 개발자가 되기 위해 개발자도구에 대하여 몰랏던 부분을 정리해보았습니다.

<hr>

#### :smirk: Open Command

<div id = "command"></div>

##### 사용방법

- 개발자도구로 이동 후 `ctrl + shift + p` 를 눌러 커맨드 창을 엽니다.

##### 설명

- 명령어를 통해 tool을 검색할 수 있습니다.다. 기능을 검색 할 때 이제 검색을 통해 열어보면 좋을 것 같습니다. 내가 모르는 너무 많은 기능들이 나열되서 놀랐습니다. 아직도 가야할 길이 많은 것 같습니다.:weary::weary::weary:

![image](/assets/imgs/post/chrome/chrome-02.png)

<hr>
#### Animation

##### 열기

- <a href="#command">명령창</a>을 열어 "Animation"을 클릭하여 이동합니다.

##### 설명

개발을 하다보면 anmation이 들어간 요소들을 확인해야 할 경우가 있습니다. 이와 같은 경우 애니메이션을 디버깅 하기 위해 매번 새로고침을 했던 기억이 납니다. :joy:

이제는 그런 불필요한 행동은 No No! Animation 툴을 넣어 디버깅 하면 됩니다.

![image](/assets/imgs/post/chrome/animation-tool.png)

상단 탭에 100%, 25%, 10% 중 선택해서 속도도 제어해보면서 상세하게 애니메이션을 검수 할 수 있을 뿐만 아니라 드래그를 해서 내가 원하는 단계에 맞춰 애니매이션을 확인 할 수 있습니다.

[사이트](https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions)에 들어가 직접 확인해보세요!

<hr>

#### Rendering

##### 열기

- <a href="#command">명령창</a>을 열어 "Rendering"을 클릭하여 이동합니다.

##### 페인팅 플래시

렌더링 탭이 열였다면 페인팅 플래시를 체크해보세요. 이제 체크 한 상태로 마우스를 이동하거나 버튼을 클릭해보세요. 클릭 할 때마다 리렌더링 부분이 초록색으로 깜박거리면서 시각적으로 리렌더링 되는 요소를 너무나도 쉽게 파악 할 수 있습니다.

dev tool에 profile탭을 이용여도 리렌더링되는 부분을 확인 할 수 있지만 리렌더링을 직관적으로 확인하는 부분에는 이 툴이 짱짱인 것 같습니다. 구글 개발자들은 뭘 할까 생각해보았는데 이런걸 만드는 것 같네요. (감사합니다.:smile::smile::smile: )

![image](/assets/imgs/post/chrome/chrome-03.png)

#### Capture

- 자체적으로 웹페이지 캡쳐를 할 수 있는 기능이 있습니다. 이 기능을 몰랐을 때에는 확장프로그램을 설치해서 캡쳐했었는데 이제부터는 그런일이 필요없을 것 같습니다.

#### Reference

- [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/overview/)
