Running this project involves running different programs/scripts in java and perl.

1. Perl scripts
Instructions to run the perl script are included inside each script.

2. POSTagging project
The POSTagging directory is an Eclipse project which can be imported following the instructions on:
http://www.galalaly.me/index.php/2011/05/tagging-text-with-stanford-pos-tagger-in-java-applications/
Under the src directory you will find a Tagger.java file, this program uses the Stanford tagger to compute POS Tagging for our dataset.


3. Java projects
Make sure that you import the required jar files for the java projects. You can do this in eclipse or by updating your PATH variable to include them.

Each Java file has been named appropriately to represent the feature it generates when run on the data. Please update the path to where the training and test file are before running any of the java classes for extracting features.

For compiling run the following script in the directory where the java files are:

javac -cp path_to_liblinear.jar *.java

To run use the command:

java -cp path_to_liblinear.jar name_of_the_compiled_class
