# JVM

Difference between JVM, JDK and JRE.

  1. JDK: Java Developer Kit contains tools needed to develop the Java programs, and JRE to run the programs. The tools include
  compiler (javac.exe), Java application launcher (java.exe), Appletviewer, etc… Compiler converts java code into byte code.Java   application launcher opens a JRE, loads the class, and invokes its main method.
  
  
  You need JDK, if at all you want to write your own programs, and to compile the m. For running java programs, JRE is
  sufficient. JDK is mainly targeted for java development. I.e. You can create a Java file (with the help
  of Java packages), compile a Java file and run a java file.


  2. JRE:  JRE is targeted for execution of Java files i.e. JRE = JVM + Java Packages Classes(like util, math, lang,
  awt,swing etc)+runtime libraries.  Java Runtime Environment contains JVM, class libraries, and other supporting files. It does
  not contain any development tools such as compiler, debugger, etc. Actually JVM runs the program, and it uses the class
  libraries, and other supporting files provided in JRE. If you want to run any java program, you need to have JRE installed in
  the system.
  
  3. JVM:  As we all aware when we compile a Java file, output is not an ‘exe’ but it’s a ‘.class’ file. ‘.class’ file consists
  of Java byte codes which are understandable by JVM. Java Virtual Machine interprets the byte code into the machine code
  depending upon the underlying operating system and hardware combination. It is responsible for all the things like garbage
  collection, array bounds checking, etc… JVM is platform dependent.

Phsical structure of JVM: go to wiki.

  
