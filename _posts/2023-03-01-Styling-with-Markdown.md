---
layout: post
author: Zhang Bo
title: Styling with Markdown
---

First blog with markdown as an example.

This post can be found in `_posts` directory. Go ahead and edit it and re-build the site to see the changes.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.md` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

## Some great heading (h2)

> Stay Hungry Stay Foolish

### Some great subheading (h3)

Jekyll offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Haskell 优雅地实现快排

```haskell
quick_sort :: Ord a => [a] -> [a]
quick_sort [] = []
quick_sort [x] = [x]
quick_sort (x:xs) = quick_sort (filter (<= x) xs)
                    ++ [x]
                    ++ quick_sort (filter (> x) xs)
```

#### You might want a sub-subheading (h4)

Text here.

### An unordered list!!

- First item
- Second item
- Third item
- Fourth item

### An ordered list!!

1. First item
2. Second item
3. Third item
4. Fourth item

## Headings are cool! (h2)

### Tables

| Title 1 | Title 2 | Title 3 | Title 4 |
| ------- | ------- | ------- | ------- |
| lorem   | lorem   | lorem   | lorem   |
| lorem   | lorem   | lorem   | lorem   |
| lorem   | lorem   | lorem   | lorem   |

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
