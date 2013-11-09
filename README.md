# spring-commands-testunit

This gem implements a `testunit` command for
[Spring](https://github.com/jonleighton/spring), which supports running
a file/directory of `Test::Unit`-style tests:

```
spring testunit test/controllers/posts_controller_test.rb
spring testunit test/controllers
```

It's no longer necessary if you're on Rails 4, since in Rails 4 you can
pass the file/directory to the `rake test` command:

```
spring rake test test/controllers/posts_controller_test.rb
spring rake test test/controllers
```

## Usage

Add to your Gemfile:

``` ruby
gem "spring-commands-testunit"
```
