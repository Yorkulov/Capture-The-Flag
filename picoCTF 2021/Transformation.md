> **Description**

    I wonder what this really is... enc 
    `''.join([chr((ord(flag[i]) << 8) + ord(flag[i + 1])) for i in range(0, len(flag), 2)])`


> **Files**

[Download enc](https://mercury.picoctf.net/static/a757282979af14ab5ed74f0ed5e2ca95/enc).


> **Solve**
    
    I wrote python code and I launched it with the enc file
    `python name.py encpy enc` 

    python code in the image below


> **Result**

![image](https://github.com/Yorkulov/Capture-The-Flag/assets/102275892/2fc1112a-c000-4737-a7e7-a9cfaf34748a)


> _Additional Information_ 

    1. `python` command is used to run python programs

> _Point_

    20

> _Type_

    Reverse Engineering
