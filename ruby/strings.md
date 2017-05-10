### Strings Notes

**Interpolations**

Evaluation rather than simple concatenation
```ruby
how_many = 4
others = 3
puts "You have #{how_many + others} apples."
```
[String Interpolation](http://ruby-for-beginners.rubymonstas.org/bonus/string_interpolation.html)

**Useful Methods**
```ruby
.upcase
.downcase

.length

.reverse

.split(" ") # Split each portion of a string into an array element, eg:
  array = some_var.split(";")

str * integer -> new_str # eg:
  "ho" * 3 #=> "ho ho ho"
```
