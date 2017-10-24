# GitHub Tutorial

_by Islam Eleish_

---
## **_Git_** vs. **GitHub**
So you want to learn the ways of git and github. This tutorial will help you do so but before we go into depth on that you need to know what git and github are, how they are used and why they are used together.
Git is a version control system developed by linux. Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.
Github is a service that hosts git repositories. GitHub is essentially made up of two words Git, which we already know what that is, and hub which is defined by webster as 
the effective center of an activity, region, or network. So if we put it together it is a center in which git is echanged utilized etc, github describes their company as "a code hosting platform for version control and collaboration. Which lets you and others work together on projects from anywhere.
So now you know what git and github are, its time to explain the differences. 
Git is taking snapshots of code and it doesn't require Github, on the other hand Github requires Git, it stores the code in the "clouds" known as the website in this case its c9.
![alt text](https://image.slidesharecdn.com/gitversioncontrolcomputerscience-170613072639/95/git-version-control-computer-science-6-638.jpg?cb=1497432325)

---
## Initial Setup
So now that we know what github and git is, as well as the differences lets go over how to setup your github account.
* First go to **_GitHub_**
  * [link to GITHUB here](www.github.com)

[![Screen_Shot_2017-10-19_at_9.24.31_AM.png](https://s1.postimg.org/1abi0z5uxr/Screen_Shot_2017-10-19_at_9.24.31_AM.png)](https://postimg.org/image/9gj2rh74d7/)
After you click sign in you can make an account and when thats done your screen should look like this
[![Screen_Shot_2017-10-19_at_9.33.31_AM.png](https://s1.postimg.org/6fpgwrlntb/Screen_Shot_2017-10-19_at_9.33.31_AM.png)](https://postimg.org/image/1pk7ycu1fv/)
* Now that you have done that its time to sign up for [c9](c9.io)
* Click on the sign up page which is similar to githubs and log in your screen should look like this
[![Screen_Shot_2017-10-19_at_9.43.58_AM.png](https://s1.postimg.org/8lde26qslb/Screen_Shot_2017-10-19_at_9.43.58_AM.png)](https://postimg.org/image/17iotf64vv/)
* Now we have to connect the two programs together, merge them in a way
* To do this we use whats called an SSH Key
* SSH uses public-key cryptography to authenticate the remote computer and allow it to authenticate the user

  [![Screen_Shot_2017-10-20_at_9.16.05_AM.png](https://s1.postimg.org/91ktzxoigf/Screen_Shot_2017-10-20_at_9.16.05_AM.png)](https://postimg.org/image/3mmbhi9d2j/)
* If you make your way to your top left corner of cloud nine you should see a gear icon, Click on it
 * Now if you look on your left after clicking the gear icon you should see this
 [![Screen_Shot_2017-10-20_at_9.20.33_AM.png](https://s1.postimg.org/3rm8xq6nu7/Screen_Shot_2017-10-20_at_9.20.33_AM.png)](https://postimg.org/image/4r2caw9ezv/)
* Click on **SSH KEYS**
* WHen you click on that you should see two options, SSH to server or SSH to Github, Copy and paste the contents of the second box
 [![Screen_Shot_2017-10-20_at_9.26.22_AM.png](https://s1.postimg.org/5zdgicxn9b/Screen_Shot_2017-10-20_at_9.26.22_AM.png)](https://postimg.org/image/254ozefpbv/)
* Your **SSH** key will not be blurred i just blurred mine out for my protection ;)
* After you copy the SSH key to from the second box we now have to  head over to github

 [![Screen_Shot_2017-10-20_at_9.29.38_AM.png](https://s1.postimg.org/7ajxszx1xb/Screen_Shot_2017-10-20_at_9.29.38_AM.png)](https://postimg.org/image/9gjceropob/)
* Again in the top right corner you should see a scroll down menu with your avatar, If you click on it a dropdown should appear, Click Settings
* When you have clicked on settings you should see a menu to your left

[![Screen_Shot_2017-10-20_at_9.32.15_AM.png](https://s1.postimg.org/7quxwwbtvj/Screen_Shot_2017-10-20_at_9.32.15_AM.png)](https://postimg.org/image/9f4au3241n/)
* Click on **SSH** and **GPG Keys** 
* [![Screen_Shot_2017-10-20_at_9.34.41_AM.png](https://s1.postimg.org/34ytojp0gv/Screen_Shot_2017-10-20_at_9.34.41_AM.png)](https://postimg.org/image/7o0uriuhej/)
* when you have clicked that in the top right hand corner you should see a green button that says New **SSH key**, Click on it
* You should be prompted with a box that looks like the one below
[![Screen_Shot_2017-10-20_at_9.44.09_AM.png](https://s1.postimg.org/889i54hoen/Screen_Shot_2017-10-20_at_9.44.09_AM.png)](https://postimg.org/image/1tuw9izruz/)

* WooHoo Your c9 and **_Github_** are now linked together now we have to worko on how to setup a repo!


---
## Repository Setup
So Now we are going to learn how to set up a repo which is short for repository.
A repository is a place/ recepticale where data is stored.
* To initiate a repository go into the command line on cloud 9 
* Then make sure you make a new file and name it, we do so using  mkdir 
* Then cd into the file you just made 
* Then type in `git init`

[![git_1.png](https://s1.postimg.org/20nf5z6khr/git_1.png)](https://postimg.org/image/3zjlwbc2t7/)

* inside the folder make sure you` touch readme.md`
* this creates a file that you can put text in
* Then you want to `add --all`
* Then `Git commit -m "insert message here"`
*[![snip_3.png](https://s1.postimg.org/5a7lj5micv/snip_3.png)](https://postimg.org/image/3wl2f4bgbv/)
* now we need somwthing to push to
* Make your way to github and go to the plus icon, when the drop down appears choose new reopsitory

[![git_3.png](https://s1.postimg.org/4kdbqfq0bj/git_3.png)](https://postimg.org/image/7bmdyic4d7/)
[![git_4.png](https://s1.postimg.org/1xq5mlrn1b/git_4.png)](https://postimg.org/image/1xq5mlrn17/)
* MAKE SURE WHATEVER YOU TYPE INTO THE REPOSITORY NAME MATCHES THE FOLDER YOU MADE ON C9!!!!!!!!!!!!!!!!!
* Create new repository
* [![git_6.png](https://s1.postimg.org/5610oqhldr/git_6.png)](https://postimg.org/image/4rukxv9aij/)
1. make sure ssh is selected
2. copy to clipboard, go into cloud nine , `git clone <link you just copied>`
3. copy to clipboard, past cloud 9
4. copy to clipboard paste cloud 9
5. Congrats now lets talk about workflow and commands
---

## Workflow & Commands
There are many commands that you can utilize in git here are some below
[![sc1.png](https://s1.postimg.org/1yk57bambj/sc1.png)](https://postimg.org/image/6s903fvbej/)
[![screen_shot_number_2.png](https://s1.postimg.org/1unwgsmyb3/screen_shot_number_2.png)](https://postimg.org/image/15umwrzfaj/)
[![sc3.png](https://s1.postimg.org/43vayjvba7/sc3.png)](https://postimg.org/image/857acxzemz/)

---
## Rolling Back Change
[![git_2.png](https://s1.postimg.org/9t2q2zp2xr/git_2.png)](https://postimg.org/image/4vu995bb4r/)
* Lets go over what this diagram means
*  This diagram basically tells you how to rollback almost any change for example if u accidently commit, you can roll that back by using `git reset --soft HEAD~1`
---
## Error Handling`
Since we are all human we all make mistakes, which is why the rollbackchanges exist
However im going to show you what to do if something goes wrong
One of the most common problems is that you `git init` into the wrong folder
to fix ths we just do `rm -rf .git`


---