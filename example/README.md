<h1 align="center">
  Tired of watching the progbar till your world class model reaches SOTA?
</h1>

<p align="center">
  Follow along if you want to be notified remotely when your model finishes learning the difference between cats and dogs!
</p>

<br/>

<p align="center">
  <a href="#"><img src="/home/hasib/pynotify/media/output.png" height=400/></a>
</p>


## Motivations
<p> 
I'm to lazy to keep watching my model finish training and also to write up a thorough tutorial on this. I also train models in CPU which takes hours or in the worst case even days. Hence wrote a program to notify me when the task is done and also providing details of it. More time to play Counter Strike! 
</p>

## What this notebook does?

* Runs a simple Convnet on **CIFAR10** dataset
* Generates and saves the model's train/test **loss** and **accuracy** graphs
* Makes a template with model parameters and saved graphs
* Sends the template as an email to the pre-defined user **after** completion of training, providing the neccesary model information.
<br>

## How to use this?

* open a **new** gmail account and set it's application status to [**less secured**](https://myaccount.google.com/intro/security) (DO NOT USE YOUR PERSONAL EMAIL ADDRESS FOR THIS. HIGHLY  RECOMMENDED TO USE NEW EMAIL)
* put the new account's credentials in **fromaddr** and **password**
* put the address to which you want to send in **toaddr**
* After you set the credentials, you are good to goooo!
* Click **RUN ALL CELLS**

**YOU HAVE TO SETUP THE NEW EMAIL ACCOUNT ONLY ONCE!**


## Trick or treat

Too lazy to set all of these up? I wrapped everything in a python package which is uploaded in TestPyPi and ready for use. You can get it [here](https://test.pypi.org/project/pynotify/)

## Takeaways

* Program written in Python 3.6
* Nothing here. What did you expect? A cookie!?

## License
[MIT](https://github.com/hasibzunair/boss-detector/blob/master/LICENSE)

## Author
Made with ❤️ by Hasib Zunair
