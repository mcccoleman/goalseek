# GoalSeek

This gem implements a method similar to Microsoft Excel's GoalSeek macro. According to Microsoft,
GoalSeek uses a simple linear search:
> The Goal Seek command uses a simple linear search beginning with guesses on the positive or negative side of the
> value in the source cell (By Changing Cell). Excel uses the initial guesses and recalculates the formula.
> Whichever guess brings the formula result closer to the targeted result (To Value) is the direction (positive or
> negative) in which Goal Seek heads. If neither direction appears to approach the target value, Goal Seek makes
> additional guesses that are further away from the source cell. After the direction is determined, Goal Seek uses
> an iterative process in which the source cell is incremented or decremented at varying rates until the target value
> is reached.

Source: https://support.microsoft.com/en-us/help/100782/xl-method-used-by-goal-seek-to-find-a-solution

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'goalseek'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install goalseek

## Usage

TODO: Write usage instructions here

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/pehlert/goalseek.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Goalseek project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/pehlert/goalseek/blob/master/CODE_OF_CONDUCT.md).
