---
layout: post
title: 자주 사용할 vi 단축키 정리
comments: true
---

프로젝트를 진행하면서 vi를 사용하기 시작했다.

학교 다닐 때에도 주변에서 몇몇 쓰는 사람들이 보였지만 그 당시엔 리눅스 프로그래밍이 익숙하지 않아서 넘어갔었는데 이걸 여기서 쓰게 될 줄이야.

오랜만에 생각이 나서 친구에게 물어보니 정리된 이미지를 뽑아놓고 그거 보고 하라고 한다.

그 중에서 가장 자주 사용하게 될 명령어만 외울겸 몇 개 정리해 보았다.

h - 왼쪽 한 칸 이동
j - 아래 한 칸 이동
k - 위 한 칸 이동
l - 오른쪽 한 칸 이동

w - 다음 단어
b - 이전 단어

i - 편집 모드
I - 줄 맨 앞에 삽입
o - 아랫줄에 삽입
O - 윗줄에 삽입

x - 글자 삭제
r - 한 글자 교체

y - 복사
p - 커서 뒤에 붙여넣기
P - 커서 앞에 붙여넣기

/ - 찾기

참고) Vi/Vim 단축키 모음 - https://kldp.org/node/102947

{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://sjh90.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}