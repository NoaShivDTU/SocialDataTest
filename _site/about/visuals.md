---
layout: page
title:  "Assignment 2"
#date:   2025-03-18 11:01:26 +0100
categories: jekyll update
---
What being under the influence does to your family and children.

The data is retrieved from San Francisco police reports, where the crimes reported under the category Offences against the familiy and children, Drunkenness and Drug/Narcotics are selected. In order to only investigate trends in recent years, only years from 2018-2024 are used. 

In order to compare daily patterns of the crime-reports, a polar bar chart is plotted for each of the crime types. 
<div style="padding: 0px 5px; ">
  <iframe 
      src="/plots/bokeh_overlay_plot.html" 
      width="100%" 
      height="900"
      style="max-width: 1200px; margin: auto; display: block; border: none;">
  </iframe>
</div>

<div style="padding: 0px 5px; ">
  <iframe 
      src="/plots/crime_animation_map.html" 
      width="100%" 
      height="900"
      style="max-width: 1200px; margin: auto; display: block; border: none;">
  </iframe>
</div>

<img src="/polar_subplots.png" width="100%" height="300" alt="Polar Subplots" style="border:none;">
Caption 1: polar bar chart of each crime type for hour of the day
The polar bar chart shows that drug and narcotic-related crimes mostly occur during the afternoon and follow a somewhat similar pattern compared to the other two crime types. Reports of offences against the family and children are fairly spread throughout the day, with noticeable spikes around noon and midnight. These same spikes are also observed for drunkenness, although many of the reported cases of drunkenness primarily occur during the middle of the day and afternoon.

These spikes in drunkenness and  offences against the familiy and children occuring during the same time of day could indicate that a correlation between those two could be investigated.


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
