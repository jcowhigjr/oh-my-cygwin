Changed apt-cyg source to a more recent (and multi-arch aware) version of the apt-cyg script. Now works as intended.

Warning, this currently attempts to disable certificate checks on the mirrors it uses, this doesn't always work and sometimes endlessly fills the terminal with a warning about the certificate from GnuPG. I have no idea why. USE AT OWN risk.

--

# OH MY CYGWIN

Looking for a real Terminal for Windows?
Relax you just found it. This sets up a working ZSH Shell powered by [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) and the [apt-cyg](https://github.com/kou1okada/apt-cyg) package manager.

I took care of installing and configuring some packages so that you have vim, git and ssh just one keystroke away.

# Setup

Install [cygwin](http://www.cygwin.com/) with wget (check wget in the installation process) then start cygwin and execute 

    wget --no-check-certificate https://raw.github.com/DougBarry/oh-my-cygwin/master/oh-my-cygwin.sh -O - | sh

Et Voila!
Your windows Terminal will look like this

![oh-my](https://coderwall-assets-0.s3.amazonaws.com/uploads/picture/file/1297/oh-my-cygwin.PNG "OH-MY-OH-MY")
