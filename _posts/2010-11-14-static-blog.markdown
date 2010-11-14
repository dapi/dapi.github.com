--- 
title: Быстрый статичный блог (jekyll)
tags: blog static emacs jekyll dropbox ruby google_analytics disqus heroku
layout: post
category: personal
published: true 

# permalink: statis-blog.html
# date: 2010-11-10
---


# {{ page.title }}

http://www.juev.ru/2010/11/13/jekyll-hyde/

Ух, сколько я всего перепробовал для публикации статей – wordpress, tumblr, blogger, livejournal, zhazhda, habrahabr. У них были свои преимущества и один большой недостаток – сложновть или невозможность модифицировать окружений статей.

А еще так чтобы управлять блогом можно было с моего любимого emacs-а, потому что все эти веб-интерфейсы требуют мышки, а у меня ее нет.

{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}

{{ page.tags | array_to_sentence_string }}
