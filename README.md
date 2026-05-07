## Seminar Webpage 

This repository stores the HTML for the Algebraic Geometry Working Seminar at the
University of Waterloo.

###  Copying the webpage to your personal domain

You will need to do the following steps on a computer connected to the university
network, be it on campus or via VPN.

I am going to assume that you are at least tech-savvy enough to navigate a filesystem
using a terminal. If you aren't, you will need to [read this guide](https://www.redhat.com/en/blog/navigating-linux-filesystem) after connecting to the math faculty server.

Your userID is the prefix of your uwaterloo email. For example, my userID is `kdruscit`,
and my email is kdruscit@uwaterloo.ca. To log in to the math faculty server, open a terminal on your computer and enter:
```
ssh your_userID@linux.math.uwaterloo.ca
```
You will be prompted for your password, which is the same as your password for Quest or Outlook.
Next, you can copy the files from this GitHub repository to your home folder:
```
git clone https://github.com/kalebruscitti/seminar-webpage.git
``` 
Finally, to make the webpage live, you must rename the folder you just created from `seminar-webpage`
to `public_html`. To do this, enter:
```
mv seminar-webpage public_html
```
Now if you go to https://math.uwaterloo.ca/~yourUSERID/agws.html you should see the seminar webpage!
