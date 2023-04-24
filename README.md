## Do it!

* Copy the ssh key from the server [to GHs deployment keys for this repo](https://github.com/jk779/server-dotfiles/settings/keys). `ssh-keygen -t ed25519 -a 128` (or use agent forwarding)
* `cd ~/ && git clone git@github.com:jk779/server-dotfiles.git tmp && mv tmp/.git . && rm -rf tmp && git reset --hard && cp .profile.sample .profile && vim .profile`
* change the emoji
* set the "original" hostname of the machine: `hostnamectl hostname foo.bar.srv.gdn --static`
