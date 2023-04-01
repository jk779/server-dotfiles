## Do it!

* Copy add ssh key from the server to GH `ssh-keygen -t ed25519 -a 128`
* `cd ~/ && git clone git@github.com:jk779/server-dotfiles.git tmp && mv tmp/.git . && rm -rf tmp && git reset --hard`
* `cp .profile.sample .profile` and change the emoji
