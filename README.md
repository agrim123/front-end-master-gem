# MaterialMaster

Welcome to your material_master gem! It comprises of material design libraries including materialize( a modern responsive front-end framework based on Material Design.) and Google material icons library. 

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'material_master'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install material_master

## Usage
### a. CSS

require the following files in application.css

```scss
	*= require materialize
	*= require material-icons
```
### b. Javascript
 require the following files in application.js

```js
	//= require materialize
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/agrim123/material_master.

## License

MIT

