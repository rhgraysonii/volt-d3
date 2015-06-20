# Volt-D3

# NOTE: This software is currently deprecated outside of the inclusion of D3 source

<a href="http://d3js.org"><img src="http://d3js.org/logo.svg"></a>

This component includes D3.js in Volt's assets when added

## Installation

Add this line to your application's Gemfile:

    gem 'volt-d3'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install volt-d3

Proceed to add it to `dependencies.rb`

```RUBY
component 'd3'
```

## Usage
Use the standard D3.js API in the FE and you will have access to all endpoints

There is an example applicatoin that draws a circle that fills with a new color when moused over [here](example).

## TODO
I am currently working on getting proper Ruby bindings for the larger API functionalities.

## Contributing

1. Fork it ( http://github.com/rhgraysonii/volt-d3/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
