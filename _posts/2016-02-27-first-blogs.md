---
layout: post
title:  "My First Blog!"
date:   2016-02-27 21:41:37 +0800
---
### Overview
Today i was very happy. In the Morning, I install the
Ubuntu 15.10 and install the [Flatabulous](https://github.com/anmoljagetia/Flatabulous)
theme. It looks perfect and I decide to use Ubuntu as my main OS.
Then I try to install lasest Ruby in Ubuntu. But use the apt-get 
command just install the old version Ruby. Then after search in
Goggle, I decide to use [RVM](https://rvm.io/) to install the lasest 
Ruby.
First, I install RVM

> gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3

> \curl -sSL https://get.rvm.io | bash -s stable

Then we use rvm to install lasest Ruby(Ruby-2.3.0).

> rvm install 2.3.0

Then make sure the lasest ruby is default.

> rvm use 2.3.0 --default

Then we can use gem command to install [Jekyll](http://jekyllrb.com/)

> gem install jekyll

The we can use jekyll command to create new blogs.

> jekyll new Blogs

And we browse in `http://localhost:4000` after

> jekyll serve

<!-- break -->

After my finsh our code, we can put it on GitHub.