# <u>Funny Linux Commands</u>

Getting **Bored**! π₯± Then follow some ***Linux Terminal*** funny tricks π, that makes you fun π. 

## <u>**`figlet` command :**</u>
`FIGlet` is a simple command-line utility for creating `ASCII` text banners or large letters out of ordinary text.

```bash
sudo apt install figlet
```
```bash
figlet Hello World!
```
```
output :

 _   _      _ _        __        __         _     _ _ 
| | | | ___| | | ___   \ \      / /__  _ __| | __| | |
| |_| |/ _ \ | |/ _ \   \ \ /\ / / _ \| '__| |/ _` | |
|  _  |  __/ | | (_) |   \ V  V / (_) | |  | | (_| |_|
|_| |_|\___|_|_|\___/     \_/\_/ \___/|_|  |_|\__,_(_)

```


<br><br>


## <u>**`toilet` command :**</u>
`TOIlet` (a sub-command under `figlet`) is a command-line utility for creating colorful large characters from ordinary text.
```bash
sudo apt install toilet
```
```bash
toilet Welcome
```
```
output :

m     m        ""#                               
#  #  #  mmm     #     mmm    mmm   mmmmm   mmm  
" #"# # #"  #    #    #"  "  #" "#  # # #  #"  # 
 ## ##" #""""    #    #      #   #  # # #  #"""" 
 #   #  "#mm"    "mm  "#mm"  "#m#"  # # #  "#mm" 
                                                 
```

```bash
toilet -f mono12 -F metal Linux
```
```
output :

 ββ           ββ                                  
 ββ           ββ                                  
 ββ         ββββ     ββββββββ  ββ    ββ  βββ  βββ 
 ββ           ββ     βββ   ββ  ββ    ββ    ββββ   
 ββ           ββ     ββ    ββ  ββ    ββ    ββββ   
 ββββββββ  ββββββββ  ββ    ββ  ββββββββ   ββββββ  
 ββββββββ  ββββββββ  ββ    ββ   ββββ ββ  βββ  βββ 

```

<br>

```bash
while true; do echo β$(date | toilet -f term -F border βLinux)β; sleep 1; done
```

output :
<img alt="toilet linux" src="https://www.tecmint.com/wp-content/uploads/2014/08/toilet-command.gif">

* To know more about `figlet` & `toilet`, follow this <a href="https://www.tecmint.com/create-ascii-text-banners-in-linux-terminal/#:~:text=FIGlet%20is%20a%20simple%20command,large%20characters%20from%20ordinary%20text."><u>LINK</u></a>


<br><br>


## <u>**`sl` command :**</u>
`sl` is a joke software or classic `UNIX` game. It is a steam locomotive runs across your screen if you type `sl` (Steam Locomotive) instead of `ls` by mistake. sl is a highly advanced animation program for curing your bad habit of mistyping. In other words, you see Steam locomotive in `ASCII` art.
```bash
sudo apt install sl
```
```bash
sl
```
```bash
sl -a
```
```bash
sl -l
```
```bash
sl -F
```
<img alt="sl" src="https://www.cyberciti.biz/tips/wp-content/uploads/2011/05/sl-command-on-a-centos-linux.gif">


<br><br>


## <u>**`pi` command :**</u>
`pi` command gives the actual value of `Ο`
```bash
sudo apt install pi
```
```bash
pi 12
```
```
output :
3.14159265358
```


<br><br>


## <u>**`telnet` command :**</u>
`Telnet` is a text-oriented bidirectional network protocol over a network. Showing ***Star War*** film.
```bash
telnet towel.blinkenlights.nl
```

<img alt="time" src="https://www.tecmint.com/wp-content/uploads/2013/05/telnet.png">


<br><br>


## <u>**`fortune` command :**</u>
what about getting your random fortune, sometimes funny in terminal.
```bash
sudo apt install fortune
```
```bash
fortune
```
```
output :
Your mode of life will be changed for the better because of new developments.
```


<br><br>


## <u>**`rev` command :**</u>
It reverses every string given to it, is not it funny.
```bash
rev

123abc
```
```
output :

cba321
```


<br><br>


## <u>**`factor` command :**</u>
Time for some Mathematics, this command output all the possible factors of a given number.
```bash
factor 12
```

```
output :

12: 2 2 3
```


<br><br>


## <u>**`script` command :**</u>
OK fine this is not a command and a `script` but it is nice.
```bash
for i in {1..12}; do for j in $(seq 1 $i); do echo -ne $iΓβ$j=$((i*j))\\t;done; echo;done
```

```
output :

1Γβ1=1	
2Γβ1=2	2Γβ2=4	
3Γβ1=3	3Γβ2=6	3Γβ3=9	
4Γβ1=4	4Γβ2=8	4Γβ3=12	4Γβ4=16	
5Γβ1=5	5Γβ2=10	5Γβ3=15	5Γβ4=20	5Γβ5=25	
6Γβ1=6	6Γβ2=12	6Γβ3=18	6Γβ4=24	6Γβ5=30	6Γβ6=36	
7Γβ1=7	7Γβ2=14	7Γβ3=21	7Γβ4=28	7Γβ5=35	7Γβ6=42	7Γβ7=49	
8Γβ1=8	8Γβ2=16	8Γβ3=24	8Γβ4=32	8Γβ5=40	8Γβ6=48	8Γβ7=56	8Γβ8=64	
9Γβ1=9	9Γβ2=18	9Γβ3=27	9Γβ4=36	9Γβ5=45	9Γβ6=54	9Γβ7=63	9Γβ8=72	9Γβ9=81	
10Γβ1=10	10Γβ2=20	10Γβ3=30	10Γβ4=40	10Γβ5=50	10Γβ6=60	10Γβ7=70	10Γβ8=80	10Γβ9=90	10Γβ10=100	
11Γβ1=11	11Γβ2=22	11Γβ3=33	11Γβ4=44	11Γβ5=55	11Γβ6=66	11Γβ7=77	11Γβ8=88	11Γβ9=99	11Γβ10=110	11Γβ11=121	
12Γβ1=12	12Γβ2=24	12Γβ3=36	12Γβ4=48	12Γβ5=60	12Γβ6=72	12Γβ7=84	12Γβ8=96	12Γβ9=108	12Γβ10=120	12Γβ11=132	12Γβ12=144
```


<br><br>


## <u>**`cowsay` command :**</u>
An `ASCII` cow in the terminal will say whatever you want.
```bash
sudo apt install cowsay
```
```bash
cowsay Hello World!
```
```
output :

 ______________
< Hello World! >
 --------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

```

<br>

```bash
fortune | cowsay 
```

```
output :

 _________________________________________
/ You have a deep interest in all that is \
\ artistic.                               /
 -----------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

```

<br>

```bash
cowsay -f gnu Ubuntu is Best
```

output :
<img alt="cowsay" src="https://www.tecmint.com/wp-content/uploads/2014/08/cowsay-goat.gif">


<br><br>


## <u>**`xcowsay` command :**</u>
`xcowsay` is a graphical program that response similar to `cowsay` but in a graphical manner, hence it is X of `cowsay`.
```bash
sudo apt install xcowsay
```
```bash
xcowsay I Love nix
```

<img alt="xcowsay" src="https://www.tecmint.com/wp-content/uploads/2013/05/xcowsay.png">


<br><br>


## <u>**`cowthink` command :**</u>
`cowthink` is another command just run βcowthink Linux is so funnyβ and see the difference in the output of `cowsay` and `cowthink`.
```bash
cowthink ....Linux is sooo funny
```

```
output :

 _________________________
( ....Linux is sooo funny )
 -------------------------
        o   ^__^
         o  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

```


<br><br>


## <u>**`yes` command :**</u>
It is funny but useful as well, especially in scripts and for **System Administrators** where an automated predefined response can be passed to the terminal or generated.
```bash
yes I love India # it runs for infinite time, press Ctrl + c to exit
```

```
output :

I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
I love India
```


<br><br>


## <u>**`cmatrix` command :**</u>
You might have seen the Hollywood movie **βmatrixβ** and would be fascinated with the power, **Neo** was provided with, to see anything and everything in the matrix or you might think of an animation that looks like Hackerβs desktop.
```bash
sudo apt install cmatrix
```
```bash
cmatrix
```

output

<img alt="cmatrix" src="https://www.tecmint.com/wp-content/uploads/2013/05/cmatrix.png">


<br><br>


## <u>**`oneko` command :**</u>
OK so you believe that the mouse pointer of Linux is the same silly black/white pointer were no animation lies then I fear you could be wrong. `oneko` is a package that will attach a ***βJerryβ*** with your mouse pointer and moves along with you pointer.
```bash
sudo apt install oneko
```
```bash
oneko
```

output

<img alt="cmatrix" src="https://www.tecmint.com/wp-content/uploads/2013/05/oneko.png">


<br><br>


## <u>**`while` command :**</u>
The below βwhileβ command is a script that provides you with a colored date and file till you interrupt (Ctrl + c). Just copy and paste the below code into the terminal.
```bash
while true; do echo "$(date '+%D %T' | toilet -f term -F border --gay)"; sleep 1; done
```
or
```bash
while true; do clear; echo "$(date '+%D %T' | toilet -f term -F border --gay)"; sleep 1; done
```
output

<img alt="time" src="https://www.linux.com/images/stories/3734/figlet5.png">


<br><br>


## <u>**`espeak` command :**</u>
Just Turn the Knob of your multimedia speaker to full before pasting this command in your terminal and let us know how you felt listening to the godβs voice.
```bash
sudo apt install espeak
```
```bash
espeak "Linux is my Love"
```


<br><br>


## <u>**`aafire` command :**</u>
How about a fire in your terminal. Just type `aafire` in the terminal, without quotes, and see the magic. Press any key to interrupt the program.
```bash
sudo apt install libaa-bin
```
```bash
aafire
```

output

<img alt="time" src="https://www.tecmint.com/wp-content/uploads/2013/05/aafire.png">


<br><br>


## <u>`Fork Bomb` command :</u>
This is a very nasty piece of code. **Run this at your own risk**. This actually is a `fork bomb` which exponentially multiplies itself till all the system resource is utilized and the system hangs.

To check the power of this command you should try it once, but all at your own risk, close and save all other programs and files before running a `fork bomb`.

```bash
:(){ :|:& }:
```


<br><br>


## <u>`bb` command :</u>
First, install the command and then, type `bb` in the terminal and see what happens.

```bash
bb
```

<img src="https://www.tecmint.com/wp-content/uploads/2013/05/bb.png" alt="bb">


<br><br>


## <u>`curl` command :</u>
Wonβt it be an awesome feeling for you if you can update your **Twitter status** from the command line in front of your friend and they seem impressed? OK just replace ***username***, ***password***, and ***your status message*** with yourβs `username`, `password`, and `your status message`.

```bash
curl -u YourUsername:YourPassword -d status="Your status message" http://twitter.com/statuses/update.xml
```


<br><br>


## <u>`ASCIIquarium` command :</u>
* How it will be to get an aquarium in the terminal.

```bash
apt-get install libcurses-perl
cd /tmp 
wget http://search.cpan.org/CPAN/authors/id/K/KB/KBAUCOM/Term-Animation-2.4.tar.gz
tar -zxvf Term-Animation-2.4.tar.gz
cd Term-Animation-2.4/
perl Makefile.PL &&  make &&   make test
make install
```

* Install ASCIIquarium.
Now Download and Install ASCIIquarium.
```bash
cd /tmp
wget http://www.robobunny.com/projects/asciiquarium/asciiquarium.tar.gz
tar -zxvf asciiquarium.tar.gz
cd asciiquarium_1.1/
cp asciiquarium /usr/local/bin
chmod 0755 /usr/local/bin/asciiquarium
```

* And finally, run `asciiquarium` or `/usr/local/bin/asciiquarium` in the `terminal` without quotes and be a part of the magic that will be taking place in front of your eyes.

```bash
`
```

output :

<img src="https://www.tecmint.com/wp-content/uploads/2013/05/ascliquarium.png" alt="asciiquarium">


<br><br>


## <u>Linux Tweaks :</u>
It is time for you to have some one-liner tweaks.

```bash
world
```
```
output :

bash: world: not found
```

```bash
touch girls\ boo** 
```
```
output :

touch: cannot touch `girls boo**': Permission denied
```
```bash
nice man woman
```
```
output :

No manual entry for woman
```
```bash
^How did the sex change operation go?^ 
```
```
output :

bash: :s^How did the sex change operation go?^ : substitution failed
%blow 
```
```
bash: fg: %blow: no such job
make love 
```
```
output :

make: *** No rule to make target `love'.  Stop.
```

```bash
$ [ whereis my brain?   
```
```
output :
                 
sh: 2: [: missing ]
```
```bash
% man: why did you get a divorce?
```
```
output :

man:: Too many arguments.
```

```bash
% !:say, what is saccharine?
```
```
output :

Bad substitute.
```

```bash
/srv$ \(- 
```
```
output

bash: (-: command not found
```


<br><br>


## <u>funny manpages :</u>
First, install the funny manpages and then run man pages for the commands below.

```bash
$ sudo apt install funny-manpages
```
Some of them may be **18+**, run at your own risk, they all are too funny.

```bash
baby
celibacy
condom
date
echo
flame
flog
gong
grope, egrope, fgrope 
party 
rescrog 
rm
rtfm
tm
uubp
woman (undocumented)
xkill 
xlart 
sex 
strfry
```

```bash
man baby
```
<br>

**Happy Coding β**