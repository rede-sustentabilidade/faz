#Faz

## Setup

1. Setup [Ruby on Rails environment](http://installrails.com/steps/choose_os)

2. Run `bundle exec rake db:create db:migrate db:test:prepare`

3. Set `MEURIO_DOMAIN` environment variable:

  `export MEURIO_DOMAIN="lvh.me:3000"`

4. Run meurio_accounts on port 3000:

5. Run Multitude on port 3001 with `rails s -p 3001`
