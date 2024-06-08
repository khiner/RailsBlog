# Rails getting started blog

Following the [getting started guide](https://guides.rubyonrails.org/getting_started.html) to re-learn Rails.

My Ruby/Rails setup below, using Homebrew on Mac:
```shell
$ brew install ruby sqlite
# I put homebrew ruby, gems, and sqlite first in my path.
# This is not officially recommended since it overrides the system-installed /usr/bin/(ruby|gem|sqlite)
$ echo 'export PATH="/opt/homebrew/opt/ruby/bin:/opt/homebrew/lib/ruby/gems/$(ls /opt/homebrew/lib/ruby/gems)/bin:/opt/homebrew/opt/sqlite/bin:$PATH"' >> ~/.zshrc && source ~/.zshrc
$ gem install rails
$ ruby --version
ruby 3.3.2 (2024-05-30 revision e5a195edf6) [arm64-darwin23]
$ gem --version
3.5.11
$ rails --version
Rails 7.1.3.4
$ sqlite3 --version
3.46.0 2024-05-23 13:25:27 96c92aba00c8375bc32fafcdf12429c58bd8aabfcadab6683e35bbb9cdebf19e (64-bit)
```

After that ...
```
$ rails new blog
```
... and so on, following the guide.
