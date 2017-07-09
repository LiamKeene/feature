# Feature
Wrapper to rollout gem.

Allow you to have default yml file so that you don't need redis and rollout running on every environment.
( ei. front-end development or local testing).

Give a webview to enable/disable features.

## Usage
How to use my plugin.
<!-- TODO -->

### Feature definition and default
Define feature and default on feature.yml file.
You can define different default value per environment.

### Boolean Feature
<!-- TODO -->

### Data Feature
<!-- TODO -->


## Installation
Add this line to your application's Gemfile:

```ruby
gem 'feature'
```

And then execute:
```bash
$ bundle
```

Or install it yourself as:
```bash
$ gem install feature
```

Then Run installer to create feature initializer and yml

```bash
$ rails g feature:install
```

Mount the web views on your application adding to routes
```
mount Feature::Engine => "services/feature"
```
## Todo


## License
The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

