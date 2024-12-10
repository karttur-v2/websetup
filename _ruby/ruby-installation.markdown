---
title:  "Ruby installation"
layout: single
permalink: /websetup/ruby/ruby-installation
author_profile: true
---

To install and maintain a separate version of Ruby on your MacOS, you can choose from a range of approaches. I use the package manager [Howebrew](https://brew.sh). Installing Homebrew is fairly easy and explained on the home page.

Once Homebrew is installed you can go on to install Ruby. But you have to make up your mind if you want a bare-bone installation or if you prefer to use a software version manager.

## Ruby version managers

When I built the [first version of Karrtur's website](kartturv1), I used [Homebrew and Ruby Version Manager RVM](karttur_setup-blog-tools). Since then more alternatives have become available. Apart from [RVM](rvm), there are also [Asdf][asdf], [Chruby][chruby] and [Frum][frum], and more, version managers available. The ones mentioned above can all be installed via [Homebrew][homebrew].

Having tried out [RVM][rvm] and [Chruby][chruby], and run into troubles with updating individual gem packages, I found the blog on [installing Ruby on MacOS][ruby4macos] by Daniel Kehoe. I recommend using Daniel's site for your MacOS installation of Ruby.

In the end I skipped using a version manager and installed a bare-bone Ruby version using [Homebrew][homebrew]:

```
brew install ruby
```

For details on how to do this, see the [Brew Install Ruby][ruby4macos_13] post by Daniel Kehoe.

This installed version 3.5.5. When deploying my pages using this Ruby version and the [Jekyll theme Minimal Mistakes][mmistakes], I got security warnings and had to update first Ruby and its Gems and then Minimal Mistakes. The topic of the last document in this collection.

## Resources

[Howebrew][homebrew]

[RVM][rvm]

[Asdf][asdf]

[Chruby][chruby]

[Frum][frum]

[blog on installing Ruby on MacOS][ruby4macos]

[Minimal Mistakes Jekyll Theme][mmistakes]

[homebrew]: https://brew.sh

[rvm]: https://rvm.io

[asdf]: https://asdf-vm.com

[chruby]: https://github.com/postmodern/chruby

[frum]:https://github.com/TaKO8Ki/frum

[mmistakes]: https://mmistakes.github.io/minimal-mistakes/

[kartturv1]: https://karttur.github.io

[karttur_setup-blog-tools]: https://karttur.github.io/setup-blog/2017/12/21/setup-blog-tools.html

[ruby4macos]: https://mac.install.guide/ruby/

[ruby4macos_13]: https://mac.install.guide/ruby/13
