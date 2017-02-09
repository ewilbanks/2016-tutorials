- What is Cloud Computing and why is it useful?

- [Getting started with Amazon EC2](http://angus.readthedocs.io/en/2015/amazon/index.html)

Once you're logged on to the EC2 instance, use the commands

mkdir tutorial_shell

cd tutorial_shell

mkdir data  
cd data  
curl -L https://www.dropbox.com/sh/w88b739sr171888/AAB00S4615cM689T9kco6ylLa?dl=1 > download.zip  
unzip download.zip

To get the 16S data use the commands

cd  
cd tutorial_shell  
wget https://s3.amazonaws.com/edamame/EDAMAME_16S.tar.gz  
tar xvfz EDAMAME_16S.tar.gz

- [Using the command line](https://github.com/ewilbanks/2015-tutorials/blob/master/final/2015-06-22-introduction_to_the_shell.md)






