# Task 1: Basic Task
```
learner@host:~$ ls
Desktop    Downloads         Music     Projects  snap       Videos      Documents  examples.desktop  Pictures  Public    Templates
```
> It display list of folders and files in the current directory. 

> It means list source.

```
learner@host:~$ pwd
/home/learner
```
> It display the full path of the current directory
It means print working directory

```
learner@host:~$ mkdir workspace && cd workspace 
learner@host:~/workspace$ ls
```

> It display nothing because the directory is empty
It means list sources in the current directory

```
learner@host:~/workspace$ touch README.md
learner@host:~/workspace$ cp README.md CHANGELOG.md
```

# Task 2: Absolute and Relative Paths
```
learner@host:~$ touch exercise.md && sudo mv exercise.md /tmp
learner@host:~$ sudo rm /tmp/exercise.md
```

# Task 3: cat commands
```
learner@host:~$ touch {umuzi,recruits,cohort}.md
learner@host:~$ echo "Umuzi is the best" >> {umuzi,recruits,cohort}.md
learner@host:~$ cat {umuzi,recruits,cohort}.md > summary.md
learner@host:~$ echo "The End" >> summary.md
```

# Task 4: The locate command
```
learner@host:~$ locate umuzi
learner@host:~$ locate umuzi > search_result.md
```

# Task 5: The locate command cont..
```
learlearner@host:~$ cd Documents
learner@host:~/Documents$ touch pad.md
learner@host:~/Documents$ cd ~/Desktop && mkdir work
learner@host:~/Desktop$ cp ~/Documents/pad.md ~/Desktop/work/pad_copy.md
learner@host:~/Desktop$ locate updatedb
learner@host:~/Desktop$ cd -
learner@host:~/Documents$ locate pad_copy.md
```

# Task 6: Find commands
```
learner@host:~$ sudo find / -name "*.pdf"
learner@host:~$ sudo find / -name "*.pdf" > ~/Documents/files.md
learner@host:~$ find / -mtime -1
```

# Task 7: 
```
learner@host~$ nano my_bio.md
```
```
GNU     nano 2.9.3                                      my_bio.md







                                        [ New File ]
^G Get Help     ^O Write Out    ^W Where Is     ^K Cut Text     ^J Justify      ^C Cur Pos      ^X Exit     ^R Read File    ^\ Replace      ^U Uncut Text   ^T To Spell     ^_ Go To Line
```
> To save file type  ``` ctrl+x ``` then press  ``` y ``` and ```ENTER``` to save and close the editor

```
learner@host:~$ mkdir my_files && mv my_bio.md my_files/ 
```

@Author - Sjk-Lacoste [Tshepo Mohlatlole]