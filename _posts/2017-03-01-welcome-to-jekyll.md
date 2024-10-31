---
title: "Welcome to My test website"
layout: post
---
<script>
  $(document).ready(function() {
    $("#my life").css('color', 'red');
    $("#my goals").html('<em>#my goals</em>');
  });
</script>

<div class="container-fluid">
  <h3 class="text-primary text-center">Additional info</h3>
  <div class="row">
    <div class="col-xs-6">
      <h4>#top</h4>
      <div class="well" id="left-well">
        <button class="btn btn-default target" id="my life">#my life</button>
        <button class="btn btn-default target" id="my goals">#my goals</button>
        <button class="btn btn-default target" id="my hobbies">#my hobbies</button>
      </div>
    </div>
    <div class="col-xs-6">
      <h4>#bottom</h4>
      <div class="well" id="right-well">
        <button class="btn btn-default target" id="my desires">#my desires</button>
        <button class="btn btn-default target" id="my achievements">#my achievements</button>
        <button class="btn btn-default target" id="others">#others</button>
      </div>
    </div>
  </div>
</div>
under construction



{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

under construction

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
