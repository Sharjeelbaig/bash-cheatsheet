# # Switch Case:

```bash
#!/bin/bash

number=3

case $number in
    1)
        echo "Number is 1"
        ;;
    2)
        echo "Number is 2"
        ;;
    3)
        echo "Number is 3"
        ;;
    *)
        echo "Number is neither 1, 2, nor 3"
        ;;
esac
```

# Assingning a variable:

```bash
variable_name=value
```

# accessing a variable:

```bash
echo $variable_name
```

# Mathematical Operation

```bash
counter=2
result=$((counter + 1))
```

# do while loop:

```bash
counter=0
while true; do
    # Code to be executed
    echo "Executing code - Iteration: $counter"

    # TODO: Add loop condition
    counter=$((counter + 1))

    # Break statement example
    if [ $counter -eq 5 ]; then
        echo "Breaking the loop at Iteration: $counter"
        break
    fi
done
```

# displaying any number/s of lines from a command or file

```bash
command | head -n 1 # displays the first line
command | head -n 2 # displays the first two lines
command | head -n 3 # displays the first three lines
```

# list all files in a directory

```bash
ls
```

# if elsif else

```bash
if [ $number -eq 1 ]; then
    echo "Number is 1"
elif [ $number -eq 2 ]; then
    echo "Number is 2"
else
    echo "Number is neither 1 nor 2"
fi
                ---------------------
                # -eq is equal to
                # -ne is not equal to
                # -gt is greater than
                # -ge is greater than or equal to
                # -lt is less than
                # -le is less than or equal to
                # -z is empty
                # -n is not empty
                ----------------------
```

# $ stuff

```bash
$variable_name # displays the value of the variable
$# # displays the number of arguments passed to the script
$@ # displays all the arguments passed to the script
$0 # displays the name of the script
$1 # displays the first argument passed to the script
$2 # displays the second argument passed to the script
$? # displays the exit status of the last command executed
```

# % stuff

```bash
%variable_name # stores the value of the variable
%H # hour
%M # minute
%S # second
%Y # year
%m # month
%d # day
%a # weekday
%b # month
```

# command "-" stuff

```bash
- r # recursive
- f # force
- v # verbose
- h # human readable
- l # symbolic link
- a # all
- i # interactive
- d # directory
- p # preserve
- u # update
- t # time
- c # count
- n # number
- s # summary
- q # quiet
- x # extract
- z # zip
- e # extract
- k # keep
- m # move
- o # owner
- g # group
- w # write
- b # block
- c # character
- p # port
- P # port
- I # interface
- s # source
- d # destination
- S # source
- D # destination
```

# commands

```bash
ls # list files
cd # change directory
pwd # print working directory
mkdir # make directory
touch # create file
cp # copy
mv # move
rm # remove
cat # concatenate
less # page through file
head # display first lines of a file
tail # display last lines of a file
sort # sort
wc # word count
uniq # display unique lines
grep # search
sed # stream editor
awk # pattern scanning and processing language
find # find files
chmod # change permissions
chown # change ownership
tar # archive
gzip # compress
gunzip # uncompress
curl # transfer data
ssh # secure shell
scp # secure copy
rsync # remote sync
ping # ping
traceroute # trace route
dig # domain information groper
```
