---
layout: post
title: 프로젝트 시작
comments: true
---

프로젝트를 본격적으로 시작했다.

조원들 중에서는 내가 그나마 최근에 스프링을 사용해보았기 때문에 프로젝트의 기본 구조를 잡고 그 구조에 맞춰서 각자 개발을 진행하기로 했다.

다른 사람들에 비해서 최근이지 잘 쓴다고는 할 수가 없어서 많이 불안하지만 없는 기억력을 짜내서 최대한 비슷하게 만들었다.

간단한 메일서비스를 만들어 보는 프로젝트인데 핵심부분을 몇가지로 구분해 보았다.

메일 읽기
메일 쓰기
메일 보관함
로그인

위 네가지로 구분하여 각자 맡아서 진행하는 것으로 하였으며, 작업량이 개개인마다 다르므로 먼저 끝난 쪽이 부족한 쪽에 붙어서 도와주기로 하였다.

기간이 일주일이라 많이 빡빡해서 기본적인 기능이나 구현 할 수 있을지 불안하지만, 반면에 정말 오랜만에 진행하는 프로젝트라 재미있을 것 같다는 생각도 든다.

무사히 완성할 수 있었으면 좋겠다.

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