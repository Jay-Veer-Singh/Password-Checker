# Password-Checker

It's not just any silly, dumb password checker.This is legitimately going to be the most secure way for you to check if your password has ever been hacked.

Here, when we run this program, we're going to be able to input any password. And check if it's ever been hacked or not.

If it is hacked then you shouldn't use that password.

if it is not hacked then you should use that password
"This password has actually never been found. So you should carry on and use this password."

And this is where we're going to build a program that by using password API for us to do this.
In this project we are going to use Pwned API URL this API uses the SHA 1 hashing algorithm. It's an algorithm that is a function that does this gibberish output of password.

this API also uses a technique called K anonymity and this is actually a modern technique that big companies like Google, Facebook, Netflix, Amazon all use.

K anonymity allows somebody to receive information about us yet still not know who we are.

*How does this work?*

By the way, this is actually a technique that is used a lot, especially now, where using personal data for companies, it's frowned upon.

So ideally you don't want to give your personal information to companies.

So some companies that care about security and privacy use this anonymity to track you, but still not know who you are.

*Now, the way this works.*

Is that we only give the first five characters of our hash password.

However, all those passwords are hashed with the SHA one algorithm.

This way, this API is never going to know our full hash and therefore never ever be able to guess our password.

They'll just know that we have this tiny bit of a hash function that could match any hundreds of passwords.

But with this response data, we can now check our full hash to see if the password has ever been postponed or has ever been hacked.
