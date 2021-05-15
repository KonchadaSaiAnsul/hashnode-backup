## How to schedule WhatsApp message using just 2 lines of code

Hey Guys!
Welcome back to another brand new post of ** Sai Ansul's Blog**.
Today we are gonna find out ** How to schedule WhatsApp message using just 2 lines of code** , yes you heard it right just 2 lines of code.

So lets start,
We will divide the process in 3 parts
- Creating a project
- Installing ```pywhatkit```
- 2 lines of code

# Part 1

First of all you need to a python interpreter for this project in your device.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620982341953/5Tpu5lsHD.png)
I have here used **pycharm** by **JetBrains**, you can use any other also.
Then you have to name the file.
I have named it as   ``` WHATSAPP MESSAGE AUTOMATION ```.
Then press create, after that a page would open.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620982776647/DAIRFvEYn.png)
 Then select the whole over there with ```Ctrl+A``` and click on ```Backspace```.
So now you have a empty slate open just like the below image.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620982890342/7V0qUT8mu.png)

# Part 2
Then you need to go to your Browser and search for  [```pywhatkit```.](https://pypi.org/project/pywhatkit/) 

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620983162597/mbAwcNo-E.png)
Then after you open the site, you'll see a interface like this,

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620983258668/vomX_A-rI.png)
Then you need to click on ```pip install pywhatkit``` to copy the code.
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620983317939/JDQ0yp9pl.png)

Then we again need to go to the project created.
And open ```Terminal``` and paste this.

![Untitled.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620983711503/_sNdQL6py.png)
After clicking on that you need to paste the code```pip install pywhatkit```. 

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620984098797/_WoVE1bZM.png)
Like this and press ```Enter```, it will take 1-2 mins to get downloaded, till that you need to open your Browser and open ```WhatsApp Web``` and while login remember to tick on the option ```Keep me signed in```.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620984137732/5TDne7wfJ.png)
And when it shows the message as shown in the image, then we are good to start.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620984348113/nE7bo1RNG.png)

Now lets proceed towards the part 3 that is to code

# Part 3

Now we need write in the first line as
```
import pywhatkit
``` 
Then this part is divided into 2 parts
- Part 1: Message to a personal chat
- Part 2: Message to a group

So first lets learn how to send a automated message to a **personal chat**

Now to need to type

```
pywhatkit.sendwhatmsg()
```
Inside the bracket you need to pass all the parameters like, phone number with country code, message and the timing in the format of `` HH:MM``.
Check the sample code out

```
pywhatkit.sendwhatmsg( '+911234567890', 'HI IM SAI ANSUL',15, 25)
```

I have written the country code as ``+91`` and then the phone number of the receiver, and the write your message with in`` 'MESSAGE', ``, then select the time according to the 24 hours format where I have chosen at 15hours and 25 minutes. 
and that it ,and press on the execution button and you'll see the message like this.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620985823394/COZiotgJo.png)

And now you don't have to do anything just keep the browser open and it will automatically open `` WhatsApp Web`` before 20 seconds of the time given, and it will keep the message typed as soon as the time is reached it will send the message.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620986156266/mqeaCvUg1.png)
And at 15:24 a tab opened of WhatsApp Web and opened the contact whose number I had entered in the code, and at exactly 15:25 the message got send.

## This was how to send a automated WhatsApp message to a personal chat.

So now let us know how to send a automated WhatsApp message to a group.

The process is very similar and simple to the previous one.

Just what you have to do is rather putting the number of the recipient, you need to put the group id. and change the command to `` sendwhatsmsg_to_group_ ``
You can find the group id by going into the group info and then click on invite via link and then you need to put the prefix of that. The suffix of the link is the group id code. 

Like this
```
import pywhatkit
pywhatkit.sendwhatmsg_to_group('CBURAqngjD54UzFHg6CGi7','HELLO',16 ,47 )
```

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1620991086192/HxnJ1C-v4.png)

The parameters are:
phone_num (required) - Phone number of target with country code
message (required) - Message that you want to sendwhatmsg
time_hour (required) - Hours at which you want to send message in 24 hour format
time_min (required) - Minutes at which you want to send message
wait_time (optional, val=20) - Seconds after which the message will be sent after opening the web
print_waitTime (optional, val=True) - Will print the remaining time if set to true

Some common errors:
CountryCodeException - Check if the phone number passed into the parameter has country code
Message not getting delivered - Check internet speed and increase wait_time to 30 or above CallTimeException - The web takes some time to load so some delay is required, make sure the seconds left is greater than the wait_time
SyntaxError - Make sure the first two parameters are string and the rest are int

So now this was how to send a automated WhatsApp message to a personal chat or a group using just 2 lines of code.

That is it for today guys! I hope you liked the article and got to know something new.

Stay tuned for some more interesting blogs coming up soon.

If you like my content and want to support my efforts please like👍🏻, share📲 & subscribe to the newsletter to be get notified whenever I post a new blog.

%%[no-login-reactions]
%%[poll]
