# Rails getting started blog

Following the [getting started guide](https://guides.rubyonrails.org/getting_started.html) to re-learn Rails.

My Ruby/Rails setup below, using Homebrew on Mac:
```shell
$ brew install ruby sqlite
# I put homebrew ruby, gems, and sqlite as first in my path.
# This is not officially recommended since it overrides the system-installed /usr/bin/(ruby|gem|sqlite)
$ echo 'export PATH="/opt/homebrew/opt/ruby/bin:/opt/homebrew/lib/ruby/gems/3.3.0/bin:/opt/homebrew/Cellar/sqlite/3.46.0/bin:$PATH"' >> ~/.zshrc && source ~/.zshrc
$ gem install rails
$ ruby --version
ruby 3.3.2 (2024-05-30 revision e5a195edf6) [arm64-darwin23]
$ gem --version
3.5.11
$ rails --version
Rails 7.1.3.4
```
