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
```sh 
ls
```
5. `cd ` is used to move forward
```sh
cd dir
```
6. `cd ..` is used to go back
```sh
cd ..
```
7. `mv` used to move a directory or file to a new directory
```sh
mv filename 'new directory'

mv filename newfilename

mv filename filename.html
``` 

> the second code renames the file from current name to new name

>the third code changes the file from current format to a new format

8. `touch` creates a newfile
```sh
touch index.html
```

9. `echo` displays a string on a the terminal
```sh
echo hello world
echo hello world 'new file'
echo hello world >> 'new file'
```
>the second code prints a string on a file

>the third code prints another string without overwriting the original content

10. `cat` displays the content of a file
```sh
cat file
```
11. `vi` is used to enter the inbuilt IDE in git bash `i` is used to enter edit mode
```sh
vi
vi file
```
> the second code "`vi` newfile" is used to enter the IDE with a file
12. `esc` to exit editor mode & `:q!` to exit the IDE. Also `:wq` to save and quit if you entered with a file
 
    
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


