# Web Dev Assignment      25-05-2024
# Shell commands

Shell Commands: A shell command is a text-based instruction given to a command-line interface (CLI) shell to perform a specific task on a computer.

CLI: CLI stands for Command Line Interface. It is a text-based user interface used to interact with software and operating systems.

### Here are some of my favourite shell commands
-----


1. The command `pwd` is used to show the current working directory
```sh
pwd
```
2. `mkdir` is used to create a new directory
```sh
mkdir dirname
```
 `dirname` is to be replaced with the name of the directory you are creating

3. `rmdir` is used to delete a directory
```sh
 rmdir dirname 
```
4. `ls` shows the content of current working directory
5. `cd .` is used to move forward
6. `cd ..` is used to go back
7. `mv` used to move a directory or file & also used to rename files. 
    >`mv` newfile 'new directory'. #moves the file to a new directory

    >`mv` newfile newfile.html #changes file to a different format

8. `echo` creates a newfile

9. `echo` displays a string on a the terminal
    >`echo` 'Hello World' > newfile #displays on a file

    >`echo` 'Hello World' >> newfile #displays without overwriting the original content

10. `cat` displays the content of a file
11. `vi` is used to enter the inbuilt IDE in git bash `i` is used to enter edit mode
    > `vi` newfile #to enter the IDE with a file
12. `esc` to exit editor mode & `:q!` to exit the IDE
    > `:wq` to save and quit if you entered with a file
    
click [**here**](https://medium.com/@okehchimaobi/binary-beginnings-debugging-my-way-forward-d97b56dc6189) to view full article.



#### testing the code block function

```sh
pwd
ls
mkdir newfile
```

```html
<html>
    <head>
        <title>
            my website
        </title>
    </head>

    <body>
        <h1> this is a h1 header </h1>
        <hr>
        <p> this is a block of text </p>
        <br>
        <pre> this is a pre formatted text </pre>

    </body>
</html>

```

```python
a = 0
while a < 5000:
    print('yes')
    a += 100
```

```sql
create table employees(id int primary, firstname varchar(50), lastname varchar(50), email varchar(50), date_of_birth date);
values(001,'michael','peters','michaelpeters@yahoo.com, 1985-05-29')

select * from employees;
```


