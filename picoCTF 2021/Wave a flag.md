> **Description**

    Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information...
    **Hints**
    Run this program by entering the following in the Terminal prompt: $ ./warm, 
    but you'll first have to make it executable with $ chmod +x warm


> **Files**

    [this Program](https://mercury.picoctf.net/static/f95b1ee9f29d631d99073e34703a2826/warm).


> **Solve**

```
file warm
chmod u+x warm
./warm
./warm -h
```


> **Result**

![Screenshot at 2024-03-13 13-13-11](https://github.com/Yorkulov/Capture-The-Flag/assets/102275892/0f0b46a9-e147-499e-a332-ddedb18b3b01)


> _Additional Information_ 


    file warm: This checks if a file named "warm" exists in your current directory.

    chmod u+x warm: This makes the "warm" file executable by you (the current user) if it's a script.

    ./warm: If "warm" is executable, this runs the script.

    ./warm -h: If "warm" is executable and has a help option, this displays usage instructions.

> _Point_

    10

> _Type_

    General Skills
