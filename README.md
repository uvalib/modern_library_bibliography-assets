# ModernLibraryBibliography::Assets

This is a gem whose entire purpose is to encapsulate some static resources associated with the 
Modern Library Bibliography project at the University of Virginia.

This includes:
- preview-sized images of the coded Torchbearer Images (Modern Library logo)
- metadata about said images
- copies of the variations on the publisher's note


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'modern_library_bibliography-assets' git: 'https://github.com/uvalib/'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install modern_library_bibliography-assets

## Usage

Simpley add the following to the facets partial:

    $ <%= javascript_include_tag 'ml-facet-enhance' %>
    $ <%= stylesheet_link_tag 'ml-facet-enhance' %>
    
Note: this code is dependent on the specific versions of jquery as well as the specific class assignment for elements 
in the facet display in order to work.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake false` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/uvalib/modern_library_bibliography-assets.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

