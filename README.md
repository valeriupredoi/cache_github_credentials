```
git config credential.helper store
sudo apt-get install libsecret-1-0 libsecret-1-dev
cd /usr/share/doc/git/contrib/credential/libsecret
sudo apt-get install make  # optional
sudo apt-get install gcc  # optional
sudo make
git config --global credential.helper /usr/share/doc/git/contrib/credential/libsecret/git-credential-libsecret
```