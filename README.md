# Case Statements Quiz

## Objectives

1. Distinguish a case statement from other patterns
2. Identify when to use a case statement
3. Write a case statement


**Note:** If you see concepts in the quiz that you might not have seen before, then Google it. Knowing how to look for information is an important part of being a good programmer so we're not going to always give you everything you need to figure out a problem; some of it will be on you. 

???

# Quiz

?: Which of the following is a case statement?

( )
```ruby
name = "Steven"

if name == "Steven"
  "Hi, #{name}"
else
  puts "Hi, stranger!"
``` 
(X)
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
( )
```ruby
def case
  puts "Am I a case statement?"
end

case
```

?: Of the following two examples, which example uses the case statement the best?

( )
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
(X)
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
( ) Neither are good as case statements

?: Which operator does a case statement use to compare the value to the conditions?

(X) `===`
( ) `==`
( ) `=`

???

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/case-statements-quiz' title='Case Statements Quiz'>Case Statements Quiz</a> on Learn.co and start learning to code for free.</p>
