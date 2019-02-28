# HMACSHA1
A Implementation of HMAC Encryption by using SHA-1 Hash Function

### Introduction
**HMACSHA1** is a C++ Implementation of Image Super-Resolution using SRCNN which is proposed by Chao Dong in 2014.
 - If you want to find the details of SRCNN algorithm, please read the paper:  



### License
SRCNN_Cpp is released under the GPL v2 License (refer to the LICENSE file for details).

### Contents
1. [Requirements](#requirements)
2. [Compile](#compile)
3. [Demo](#demo)

### Requirements

1. 

**Note:**

### Compile

You can compile the Java files on the command line in your Linux system. 

``` Shell
$ ./opencv.sh SRCNN
```

If the compile is successful, you will see the information below:

### Demo

You can run the following command to test the demo program.

``` Shell
java HMACSHA1 [key] [file]
```

For example,

``` Shell
java HMACSHA1 shuw127 mytarball5.tgz
```

And the output should be:
``` Shell
Key         : shuw127
Hashed Key  : 5E9D8FF86CCE4780AF80C37A47BC8251E85D1AD4
File name   : mytarball5.tgz
HMAC result : CA6ED3DE879E81F710EEF5D53C56E8B90244BD34
```


Enjoy yourself~
