#Case Statements Quiz

## Objectives

1. Distinguish a case statement from other patterns
2. Identify when to use a case statement
3. Write a case statement

???

# Quiz

?: Which of the following is a case statement

A.

```ruby
name = "Steven"

if name == "Steven"
  "Hi, #{name}"
else
  puts "Hi, stranger!"
``` 

B.

```ruby
name = "Steven"

case name
  when "Steven"
    puts "Hi, #{name}"
  when "Amanda"
    puts "Welcome back, #{name}"
  when "Admin"
    puts "You have all the power!"
  end
``` 

C.

```ruby
def case
  puts "Am I a case statement?"
end

case
```

( ) A
(X) B
( ) C

?: Of the following two examples, which example uses the case statement the best?

A.

```ruby
name = "Steven"

case name
  when "Steven"
    puts "Hi, #{name}"
  when "Amanda"
    puts "Welcome back, #{name}"
  when "Admin"
    puts "You have all the power!"
  end
```

B.

```ruby
grade = 95

case grade
  when 90..100 then "A" 
  when 80..90 then "B"
  when 70..80 then "C"
  when 60..70 then "D"
  when 0..60 then "F"
end
```

C. Neither are good as case statements

( ) A
(X) B
( ) C

?: Which operator does a case statement use to compare the value to the conditions?

(X) `===`
( ) `==`
( ) `=`

???

<a href='https://learn.co/lessons/case-statements-quiz' data-visibility='hidden'>View this lesson on Learn.co</a>
