> **Description**

    Files can always be changed in a secret way. Can you find the flag? cat.jpg
    **Hints**
    Look at the details of the file


> **Files**

[Download flag](https://mercury.picoctf.net/static/0e428b2db9788d31189329bed089ce98/flag).


> **Solve**

```
head -n 10 cat.jpg
    Supernatural objects found:
    _**W5M0MpCehiHzreSzNTczkc9d**_
    _**cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9**_
echo W5M0MpCehiHzreSzNTczkc9d | base64 -d
    print: [�42���!��573��]
echo cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9 | base64 -d
    print: picoCTF{the_m3tadata_1s_modified}
```


> **Result**

![Screenshot at 2024-03-13 14-10-02](https://github.com/Yorkulov/Capture-The-Flag/assets/102275892/929a2145-1ec2-4249-942c-b296b08417f3)


> _Additional Information_

    1. head -n 10 cat.jpg: This tries to display the first 10 lines of "cat.jpg" using (-n 10) head.
    This will output the file details
    2. echo cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9 | base64 -d: This part decodes a message encoded in base64. 

> _Point_

    10

> _Type_

    Forensics
