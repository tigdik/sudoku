Commands:
-------------
Assuming pwd is top project dir ("sudoku")

to build executable jar:
-------------
    sbt assembly
    
Check test reports in target/test-reports

to run:
-------------
If on mac or linux you may need to add permissions to validate.sh first: 

     chmod +x validate.sh
     
If you are using Windows rename file to validate.bat

Execute the program:

Mac/Linux:
      
     ./validate.sh  "PATH_TO_INPUT_FILE"
     
Windows:

    validate.bat "PATH_TO_INPUT_FILE"