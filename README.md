# mruby-first_gem   [![Build Status](https://travis-ci.org/Zepprix/mruby-first_gem.svg?branch=master)](https://travis-ci.org/Zepprix/mruby-first_gem)
FirstGem class
## install by mrbgems
- add conf.gem line to `build_config.rb`

```ruby
MRuby::Build.new do |conf|

    # ... (snip) ...

    conf.gem :github => 'Zepprix/mruby-first_gem'
end
```
## example
```ruby
p CalcPI.new.leibniz 
#=> 3.151493401070993
p CalcPI.new.babylonian_sqrt(2)
#=> (6632452706042512/4689852284341727)
p CalcPI.new.gauss_l.to_s
#=> 3.141592653589792
```

## License
under the MIT License:
- see LICENSE file
