**Note:**
FiFo website uses Jekyll and Github-pages for the projects website.

- [https://jekyllrb.com/]
- [https://pages.github.com/]

**Local Dev Environment on OSX El Capitan**
```shell
sudo chown -R $(whoami):admin /usr/local
cd /usr/local && git fetch && git reset --hard origin/master
brew update
brew install ruby
gem install jekyll
```

**This step may be optional**

```shell
echo "gem: -n/usr/local/bin" >> ~/.gemrc
rehash
```

**To get project fifo website installed with jekyll**

```shell
git clone https://github.com/project-fifo/project-fifo.github.io.git
cd project-fifo.github.io
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000/` in web browser
