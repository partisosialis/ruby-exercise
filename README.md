# ruby-exercise
learning Ruby via https://learnrubythehardway.org/book/

i write the strings in atom as below and save it as ex15_sample.txt:

=====================================

This is stuff I typed into a file.
It is really cool stuff.
Lots and lots of fun to have in here.

=====================================
then create ruby as below and save it as ex15.rb

=====================================

filename = ARGV.first

txt = open(filename)

puts "Here's your file #{filename}:"
print txt.read

print "Type the filename again: "
file_again = $stdin.gets.chomp

txt_again = open(file_again)

print txt_again.read

====================================
run Ruby in Terminal:

=====================================

 $ ruby ex15.rb ex15_sample.txt
Here's your file ex15_sample.txt
This is stuff into a file.
It is really cool stuff.
Lots and lots of fun to have in here.
Type the filename again: ex15_sample.txt
This is stuff into a file.
It is really cool stuff.
Lots and lots of fun to have in here.

=====================================

i follow the Study Drill 4 at https://learnrubythehardway.org/book/ex15.html it states

Get rid of the lines 8-13 where you use gets.chomp and run the script again.

i don't understand the instruction. when i delete the lines 25 "file_again = $stdin.gets.chomp", there is an error in terminal.

and Study Drill 5, "Use only gets.chomp and try the script that way. Why is one way of getting the filename better than another?"

i delete $stdin from $stdin.gets.chomp, also error.

who understand the both instruction? thank you!
