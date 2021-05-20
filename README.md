# My 4 Favorite Ruby methods
### `zero?`
Returns a `true` boolean if the `Float` returns 0. Otherwise, it returns `false`.
```ruby
0.0.zero? #=> true
```
### `next_year`
This method is called on a Ruby `date` object and it returns the date one year in the future.
```ruby
Date.new(2014, 8, 9).next_year #=> #<Date: 2015-08-09 ...>
```
### `.nil?`
This method can be called on any Ruby `Object` and returns a boolean if that object is `nil` or not. 
```ruby
"string".nil? #=> false
```
### `[](*args)`
Returns a new array populated with the given objects.
```ruby
Array.[]( 1, 'a', /^A/)  # => [1, "a", /^A/]
```