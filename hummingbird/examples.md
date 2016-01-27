---
layout: page_hummingbird
title: "Examples"
group: "hummingbird"
description: ""
---
{% include JB/setup %}


{% highlight python %}
def test(self):
    a = 4 * b
    print a
{% endhighlight %}

```python
def test(self):
    a = 4 * b
    print a
```

{% highlight ruby %}
def foo
    puts 'foo'
    end
{% endhighlight %}

# Some math
$$a = \int_x f(x) dx$$

\\[ \mathbf{X} = \mathbf{Z} \mathbf{P^\mathsf{T}} \\]

# Fancy stuff
<p>4 + 6 = <span ng-bind="4+6"></span></p>

# StoreController (from tutorial)
<div ng-controller="StoreController as store">
    <div ng-repeat="product in store.products">
        <h1><span ng-bind="product.name"</span></h1>
        <h2>$<span ng-bind="product.price"</span></h2>
        <p><span ng-bind="product.description"</span></p>
        <button ng-show="product.canPurchase">Add to Cart</button>
    </div>
</div>
