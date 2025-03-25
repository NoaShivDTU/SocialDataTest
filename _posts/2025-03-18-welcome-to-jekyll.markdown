---
layout: post
title:  "Assignment 2"
#date:   2025-03-18 11:01:26 +0100
categories: jekyll update
---
<iframe src="/plots/bokeh_plot.html" width="700" height="500" style="border:none;"></iframe>
<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px;">
    <iframe src="/plots/map_hooray_offences.html" width="100%" height="250" style="border:none;"></iframe>
    <iframe src="/plots/map_hooray_drunk.html" width="100%" height="250" style="border:none;"></iframe>
    <iframe src="/plots/map_hooray_drug.html" width="100%" height="250" style="border:none;"></iframe>
</div>
<img src="/polar_subplots.png" width="100%" height="300" alt="Polar Subplots" style="border:none;">

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
