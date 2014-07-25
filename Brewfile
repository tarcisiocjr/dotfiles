# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
install coreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, g-prefixed
install findutils
# Install Bash 4
install bash

# Install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
install vim --override-system-vi
tap homebrew/dupes
tap homebrew/versions
tap homebrew/homebrew-php
install php55 --with-pgsql
install php55-intl php55-xdebug composer php55-mcrypt

# Install other useful tools
install ack
install git
install imagemagick --with-webp
install lynx
install node
install pigz
install rename
install rhino
install tree
install webkit2png
install zopfli
install p7zip
install nmap
install postgresql
install openssl
install curl
install git
install vim
install ssh-copy-id
install npm
install iterm2
install ngrep


# Remove outdated versions from the cellar
cleanup
