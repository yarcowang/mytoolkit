My Toolkit
============
This project contains my toolkit (python script) which may be also useful to you.

Intro
-----
Contain some useful toolkit (python script). For example, `generating random password`. See more below.

How to use
-----------
**use -h to see more help**

* genpwd -- an utility tool for generating random password

```bash
$ genpwd
IOBAOY_Z

$ genpwd -h
```

* namerule -- an utility script to convert name rule between underscores and camelCase/PascalCase

```bash
$ echo -n 'item.userName' | ./namerule -u
user_name
$ echo -n 'item.userName' | ./namerule -u --noobjname
user_name
$ echo -n 'item.userName' | ./namerule -u --objname2prefix
item_user_name
$ echo -n 'item_user_name' | ./namerule -p
ItemUserName
$ echo -n 'item_user_name' | ./namerule -p --objnamedepth 1
item.UserName
$ echo -n 'item_user_name' | ./namerule -p --objnamedepth 2
item.user.Name
$ echo -n 'item_user_name' | ./namerule -c --objnamedepth 2
item.user.name
```

ChangeLog
----------

Contact
--------
You could contact [me][] through <yarco.wang@gmail.com> according to further debugging or maintance. Programming related topics are also welcomed.

timezone: GMT+0800

[me]:http://bbish.net

