# dotfiles #

## Pre-installation ##
1. Download [Linux Mint](http://www.linuxmint.com/download.php)
2. Burn on DVD
3. Boot up from DVD
4. [Install the system](http://www.youtube.com/watch?v=BEzH3liL3y4)
5. Install git: 

<code>
sudo aptitude install git-core
</code>

## Installation ##

### Download dotfiles ###

<code>
cd ~
git clone git://github.com/fractalsoft/dotfiles ~/.dotfiles
</code>

### Install packages (as root) ###

<code>ddd
~/.dotfiles/sudo_install.sh
</code>

### Install Ruby (as user) ###

<code>
~/.dotfiles/install.sh
</code>

#### Sublime Text 2 (like IDE)  ####
All keys press in Sublime Text 2.

##### Install Sublime Text 2 Package Control #####
Press <code>Ctrl + `</code>.

Paste 
<pre>
import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print 'Please restart Sublime Text to finish installation'
</pre>
in command line and press enter.

##### Use Sublime Text 2 Package Control #####
1. Press <code>Ctrl + Alt + p</code>.
2. Write word <code>install</code> in the input. Select <code>Package Control: Install Package</code>.

3. Select interesting package and click.

#### Chrome / Chromium ####

##### Plugins #####
[Live Reload](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei)


## Initialize ##

<pre>
cd ~
~/.dotfiles/init.sh
</pre>

## Use ##
TODO
