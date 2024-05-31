# Nahamcon CTF 2024 Read The Rules & Taylor's First Swift

이번 Nahamcon CTF에서는 그래도 도전해볼만한 문제가 몇 개 있던 것 같다. 특히 Warmup 문제는 생각보다 정말 쉬워서 너무 재밌었다... 그래도 Warmup 문제로 writeup을 쓸 수는 없으니 한 개만 문서화하고 정식 문제로 넘어가야겠다. 


1.Read The Rules 문제 풀이


내가 풀었던 warmup 문제 중 가장 먼저 풀었던 문제는 Read The Rules 문제였다. 내게 생애 첫 플래그를 가져다 준 문제이니 기록해보고 싶었다ㅋㅋ 처음 연합 스터디에서 사이트를 보여주고 '플래그를 찾아보세요!' 하셨을 땐 정말 막막했지만 그래도 이번엔 어떻게든 찾다보면 나온다는 걸 알아서인지 가벼운 마음으로 시작했다.

![스크린샷 2024-05-31 161813](https://github.com/hyozii/WriteUp_Nahamcon-CTF-2024/assets/163365936/63d8cbd1-81ac-408a-99bc-de70c56ca639)

링크를 클릭해 뭐가 있는지 들어가보자.

![스크린샷 2024-05-31 161850](https://github.com/hyozii/WriteUp_Nahamcon-CTF-2024/assets/163365936/1abb8228-c868-4fe5-9ffa-422a02bb21f5)

![스크린샷 2024-05-31 161907](https://github.com/hyozii/WriteUp_Nahamcon-CTF-2024/assets/163365936/7a91159c-7c92-4a88-bb96-7187ef3cba43)


간단한 룰에 대한 설명이고... 별 말 안 쓰여있다. 여기에선 얻을만한 정보가 없을 것 같다. 아 플래그가 이런 형식이라는 걸 보여줬으니 그 부분을 잘 기억하자. 그리고 바로 f12를 눌러 웹 브라우저를 까보자.



이렇게 되어있는데, 처음엔 뭐라는지도 모르고 당황했지만, 지금은 저게 뭘 나타내는지 안다. 왜냐? 난 웹을 공부한 여자니까. elements 부분에 뭐가 있는지 먼저 확인해봐야겠다. 

![스크린샷 2024-05-31 162041](https://github.com/hyozii/WriteUp_Nahamcon-CTF-2024/assets/163365936/78ec71be-b322-47a2-b0c3-6c75cae97e8c)


코드가 정말 많은데, 연합 스터디에서는 이런 부분을 보고 뭐가 있는 거 아니냐 했지만 이젠 속지 않는다. 왜냐? ㅎㅎㅎ웹을 공부했기 때문.

![스크린샷 2024-05-31 162427](https://github.com/hyozii/WriteUp_Nahamcon-CTF-2024/assets/163365936/e37c6829-9026-46d5-b3e3-f30ee508dfd1)


엥 근데 그 뒤에 바로 flag가 보인다. 이거 아닌가????? 맞는 것 같으니까 복붙해서 답이 맞는지 확인해보자.

![스크린샷 2024-05-31 162510](https://github.com/hyozii/WriteUp_Nahamcon-CTF-2024/assets/163365936/df413780-d87e-48fd-8bfd-fd49747bbb2e)


이렇게 넣어보면,

![스크린샷 2024-05-31 162651](https://github.com/hyozii/WriteUp_Nahamcon-CTF-2024/assets/163365936/85eff329-bbe2-4d50-8d25-8c6d3ea77e71)

![스크린샷 2024-05-31 162727](https://github.com/hyozii/WriteUp_Nahamcon-CTF-2024/assets/163365936/be9b686e-5dcf-41c0-af2d-662267fbe676)

오예~~ 맞았다. 와 재밌다... 쉬운 걸 해서 재미있게 느껴지는 거겠지만 그래도 맞추니까 기분이 좋다...


2. Taylor's First Swift 문제 풀이

사실 나는 web 관련 문제를 풀고 싶었는데, 이미 대회가 끝난 터라 web 문제들은 다 웹 사이트에 접속할 수 없었다... 그래서 다른 유형의 문제를 풀어야 했는데, 제목부터 Taylor's First Swift라니... 재밌겠다 싶어 (일단 테일러스위프트 플리를 틀고...) 문제를 풀기 시작했다. (문제 설명 글귀 귀엽다)

![image](https://github.com/hyozii/Writeup_Semester/assets/163365936/ea331f16-96d4-479c-bd1a-67ce5764b9b3)

제목 보고 고른 거라 리버싱 문제인지도 몰랐다. 리버싱 문제는 아이를 이용해 풀거나 리눅스(칼리칼리)를 이용해 푼다고 한다. 리눅스는 그래도 배웠으니까 이참에 새롭게 배워보자 싶어 아이다를 설치했다 (왜그랬을까과거의나?)

![image](https://github.com/hyozii/Writeup_Semester/assets/163365936/281abf11-abb8-440b-894a-2481ae5e6958)

이렇게 아이다를 설치했다. 다운 후에 아이다를 실행해보면 이렇게 보인다.

![image](https://github.com/hyozii/Writeup_Semester/assets/163365936/859fb276-d885-4f24-bc96-82f224bee5ba)

테일러 문제 파일을 다운받은 다음, 그 파일을 아이다에 넣어 실행해보자.

![image](https://github.com/hyozii/Writeup_Semester/assets/163365936/552e2678-1e9b-4f7c-8558-12bdd162ed60)

swift 바이너리 파일인 것을 알 수 있다. 그래서 여러 단계를 거쳐 어셈블리어 해석으로 돌려보려고 했는데....

![image](https://github.com/hyozii/Writeup_Semester/assets/163365936/58672df2-6d89-4ad2-ab7a-baccd62d8938)

여기서 막혀서 이것저것 찾아보다 결국 해결하지 못해서 다른 문제를 풀어보려고 했다... 그런데 ida pro로 사용하면 된다는 검색 결과를 보고 ida pro가 깔려있는 다른 컴퓨터를 잠시 빌려 문제를 다시 풀어봤다...

![image](https://github.com/hyozii/Writeup_Semester/assets/163365936/af6d77b9-37f3-4cdf-bd44-4a47e10dd3a3)


이번엔 제대로 열린다. 다만 저게 뭔지 모르겠을 뿐.... 뭔 코드가 너무 많아서 계속 보는데 내가 그나마 알 수 있는 건 저 배열 부분이랑 type metadata for UInt8 이랑 String.UTF8View 부분밖에 모르겠다. 심지어 UTF 말고 UInt는 뭔지 몰라 검색해보니 Unsigned Integer의 줄임말이라고 한다 (이건 알지... 근데 utf랑 같이 있으니까 뭔 유니코드 같은 건 줄....)

![image](https://github.com/hyozii/Writeup_Semester/assets/163365936/56cca927-52a1-48af-bd3d-ee437503948b)

아이다는 바이너리 파일을 어셈블리어로 재구성해주는 역할을 하는데, 그럼 인코딩/디코딩을 하거나 뭘 변환해서 플래그를 얻어야 하는 것 같다. (아닐 수도)  이 부분은 base64이고,(...?) 배열을 이용하는 함수인 것 같은데, 이때 base64는 바이너리 데이터(지금 파일 데이터)를 (이진 데이터)를 ascii 문자열 형식으로 나타내기 위해 만들어진 인코딩이라고 한다. 


근데 여기에서 뭘 어떻게 해야할지 몰라서 (당연함 아이다도 방금 깔았음) 답답해하다가 저 주황색 이상한 긴 글씨가 보이길래 아닐 걸 알면서도 복붙해서 답안 제출해봤다ㅋㅋㅋ 택도 없지... 근데 그러다가 저걸 이용하는 건 맞는 것 같은데??? 싶어졌다. 예전에 예시 문제 풀어주시면서 저런 값을 발견하고 어느 사이트에 넣어서 변환하니 플래그가 나왔던 기억도 떠오르고 (이해는 못했지만) 봤던 writeup 풀이들에서도 저런 걸 활용하는 것 같았다. 그래서 저걸 활용해보기로 했다. 근데 문제는... 사이트가 기억이 안난다.

계속 검색해서 찾았다 cyberchef라는 사이트이다. base64인 건 알지만 to base64인지 from base64인지 몰라서 확인해보니 to base64는 hello를 aGVsbG8=로 변환하는 것이고, from base64는 aGVsbG8=를 hello로 변환해주는 것 같다. 그러니 나는 from base64를 활용해야 한다. 그리고 아까 파일 안에 있던 코드는 XOR 함수이기 때문에 검색해서 옵션에 xor도 추가해준다. 그리고 인풋에 내가 아까 찾은 주황색 문자열을 입력했는데 내가 예상한대로 아웃풋이 나오지 않았다.


![image](https://github.com/hyozii/Writeup_Semester/assets/163365936/93ee770a-703b-4302-a7a4-ef9cfc064ed8)


뭐가 문제지.... 싶어 계속 이것저것 바꿔봤는데 세상에 xor 키를 hex가 아니라 (hex가 기본 선택되어있었음) utf8 (그래 아까 코드에 이거라고 쓰여있었잖아)를 선택해야 하는 것이었다. 근데 그렇다고 해도 키 값을 모르는데...? 키 값만 찾고 인풋을 넣으면 답을 찾을 수 있을 것 같은데 키 값을 어떻게 찾아야 하는지 너무 막막해서 여기서 포기할까도 생각했다. 그래서 사실 처음엔 여기까지 라이트업을 작성했는데, 자고 일어나보니 배열을 아직 이용하지 않았다는 생각이 들었다. base64 디코딩으로 그 값을 디코딩하고 그 결과를 각각 v5 배열의 값과 xor 연산을 하면 ascii코드로 swifties!가 나온다고 한다. 그럼 이게 키값일테니 키값을 마저 입력하고 인풋을 넣으면? 아웃풋으로 flag가 나온다..................

![image](https://github.com/hyozii/Writeup_Semester/assets/163365936/4c8e7a8e-b8d3-47e3-b2a3-9d828d6d4988)

입력하면? 맞췄다는 표시가 뜬다.

![image](https://github.com/hyozii/Writeup_Semester/assets/163365936/9dde8af7-4ed6-40d8-b36d-c44758881edf)

정말 하나도 모르겠어서 계속 이것저것 찾아보고 비슷한 형식의 라이트업도 확인하고 하다보니 운 좋게 얻은 것 같다. 시간이 너무 많이 걸려서 포기할까도 생각했지만 결국 플래그를 얻으니 기분이 매우 좋았다......이 문제는 쉬운 편이라고 하니 다음엔 또 못 맞출 수도 있겠지만 그래도 너무 뿌듯했다. 



