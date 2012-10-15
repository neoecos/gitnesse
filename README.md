# Gitnesse

 Gitnesse is cucumber-wiki integration tool.
 It enables a project to store cucumber features in a remote git-based wiki.

## Installation

Add this line to your application's Gemfile:

    gem 'gitnesse'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install gitnesse

For Rails 3, create an initializer file config/initializer/gitnesse.rb like this:

    Gitnesse.config do |config|
      config.repository_url = "git@github.com:luishurtado/gitnesse-wiki.git"
    end

## Usage

For Rails 3 there is rake task:

    $ rake gitnesse

There is also available an executable that requires the path to the configuration file:

    $ CONFIG='./gitnesse_config.rb' gitnesse

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
