> **Description**
    
    Using tabcomplete in the Terminal will add years to your life, esp. 
    when dealing with long rambling directory structures and filenames: `Addadshashanammu.zip`
    **Hints**
    After `unzip`ing, this problem can be solved with 11 button-presses...(mostly Tab)...


> **Files**

[Download Addadshashanammu.zip](https://mercury.picoctf.net/static/9689f2b453ad5daeb73ca7534e4d1521/Addadshashanammu.zip).


> **Solve**

```
    unzip Addadshashanammu.zip
    cd Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku/
    file fang-of-haynekhtnamet
    ./fang-of-haynekhtnamet
```


> **Result**

![Screenshot at 2024-03-15 13-44-00](https://github.com/Yorkulov/Capture-The-Flag/assets/102275892/0bacca71-d05b-4fbe-937e-f5825a92c917)


> _Additional Information_ 

    1. unzip Addadshashanammu.zip: This extracts a file named "Addadshashanammu.zip"
    2.  cd Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku/: This navigates through a complex directory structure within the extracted folder.
    3. file fang-of-haynekhtnamet: This identifies the file type of "fang-of-haynekhtnamet" within the final directory.
    4. ./fang-of-haynekhtnamet: This attempts to execute the "fang-of-haynekhtnamet" file, possibly searching for a flag or hidden message.

> _Point_

    20

> _Type_

    General Skills
