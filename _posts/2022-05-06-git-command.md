---
layout: post
title:  '깃허브 입문'
date:   2022-05-06 10:27:42 +0900
categories: github
---

# ![](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTVfMjc4/MDAxNTc2NDE0MTAwNjg1.cp_9N4gi8GOe7idQjx6pC1LUhK9EqpIs9uArKqZq6iUg.1vF6bTjG3vJW4mb_WagZ5gh0gfwjoo2bznBTEs-tyXkg.JPEG.nilsine11202/github.jpg?type=w800)

# ![]<img width="600" alt="git" src="https://user-images.githubusercontent.com/96412661/167056977-3a5f75b1-8016-4a3b-97e7-4b8c6200b880.png">

----------

> Git은 버전관리 프로그램,
> 
> Github은 이 버전관리 데이터를 저장하는 저장소!

----------

간만에 포스팅을 올려봅니다.

깃헙이 뭐지? 싶어 검색해 이 글을 찾아 오신 분들이라면

깃헙이 뭔지 대략적인 느낌을 알고 있으시리라 생각합니다.

​

능력있는 개발자들은 자신의 포트폴리오로 활용하기도 한다는데,

나도 한번 해볼까? 하는 생각에 시작하지만,

많은 분들이 어려운 용어와 시스템에 대한 장벽으로 좌절하는 경험을 하죠.

바로 저의 이야기입니다.

아래는 만든지 2년이 지나도록 아무런 기록을 남길 수 없던 처참한 컨트리뷰션 창입니다.

​

![](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTVfMjQ5/MDAxNTc2NDE0Nzc2ODk2.rEDRK_b_uLskwl2owJYEkDhoVqBPIZ9ITTvzwlmNLKsg.i4adKtdS4VIWe8akEXCl3JHp2baD-OeQfyFvuOOBn-Eg.PNG.nilsine11202/20191215215924.png?type=w800)

​

그러던 중 다행히도 잘 정리된 영상을 유튜브에서 발견했고,

이를 토대로 배운 간단한 기능을 공유하고자 포스팅을 시작하게 되었습니다.

​

이해한 바를 정리하는 수준이기 때문에,

용어나 개념을 설명하는 데 있어 오류가 있을 수 있다는 점 너그럽게 봐주시면 감사하겠습니다.

틀리거나 더 나은 표현이 있다면 댓글로 말씀해 주세요!

​

​

​

1. 깃이란?

​

![](https://live.staticflickr.com/8523/8455538800_30f65954f8_b.jpg)

코딩을 하다보면,

특히 여러 사람들과 코딩을 하다보면

다양한 혼선을 겪을 수 있습니다.

이럴 때 기존에 어떤 상태로 코드를 짜여 있었는지,

그리고 어떤 변경을 가했는지 등을 기록하는 일이 굉장히 중요하겠죠.

​

코드를 수정해 새로운 버전을 만들 때마다

아래처럼 새롭게 정리해야한다면,

아마도 개발자들의 정신건강이 더 위험해질 것 같네요.

![](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTZfMjM3/MDAxNTc2NDU1Njg4MjM5.lAtOz8d3WVZShQwoFI490xKuiI22PVI-If7XLi169c0g.EBaWIlXDwCjV282aXckkiM092xHXDvjnHGE7wRMkL7kg.JPEG.nilsine11202/IMG_9694.JPG?type=w800)

​

이러한 문제를 해결하기 위해 있는 것이

"버전관리 프로그램"이고,

깃은 그 기능을 훌륭하게 수행해 줍니다.

​

​

​

2. Github은 그럼 뭔가요?

Git을 통해 기록한

버전에 대한 데이터를,

온라인으로 관리할 수 있도록 도와주는 사이트입니다.

기존에 짜인 코드에 비해 이런 점이 바뀌었다,

저런 점이 바뀌었다 하는 것을 기록하는 사이트라고 할 수 있겠습니다.

​

이와는 별개로, 일종의 SNS와 같은 기능을 수행하기도 합니다.

나는 이런 스킬을 가지고 있고, 이런 프로젝트를 수행했습니다!

혹은 이런 오픈소스에 기여하고 있어요!

하는 것을 보여주는,

포트폴리오로써의 기능도 해주는 셈이지요.

​

![](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTVfMjEx/MDAxNTc2NDE1ODY5MDM2.oNufT8wTRhFWxDmjtWNNk0DTwOoBQKz2dVrqW3gLotEg.tvEG2aJ_e125hlW9zzlRXq5dZwYBDEPT_rRF-XF02dwg.PNG.nilsine11202/20191215221638.png?type=w800)

아직은 부실한 저의 프로필입니다. 앞으로 풍성해지길 바라며, 1일 1커밋을 수행해보려고 합니다 ㅎㅎ

​

​

​

​

​

3. 깃헙 사용하기

​

​

**1) Git Bash 설치**

아래 사이트로 이동해, Git Bash를 다운받습니다.

Git Bash를 통해, Git 활용에 필요한 커맨드를 사용할 수 있습니다.

​

​

