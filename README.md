#bento-dev.github.io

This is the project page for [bento-dev website](http://bento-dev.github.io).
Bento Ubuntu Remix is an Ubuntu Openbox Remix made easy which exists since 2012, as LTS only.

#Who's this for?
Bento Ubuntu Remix distributions are meant for all sorts of users, and can be installed to machines ranging from more or less 10 years old computers with at least 768 MB  RAM and a 1 Ghz capable CPU and the most recent PC's. It could be installed on machines with lower capability but I don't advice it as it would be uncomfortable with perceptible lag between the user action and the machine reaction. 
It is made easy for the end users while lighter than other versions coming with a full fledged desktop, and it is also made easy for the advanced users who will come to install it to newcomer's machines. The reason is that Bento comes with a few handy tools which most end users won't ask for, but that the person who will perform installs and post installation fine-tuning for them should appreciate. :-)


#Versions and Updates
The versions provided here are built on Ubuntu Mini Remix 12.04, as LTS, so they will benefit of the (unofficiel) support until 2017, time when the 12.04 won't be supported anymore.

The ISOS distributed here are at the 12.04.4 stage, mostly up to date. See at the index the time when they have been uploaded, it should give you a pretty good idea of when they have been updated before built.

The basis used is Ubuntu Mini Remix, 
https://answers.launchpad.net/ubuntu-mini-remix/+faq/33 and the tool used is Ubuntu Builder, https://launchpad.net/~f-muriana/+archive/ubuntu-builder, unfortunately not developed anymore since March 10th, 2014:
https://launchpad.net/ubuntu-builder/+announcement/12508

(which obviously means the next Bento LTS, Trusty, will be built with other
tools).

The kernel in the x86_64 version is Ubuntu 3.8.0-xy-generic (at the moment, 3.8.0-37-generic), and obviously it has the PAE capability.

The kernel in the i686 version is Ubuntu 3.2.0-xy-generic (at the moment, 3.2.0-60), and this is the last serie of officiel kernels which doesn't come with the PAE capability, therefore if you need the PAE capability, you will be invited to switch kernel once the system is installed.

Or if you need a version with another kernel from the repos already in the distribution, just send me a message at the http://linuxvillage.org forum, and I might make one for you, if you are not too much in a hurry.

Both i686 and x86_64 come with the same user applications and setting.

Enjoy!!

##requirements

- ruby [jekyll](http://jekyllrb.com/) gem
