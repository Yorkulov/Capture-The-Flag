> **Description**

    Can you look at the data in this binary: `static`? This `BASH script` might help!


> **Files**

[Download static](https://mercury.picoctf.net/static/0f6ea599582dcce7b4f1ba94e3617baf/static)

[Download BASH script](https://mercury.picoctf.net/static/0f6ea599582dcce7b4f1ba94e3617baf/ltdis.sh)


> **Solve**

```
    chmod u+x  ltdish.sh
    bash ltdish.sh static
```


> **Result**

![Screenshot at 2024-03-15 13-24-34](https://github.com/Yorkulov/Capture-The-Flag/assets/102275892/715a27d3-6e74-4319-8451-101aabc83950)
![Screenshot at 2024-03-15 13-25-07](https://github.com/Yorkulov/Capture-The-Flag/assets/102275892/3499954b-0112-4f83-8e91-efbdad2ae2d2)



> _Additional Information_ 

    1. `chmod u+x ltdish.sh` This makes the "ltdish.sh" file executable by you (the current user) if it's a script.
    2. `bash ltdish.sh static` This runs thr script with 'static' file

> _Point_

    20

> _Type_

    General Skills
