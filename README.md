# Foodie

A ruby gem created by following Bundler's *[Developing a RubyGem using Bundler](http://bundler.io/v1.12/guides/creating_gem.html)* guide

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'foodie'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install foodie


## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Usage
Example CLI usage:

    $ foodie portray "Broccoli" # prints 'Gross!'
    $ foodie portray "Chicken"  # prints 'Delicious!'

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/michaelnwani/foodie.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