[https://gitforwindows.org/](https://gitforwindows.org/)

[![](https://dthumb-phinf.pstatic.net/?src=%22https%3A%2F%2Fgitforwindows.org%2Fimg%2Fgw1web_thumb.png%22&type=ff120)](https://gitforwindows.org/)[](https://gitforwindows.org/)

**Git for Windows**

Tools & Features Git for Windows focuses on offering a lightweight, native set of tools that bring the full feature set of the Git SCM to Windows while providing appropriate user interfaces for experienced Git users and novices alike. Git BASH Git for Windows provides a BASH emulation used to run Gi...

gitforwindows.org

![](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTVfMTYw/MDAxNTc2NDE2MTUyOTY5.XYZipcez3Op5WwniWkjDO7yj_bR-XQEmsYzarYly9xIg.lEP6HOKbSYzbpp6CrQ3dI35v7czthPL-EDlv_f4_nr4g.PNG.nilsine11202/20191215222217.png?type=w800)

위의 Download를 눌러 그대로 주욱 다운로드 받으시면 됩니다.

​

**2) Repository 생성**

Repository란 저장소를 의미합니다. 버전에 따른 히스토리(변경내역)을 저장하는 역할을 수행합니다.

하나의 빈 서랍을 여는 것 같다고 이해하면 쉽습니다.

​

![](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTVfMTAx/MDAxNTc2NDE3MjQ4MjE3.VZconkkVw9rPQiPKLB-Q-UVZQuetGPS1smjF8Sga590g.RU78aCy2KSNU7JktxByFg_XLIfIoPq7oin8fACL1GRcg.PNG.nilsine11202/20191215224037.png?type=w800)

자신의 git profile로 이동해,

Repositories를 누릅니다.

그리고 New 버튼으로 새로운 레포지터리를 생성합니다.

![](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTVfOTEg/MDAxNTc2NDE3MzA5MjMz.-porfyaNKLcPRvKGIWJDzpoDgIZo59KOj_QXnMwOwkYg.c4Lws3Lq7MYiH03c0uyTgx6YDRFUzZ6WV_0wT05RdGcg.PNG.nilsine11202/20191215224134.png?type=w800)

저는 example이라는 repository를 생성하고,

공개 범위를 'public'으로 지정했습니다.

​

​

**3) Root Folder와 연결**

깃헙이라는 온라인 저장소에 나의 코드를 올리려면,

먼저 내 PC에 코드가 저장된 위치를 연결해야겠죠.

github에 연결할 대상 폴더를 Root Folder라고 합니다.

​

이제 웹의 저장소에 우리의 Root Folder를 연결해보겠습니다.

​

먼저 연결하려는 폴더를 우클릭해,

"Git Bash Here"을 클릭합니다.

![](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTVfMjIg/MDAxNTc2NDE2NzUyMzU2.h9ClJVPWTf9PG2prF4Qo-3D4G21a3VG7MkdjuURnshog.Vi7e17FU7FVetDPbQY2DWMURIk8sL7VDAq_2voXBuAEg.PNG.nilsine11202/20191215223218.png?type=w800)

​

![](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTVfMjc3/MDAxNTc2NDE2ODk3Njgz.z79pvxChoKvb3g7pu58lTbnVvcPh_Z7gfeRR3G2SFAsg.34u1sdljLJUD6qvfZq6pXl4_BFYRSIW5HNaYKh5ldjEg.PNG.nilsine11202/20191215223433.png?type=w800)

이와 같은 터미널이 뜨면,

​

**git init**

을 입력합니다.

그 뒤,

**git remote add origin REPOSITORY ADDRESS**를 입력합니다.

이 때, REPOSITORY ADDRESS는 자신의 Repository 주소를 의미합니다.

​

아까 생성한 Repository로 이동해,

주소를 가져옵니다.

마지막에 .git이 있다는 것을 알아두세요!

​

![](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTVfMjg4/MDAxNTc2NDE3NDA0MDAx._EVA6iKQRIgn0JTdNzVE6bwnKQu1sEwUfj2HWtdJ_JUg.OEnPy6jaW_0C0PgJXTOL9cvQJMSKbvgBlZMp24Dle8wg.PNG.nilsine11202/20191215224240.png?type=w800)

저 주소를 긁어와도 되고,

오른쪽 끝의 아이콘을 눌러 복사해도 됩니다.

​

참고로,

git bash 창에서 붙여넣기를 수행하는 단축키는

**" shift +insert "** 입니다.

(ctrl+v) 안돼요!

​

![](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTVfMTE3/MDAxNTc2NDE3NDU0NzM4.mS5VxKZqLyeVEIqy-VirugEv00Q6MZdL5voSe3XM3zUg.R5cYKxjQRJ3iFUSzRSaoXGM4y7dcwXIBgn1OdzE7yfkg.PNG.nilsine11202/20191215224402.png?type=w800)

이렇게 입력하면 Root Folder가 연결됩니다.

​

다음 포스트에서는,

실제로 commit을 통해

코드를 관리하는 방법에 대해 배워보겠습니다.
