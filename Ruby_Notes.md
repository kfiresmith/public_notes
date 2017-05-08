# Ruby Notes

### Basics
#### Printing (puts)
```ruby
puts "Some string to putput"
```
#### User Input (gets)
```ruby
input = gets
```
#### Variable Types and Formatting
**Arrays**
```ruby
my_empty_array = []
my_array = [0,1,2,3,4]
```
**Multi-dimensional Array**
```ruby
nested_array_foo = [["string one", true], ["string two", false]]
nested_array_foo[0][0]
> "string one"
nested_array_foo[1][0]
> "string two"
nested_array_foo[1][1]
> false
```
**Hashes**
```ruby
my_hash = {"key" => "value", "old bannana" => "tasty"}

puts my_hash["old bannana"]
>tasty
```
**Nested Hash**
```ruby
nested_hash = {"car" => {"tires" => true, "skis" => false}}
nested_hash["car"]["skis"]
> false
```
#### Logic
**If, elsif, else, end**
```ruby
if my_var > 10
  ...
elsif my var < 5
  ...
else
  ...
end
```
**Case**
```ruby
case my_var
  when a
    ...
  when b
    ...
  when c
  else
    ...
end
```
**One-line conditionals**
```ruby
puts "var over ten" if my_var > 10
```
**Negated conditional**
```ruby
unless my_var > 10
  puts my_var
end
```
```ruby
if !my_var == 10
  ...
end
```

**Test multiple conditions**
```ruby
if my_var == 5 && your_var ==7
  ...
end

if my_var == 5 || your_var ==7
  ...
end
```
#### Important Methods:  Conversions
**Convert to integer**
```ruby
user_input = gets.to_i
```
**Convert to string**
```ruby
some_number.to_s
```
#### Iterators
**.each** (Similar to for loop)
```ruby
some_list.each do |my_list_item|
  puts my_list_item
end

some_hash.each do |key, value|
  ... key ... value
end
```
### Accessing Documentation
**Ruby Docs Index**
```ruby
ri -l -d /usr/share/ri/system
```
### Resources
[Code Academy:  Free Ruby intro course](https://www.codecademy.com/learn/ruby)

[Linux Academy: Paid Ruby intro course](https://linuxacademy.com/cp/modules/view/id/32)
