# PerficientTest
Instructions:
1.	Un-zip the project to the folder you desire
2.	From the console navigate to that directory
3.	Execute the batch file BatchBuild.bat (This will compile everything but the unit tests)
a.	Or you can open the solution in visual studio
b.	Select the project you wish to run from the solution properties (Note: PerficientProgrammingTest has a parameters setting that is essentially a JSON string specifying the bottom, top and a key/value pair set of word:number this configures the run.
4.	The console app will then present the output and await a carriage return to end.
a.	The WinForm app will populate the parameters from text boxes and a DataGridView once the run button is clicked
b.	The app will then output the results into the TextBox results.
5.	The Unit Tests are numbered relative to the Use Cases presented
6.	In the case of ranges of numbers greater than 1000, I created a batch process to limit the resource consumption.

PerficientTest
