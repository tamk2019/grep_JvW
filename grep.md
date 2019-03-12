#What is the grep command?
GREP stands for Groot, Rocket, Eragon and Pokémon. Or then it stands for Global Regular Expression Print.
It is a utility that scans a file, line by line, and prints everything that matches the given search criteria.
Simple example:

```bash

grep 'MAKKARA' menu.txt
```

will print all occurances of 'MAKKARA' found in the file menu.txt.
That means the lines that contain MAKKARA. Please note that grep is case sensitive. But

```bash

grep -i 'MAKKARA' menu.txt
```

will print out all the lines in menu.txt containing makkara, Makkara, maKKara (you get the point) - theswitch -i turns off case snsistivity.


#What is the averege flight velocity of an unlaiden swallow?
What do you mean, an african or an european swallow?

#Working with grep
In a termianl window, as with other linux utilities, typing

```bash
grep --help
```

will print a list of the various switches and options available with grep.

Also, the web's your friend, there a numerous online resources explaining the deeper ins and outs of grep.

Happy grepping!

