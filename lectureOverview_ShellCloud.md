- What is Cloud Computing and why is it useful?

- [Getting started with Amazon EC2](http://angus.readthedocs.io/en/2015/amazon/index.html)

Once you're logged on to the EC2 instance, use the commands

```
mkdir tutorial_shell
cd tutorial_shell
mkdir data  
cd data  
curl -L https://www.dropbox.com/sh/w88b739sr171888/AAB00S4615cM689T9kco6ylLa?dl=1 > download.zip  
unzip download.zip
```

These tutorials were designed for the EDAMAME (U Mich) summer course and use a test 16S dataset of soil cores from Centralia, PA test 16S data (from the Shade lab).  Today, we'll use their data and next week, we'll switch over to analyzing our big WHALE of a dataset... (heh)...
To get the test 16S data, use the commands:
```
cd  
cd tutorial_shell  
wget https://s3.amazonaws.com/edamame/EDAMAME_16S.tar.gz  
tar xvfz EDAMAME_16S.tar.gz
```

Now we'll proceed to our command line tutorial!  Follow the link below.  Be sure you're working from the terminal ssh'd into your EC2 machine on AWS.
- [Using the command line](https://github.com/ewilbanks/2015-tutorials/blob/master/final/2015-06-22-introduction_to_the_shell.md)






