# RSpec TextMate Bundle

## TextMate Bundle for RSpec-1 and RSpec-2

This TMBundle works with both rspec-1 and rspec-2. Given that they work
differently, the TMBundle tries its best to figure out which one you're using
in each project.

If you're using Bundler in your project, the TMBundle will always do the right
thing based on the version of RSpec specified in your Gemfile.

If you're not using Bundler, the TMBundle tries to do the right thing based the
presence of assorted files and paths in your project. Obviously, everybody's
environment is going to be a bit different, so let us know if this doesn't work
for you by filing an issue at
[http://github.com/rspec/rspec-tmbundle](http://github.com/rspec/rspec-tmbundle)
and we'll do our best to resolve the situation.

## Installation

    cd ~/Library/Application\ Support/TextMate/Bundles/
    git clone git://github.com/rspec/rspec-tmbundle.git RSpec.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

## Configuration

The RSpec TextMate bundle does not `require "rubygems"` so that users who choose
other packaging mechanisms can still use it. If you _are_ using Rubygems as your package
manager, then the simplest thing to do is

* open up TextMate Preferences
* go to the Advanced tab
* add a variable named `RUBYOPT` with the value `rubygems`

## History
Parts of RSpec.tmbundle is based on Florian Weber's TDDMate.

## License
The license of RSpec.tmbundle is the same as [RSpec](http://github.com/rspec/rspec/blob/master/License.txt)'s.

