# Omniauth::Thumbtack

This is a completed and tested Thumbtack strategy using Omniauth Oauth2 and connecting to Thumbtack's API.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'omniauth-thumbtack', git: 'https://github.com/kevinneub/omniauth-thumbtack'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install https://github.com/kevinneub/omniauth-thumbtack

## Usage with Devise

config.omniauth :thumbtack, <CLIENT_ID>, <CLIENT_SECRET>,
  {
    response_type: 'code',
    scope: ''
  }

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/kevinneub/omniauth-thumbtack.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

