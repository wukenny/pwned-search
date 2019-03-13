# pwned-search
Pwned Password API lookup

Usage:

* `python pwned.py` – reads passwords from standard input;
* `pytohn pwned.py <[file-with-passwords]` – reads passwords from
  a file;
* `another-command | pytohn pwned.py <[file-with-passwords]` – reads
  passwords written to standard output by another command;
* `python pwned.py [password]` – checks passwords given as command line
  arguments (beware the password may be saved in shell history and that
  other users on the system ma be able to observe the command line).

Have fun! Oh, and if you find one of your own passwords, change it asap!