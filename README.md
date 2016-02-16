# Image-Analysis-in-Python

Materials for a 90 minute workshop "Image Analysis in Python".


# Prerequisites
* Python 2.7
* pip (to install the other packages)
* A recent version of ipython. I'm using 4.0.2, I believe any 4.X version will work fine.
* The python scientific stack (`numpy`, `scipy`, `matplotlib`)
* `scikit-image`

# Download materials
If you have git, you can run the command `git clone https://github.com/brikeats/Image-Analysis-in-Python.git`. 
If you don't have git, or it's not working for you for some reason, you can just click the "Download zip" button above and extract the contents.

If you've installed ipython, but you still get `command not found` when you enter `ipython`, you can try the command `python -m IPython notebook`, as shown in [this stackoverflow post.](http://stackoverflow.com/questions/34441943/ipython-installed-but-not-found).

# Running the notebook on midway

* [Click here to connect to thinlinc through your browser.](https://midway-login1.rcc.uchicago.edu/main/) Use your CNET credentials to log on to midway. When you are successful, you should see a blank blue desktop in your browser.
* Open a terminal by clicking on the black monitor icon at the bottom-left. (It's the third button from the left.) This will open a window and present you with a prompt like `<your user name>@midway-login1:~$ `.
* Type `cd /project/rcc/brikeats` to change to my project directory.
* Type `./get_notebook.sh`. This will download the course material to your home directory, load the python module, and start an interactive session. It may take a minute for the interactive session to start.
* Once your interactive session starts, you can start the notebook server with the command `ipython notebook`. This will open firefox and display a list of files. 
* Click on "Intro to Image Analysis in Python.ipynb" to follow along with the code demo. You should also open "Hands-on Exercise.ipynb" so you can follow along with the hands-on portions of the session.
