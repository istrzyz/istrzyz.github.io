layout: post
title: Blocitoff
thumbnail-path: "img/blocitoff.png"
short-description: blocitoff is a way to get tasks done.

{:.center}
![]({{ site.baseurl }}/img/blocitoff.png)


{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
