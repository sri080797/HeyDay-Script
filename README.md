# Hey Day Script 

Welcome to Auburn University's **Hey Day**, an annual tradition that fosters community, friendliness, and school spirit. This Bash script reflects the spirit of Hey Day by asking for your name and greeting you with a simple, friendly message!

## About Hey Day

Hey Day is one of Auburn University's longest-running traditions where students, faculty, and staff are encouraged to greet each other with a friendly “Hey!” It’s a celebration of community and togetherness that’s held every year, helping to bring the Auburn Family closer.

For more information, visit the official [Auburn University Hey Day webpage](http://sga.auburn.edu/hey-day/).

## What the script does

This simple Bash script asks the user for their name and provides a personalized greeting and welcome message to celebrate Auburn’s Hey Day!

## Code Description

Here’s the script in action:
>The Script Starts with a Greeting:
The greeting="Hey" variable holds the greeting message.
The Wishes="Welcome to Auburn's Hey Day!" variable holds a welcome message for Auburn's Hey Day.
```ruby

Greeting="Hey"
Wishes="Welcome to Auburn's Hey Day!"

```
>The script prints "Hey there! What's your name?" using the``` echo ```command.

It then waits for the user to enter their name and stores it in the name variable using
```ruby 
read -p "Enter your name: " name.
```
> Then script uses the name and display the personalized greeting and  wishes for Auburn Hey day
```ruby
echo "$Greeting, $name!"
echo "$Wishes"
echo "Have a great day, $name!"
```
**Example Output**
Here’s an example of what the script will output:
```
Hey there! What's your name?
Enter your name: Mounika
Hey, Mounika!
Welcome to Auburn's Hey Day!
Have a great day, Mounika!
```
*This script is simple, friendly, and gives the user a personalized greeting while celebrating Auburn's Hey Day!*


