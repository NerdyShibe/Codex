# Ruby

Ruby is a dynamic, open-source programming language with a focus on simplicity and productivity. It has an elegant syntax that is natural to read and easy to write.

## Introduction

Ruby was created by Yukihiro "Matz" Matsumoto in the mid-1990s. It was designed to make programming happy. Everything in Ruby is an object, which gives it great flexibility.

## Getting Started

### Installation

To check if you already have Ruby installed, open your terminal and type:

```bash
ruby -v
```

If it is not installed, you can use a version manager like `rbenv` or `rvm` (highly recommended), or install it via your system's package manager.

### Your First Program

Create a file named `hello.rb` and add the following line:

```ruby
puts "Hello, World!"
```

Run it from your terminal:

```bash
ruby hello.rb
```

`puts` stands for "put string" and prints text to the screen.

## Basic Syntax

### Variables

You don't need to declare types in Ruby.

```ruby
name = "Fernando"
age = 30
is_developer = true
```

### Methods

Methods are defined using the `def` keyword and end with `end`.

```ruby
def greet(name)
  "Hello, #{name}!"
end

puts greet("Fernando") # Output: Hello, Fernando!
```

*Note: The last evaluated expression in a method is automatically returned.*

### Control Structures

```ruby
if age > 18
  puts "Adult"
else
  puts "Minor"
end
```

## Resources

- [Official Ruby Site](https://www.ruby-lang.org/en/)
- [Ruby Documentation](https://ruby-doc.org/)
- [Ruby on Rails](https://rubyonrails.org/) (The most popular web framework for Ruby)
