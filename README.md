# HMACSHA1
A Implementation of HMAC Encryption by using SHA-1 Hash Function

### Introduction
**HMACSHA1** is a Java Implementation of HMAC Encryption by using SHA-1 Hash Function.
 - If you want to find the details of encryption algorithm, please read the links:  
 SHA-1: https://en.wikipedia.org/wiki/SHA-1
 HMAC:  https://en.wikipedia.org/wiki/HMAC


### License
HMACSHA1 is released under the GPL v2 License (refer to the LICENSE file for details).

### Contents
1. [Requirements](#requirements)
2. [Compile](#compile)
3. [Demo](#demo)

### Requirements

1. Linux System
2. Java

**Note:** You can use Eclipse IDE to compile the code.

### Compile

You can compile the Java files on the command line in your Linux system. 

``` Shell
$ javac HMACSHA1.java
```

If the compile is successful, you will see the file: HMACSHA1.class

### Demo

You can run the following command to test the demo program.

``` Shell
java HMACSHA1 [key] [file]
```

For example,

``` Shell
java HMACSHA1 shuw127 testfile.tgz
```

And the output should be:
``` Shell
Key         : shuw127
Hashed Key  : 5E9D8FF86CCE4780AF80C37A47BC8251E85D1AD4
File name   : testfile.tgz
HMAC result : CA6ED3DE879E81F710EEF5D53C56E8B90244BD34
```


Enjoy yourself~
