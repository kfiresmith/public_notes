## Dir Class important methods
**Chdir method**
```ruby
Dir.chdir("/var/spool/mail")
```
**Entries (list entries)**
Returns array containing all filenames in a given dir
```ruby
Dir.entries("testdir")   #=> [".", "..", "config.h", "main.rb"]
```


**Other useful methods**
```ruby
chroot(string)

delete(string)

exist?(file_name) # True if exists and is a dir
```
**foreach**
```ruby
Dir.foreach("testdir") {|x| puts "Got #{x}" }
```

