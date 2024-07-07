# My Blog Website
https://mateus2k2.github.io/en/
https://mateus2k2.github.io/pt/


## Install
sudo apt-get install zlib1g-dev

brew install rbenv

export PATH="$HOME/.rbenv/bin:$PATH"
eval "$(rbenv init -)"

rbenv install 3.1.2

bundle install

## Run
bundle exec jekyll serve -d ./genereted/en --source ./blog/en --config _config_en.yml
bundle exec jekyll serve -d ./genereted/pt --source ./blog/pt --config _config_pt.yml

## License

This work is published under [MIT][mit] License.

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[chirpy]: https://github.com/cotes2020/jekyll-theme-chirpy/
[use-template]: https://github.com/cotes2020/chirpy-starter/generate
[CD]: https://en.wikipedia.org/wiki/Continuous_deployment
[mit]: https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE
