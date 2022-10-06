This is a basic flask WhatsApp Bot that make use
of two public APIs one to get random quotes and the
other is to get cat images.

To get started, make sure you have installed flask, requset, twillo using the pip command

"pip install flask request twillo"


To use this bot you need to get a Twillo account,
be it paid or free account. 

=> If you do not have a Twillo Account, you need
to signup and the connect it to your bot.


Inorder to be able to connect your twillo account
to the bot on your local machine, you need to point
your local machine to a public IP that twillo will
be able to access it. 

In that case, you also need to sign up for ngrok and
install on your local machine. After you have signed up
for the twillo account. 

run "ngrok http 4040" to start the server 

if all works fine, it will give you an external web
address ending with "ngrok.io" 
Eg. "https://hr-90-uu-ii-mq.ngrok.io"

Go back to the Twilio Console, click on Programmable
Messaging, then on Settings, and finally on WhatsApp
Sandbox Settings. Copy the https:// URL from the ngrok
output and then paste it on the “When a message comes in” field.



then add the name of the "/bot" after the ngrok.io 
Eg. "https://dd-d4-cs.ngrok.io/bot" 




To Test your bot, under the page in the console where
you pasted the ngrok url, save the WhatsApp number and
send the message require to send inorder to initiate
communication between you whatsapp number and Twillo.

Thats it! Send any message to the bot, containing the
key word "quote" or "cat". also you can send a message
with both that is "quote cat" and the bot will get you
a random  quote with a cat image.
