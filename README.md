# laurenmackey.github.io
Personal Website

## First-time setup
```
# clone repo
git clone https://github.com/laurenmackey/laurenmackey.github.io.git

# make sure jekyll, node, and bundler are installed
jekyll -v
node -v
bundler -v

# NOTE: if the step above doesn't work, may need to re-install ruby:
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install ruby
echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.bash_profile
source ~/.bash_profile

# install ruby gems
bundle install
```
    
## Run
`bundle exec jekyll serve --config _config.yml,_config-dev.yml`

## Visit dev site
`http://localhost:4000`

## Deploy
- site is set up to automatically deploy via Netlify
- deploy should be automatically triggered once code is pushed
