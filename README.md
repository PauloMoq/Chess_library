## Author : Paul Hurdebourcq
## Contact : 
    -mail : phurdepro@gmail.com
    -discord : Moqmoq#9059

## Getting Started

    -1.0 : Setup
    -1.1 : Useful commands
    -1.2 : greetings

## 1.0
    Setup the myChessLib :

        Step (1) : download the Lib_Echec.jar file at https://github.com/PauloMoq/Chess_library

        Step (2) : choose Configure Classpath for your actual Java Project, you will find it on the low part of the explorer, on the left of the JAVA PROJECT section, with the ... button. 

            => if you have any trouble, look how to create a Java Project at https://code.visualstudio.com/docs/java/java-project#:~:text=You%20can%20create%20a%20new%20Java%20project%20by,%28s%29%20weren%27t%20already%20installed.%20Import%20Java%20projects%20%23

        Step (3) : in the Configure Classpath, scroll down and at the end, you will see a "Referenced Libraries" title. Just below this title, you will see the Add button, below the Path section. Click on the Add button.

        Step (4) : then, simply select the Lib_Echec.jar file downloaded earlier.

        Step (5) : you're done, you can now enjoy my awesome library !!!


## 1.1
    Useful commands for library management :

        [1] => Create javadoc : javadoc -encoding utf-8 -d ../doc .\myChessLib\pieces\pions\Pion.java 
        (for one Class only)

        OR

        javadoc -encoding utf-8 -d ../doc *.java
        (for all Classes at once)

        [2] => Create a jar archive : (keyboard) ctrl+shift+p, java: export jar, select the main class, select the elements, OK
        if done correctyly, vsc terminal will go crazy & ask you to press any key to escape the export jar mode

## 1.2
    Thank you for downloading my library !!!
    You can contact me if you have any question, you will find those information on top of this file (l.3 & l.4)
