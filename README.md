# Hierapolis::Rails

This gem using to  integrate [hierapolis](https://github.com/kebab-project/hierapolis) theme  on rails project.

## Installation

This gem requires

```ruby
gem 'bootstrap-sass', :git => 'git://github.com/thomas-mcdonald/bootstrap-sass.git', :branch => '3'
```

Add this line to your application's Gemfile:

    gem 'hierapolis-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install hierapolis-rails

Run the generator:

```ruby
rails g hierapolis:install
```

## Usage

Add these lines to application.css

```ruby
@import "hierapolis"
```

Add these lines to application.js
```ruby
#= require bootstrap
#= require hierapolis
```


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Credits

![lab2023](http://lab2023.com/assets/images/named-logo.png)

- hierapolis-rails is maintained and funded by [lab2023 - information technologies](http://lab2023.com/)
- Thank you to all the [contributors!](https://github.com/lab2023/hierapolis-rails/graphs/contributors)
- The names and logos for lab2023 are trademarks of lab2023, inc.

## License

Copyright 2014 lab2023 – information technologies