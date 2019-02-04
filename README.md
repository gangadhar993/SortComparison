# SortComparison

Team Assignment

Team members:
Gangadhar Adusumalli
Gouthami Pasham
Poojitha Singham
Srujana Gattu
Himabindu Poshala

Questionns:
1)	Which algorithm is faster?
Ans) Bucket Sort is the fastest algorithm.

2)	Where is the entry point of the application? (The place execution begins - provide the fully qualified class name and method name)
Ans) SortComparison.Program.Main

3)	What is the name of the code file that displays the main form?
Ans) frmMain.cs

4)	What method does the main form constructor call?  Hint: look at frmMain.cs, right-click if necessary to "View Code", and then find the constructor (the constructor method name is the same as the class name.)
Ans) InitializeComponent();

5)	What is the fully qualified name of the class from which the main form is derived?
Ans) System.Windows.Forms.Form

6)	Add code to the Form1_Load method - use intellisense and your IDE to determine: What is this.tbSamples.Value? Set the default value to 10x your team number (if team 1, use 100). If this causes an error, read the error message carefully and make changes as needed.
Ans) It is an instance of System.Windows.Forms.TrackBar class. It stores the sample value for sorting.

7)	What is this.cboAlg1?  Set its SelectedIndex to an integer so that the default is Bucket Sort.
Ans) It is an instance of System.Windows.Forms.ComboBox class. It stores the reference of first selected algorithm.

8)	What is this.cboAlg2? Set its SelectedIndex to an integer so that the default is Quick Sort.
Ans) It is an instance of System.Windows.Forms.ComboBox class. It stores the reference of second selected algorithm.

9)	Use AppDomain.CurrentDomain.BaseDirectory.ToString() to get the base directory.
Done

10)	Create a new method called InitializeOutputFolder() and call it - see the suggested content below. What does this method do?
Ans) InitializeOutputFolder() method return the returns the directory from where the current application domain was loaded.

11)	What is this.cmdShuffle?  Call its PerformClick() method before exiting Form1_Load.
Ans) It is an instance of System.Windows.Forms.Button class. It stores the reference to the shuffle button.

12)	What is this.cmdSort?  Change its appearance (e.g. ForeColor or BackColor) to highlight it so users will click it.
 Ans) It is an instance of System.Windows.Forms.Button class. It stores the reference to the sort button and when the button is clicked the sorting comparison starts.

13)	Make at least one other obvious improvement or customization as desired.
 Ans) Changed background color of shuffle and sort selection list.

