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
**Hashes**
```ruby
my_hash = {"key" => "value", "old bannana" => "tasty"}

puts my_hash["old bannana"]
>tasty
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


### Resources
[Code Academy:  Free Ruby intro course](https://www.codecademy.com/learn/ruby)

[Linux Academy: Paid Ruby intro course](https://linuxacademy.com/cp/modules/view/id/32)
