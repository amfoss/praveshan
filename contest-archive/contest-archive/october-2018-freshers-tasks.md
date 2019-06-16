# October 2018 - Fresher's Tasks

**Type I: Easy**  
Stone Paper Scissors Game  
  
We assume that all of you have played this at least in your childhood. Battle yourself with the computer to be the king, the basic rule for the game is that you and the computer both choose rock, paper or scissors the winner is decided based on:

* Rock blunts scissors.
* Paper covers rock.
* Scissors cut paper.

Fill up the rest using your logic.  
  
Simple Telegram chatbot  
  
Here we expect you to develop a simple telegram chatting bot where you could chat with a bot for timepass when there is no one around. We would propose you to use the telebot API for this development \[1\].  
  
  
**Type II: Medium**  
  
Plagiarism checker using Web Scraping  
  
The intention of this project is to create a small command line application where it should check whether the contents you feed into the command line application is a plagiarized content or not.  
  
What we expect from you is to have a text file or a PDF file which will be passed as input, then parse that file using python. After that split each phrase or sentence as far as you like then do a simple Google search of it via command line. Then produce an output or display that you found matches in so and so websites.  
  
One possible approach you could take is like :  


* Take the input as a text file or a PDF. 
* Parse the file using python. 
* Split the phrases using .split\(\) function in python. 
* Add a small functionality to do google search via terminal/command line. 
* Do a double quote search in Google through the CMD 
* Produce the results with the matches and print it out. 

  
CLI Shopping Cart  
  
Write a python program which would enable to shop items using the command line interface. The program should be able to list the available products and asks the customer to select the lists of products which he/she needs. Furthermore, the user can select needed items and proceed to check out which would show them the amount payable along with coupon options which will give 4% discount and also have some sort of fancy steps showing payment, also as a task you have done captcha reading and you could also improvise this here for gimmicking the payment step. The idea is so much vast and so much expandable.  
  
**Type III: Hard**  
  
Send a tweet using python  
  
Here we intend to make an application where you would take an input from the user and after that tweet that input.  
One possible approach you could take is like :  


* Create a twitter app and generate key 
* Store Credentials of the user in a separate file “tokens.py” 
* OAuth Authentication where you would import the tokens and using tweepy.AuthHandler complete the authentication 
* Get input from user about the tweet about to be send 
* Update the tweet using update\_status of tweepy API.

That's pretty much outline for this task for more information go to tweepy\[2\] documentation and find out \[2\]  
  
  
Send mail via CLI  
  
Here, what we expect you to do is to create a small python script that automatically sends in emails. You just need to take in the ‘To’  address, the subject, the description and send an email via command line to the recipient. Refer Gmail API \[3\] for more information on how to do this.  
  
Hint: You might have to authenticate yourself at first.  
\[1\]: [https://github.com/eternnoir/pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI)

\[2\]: [http://docs.tweepy.org/en/v3.5.0/](http://docs.tweepy.org/en/v3.5.0/)  
\[3\]: [https://developers.google.com/gmail/api/quickstart/](https://developers.google.com/gmail/api/quickstart/python)

