> **Description**

    Python scripts are invoked kind of like programs in the Terminal... 
    Can you run this Python script using this password to get the flag?


> **Files**

[this Pyhton script](https://mercury.picoctf.net/static/325a52d249be0bd3811421eacd2c877a/ende.py)

[this password](https://mercury.picoctf.net/static/325a52d249be0bd3811421eacd2c877a/pw.txt)

[the flag](https://mercury.picoctf.net/static/325a52d249be0bd3811421eacd2c877a/flag.txt.en)


> **Solve**

```
    cat pw.txt
    python ende.py -d flag.txt.en
```



> **Result**

![Screenshot at 2024-03-13 13-13-11](https://github.com/Yorkulov/Capture-The-Flag/assets/102275892/f9703d3f-06b4-42a1-81c2-992111dddb87)


> _Additional Information_ 

    1. `cat` is a versatile command for viewing, manipulating, and working with file content in Linux.
    2. The `python` command is used to run python files

> _Point_

    10

> _Type_

    General Skills
