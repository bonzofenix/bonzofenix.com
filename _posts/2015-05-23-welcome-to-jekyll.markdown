---
layout: post
title:  "Setting your own nameserver with DNSChain"
date:   2015-05-23 23:46:52
categories: jekyll update
---

If you are asking yourself what is DNSChain make sure not to miss the following video. IMO its a must if you are into DevOps and cryptocurrencies.

<iframe width="420" height="315" src="http://www.youtube.com/embed/DGe-TOI1180" frameborder="0" allowfullscreen></iframe>

The second pice of knowledge that you will need is namecoin. 
Namecoin is a blockchain base technology cryptocurrency that let you:

- Securely record and transfer arbitrary names (keys).
- Attach a value (data) to the names
- Transact namecoins, the digital currency (ℕ, NM)

Amoung its uses it stores .bit domains.
related video:
<iframe width="420" height="315" src="http://www.youtube.com/embed/iNCxJ-k0A8xY" frameborder="0" allowfullscreen></iframe>



AS a PoC I decided to get my own nameserver and give also bonzofenix.bit got my own nameserver with DNSChain deployed on AWS and register bonzofenix.bit in namecoin.

For saveing someone the struggle with this I will describe and point to the resources that helped me.

1. ## Get a .bit domain register
2. ## Referencing .bit domain to website
3. ## Setting my personal nameserver base on DNSChain

There is a well documented document on how to setup DNSChain locally and on ubuntu.

For the sake of reproductibility I put together a Vagrant machine that can perform the deployment of the DNSChain server on AWS or locally.


{% highlight bash %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}











Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
