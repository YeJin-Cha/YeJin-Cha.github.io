---
layout: post
title:  "Vue JS Guide"
date:   2022-10-01 17:06:43 +0900
categories: vue
---
Vue.js 개요
=============
vue는 사용자 인터페이스를 위한 JavaScript 프레임 워크 입니다.   
기본적인 웹 프론트 처럼 표준 HTML, CSS 및 JavaScript 를 기반으로 구축되며, 사용자 인터페이스를 더 편하게 개발 할 수 있도록 컴포넌트 기반 프로그래밍 모델을 제공합니다.   
> Componenet Programing   
> 컴포넌트란 프로그래밍에 있어서 재사용이 가능하도록 만듵 각각의 독립된 모듈을 말합니다.   

간단한 vuejs 예제 : 
{% highlight javascript %}
import { createApp } from 'vue'

createApp({
  data() {
    return {
      count: 0
    }
  }
}).mount('#app')
{% endhighlight %}

{% highlight html %}
<div id="app">
  <button @click="count++">
    숫자 세기: {{ count }}
  </button>
</div>
{% endhighlight %}



Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
