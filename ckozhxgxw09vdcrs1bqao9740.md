## How to make a Talking Virtual Friend using just 4 lines of code

Hey Guys! Welcome back to another brand new post of Sai Ansul's Blog. Today we are gonna find out **How to make a Talking Virtual Friend using just 4 lines of code** , yes you heard it right just 4 lines of code.

Lets divide this process in 3 steps

- Create a project
- Install ``pyttsx3 ``
- Coding 

# Part1- Create a project
First of all you need to a python interpreter for this project in your device.

I have here used **pycharm** by **JetBrains**, you can use any other also.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1621533728459/RBbQstzSw.png)
Then you have to name the file. I have named it as `` Virtual Friend``.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1621534023772/QT2R6CvAR.png)

Then select the whole over there with ``Ctrl+A`` and click on ``Backspace``. So now you have a empty slate open just like the below image.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1621534058824/YCG6ScOAS.png)

# Part 2- Installing ``pyttsx3``

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1621534696903/iJMjJj4i8.png)

Now you need to open the website and copy the code and paste it in the terminal and wait for it to get downloaded.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1621534767999/wbpC1Q_4b.png)

After the packages is installed, we can start coding.
The py means here python, tt means text to, s means speech and x3 means its version.


# Part 3 - Coding


![carbon (6).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1621535379811/_uCPFPKm4E.png)
 
First we need to import the kit we have installed.
```
import pyttsx3
```
Then in the second line you need to make a friend.
For that you need to write this code.
```
friend = pyttsx3.init()
```
Then you can write just a code to make your friend say whatever you want.
```
friend.say("Hello Sai, I'm your talking virtual friend,you can make me speak whatever you want, your blogs are very interesting.")

```
Now you can replace the text.

And then, you can write this short code so the process is proper.
```
friend.runAndWait()
```
Now this was how to make a talking virtual friend.
You can also use this code and make your own, try it and let me know in the comment section.

You can check the output here:

%[https://youtu.be/NaxhcXsnafs]


That is it for today guys! I hope you liked the article and got to know something new.

Stay tuned for some more interesting blogs coming up soon.

If you like my content and want to support my efforts please like👍🏻, share📲 & subscribe to the newsletter to be get notified whenever I post a new blog.

You can also check out this amazing article [**Vanilla JavaScript speech-to-text 🦻**](https://h.daily-dev-tips.com/vanilla-javascript-speech-to-text)  by @[Chris Bongers](@dailydevtips).
