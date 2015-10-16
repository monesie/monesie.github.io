---
layout: post
title: "Hank Quinlan, Horrible Cop, Launches Site"
date: 2014-04-30
myOwnTag: "hello there"
---

Well. Finally got around to putting this old website together. Neat thing about it - powered by [Jekyll](http://jekyllrb.com) and I can use Markdown to author my posts. It actually is a lot easier than I thought it was going to be.

# Header Test Markdown

**Is this Bold?**

fesfes **BOLLLD?** fsef
f


__Hello__


{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

{% highlight C# %}
public void MyFunction(int myInt, float myFloat)
{
	var myVar = new Bla();

	myVar.Hello();
}
{% endhighlight %}

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
{% gist 1027674 %}

fesfsefs