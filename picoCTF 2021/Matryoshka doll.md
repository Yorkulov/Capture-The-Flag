> **Description**
    
    Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another.
    What's the final one? Image: `this`
    **Hints**
    Wait, you can hide files inside files? But how do you find them?

> **Files**

[Download image](https://mercury.picoctf.net/static/b6205dd933ec01c022c4e6acbdf11116/dolls.jpg)


> **Solve**

```
  unzip dolls.jpg
  unzip /base_images/2_c.jpg
  unzip /base_images/base_images/3_c.jpg
  unzip /base_images/base_images/base_images/4_c.jpg
  cat flag.txt
```


> **Result**

![image](https://github.com/Yorkulov/Capture-The-Flag/assets/102275892/1fd147b5-7129-448f-8233-01f302c11386)


> _Additional Information_ 

    The Task: Unzipping a Secret
    
        Imagine a seemingly ordinary image file, dolls.jpg.
        The first command, unzip dolls.jpg, treats this image as a hidden archive.
        Unzipping it unlocks a secret folder structure, likely named base_images.
    
    A Matryoshka Doll of Secrets
    
        The subsequent commands (unzip /base_images/2_c.jpg, etc.) act like opening a set of Matryoshka dolls.
        Each unzip command operates on an image file found within the previous archive.
        These image files themselves contain hidden archives!
    
    Reaching the Core: Unveiling the Flag
    
        After navigating through these nested archives, the final unzip command likely extracts a special file named flag.txt.
    
    Displaying the Prize: Reading the Flag
    
        The last command, cat flag.txt, reveals the contents of the flag.txt file.
        This file most likely holds the hidden message or code, potentially the answer to a challenge.
    
    In Summary:
    
    These commands cleverly utilize hidden archives within image files to conceal a message. 
    By unzipping these layers, you ultimately reach the hidden flag. This process demonstrates a technique called steganography,
    used to hide information in plain sight.

> _Point_

    30

> _Type_

    Forensics
