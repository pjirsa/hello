# Hello world script

A simple script showing the basic Hello World! example for the Nextflow framework.

This fork includes a devcontainer configuration which will create a GitHub Codespace for Nextflow development!

Devcontainer specs:
- [DevContainer config](.devcontainer/devcontainer.json)
- [Dockerfile](.devcontainer/Dockerfile)

# Getting started
- Create a new repo in GitHub using this [template](https://github.com/pjirsa/hello/generate).
- Open the repo in [Codespaces](../../codespaces)
- Once Codespace is open, enter this into the terminal:
`~/nextflow main.nf`

expected output:
```
N E X T F L O W  ~  version 21.10.6
Launching `main.nf` [fervent_ardinghelli] - revision: d3a65fa206
executor >  local (4)
[3c/886523] process > sayHello (4) [100%] 4 of 4 ✔
Hello world!

Ciao world!

Bonjour world!

Hola world!
```

# Error:

```
NOTE: Nextflow is not tested with Java 1.8.0_322 -- It's recommended the use of version 11 up to 18

Error: A JNI error has occurred, please check your installation and try again
Exception in thread "main" java.lang.UnsupportedClassVersionError: org/eclipse/jgit/api/errors/GitAPIException has been compiled by a more recent version of the Java Runtime (class file version 55.0), this version of the Java Runtime only recognizes class file versions up to 52.0
        at java.lang.ClassLoader.defineClass1(Native Method)
        at java.lang.ClassLoader.defineClass(ClassLoader.java:756)
        at java.security.SecureClassLoader.defineClass(SecureClassLoader.java:142)
        at java.net.URLClassLoader.defineClass(URLClassLoader.java:473)
        at java.net.URLClassLoader.access$100(URLClassLoader.java:74)
        at java.net.URLClassLoader$1.run(URLClassLoader.java:369)
        at java.net.URLClassLoader$1.run(URLClassLoader.java:363)
        at java.security.AccessController.doPrivileged(Native Method)
        at java.net.URLClassLoader.findClass(URLClassLoader.java:362)
        at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
        at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
        at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
        at java.lang.Class.getDeclaredMethods0(Native Method)
        at java.lang.Class.privateGetDeclaredMethods(Class.java:2701)
        at java.lang.Class.privateGetMethodRecursive(Class.java:3048)
        at java.lang.Class.getMethod0(Class.java:3018)
        at java.lang.Class.getMethod(Class.java:1784)
        at sun.launcher.LauncherHelper.validateMainClass(LauncherHelper.java:650)
        at sun.launcher.LauncherHelper.checkAndLoadMain(LauncherHelper.java:632)
```
