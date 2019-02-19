# Lab1 Reflection

(This only involves basic concept and common mistakes, if you are looking for detailed instruction on how to do something, you're in the wrong place.)

## Environmental Variables

### In Lab

In the first lab, we need to set up a few environmental variables in order to get things work, so what happened exactly?

In a CLI(Command Line Interface), when you input a command(in our case, the `java` and `javac`), the `cmd` (for Windows) will not try to search this program in the entire disk, which will take insanely long time to do. Instead, it will just go and look things that is listed in the `PATH` environmental variable. That's where the environmental variable do its magic. 

For the `PATH` variable here, it's just a list of folders for the `cmd` to find, in other cases the variable can be more complex.

### In Real World

There are quite a few environmental variables in all platforms. They are just pre-set values for system to read. Like where to search certain program or what program should be used for certain purpose. In the lab we just set the `PATH` to tell the system where the `java` and `javac` are.

## System Permission

### In Lab

When trying to fire the Java up, some of you meet the problem that you cannot create new files in certain place(Windows Disk C in general cases).

It's because the Windows and most systems are designed for the multi-user scenario. So it come with a system that manage the access to certain file(you definitely do not want someone can just open your file simply by clicking it.)

 In the Lab, since the C Disk is the place where usually system is installed, it is also protected by this system, it will not allow you to mess with it unless you say so.

### In Real World

The permission system is to complex to be talked about here. It's widely used in the UNIX-Like world. If you want to know more, please search by yourself.



## JVM and Why

TODO. 

