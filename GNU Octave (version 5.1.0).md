# GNU Octave (version 5.1.0)

Copyright © 1996-2018 John W. Eaton.

Permission is granted to make and distribute verbatim copies of this manual provided the copyright notice and this permission notice are preserved on all copies.

Permission is granted to copy and distribute modified versions of this manual under the conditions for verbatim copying, provided that the entire resulting derived work is distributed under the terms of a permission notice identical to this one.

Permission is granted to copy and distribute translations of this manual into another language, under the above conditions for modified versions.





## Table of Contents

- Preface
  - [Acknowledgements](https://octave.org/doc/interpreter/Acknowledgements.html#Acknowledgements)
  - [Citing Octave in Publications](https://octave.org/doc/interpreter/Citing-Octave-in-Publications.html#Citing-Octave-in-Publications)
  - [How You Can Contribute to Octave](https://octave.org/doc/interpreter/How-You-Can-Contribute-to-Octave.html#How-You-Can-Contribute-to-Octave)
  - [Distribution](https://octave.org/doc/interpreter/Distribution.html#Distribution)
- 1 A Brief Introduction to Octave
  - [1.1 Running Octave](https://octave.org/doc/interpreter/Running-Octave.html#Running-Octave)
  - 1.2 Simple Examples
    - [1.2.1 Elementary Calculations](https://octave.org/doc/interpreter/Simple-Examples.html#Elementary-Calculations)
    - [1.2.2 Creating a Matrix](https://octave.org/doc/interpreter/Simple-Examples.html#Creating-a-Matrix)
    - [1.2.3 Matrix Arithmetic](https://octave.org/doc/interpreter/Simple-Examples.html#Matrix-Arithmetic)
    - [1.2.4 Solving Systems of Linear Equations](https://octave.org/doc/interpreter/Simple-Examples.html#Solving-Systems-of-Linear-Equations)
    - [1.2.5 Integrating Differential Equations](https://octave.org/doc/interpreter/Simple-Examples.html#Integrating-Differential-Equations)
    - [1.2.6 Producing Graphical Output](https://octave.org/doc/interpreter/Simple-Examples.html#Producing-Graphical-Output)
    - [1.2.7 Help and Documentation](https://octave.org/doc/interpreter/Simple-Examples.html#Help-and-Documentation)
    - [1.2.8 Editing What You Have Typed](https://octave.org/doc/interpreter/Simple-Examples.html#Editing-What-You-Have-Typed)
  - 1.3 Conventions
    - [1.3.1 Fonts](https://octave.org/doc/interpreter/Fonts.html#Fonts)
    - [1.3.2 Evaluation Notation](https://octave.org/doc/interpreter/Evaluation-Notation.html#Evaluation-Notation)
    - [1.3.3 Printing Notation](https://octave.org/doc/interpreter/Printing-Notation.html#Printing-Notation)
    - [1.3.4 Error Messages](https://octave.org/doc/interpreter/Error-Messages.html#Error-Messages)
    - 1.3.5 Format of Descriptions
      - [1.3.5.1 A Sample Function Description](https://octave.org/doc/interpreter/A-Sample-Function-Description.html#A-Sample-Function-Description)
      - [1.3.5.2 A Sample Command Description](https://octave.org/doc/interpreter/A-Sample-Command-Description.html#A-Sample-Command-Description)
- 2 Getting Started
  - 2.1 Invoking Octave from the Command Line
    - [2.1.1 Command Line Options](https://octave.org/doc/interpreter/Command-Line-Options.html#Command-Line-Options)
    - [2.1.2 Startup Files](https://octave.org/doc/interpreter/Startup-Files.html#Startup-Files)
  - [2.2 Quitting Octave](https://octave.org/doc/interpreter/Quitting-Octave.html#Quitting-Octave)
  - [2.3 Commands for Getting Help](https://octave.org/doc/interpreter/Getting-Help.html#Getting-Help)
  - 2.4 Command Line Editing
    - [2.4.1 Cursor Motion](https://octave.org/doc/interpreter/Cursor-Motion.html#Cursor-Motion)
    - [2.4.2 Killing and Yanking](https://octave.org/doc/interpreter/Killing-and-Yanking.html#Killing-and-Yanking)
    - [2.4.3 Commands for Changing Text](https://octave.org/doc/interpreter/Commands-for-Text.html#Commands-for-Text)
    - [2.4.4 Letting Readline Type for You](https://octave.org/doc/interpreter/Commands-for-Completion.html#Commands-for-Completion)
    - [2.4.5 Commands for Manipulating the History](https://octave.org/doc/interpreter/Commands-for-History.html#Commands-for-History)
    - [2.4.6 Customizing `readline`](https://octave.org/doc/interpreter/Customizing-readline.html#Customizing-readline)
    - [2.4.7 Customizing the Prompt](https://octave.org/doc/interpreter/Customizing-the-Prompt.html#Customizing-the-Prompt)
    - [2.4.8 Diary and Echo Commands](https://octave.org/doc/interpreter/Diary-and-Echo-Commands.html#Diary-and-Echo-Commands)
  - [2.5 How Octave Reports Errors](https://octave.org/doc/interpreter/Errors.html#Errors)
  - [2.6 Executable Octave Programs](https://octave.org/doc/interpreter/Executable-Octave-Programs.html#Executable-Octave-Programs)
  - 2.7 Comments in Octave Programs
    - [2.7.1 Single Line Comments](https://octave.org/doc/interpreter/Single-Line-Comments.html#Single-Line-Comments)
    - [2.7.2 Block Comments](https://octave.org/doc/interpreter/Block-Comments.html#Block-Comments)
    - [2.7.3 Comments and the Help System](https://octave.org/doc/interpreter/Comments-and-the-Help-System.html#Comments-and-the-Help-System)
- 3 Data Types
  - 3.1 Built-in Data Types
    - [3.1.1 Numeric Objects](https://octave.org/doc/interpreter/Numeric-Objects.html#Numeric-Objects)
    - [3.1.2 Missing Data](https://octave.org/doc/interpreter/Missing-Data.html#Missing-Data)
    - [3.1.3 String Objects](https://octave.org/doc/interpreter/String-Objects.html#String-Objects)
    - [3.1.4 Data Structure Objects](https://octave.org/doc/interpreter/Data-Structure-Objects.html#Data-Structure-Objects)
    - [3.1.5 Cell Array Objects](https://octave.org/doc/interpreter/Cell-Array-Objects.html#Cell-Array-Objects)
  - [3.2 User-defined Data Types](https://octave.org/doc/interpreter/User_002ddefined-Data-Types.html#User_002ddefined-Data-Types)
  - [3.3 Object Sizes](https://octave.org/doc/interpreter/Object-Sizes.html#Object-Sizes)
- 4 Numeric Data Types
  - 4.1 Matrices
    - [4.1.1 Empty Matrices](https://octave.org/doc/interpreter/Empty-Matrices.html#Empty-Matrices)
  - [4.2 Ranges](https://octave.org/doc/interpreter/Ranges.html#Ranges)
  - [4.3 Single Precision Data Types](https://octave.org/doc/interpreter/Single-Precision-Data-Types.html#Single-Precision-Data-Types)
  - 4.4 Integer Data Types
    - [4.4.1 Integer Arithmetic](https://octave.org/doc/interpreter/Integer-Arithmetic.html#Integer-Arithmetic)
  - [4.5 Bit Manipulations](https://octave.org/doc/interpreter/Bit-Manipulations.html#Bit-Manipulations)
  - [4.6 Logical Values](https://octave.org/doc/interpreter/Logical-Values.html#Logical-Values)
  - [4.7 Promotion and Demotion of Data Types](https://octave.org/doc/interpreter/Promotion-and-Demotion-of-Data-Types.html#Promotion-and-Demotion-of-Data-Types)
  - [4.8 Predicates for Numeric Objects](https://octave.org/doc/interpreter/Predicates-for-Numeric-Objects.html#Predicates-for-Numeric-Objects)
- 5 Strings
  - [5.1 Escape Sequences in String Constants](https://octave.org/doc/interpreter/Escape-Sequences-in-String-Constants.html#Escape-Sequences-in-String-Constants)
  - [5.2 Character Arrays](https://octave.org/doc/interpreter/Character-Arrays.html#Character-Arrays)
  - 5.3 Creating Strings
    - [5.3.1 Concatenating Strings](https://octave.org/doc/interpreter/Concatenating-Strings.html#Concatenating-Strings)
    - [5.3.2 Converting Numerical Data to Strings](https://octave.org/doc/interpreter/Converting-Numerical-Data-to-Strings.html#Converting-Numerical-Data-to-Strings)
  - [5.4 Comparing Strings](https://octave.org/doc/interpreter/Comparing-Strings.html#Comparing-Strings)
  - [5.5 Manipulating Strings](https://octave.org/doc/interpreter/Manipulating-Strings.html#Manipulating-Strings)
  - [5.6 String Conversions](https://octave.org/doc/interpreter/String-Conversions.html#String-Conversions)
  - [5.7 Character Class Functions](https://octave.org/doc/interpreter/Character-Class-Functions.html#Character-Class-Functions)
- 6 Data Containers
  - 6.1 Structures
    - [6.1.1 Basic Usage and Examples](https://octave.org/doc/interpreter/Basic-Usage-and-Examples.html#Basic-Usage-and-Examples)
    - [6.1.2 Structure Arrays](https://octave.org/doc/interpreter/Structure-Arrays.html#Structure-Arrays)
    - [6.1.3 Creating Structures](https://octave.org/doc/interpreter/Creating-Structures.html#Creating-Structures)
    - [6.1.4 Manipulating Structures](https://octave.org/doc/interpreter/Manipulating-Structures.html#Manipulating-Structures)
    - [6.1.5 Processing Data in Structures](https://octave.org/doc/interpreter/Processing-Data-in-Structures.html#Processing-Data-in-Structures)
  - [6.2 containers.Map](https://octave.org/doc/interpreter/containers_002eMap.html#containers_002eMap)
  - 6.3 Cell Arrays
    - [6.3.1 Basic Usage of Cell Arrays](https://octave.org/doc/interpreter/Basic-Usage-of-Cell-Arrays.html#Basic-Usage-of-Cell-Arrays)
    - [6.3.2 Creating Cell Arrays](https://octave.org/doc/interpreter/Creating-Cell-Arrays.html#Creating-Cell-Arrays)
    - [6.3.3 Indexing Cell Arrays](https://octave.org/doc/interpreter/Indexing-Cell-Arrays.html#Indexing-Cell-Arrays)
    - [6.3.4 Cell Arrays of Strings](https://octave.org/doc/interpreter/Cell-Arrays-of-Strings.html#Cell-Arrays-of-Strings)
    - [6.3.5 Processing Data in Cell Arrays](https://octave.org/doc/interpreter/Processing-Data-in-Cell-Arrays.html#Processing-Data-in-Cell-Arrays)
  - 6.4 Comma Separated Lists
    - [6.4.1 Comma Separated Lists Generated from Cell Arrays](https://octave.org/doc/interpreter/Comma-Separated-Lists-Generated-from-Cell-Arrays.html#Comma-Separated-Lists-Generated-from-Cell-Arrays)
    - [6.4.2 Comma Separated Lists Generated from Structure Arrays](https://octave.org/doc/interpreter/Comma-Separated-Lists-Generated-from-Structure-Arrays.html#Comma-Separated-Lists-Generated-from-Structure-Arrays)
- 7 Variables
  - [7.1 Global Variables](https://octave.org/doc/interpreter/Global-Variables.html#Global-Variables)
  - [7.2 Persistent Variables](https://octave.org/doc/interpreter/Persistent-Variables.html#Persistent-Variables)
  - [7.3 Status of Variables](https://octave.org/doc/interpreter/Status-of-Variables.html#Status-of-Variables)
- 8 Expressions
  - 8.1 Index Expressions
    - [8.1.1 Advanced Indexing](https://octave.org/doc/interpreter/Advanced-Indexing.html#Advanced-Indexing)
  - 8.2 Calling Functions
    - [8.2.1 Call by Value](https://octave.org/doc/interpreter/Call-by-Value.html#Call-by-Value)
    - [8.2.2 Recursion](https://octave.org/doc/interpreter/Recursion.html#Recursion)
    - [8.2.3 Access via Handle](https://octave.org/doc/interpreter/Access-via-Handle.html#Access-via-Handle)
  - [8.3 Arithmetic Operators](https://octave.org/doc/interpreter/Arithmetic-Ops.html#Arithmetic-Ops)
  - [8.4 Comparison Operators](https://octave.org/doc/interpreter/Comparison-Ops.html#Comparison-Ops)
  - 8.5 Boolean Expressions
    - [8.5.1 Element-by-element Boolean Operators](https://octave.org/doc/interpreter/Element_002dby_002delement-Boolean-Operators.html#Element_002dby_002delement-Boolean-Operators)
    - [8.5.2 Short-circuit Boolean Operators](https://octave.org/doc/interpreter/Short_002dcircuit-Boolean-Operators.html#Short_002dcircuit-Boolean-Operators)
  - [8.6 Assignment Expressions](https://octave.org/doc/interpreter/Assignment-Ops.html#Assignment-Ops)
  - [8.7 Increment Operators](https://octave.org/doc/interpreter/Increment-Ops.html#Increment-Ops)
  - [8.8 Operator Precedence](https://octave.org/doc/interpreter/Operator-Precedence.html#Operator-Precedence)
- 9 Evaluation
  - [9.1 Calling a Function by its Name](https://octave.org/doc/interpreter/Calling-a-Function-by-its-Name.html#Calling-a-Function-by-its-Name)
  - [9.2 Evaluation in a Different Context](https://octave.org/doc/interpreter/Evaluation-in-a-Different-Context.html#Evaluation-in-a-Different-Context)
- 10 Statements
  - [10.1 The if Statement](https://octave.org/doc/interpreter/The-if-Statement.html#The-if-Statement)
  - 10.2 The switch Statement
    - [10.2.1 Notes for the C Programmer](https://octave.org/doc/interpreter/Notes-for-the-C-Programmer.html#Notes-for-the-C-Programmer)
  - [10.3 The while Statement](https://octave.org/doc/interpreter/The-while-Statement.html#The-while-Statement)
  - [10.4 The do-until Statement](https://octave.org/doc/interpreter/The-do_002duntil-Statement.html#The-do_002duntil-Statement)
  - 10.5 The for Statement
    - [10.5.1 Looping Over Structure Elements](https://octave.org/doc/interpreter/Looping-Over-Structure-Elements.html#Looping-Over-Structure-Elements)
  - [10.6 The break Statement](https://octave.org/doc/interpreter/The-break-Statement.html#The-break-Statement)
  - [10.7 The continue Statement](https://octave.org/doc/interpreter/The-continue-Statement.html#The-continue-Statement)
  - [10.8 The unwind_protect Statement](https://octave.org/doc/interpreter/The-unwind_005fprotect-Statement.html#The-unwind_005fprotect-Statement)
  - [10.9 The try Statement](https://octave.org/doc/interpreter/The-try-Statement.html#The-try-Statement)
  - [10.10 Continuation Lines](https://octave.org/doc/interpreter/Continuation-Lines.html#Continuation-Lines)
- 11 Functions and Scripts
  - [11.1 Introduction to Function and Script Files](https://octave.org/doc/interpreter/Introduction-to-Function-and-Script-Files.html#Introduction-to-Function-and-Script-Files)
  - [11.2 Defining Functions](https://octave.org/doc/interpreter/Defining-Functions.html#Defining-Functions)
  - [11.3 Multiple Return Values](https://octave.org/doc/interpreter/Multiple-Return-Values.html#Multiple-Return-Values)
  - [11.4 Variable-length Argument Lists](https://octave.org/doc/interpreter/Variable_002dlength-Argument-Lists.html#Variable_002dlength-Argument-Lists)
  - [11.5 Ignoring Arguments](https://octave.org/doc/interpreter/Ignoring-Arguments.html#Ignoring-Arguments)
  - [11.6 Variable-length Return Lists](https://octave.org/doc/interpreter/Variable_002dlength-Return-Lists.html#Variable_002dlength-Return-Lists)
  - [11.7 Returning from a Function](https://octave.org/doc/interpreter/Returning-from-a-Function.html#Returning-from-a-Function)
  - [11.8 Default Arguments](https://octave.org/doc/interpreter/Default-Arguments.html#Default-Arguments)
  - 11.9 Function Files
    - [11.9.1 Manipulating the Load Path](https://octave.org/doc/interpreter/Manipulating-the-Load-Path.html#Manipulating-the-Load-Path)
    - [11.9.2 Subfunctions](https://octave.org/doc/interpreter/Subfunctions.html#Subfunctions)
    - [11.9.3 Private Functions](https://octave.org/doc/interpreter/Private-Functions.html#Private-Functions)
    - [11.9.4 Nested Functions](https://octave.org/doc/interpreter/Nested-Functions.html#Nested-Functions)
    - [11.9.5 Overloading and Autoloading](https://octave.org/doc/interpreter/Overloading-and-Autoloading.html#Overloading-and-Autoloading)
    - [11.9.6 Function Locking](https://octave.org/doc/interpreter/Function-Locking.html#Function-Locking)
    - [11.9.7 Function Precedence](https://octave.org/doc/interpreter/Function-Precedence.html#Function-Precedence)
  - 11.10 Script Files
    - [11.10.1 Publish Octave Script Files](https://octave.org/doc/interpreter/Publish-Octave-Script-Files.html#Publish-Octave-Script-Files)
    - 11.10.2 Publishing Markup
      - [11.10.2.1 Using Publishing Markup in Script Files](https://octave.org/doc/interpreter/Using-Publishing-Markup-in-Script-Files.html#Using-Publishing-Markup-in-Script-Files)
      - [11.10.2.2 Text Formatting](https://octave.org/doc/interpreter/Text-Formatting.html#Text-Formatting)
      - [11.10.2.3 Sections](https://octave.org/doc/interpreter/Sections.html#Sections)
      - [11.10.2.4 Preformatted Code](https://octave.org/doc/interpreter/Preformatted-Code.html#Preformatted-Code)
      - [11.10.2.5 Preformatted Text](https://octave.org/doc/interpreter/Preformatted-Text.html#Preformatted-Text)
      - [11.10.2.6 Bulleted Lists](https://octave.org/doc/interpreter/Bulleted-Lists.html#Bulleted-Lists)
      - [11.10.2.7 Numbered Lists](https://octave.org/doc/interpreter/Numbered-Lists.html#Numbered-Lists)
      - [11.10.2.8 Including File Content](https://octave.org/doc/interpreter/Including-File-Content.html#Including-File-Content)
      - [11.10.2.9 Including Graphics](https://octave.org/doc/interpreter/Including-Graphics.html#Including-Graphics)
      - [11.10.2.10 Including URLs](https://octave.org/doc/interpreter/Including-URLs.html#Including-URLs)
      - [11.10.2.11 Mathematical Equations](https://octave.org/doc/interpreter/Mathematical-Equations.html#Mathematical-Equations)
      - [11.10.2.12 HTML Markup](https://octave.org/doc/interpreter/HTML-Markup.html#HTML-Markup)
      - [11.10.2.13 LaTeX Markup](https://octave.org/doc/interpreter/LaTeX-Markup.html#LaTeX-Markup)
  - 11.11 Function Handles, Anonymous Functions, Inline Functions
    - [11.11.1 Function Handles](https://octave.org/doc/interpreter/Function-Handles.html#Function-Handles)
    - [11.11.2 Anonymous Functions](https://octave.org/doc/interpreter/Anonymous-Functions.html#Anonymous-Functions)
    - [11.11.3 Inline Functions](https://octave.org/doc/interpreter/Inline-Functions.html#Inline-Functions)
  - [11.12 Commands](https://octave.org/doc/interpreter/Commands.html#Commands)
  - [11.13 Organization of Functions Distributed with Octave](https://octave.org/doc/interpreter/Organization-of-Functions.html#Organization-of-Functions)
- 12 Errors and Warnings
  - 12.1 Handling Errors
    - [12.1.1 Raising Errors](https://octave.org/doc/interpreter/Raising-Errors.html#Raising-Errors)
    - [12.1.2 Catching Errors](https://octave.org/doc/interpreter/Catching-Errors.html#Catching-Errors)
    - [12.1.3 Recovering From Errors](https://octave.org/doc/interpreter/Recovering-From-Errors.html#Recovering-From-Errors)
  - 12.2 Handling Warnings
    - [12.2.1 Issuing Warnings](https://octave.org/doc/interpreter/Issuing-Warnings.html#Issuing-Warnings)
    - [12.2.2 Enabling and Disabling Warnings](https://octave.org/doc/interpreter/Enabling-and-Disabling-Warnings.html#Enabling-and-Disabling-Warnings)
- 13 Debugging
  - [13.1 Entering Debug Mode](https://octave.org/doc/interpreter/Entering-Debug-Mode.html#Entering-Debug-Mode)
  - [13.2 Leaving Debug Mode](https://octave.org/doc/interpreter/Leaving-Debug-Mode.html#Leaving-Debug-Mode)
  - [13.3 Breakpoints](https://octave.org/doc/interpreter/Breakpoints.html#Breakpoints)
  - [13.4 Debug Mode](https://octave.org/doc/interpreter/Debug-Mode.html#Debug-Mode)
  - [13.5 Call Stack](https://octave.org/doc/interpreter/Call-Stack.html#Call-Stack)
  - [13.6 Profiling](https://octave.org/doc/interpreter/Profiling.html#Profiling)
  - [13.7 Profiler Example](https://octave.org/doc/interpreter/Profiler-Example.html#Profiler-Example)
- 14 Input and Output
  - 14.1 Basic Input and Output
    - 14.1.1 Terminal Output
      - [14.1.1.1 Paging Screen Output](https://octave.org/doc/interpreter/Paging-Screen-Output.html#Paging-Screen-Output)
    - [14.1.2 Terminal Input](https://octave.org/doc/interpreter/Terminal-Input.html#Terminal-Input)
    - 14.1.3 Simple File I/O
      - [14.1.3.1 Saving Data on Unexpected Exits](https://octave.org/doc/interpreter/Saving-Data-on-Unexpected-Exits.html#Saving-Data-on-Unexpected-Exits)
  - 14.2 C-Style I/O Functions
    - [14.2.1 Opening and Closing Files](https://octave.org/doc/interpreter/Opening-and-Closing-Files.html#Opening-and-Closing-Files)
    - [14.2.2 Simple Output](https://octave.org/doc/interpreter/Simple-Output.html#Simple-Output)
    - [14.2.3 Line-Oriented Input](https://octave.org/doc/interpreter/Line_002dOriented-Input.html#Line_002dOriented-Input)
    - [14.2.4 Formatted Output](https://octave.org/doc/interpreter/Formatted-Output.html#Formatted-Output)
    - [14.2.5 Output Conversion for Matrices](https://octave.org/doc/interpreter/Output-Conversion-for-Matrices.html#Output-Conversion-for-Matrices)
    - [14.2.6 Output Conversion Syntax](https://octave.org/doc/interpreter/Output-Conversion-Syntax.html#Output-Conversion-Syntax)
    - [14.2.7 Table of Output Conversions](https://octave.org/doc/interpreter/Table-of-Output-Conversions.html#Table-of-Output-Conversions)
    - [14.2.8 Integer Conversions](https://octave.org/doc/interpreter/Integer-Conversions.html#Integer-Conversions)
    - [14.2.9 Floating-Point Conversions](https://octave.org/doc/interpreter/Floating_002dPoint-Conversions.html#Floating_002dPoint-Conversions)
    - [14.2.10 Other Output Conversions](https://octave.org/doc/interpreter/Other-Output-Conversions.html#Other-Output-Conversions)
    - [14.2.11 Formatted Input](https://octave.org/doc/interpreter/Formatted-Input.html#Formatted-Input)
    - [14.2.12 Input Conversion Syntax](https://octave.org/doc/interpreter/Input-Conversion-Syntax.html#Input-Conversion-Syntax)
    - [14.2.13 Table of Input Conversions](https://octave.org/doc/interpreter/Table-of-Input-Conversions.html#Table-of-Input-Conversions)
    - [14.2.14 Numeric Input Conversions](https://octave.org/doc/interpreter/Numeric-Input-Conversions.html#Numeric-Input-Conversions)
    - [14.2.15 String Input Conversions](https://octave.org/doc/interpreter/String-Input-Conversions.html#String-Input-Conversions)
    - [14.2.16 Binary I/O](https://octave.org/doc/interpreter/Binary-I_002fO.html#Binary-I_002fO)
    - [14.2.17 Temporary Files](https://octave.org/doc/interpreter/Temporary-Files.html#Temporary-Files)
    - [14.2.18 End of File and Errors](https://octave.org/doc/interpreter/EOF-and-Errors.html#EOF-and-Errors)
    - [14.2.19 File Positioning](https://octave.org/doc/interpreter/File-Positioning.html#File-Positioning)
- 15 Plotting
  - [15.1 Introduction to Plotting](https://octave.org/doc/interpreter/Introduction-to-Plotting.html#Introduction-to-Plotting)
  - 15.2 High-Level Plotting
    - 15.2.1 Two-Dimensional Plots
      - [15.2.1.1 Axis Configuration](https://octave.org/doc/interpreter/Axis-Configuration.html#Axis-Configuration)
      - [15.2.1.2 Two-dimensional Function Plotting](https://octave.org/doc/interpreter/Two_002ddimensional-Function-Plotting.html#Two_002ddimensional-Function-Plotting)
      - [15.2.1.3 Two-dimensional Geometric Shapes](https://octave.org/doc/interpreter/Two_002ddimensional-Geometric-Shapes.html#Two_002ddimensional-Geometric-Shapes)
    - 15.2.2 Three-Dimensional Plots
      - [15.2.2.1 Aspect Ratio](https://octave.org/doc/interpreter/Aspect-Ratio.html#Aspect-Ratio)
      - [15.2.2.2 Three-dimensional Function Plotting](https://octave.org/doc/interpreter/Three_002ddimensional-Function-Plotting.html#Three_002ddimensional-Function-Plotting)
      - [15.2.2.3 Three-dimensional Geometric Shapes](https://octave.org/doc/interpreter/Three_002ddimensional-Geometric-Shapes.html#Three_002ddimensional-Geometric-Shapes)
    - [15.2.3 Plot Annotations](https://octave.org/doc/interpreter/Plot-Annotations.html#Plot-Annotations)
    - [15.2.4 Multiple Plots on One Page](https://octave.org/doc/interpreter/Multiple-Plots-on-One-Page.html#Multiple-Plots-on-One-Page)
    - [15.2.5 Multiple Plot Windows](https://octave.org/doc/interpreter/Multiple-Plot-Windows.html#Multiple-Plot-Windows)
    - [15.2.6 Manipulation of Plot Objects](https://octave.org/doc/interpreter/Manipulation-of-Plot-Objects.html#Manipulation-of-Plot-Objects)
    - [15.2.7 Manipulation of Plot Windows](https://octave.org/doc/interpreter/Manipulation-of-Plot-Windows.html#Manipulation-of-Plot-Windows)
    - 15.2.8 Use of the `interpreter` Property
      - [15.2.8.1 Degree Symbol](https://octave.org/doc/interpreter/Use-of-the-interpreter-Property.html#Degree-Symbol)
    - [15.2.9 Printing and Saving Plots](https://octave.org/doc/interpreter/Printing-and-Saving-Plots.html#Printing-and-Saving-Plots)
    - [15.2.10 Interacting with Plots](https://octave.org/doc/interpreter/Interacting-with-Plots.html#Interacting-with-Plots)
    - [15.2.11 Test Plotting Functions](https://octave.org/doc/interpreter/Test-Plotting-Functions.html#Test-Plotting-Functions)
  - 15.3 Graphics Data Structures
    - [15.3.1 Introduction to Graphics Structures](https://octave.org/doc/interpreter/Introduction-to-Graphics-Structures.html#Introduction-to-Graphics-Structures)
    - 15.3.2 Graphics Objects
      - [15.3.2.1 Creating Graphics Objects](https://octave.org/doc/interpreter/Graphics-Objects.html#Creating-Graphics-Objects)
      - [15.3.2.2 Handle Functions](https://octave.org/doc/interpreter/Graphics-Objects.html#Handle-Functions)
    - 15.3.3 Graphics Object Properties
      - [15.3.3.1 Root Figure Properties](https://octave.org/doc/interpreter/Root-Figure-Properties.html#Root-Figure-Properties)
      - [15.3.3.2 Figure Properties](https://octave.org/doc/interpreter/Figure-Properties.html#Figure-Properties)
      - [15.3.3.3 Axes Properties](https://octave.org/doc/interpreter/Axes-Properties.html#Axes-Properties)
      - [15.3.3.4 Line Properties](https://octave.org/doc/interpreter/Line-Properties.html#Line-Properties)
      - [15.3.3.5 Text Properties](https://octave.org/doc/interpreter/Text-Properties.html#Text-Properties)
      - [15.3.3.6 Image Properties](https://octave.org/doc/interpreter/Image-Properties.html#Image-Properties)
      - [15.3.3.7 Patch Properties](https://octave.org/doc/interpreter/Patch-Properties.html#Patch-Properties)
      - [15.3.3.8 Surface Properties](https://octave.org/doc/interpreter/Surface-Properties.html#Surface-Properties)
      - [15.3.3.9 Light Properties](https://octave.org/doc/interpreter/Light-Properties.html#Light-Properties)
      - [15.3.3.10 Uimenu Properties](https://octave.org/doc/interpreter/Uimenu-Properties.html#Uimenu-Properties)
      - [15.3.3.11 Uibuttongroup Properties](https://octave.org/doc/interpreter/Uibuttongroup-Properties.html#Uibuttongroup-Properties)
      - [15.3.3.12 Uicontextmenu Properties](https://octave.org/doc/interpreter/Uicontextmenu-Properties.html#Uicontextmenu-Properties)
      - [15.3.3.13 Uipanel Properties](https://octave.org/doc/interpreter/Uipanel-Properties.html#Uipanel-Properties)
      - [15.3.3.14 Uicontrol Properties](https://octave.org/doc/interpreter/Uicontrol-Properties.html#Uicontrol-Properties)
      - [15.3.3.15 Uitable Properties](https://octave.org/doc/interpreter/Uitable-Properties.html#Uitable-Properties)
      - [15.3.3.16 Uitoolbar Properties](https://octave.org/doc/interpreter/Uitoolbar-Properties.html#Uitoolbar-Properties)
      - [15.3.3.17 Uipushtool Properties](https://octave.org/doc/interpreter/Uipushtool-Properties.html#Uipushtool-Properties)
      - [15.3.3.18 Uitoggletool Properties](https://octave.org/doc/interpreter/Uitoggletool-Properties.html#Uitoggletool-Properties)
    - [15.3.4 Searching Properties](https://octave.org/doc/interpreter/Searching-Properties.html#Searching-Properties)
    - [15.3.5 Managing Default Properties](https://octave.org/doc/interpreter/Managing-Default-Properties.html#Managing-Default-Properties)
  - 15.4 Advanced Plotting
    - [15.4.1 Colors](https://octave.org/doc/interpreter/Colors.html#Colors)
    - [15.4.2 Line Styles](https://octave.org/doc/interpreter/Line-Styles.html#Line-Styles)
    - [15.4.3 Marker Styles](https://octave.org/doc/interpreter/Marker-Styles.html#Marker-Styles)
    - [15.4.4 Callbacks](https://octave.org/doc/interpreter/Callbacks.html#Callbacks)
    - [15.4.5 Application-defined Data](https://octave.org/doc/interpreter/Application_002ddefined-Data.html#Application_002ddefined-Data)
    - 15.4.6 Object Groups
      - [15.4.6.1 Data Sources in Object Groups](https://octave.org/doc/interpreter/Data-Sources-in-Object-Groups.html#Data-Sources-in-Object-Groups)
      - [15.4.6.2 Area Series](https://octave.org/doc/interpreter/Area-Series.html#Area-Series)
      - [15.4.6.3 Bar Series](https://octave.org/doc/interpreter/Bar-Series.html#Bar-Series)
      - [15.4.6.4 Contour Groups](https://octave.org/doc/interpreter/Contour-Groups.html#Contour-Groups)
      - [15.4.6.5 Error Bar Series](https://octave.org/doc/interpreter/Error-Bar-Series.html#Error-Bar-Series)
      - [15.4.6.6 Line Series](https://octave.org/doc/interpreter/Line-Series.html#Line-Series)
      - [15.4.6.7 Quiver Group](https://octave.org/doc/interpreter/Quiver-Group.html#Quiver-Group)
      - [15.4.6.8 Scatter Group](https://octave.org/doc/interpreter/Scatter-Group.html#Scatter-Group)
      - [15.4.6.9 Stair Group](https://octave.org/doc/interpreter/Stair-Group.html#Stair-Group)
      - [15.4.6.10 Stem Series](https://octave.org/doc/interpreter/Stem-Series.html#Stem-Series)
      - [15.4.6.11 Surface Group](https://octave.org/doc/interpreter/Surface-Group.html#Surface-Group)
    - [15.4.7 Transform Groups](https://octave.org/doc/interpreter/Transform-Groups.html#Transform-Groups)
    - 15.4.8 Graphics Toolkits
      - [15.4.8.1 Customizing Toolkit Behavior](https://octave.org/doc/interpreter/Customizing-Toolkit-Behavior.html#Customizing-Toolkit-Behavior)
      - [15.4.8.2 Hardware vs. Software Rendering](https://octave.org/doc/interpreter/Hardware-vs_002e-Software-Rendering.html#Hardware-vs_002e-Software-Rendering)
- 16 Matrix Manipulation
  - [16.1 Finding Elements and Checking Conditions](https://octave.org/doc/interpreter/Finding-Elements-and-Checking-Conditions.html#Finding-Elements-and-Checking-Conditions)
  - [16.2 Rearranging Matrices](https://octave.org/doc/interpreter/Rearranging-Matrices.html#Rearranging-Matrices)
  - [16.3 Special Utility Matrices](https://octave.org/doc/interpreter/Special-Utility-Matrices.html#Special-Utility-Matrices)
  - [16.4 Famous Matrices](https://octave.org/doc/interpreter/Famous-Matrices.html#Famous-Matrices)
- 17 Arithmetic
  - [17.1 Exponents and Logarithms](https://octave.org/doc/interpreter/Exponents-and-Logarithms.html#Exponents-and-Logarithms)
  - [17.2 Complex Arithmetic](https://octave.org/doc/interpreter/Complex-Arithmetic.html#Complex-Arithmetic)
  - [17.3 Trigonometry](https://octave.org/doc/interpreter/Trigonometry.html#Trigonometry)
  - [17.4 Sums and Products](https://octave.org/doc/interpreter/Sums-and-Products.html#Sums-and-Products)
  - [17.5 Utility Functions](https://octave.org/doc/interpreter/Utility-Functions.html#Utility-Functions)
  - [17.6 Special Functions](https://octave.org/doc/interpreter/Special-Functions.html#Special-Functions)
  - [17.7 Rational Approximations](https://octave.org/doc/interpreter/Rational-Approximations.html#Rational-Approximations)
  - [17.8 Coordinate Transformations](https://octave.org/doc/interpreter/Coordinate-Transformations.html#Coordinate-Transformations)
  - [17.9 Mathematical Constants](https://octave.org/doc/interpreter/Mathematical-Constants.html#Mathematical-Constants)
- 18 Linear Algebra
  - [18.1 Techniques Used for Linear Algebra](https://octave.org/doc/interpreter/Techniques-Used-for-Linear-Algebra.html#Techniques-Used-for-Linear-Algebra)
  - [18.2 Basic Matrix Functions](https://octave.org/doc/interpreter/Basic-Matrix-Functions.html#Basic-Matrix-Functions)
  - [18.3 Matrix Factorizations](https://octave.org/doc/interpreter/Matrix-Factorizations.html#Matrix-Factorizations)
  - [18.4 Functions of a Matrix](https://octave.org/doc/interpreter/Functions-of-a-Matrix.html#Functions-of-a-Matrix)
  - [18.5 Specialized Solvers](https://octave.org/doc/interpreter/Specialized-Solvers.html#Specialized-Solvers)
- 19 Vectorization and Faster Code Execution
  - [19.1 Basic Vectorization](https://octave.org/doc/interpreter/Basic-Vectorization.html#Basic-Vectorization)
  - 19.2 Broadcasting
    - [19.2.1 Broadcasting and Legacy Code](https://octave.org/doc/interpreter/Broadcasting.html#Broadcasting-and-Legacy-Code)
  - [19.3 Function Application](https://octave.org/doc/interpreter/Function-Application.html#Function-Application)
  - [19.4 Accumulation](https://octave.org/doc/interpreter/Accumulation.html#Accumulation)
  - [19.5 JIT Compiler](https://octave.org/doc/interpreter/JIT-Compiler.html#JIT-Compiler)
  - [19.6 Miscellaneous Techniques](https://octave.org/doc/interpreter/Miscellaneous-Techniques.html#Miscellaneous-Techniques)
  - [19.7 Examples](https://octave.org/doc/interpreter/Examples.html#Examples)
- 20 Nonlinear Equations
  - [20.1 Solvers](https://octave.org/doc/interpreter/Solvers.html#Solvers)
  - [20.2 Minimizers](https://octave.org/doc/interpreter/Minimizers.html#Minimizers)
- 21 Diagonal and Permutation Matrices
  - 21.1 Creating and Manipulating Diagonal/Permutation Matrices
    - [21.1.1 Creating Diagonal Matrices](https://octave.org/doc/interpreter/Creating-Diagonal-Matrices.html#Creating-Diagonal-Matrices)
    - [21.1.2 Creating Permutation Matrices](https://octave.org/doc/interpreter/Creating-Permutation-Matrices.html#Creating-Permutation-Matrices)
    - [21.1.3 Explicit and Implicit Conversions](https://octave.org/doc/interpreter/Explicit-and-Implicit-Conversions.html#Explicit-and-Implicit-Conversions)
  - 21.2 Linear Algebra with Diagonal/Permutation Matrices
    - [21.2.1 Expressions Involving Diagonal Matrices](https://octave.org/doc/interpreter/Expressions-Involving-Diagonal-Matrices.html#Expressions-Involving-Diagonal-Matrices)
    - [21.2.2 Expressions Involving Permutation Matrices](https://octave.org/doc/interpreter/Expressions-Involving-Permutation-Matrices.html#Expressions-Involving-Permutation-Matrices)
  - 21.3 Functions That Are Aware of These Matrices
    - [21.3.1 Diagonal Matrix Functions](https://octave.org/doc/interpreter/Diagonal-Matrix-Functions.html#Diagonal-Matrix-Functions)
    - [21.3.2 Permutation Matrix Functions](https://octave.org/doc/interpreter/Permutation-Matrix-Functions.html#Permutation-Matrix-Functions)
  - [21.4 Examples of Usage](https://octave.org/doc/interpreter/Example-Code.html#Example-Code)
  - [21.5 Differences in Treatment of Zero Elements](https://octave.org/doc/interpreter/Zeros-Treatment.html#Zeros-Treatment)
- 22 Sparse Matrices
  - 22.1 Creation and Manipulation of Sparse Matrices
    - [22.1.1 Storage of Sparse Matrices](https://octave.org/doc/interpreter/Storage-of-Sparse-Matrices.html#Storage-of-Sparse-Matrices)
    - [22.1.2 Creating Sparse Matrices](https://octave.org/doc/interpreter/Creating-Sparse-Matrices.html#Creating-Sparse-Matrices)
    - [22.1.3 Finding Information about Sparse Matrices](https://octave.org/doc/interpreter/Information.html#Information)
    - 22.1.4 Basic Operators and Functions on Sparse Matrices
      - [22.1.4.1 Sparse Functions](https://octave.org/doc/interpreter/Sparse-Functions.html#Sparse-Functions)
      - [22.1.4.2 Return Types of Operators and Functions](https://octave.org/doc/interpreter/Return-Types-of-Operators-and-Functions.html#Return-Types-of-Operators-and-Functions)
      - [22.1.4.3 Mathematical Considerations](https://octave.org/doc/interpreter/Mathematical-Considerations.html#Mathematical-Considerations)
  - [22.2 Linear Algebra on Sparse Matrices](https://octave.org/doc/interpreter/Sparse-Linear-Algebra.html#Sparse-Linear-Algebra)
  - [22.3 Iterative Techniques Applied to Sparse Matrices](https://octave.org/doc/interpreter/Iterative-Techniques.html#Iterative-Techniques)
  - [22.4 Real Life Example using Sparse Matrices](https://octave.org/doc/interpreter/Real-Life-Example.html#Real-Life-Example)
- 23 Numerical Integration
  - [23.1 Functions of One Variable](https://octave.org/doc/interpreter/Functions-of-One-Variable.html#Functions-of-One-Variable)
  - [23.2 Orthogonal Collocation](https://octave.org/doc/interpreter/Orthogonal-Collocation.html#Orthogonal-Collocation)
  - [23.3 Functions of Multiple Variables](https://octave.org/doc/interpreter/Functions-of-Multiple-Variables.html#Functions-of-Multiple-Variables)
- 24 Differential Equations
  - 24.1 Ordinary Differential Equations
    - [24.1.1 Matlab-compatible solvers](https://octave.org/doc/interpreter/Matlab_002dcompatible-solvers.html#Matlab_002dcompatible-solvers)
  - [24.2 Differential-Algebraic Equations](https://octave.org/doc/interpreter/Differential_002dAlgebraic-Equations.html#Differential_002dAlgebraic-Equations)
- 25 Optimization
  - [25.1 Linear Programming](https://octave.org/doc/interpreter/Linear-Programming.html#Linear-Programming)
  - [25.2 Quadratic Programming](https://octave.org/doc/interpreter/Quadratic-Programming.html#Quadratic-Programming)
  - [25.3 Nonlinear Programming](https://octave.org/doc/interpreter/Nonlinear-Programming.html#Nonlinear-Programming)
  - [25.4 Linear Least Squares](https://octave.org/doc/interpreter/Linear-Least-Squares.html#Linear-Least-Squares)
- 26 Statistics
  - [26.1 Descriptive Statistics](https://octave.org/doc/interpreter/Descriptive-Statistics.html#Descriptive-Statistics)
  - [26.2 Statistics on Sliding Windows of Data](https://octave.org/doc/interpreter/Statistics-on-Sliding-Windows-of-Data.html#Statistics-on-Sliding-Windows-of-Data)
  - [26.3 Basic Statistical Functions](https://octave.org/doc/interpreter/Basic-Statistical-Functions.html#Basic-Statistical-Functions)
  - [26.4 Correlation and Regression Analysis](https://octave.org/doc/interpreter/Correlation-and-Regression-Analysis.html#Correlation-and-Regression-Analysis)
  - [26.5 Distributions](https://octave.org/doc/interpreter/Distributions.html#Distributions)
  - [26.6 Random Number Generation](https://octave.org/doc/interpreter/Random-Number-Generation.html#Random-Number-Generation)
- 27 Sets
  - [27.1 Set Operations](https://octave.org/doc/interpreter/Set-Operations.html#Set-Operations)
- 28 Polynomial Manipulations
  - [28.1 Evaluating Polynomials](https://octave.org/doc/interpreter/Evaluating-Polynomials.html#Evaluating-Polynomials)
  - [28.2 Finding Roots](https://octave.org/doc/interpreter/Finding-Roots.html#Finding-Roots)
  - [28.3 Products of Polynomials](https://octave.org/doc/interpreter/Products-of-Polynomials.html#Products-of-Polynomials)
  - [28.4 Derivatives / Integrals / Transforms](https://octave.org/doc/interpreter/Derivatives-_002f-Integrals-_002f-Transforms.html#Derivatives-_002f-Integrals-_002f-Transforms)
  - [28.5 Polynomial Interpolation](https://octave.org/doc/interpreter/Polynomial-Interpolation.html#Polynomial-Interpolation)
  - [28.6 Miscellaneous Functions](https://octave.org/doc/interpreter/Miscellaneous-Functions.html#Miscellaneous-Functions)
- 29 Interpolation
  - [29.1 One-dimensional Interpolation](https://octave.org/doc/interpreter/One_002ddimensional-Interpolation.html#One_002ddimensional-Interpolation)
  - [29.2 Multi-dimensional Interpolation](https://octave.org/doc/interpreter/Multi_002ddimensional-Interpolation.html#Multi_002ddimensional-Interpolation)
- 30 Geometry
  - 30.1 Delaunay Triangulation
    - [30.1.1 Plotting the Triangulation](https://octave.org/doc/interpreter/Plotting-the-Triangulation.html#Plotting-the-Triangulation)
    - [30.1.2 Identifying Points in Triangulation](https://octave.org/doc/interpreter/Identifying-Points-in-Triangulation.html#Identifying-Points-in-Triangulation)
  - [30.2 Voronoi Diagrams](https://octave.org/doc/interpreter/Voronoi-Diagrams.html#Voronoi-Diagrams)
  - [30.3 Convex Hull](https://octave.org/doc/interpreter/Convex-Hull.html#Convex-Hull)
  - [30.4 Interpolation on Scattered Data](https://octave.org/doc/interpreter/Interpolation-on-Scattered-Data.html#Interpolation-on-Scattered-Data)
- [31 Signal Processing](https://octave.org/doc/interpreter/Signal-Processing.html#Signal-Processing)
- 32 Image Processing
  - [32.1 Loading and Saving Images](https://octave.org/doc/interpreter/Loading-and-Saving-Images.html#Loading-and-Saving-Images)
  - [32.2 Displaying Images](https://octave.org/doc/interpreter/Displaying-Images.html#Displaying-Images)
  - [32.3 Representing Images](https://octave.org/doc/interpreter/Representing-Images.html#Representing-Images)
  - [32.4 Plotting on top of Images](https://octave.org/doc/interpreter/Plotting-on-top-of-Images.html#Plotting-on-top-of-Images)
  - [32.5 Color Conversion](https://octave.org/doc/interpreter/Color-Conversion.html#Color-Conversion)
- 33 Audio Processing
  - [33.1 Audio File Utilities](https://octave.org/doc/interpreter/Audio-File-Utilities.html#Audio-File-Utilities)
  - [33.2 Audio Device Information](https://octave.org/doc/interpreter/Audio-Device-Information.html#Audio-Device-Information)
  - 33.3 Audio Player
    - [33.3.1 Playback](https://octave.org/doc/interpreter/Playback.html#Playback)
    - [33.3.2 Properties](https://octave.org/doc/interpreter/Player-Properties.html#Player-Properties)
  - 33.4 Audio Recorder
    - [33.4.1 Recording](https://octave.org/doc/interpreter/Recording.html#Recording)
    - [33.4.2 Data Retrieval](https://octave.org/doc/interpreter/Data-Retrieval.html#Data-Retrieval)
    - [33.4.3 Properties](https://octave.org/doc/interpreter/Recorder-Properties.html#Recorder-Properties)
  - [33.5 Audio Data Processing](https://octave.org/doc/interpreter/Audio-Data-Processing.html#Audio-Data-Processing)
- 34 Object Oriented Programming
  - [34.1 Creating a Class](https://octave.org/doc/interpreter/Creating-a-Class.html#Creating-a-Class)
  - [34.2 Class Methods](https://octave.org/doc/interpreter/Class-Methods.html#Class-Methods)
  - 34.3 Indexing Objects
    - [34.3.1 Defining Indexing And Indexed Assignment](https://octave.org/doc/interpreter/Defining-Indexing-And-Indexed-Assignment.html#Defining-Indexing-And-Indexed-Assignment)
    - [34.3.2 Indexed Assignment Optimization](https://octave.org/doc/interpreter/Indexed-Assignment-Optimization.html#Indexed-Assignment-Optimization)
  - 34.4 Overloading Objects
    - [34.4.1 Function Overloading](https://octave.org/doc/interpreter/Function-Overloading.html#Function-Overloading)
    - [34.4.2 Operator Overloading](https://octave.org/doc/interpreter/Operator-Overloading.html#Operator-Overloading)
    - [34.4.3 Precedence of Objects](https://octave.org/doc/interpreter/Precedence-of-Objects.html#Precedence-of-Objects)
  - [34.5 Inheritance and Aggregation](https://octave.org/doc/interpreter/Inheritance-and-Aggregation.html#Inheritance-and-Aggregation)
  - 34.6 `classdef` Classes
    - [34.6.1 Creating a `classdef` Class](https://octave.org/doc/interpreter/Creating-a-classdef-Class.html#Creating-a-classdef-Class)
    - [34.6.2 Properties](https://octave.org/doc/interpreter/Properties.html#Properties)
    - [34.6.3 Methods](https://octave.org/doc/interpreter/Methods.html#Methods)
    - [34.6.4 Inheritance](https://octave.org/doc/interpreter/Inheritance.html#Inheritance)
    - [34.6.5 Value Classes vs. Handle Classes](https://octave.org/doc/interpreter/Value-Classes-vs_002e-Handle-Classes.html#Value-Classes-vs_002e-Handle-Classes)
- 35 GUI Development
  - [35.1 I/O Dialogs](https://octave.org/doc/interpreter/I_002fO-Dialogs.html#I_002fO-Dialogs)
  - [35.2 Progress Bar](https://octave.org/doc/interpreter/Progress-Bar.html#Progress-Bar)
  - [35.3 UI Elements](https://octave.org/doc/interpreter/UI-Elements.html#UI-Elements)
  - [35.4 GUI Utility Functions](https://octave.org/doc/interpreter/GUI-Utility-Functions.html#GUI-Utility-Functions)
  - [35.5 User-Defined Preferences](https://octave.org/doc/interpreter/User_002dDefined-Preferences.html#User_002dDefined-Preferences)
- 36 System Utilities
  - [36.1 Timing Utilities](https://octave.org/doc/interpreter/Timing-Utilities.html#Timing-Utilities)
  - [36.2 Filesystem Utilities](https://octave.org/doc/interpreter/Filesystem-Utilities.html#Filesystem-Utilities)
  - [36.3 File Archiving Utilities](https://octave.org/doc/interpreter/File-Archiving-Utilities.html#File-Archiving-Utilities)
  - 36.4 Networking Utilities
    - [36.4.1 FTP Objects](https://octave.org/doc/interpreter/FTP-Objects.html#FTP-Objects)
    - [36.4.2 URL Manipulation](https://octave.org/doc/interpreter/URL-Manipulation.html#URL-Manipulation)
    - [36.4.3 Base64 and Binary Data Transmission](https://octave.org/doc/interpreter/Base64-and-Binary-Data-Transmission.html#Base64-and-Binary-Data-Transmission)
  - [36.5 Controlling Subprocesses](https://octave.org/doc/interpreter/Controlling-Subprocesses.html#Controlling-Subprocesses)
  - [36.6 Process, Group, and User IDs](https://octave.org/doc/interpreter/Process-ID-Information.html#Process-ID-Information)
  - [36.7 Environment Variables](https://octave.org/doc/interpreter/Environment-Variables.html#Environment-Variables)
  - [36.8 Current Working Directory](https://octave.org/doc/interpreter/Current-Working-Directory.html#Current-Working-Directory)
  - [36.9 Password Database Functions](https://octave.org/doc/interpreter/Password-Database-Functions.html#Password-Database-Functions)
  - [36.10 Group Database Functions](https://octave.org/doc/interpreter/Group-Database-Functions.html#Group-Database-Functions)
  - [36.11 System Information](https://octave.org/doc/interpreter/System-Information.html#System-Information)
  - [36.12 Hashing Functions](https://octave.org/doc/interpreter/Hashing-Functions.html#Hashing-Functions)
- 37 Packages
  - [37.1 Installing and Removing Packages](https://octave.org/doc/interpreter/Installing-and-Removing-Packages.html#Installing-and-Removing-Packages)
  - [37.2 Using Packages](https://octave.org/doc/interpreter/Using-Packages.html#Using-Packages)
  - [37.3 Administrating Packages](https://octave.org/doc/interpreter/Administrating-Packages.html#Administrating-Packages)
  - 37.4 Creating Packages
    - [37.4.1 The DESCRIPTION File](https://octave.org/doc/interpreter/The-DESCRIPTION-File.html#The-DESCRIPTION-File)
    - [37.4.2 The INDEX File](https://octave.org/doc/interpreter/The-INDEX-File.html#The-INDEX-File)
    - [37.4.3 PKG_ADD and PKG_DEL Directives](https://octave.org/doc/interpreter/PKG_005fADD-and-PKG_005fDEL-Directives.html#PKG_005fADD-and-PKG_005fDEL-Directives)
    - [37.4.4 Missing Components](https://octave.org/doc/interpreter/Missing-Components.html#Missing-Components)
- Appendix A External Code Interface
  - A.1 Oct-Files
    - [A.1.1 Getting Started with Oct-Files](https://octave.org/doc/interpreter/Getting-Started-with-Oct_002dFiles.html#Getting-Started-with-Oct_002dFiles)
    - [A.1.2 Matrices and Arrays in Oct-Files](https://octave.org/doc/interpreter/Matrices-and-Arrays-in-Oct_002dFiles.html#Matrices-and-Arrays-in-Oct_002dFiles)
    - [A.1.3 Character Strings in Oct-Files](https://octave.org/doc/interpreter/Character-Strings-in-Oct_002dFiles.html#Character-Strings-in-Oct_002dFiles)
    - [A.1.4 Cell Arrays in Oct-Files](https://octave.org/doc/interpreter/Cell-Arrays-in-Oct_002dFiles.html#Cell-Arrays-in-Oct_002dFiles)
    - [A.1.5 Structures in Oct-Files](https://octave.org/doc/interpreter/Structures-in-Oct_002dFiles.html#Structures-in-Oct_002dFiles)
    - A.1.6 Sparse Matrices in Oct-Files
      - [A.1.6.1 Array and Sparse Class Differences](https://octave.org/doc/interpreter/Array-and-Sparse-Class-Differences.html#Array-and-Sparse-Class-Differences)
      - [A.1.6.2 Creating Sparse Matrices in Oct-Files](https://octave.org/doc/interpreter/Creating-Sparse-Matrices-in-Oct_002dFiles.html#Creating-Sparse-Matrices-in-Oct_002dFiles)
      - [A.1.6.3 Using Sparse Matrices in Oct-Files](https://octave.org/doc/interpreter/Using-Sparse-Matrices-in-Oct_002dFiles.html#Using-Sparse-Matrices-in-Oct_002dFiles)
    - [A.1.7 Accessing Global Variables in Oct-Files](https://octave.org/doc/interpreter/Accessing-Global-Variables-in-Oct_002dFiles.html#Accessing-Global-Variables-in-Oct_002dFiles)
    - [A.1.8 Calling Octave Functions from Oct-Files](https://octave.org/doc/interpreter/Calling-Octave-Functions-from-Oct_002dFiles.html#Calling-Octave-Functions-from-Oct_002dFiles)
    - [A.1.9 Calling External Code from Oct-Files](https://octave.org/doc/interpreter/Calling-External-Code-from-Oct_002dFiles.html#Calling-External-Code-from-Oct_002dFiles)
    - [A.1.10 Allocating Local Memory in Oct-Files](https://octave.org/doc/interpreter/Allocating-Local-Memory-in-Oct_002dFiles.html#Allocating-Local-Memory-in-Oct_002dFiles)
    - [A.1.11 Input Parameter Checking in Oct-Files](https://octave.org/doc/interpreter/Input-Parameter-Checking-in-Oct_002dFiles.html#Input-Parameter-Checking-in-Oct_002dFiles)
    - [A.1.12 Exception and Error Handling in Oct-Files](https://octave.org/doc/interpreter/Exception-and-Error-Handling-in-Oct_002dFiles.html#Exception-and-Error-Handling-in-Oct_002dFiles)
    - [A.1.13 Documentation and Testing of Oct-Files](https://octave.org/doc/interpreter/Documentation-and-Testing-of-Oct_002dFiles.html#Documentation-and-Testing-of-Oct_002dFiles)
  - A.2 Mex-Files
    - [A.2.1 Getting Started with Mex-Files](https://octave.org/doc/interpreter/Getting-Started-with-Mex_002dFiles.html#Getting-Started-with-Mex_002dFiles)
    - [A.2.2 Working with Matrices and Arrays in Mex-Files](https://octave.org/doc/interpreter/Working-with-Matrices-and-Arrays-in-Mex_002dFiles.html#Working-with-Matrices-and-Arrays-in-Mex_002dFiles)
    - [A.2.3 Character Strings in Mex-Files](https://octave.org/doc/interpreter/Character-Strings-in-Mex_002dFiles.html#Character-Strings-in-Mex_002dFiles)
    - [A.2.4 Cell Arrays with Mex-Files](https://octave.org/doc/interpreter/Cell-Arrays-with-Mex_002dFiles.html#Cell-Arrays-with-Mex_002dFiles)
    - [A.2.5 Structures with Mex-Files](https://octave.org/doc/interpreter/Structures-with-Mex_002dFiles.html#Structures-with-Mex_002dFiles)
    - [A.2.6 Sparse Matrices with Mex-Files](https://octave.org/doc/interpreter/Sparse-Matrices-with-Mex_002dFiles.html#Sparse-Matrices-with-Mex_002dFiles)
    - [A.2.7 Calling Other Functions in Mex-Files](https://octave.org/doc/interpreter/Calling-Other-Functions-in-Mex_002dFiles.html#Calling-Other-Functions-in-Mex_002dFiles)
  - [A.3 Standalone Programs](https://octave.org/doc/interpreter/Standalone-Programs.html#Standalone-Programs)
  - A.4 Java Interface
    - [A.4.1 Making Java Classes Available](https://octave.org/doc/interpreter/Making-Java-Classes-Available.html#Making-Java-Classes-Available)
    - [A.4.2 How to use Java from within Octave](https://octave.org/doc/interpreter/How-to-use-Java-from-within-Octave.html#How-to-use-Java-from-within-Octave)
    - [A.4.3 Set up the JVM](https://octave.org/doc/interpreter/Set-up-the-JVM.html#Set-up-the-JVM)
    - [A.4.4 Java Interface Functions](https://octave.org/doc/interpreter/Java-Interface-Functions.html#Java-Interface-Functions)
- Appendix B Test and Demo Functions
  - [B.1 Test Functions](https://octave.org/doc/interpreter/Test-Functions.html#Test-Functions)
  - [B.2 Demonstration Functions](https://octave.org/doc/interpreter/Demonstration-Functions.html#Demonstration-Functions)
- [Appendix C Obsolete Functions](https://octave.org/doc/interpreter/Obsolete-Functions.html#Obsolete-Functions)
- Appendix D Known Causes of Trouble
  - [D.1 Actual Bugs We Haven’t Fixed Yet](https://octave.org/doc/interpreter/Actual-Bugs.html#Actual-Bugs)
  - D.2 Reporting Bugs
    - [D.2.1 Have You Found a Bug?](https://octave.org/doc/interpreter/Bug-Criteria.html#Bug-Criteria)
    - [D.2.2 Where to Report Bugs](https://octave.org/doc/interpreter/Bug-Tracker.html#Bug-Tracker)
    - [D.2.3 How to Report Bugs](https://octave.org/doc/interpreter/Bug-Reporting.html#Bug-Reporting)
    - [D.2.4 Sending Patches for Octave](https://octave.org/doc/interpreter/Sending-Patches.html#Sending-Patches)
  - [D.3 How To Get Help with Octave](https://octave.org/doc/interpreter/How-To-Get-Help-with-Octave.html#How-To-Get-Help-with-Octave)
  - [D.4 How to Distinguish Between Octave and Matlab](https://octave.org/doc/interpreter/How-to-Distinguish-Between-Octave-and-Matlab.html#How-to-Distinguish-Between-Octave-and-Matlab)
- Appendix E Installing Octave
  - E.1 Build Dependencies
    - [E.1.1 Obtaining the Dependencies Automatically](https://octave.org/doc/interpreter/Obtaining-the-Dependencies-Automatically.html#Obtaining-the-Dependencies-Automatically)
    - [E.1.2 Build Tools](https://octave.org/doc/interpreter/Build-Tools.html#Build-Tools)
    - [E.1.3 External Packages](https://octave.org/doc/interpreter/External-Packages.html#External-Packages)
  - [E.2 Running Configure and Make](https://octave.org/doc/interpreter/Running-Configure-and-Make.html#Running-Configure-and-Make)
  - [E.3 Compiling Octave with 64-bit Indexing](https://octave.org/doc/interpreter/Compiling-Octave-with-64_002dbit-Indexing.html#Compiling-Octave-with-64_002dbit-Indexing)
  - [E.4 Installation Problems](https://octave.org/doc/interpreter/Installation-Problems.html#Installation-Problems)
- Appendix F Grammar and Parser
  - [F.1 Keywords](https://octave.org/doc/interpreter/Keywords.html#Keywords)
  - [F.2 Parser](https://octave.org/doc/interpreter/Parser.html#Parser)
- [Appendix G GNU GENERAL PUBLIC LICENSE](https://octave.org/doc/interpreter/Copying.html#Copying)
- [Concept Index](https://octave.org/doc/interpreter/Concept-Index.html#Concept-Index)
- [Function Index](https://octave.org/doc/interpreter/Function-Index.html#Function-Index)
- [Operator Index](https://octave.org/doc/interpreter/Operator-Index.html#Operator-Index)
- [Graphics Properties Index](https://octave.org/doc/interpreter/Graphics-Properties-Index.html#Graphics-Properties-Index)





Next: [Preface](https://octave.org/doc/interpreter/Preface.html#Preface), Up: [(dir)](https://octave.org/doc/dir/index.html)   [[Contents](https://octave.org/doc/interpreter/#SEC_Contents)][[Index](https://octave.org/doc/interpreter/Concept-Index.html#Concept-Index)]

------





This manual documents how to run, install and port GNU Octave, as well as its new features and incompatibilities, and how to report bugs. It corresponds to GNU Octave version 5.1.0.

| • [Preface](https://octave.org/doc/interpreter/Preface.html#Preface): |      |                                                            |
| ------------------------------------------------------------ | ---- | ---------------------------------------------------------- |
| • [Introduction](https://octave.org/doc/interpreter/Introduction.html#Introduction): |      | A brief introduction to Octave.                            |
| • [Getting Started](https://octave.org/doc/interpreter/Getting-Started.html#Getting-Started): |      |                                                            |
| • [Data Types](https://octave.org/doc/interpreter/Data-Types.html#Data-Types): |      |                                                            |
| • [Numeric Data Types](https://octave.org/doc/interpreter/Numeric-Data-Types.html#Numeric-Data-Types): |      |                                                            |
| • [Strings](https://octave.org/doc/interpreter/Strings.html#Strings): |      |                                                            |
| • [Data Containers](https://octave.org/doc/interpreter/Data-Containers.html#Data-Containers): |      |                                                            |
| • [Variables](https://octave.org/doc/interpreter/Variables.html#Variables): |      |                                                            |
| • [Expressions](https://octave.org/doc/interpreter/Expressions.html#Expressions): |      |                                                            |
| • [Evaluation](https://octave.org/doc/interpreter/Evaluation.html#Evaluation): |      |                                                            |
| • [Statements](https://octave.org/doc/interpreter/Statements.html#Statements): |      | Looping and program flow control.                          |
| • [Functions and Scripts](https://octave.org/doc/interpreter/Functions-and-Scripts.html#Functions-and-Scripts): |      |                                                            |
| • [Errors and Warnings](https://octave.org/doc/interpreter/Errors-and-Warnings.html#Errors-and-Warnings): |      |                                                            |
| • [Debugging](https://octave.org/doc/interpreter/Debugging.html#Debugging): |      |                                                            |
| • [Input and Output](https://octave.org/doc/interpreter/Input-and-Output.html#Input-and-Output): |      |                                                            |
| • [Plotting](https://octave.org/doc/interpreter/Plotting.html#Plotting): |      |                                                            |
| • [Matrix Manipulation](https://octave.org/doc/interpreter/Matrix-Manipulation.html#Matrix-Manipulation): |      |                                                            |
| • [Arithmetic](https://octave.org/doc/interpreter/Arithmetic.html#Arithmetic): |      |                                                            |
| • [Linear Algebra](https://octave.org/doc/interpreter/Linear-Algebra.html#Linear-Algebra): |      |                                                            |
| • [Vectorization and Faster Code Execution](https://octave.org/doc/interpreter/Vectorization-and-Faster-Code-Execution.html#Vectorization-and-Faster-Code-Execution): |      |                                                            |
| • [Nonlinear Equations](https://octave.org/doc/interpreter/Nonlinear-Equations.html#Nonlinear-Equations): |      |                                                            |
| • [Diagonal and Permutation Matrices](https://octave.org/doc/interpreter/Diagonal-and-Permutation-Matrices.html#Diagonal-and-Permutation-Matrices): |      |                                                            |
| • [Sparse Matrices](https://octave.org/doc/interpreter/Sparse-Matrices.html#Sparse-Matrices): |      |                                                            |
| • [Numerical Integration](https://octave.org/doc/interpreter/Numerical-Integration.html#Numerical-Integration): |      |                                                            |
| • [Differential Equations](https://octave.org/doc/interpreter/Differential-Equations.html#Differential-Equations): |      |                                                            |
| • [Optimization](https://octave.org/doc/interpreter/Optimization.html#Optimization): |      |                                                            |
| • [Statistics](https://octave.org/doc/interpreter/Statistics.html#Statistics): |      |                                                            |
| • [Sets](https://octave.org/doc/interpreter/Sets.html#Sets): |      |                                                            |
| • [Polynomial Manipulations](https://octave.org/doc/interpreter/Polynomial-Manipulations.html#Polynomial-Manipulations): |      |                                                            |
| • [Interpolation](https://octave.org/doc/interpreter/Interpolation.html#Interpolation): |      |                                                            |
| • [Geometry](https://octave.org/doc/interpreter/Geometry.html#Geometry): |      |                                                            |
| • [Signal Processing](https://octave.org/doc/interpreter/Signal-Processing.html#Signal-Processing): |      |                                                            |
| • [Image Processing](https://octave.org/doc/interpreter/Image-Processing.html#Image-Processing): |      |                                                            |
| • [Audio Processing](https://octave.org/doc/interpreter/Audio-Processing.html#Audio-Processing): |      |                                                            |
| • [Object Oriented Programming](https://octave.org/doc/interpreter/Object-Oriented-Programming.html#Object-Oriented-Programming): |      |                                                            |
| • [GUI Development](https://octave.org/doc/interpreter/GUI-Development.html#GUI-Development): |      |                                                            |
| • [System Utilities](https://octave.org/doc/interpreter/System-Utilities.html#System-Utilities): |      |                                                            |
| • [Packages](https://octave.org/doc/interpreter/Packages.html#Packages): |      |                                                            |
| • [External Code Interface](https://octave.org/doc/interpreter/External-Code-Interface.html#External-Code-Interface): |      |                                                            |
| • [Test and Demo Functions](https://octave.org/doc/interpreter/Test-and-Demo-Functions.html#Test-and-Demo-Functions): |      |                                                            |
| • [Obsolete Functions](https://octave.org/doc/interpreter/Obsolete-Functions.html#Obsolete-Functions): |      |                                                            |
| • [Trouble](https://octave.org/doc/interpreter/Trouble.html#Trouble): |      | If you have trouble installing Octave.                     |
| • [Installation](https://octave.org/doc/interpreter/Installation.html#Installation): |      | How to configure, compile and install Octave.              |
| • [Grammar and Parser](https://octave.org/doc/interpreter/Grammar-and-Parser.html#Grammar-and-Parser): |      |                                                            |
| • [Copying](https://octave.org/doc/interpreter/Copying.html#Copying): |      | The GNU General Public License.                            |
| • [Concept Index](https://octave.org/doc/interpreter/Concept-Index.html#Concept-Index): |      | An item for each concept.                                  |
| • [Function Index](https://octave.org/doc/interpreter/Function-Index.html#Function-Index): |      | An item for each documented function.                      |
| • [Operator Index](https://octave.org/doc/interpreter/Operator-Index.html#Operator-Index): |      | An item for each documented operator.                      |
| • [Graphics Properties Index](https://octave.org/doc/interpreter/Graphics-Properties-Index.html#Graphics-Properties-Index): |      | An item for each graphics object property.                 |
| ``                                                           |      |                                                            |
| ` — The Detailed Node Listing —  Preface  `                  |      |                                                            |
| • [Acknowledgements](https://octave.org/doc/interpreter/Acknowledgements.html#Acknowledgements): |      |                                                            |
| • [Citing Octave in Publications](https://octave.org/doc/interpreter/Citing-Octave-in-Publications.html#Citing-Octave-in-Publications): |      |                                                            |
| • [How You Can Contribute to Octave](https://octave.org/doc/interpreter/How-You-Can-Contribute-to-Octave.html#How-You-Can-Contribute-to-Octave): |      |                                                            |
| • [Distribution](https://octave.org/doc/interpreter/Distribution.html#Distribution): |      |                                                            |
| `Introduction  `                                             |      |                                                            |
| • [Running Octave](https://octave.org/doc/interpreter/Running-Octave.html#Running-Octave): |      |                                                            |
| • [Simple Examples](https://octave.org/doc/interpreter/Simple-Examples.html#Simple-Examples): |      |                                                            |
| • [Conventions](https://octave.org/doc/interpreter/Conventions.html#Conventions): |      |                                                            |
| `Conventions  `                                              |      |                                                            |
| • [Fonts](https://octave.org/doc/interpreter/Fonts.html#Fonts): |      |                                                            |
| • [Evaluation Notation](https://octave.org/doc/interpreter/Evaluation-Notation.html#Evaluation-Notation): |      |                                                            |
| • [Printing Notation](https://octave.org/doc/interpreter/Printing-Notation.html#Printing-Notation): |      |                                                            |
| • [Error Messages](https://octave.org/doc/interpreter/Error-Messages.html#Error-Messages): |      |                                                            |
| • [Format of Descriptions](https://octave.org/doc/interpreter/Format-of-Descriptions.html#Format-of-Descriptions): |      |                                                            |
| `Format of Descriptions  `                                   |      |                                                            |
| • [A Sample Function Description](https://octave.org/doc/interpreter/A-Sample-Function-Description.html#A-Sample-Function-Description): |      |                                                            |
| • [A Sample Command Description](https://octave.org/doc/interpreter/A-Sample-Command-Description.html#A-Sample-Command-Description): |      |                                                            |
| `Getting Started  `                                          |      |                                                            |
| • [Invoking Octave from the Command Line](https://octave.org/doc/interpreter/Invoking-Octave-from-the-Command-Line.html#Invoking-Octave-from-the-Command-Line): |      |                                                            |
| • [Quitting Octave](https://octave.org/doc/interpreter/Quitting-Octave.html#Quitting-Octave): |      |                                                            |
| • [Getting Help](https://octave.org/doc/interpreter/Getting-Help.html#Getting-Help): |      |                                                            |
| • [Command Line Editing](https://octave.org/doc/interpreter/Command-Line-Editing.html#Command-Line-Editing): |      |                                                            |
| • [Errors](https://octave.org/doc/interpreter/Errors.html#Errors): |      |                                                            |
| • [Executable Octave Programs](https://octave.org/doc/interpreter/Executable-Octave-Programs.html#Executable-Octave-Programs): |      |                                                            |
| • [Comments](https://octave.org/doc/interpreter/Comments.html#Comments): |      |                                                            |
| `Invoking Octave from the Command Line  `                    |      |                                                            |
| • [Command Line Options](https://octave.org/doc/interpreter/Command-Line-Options.html#Command-Line-Options): |      |                                                            |
| • [Startup Files](https://octave.org/doc/interpreter/Startup-Files.html#Startup-Files): |      |                                                            |
| `Command Line Editing  `                                     |      |                                                            |
| • [Cursor Motion](https://octave.org/doc/interpreter/Cursor-Motion.html#Cursor-Motion): |      |                                                            |
| • [Killing and Yanking](https://octave.org/doc/interpreter/Killing-and-Yanking.html#Killing-and-Yanking): |      |                                                            |
| • [Commands for Text](https://octave.org/doc/interpreter/Commands-for-Text.html#Commands-for-Text): |      |                                                            |
| • [Commands for Completion](https://octave.org/doc/interpreter/Commands-for-Completion.html#Commands-for-Completion): |      |                                                            |
| • [Commands for History](https://octave.org/doc/interpreter/Commands-for-History.html#Commands-for-History): |      |                                                            |
| • [Customizing readline](https://octave.org/doc/interpreter/Customizing-readline.html#Customizing-readline): |      |                                                            |
| • [Customizing the Prompt](https://octave.org/doc/interpreter/Customizing-the-Prompt.html#Customizing-the-Prompt): |      |                                                            |
| • [Diary and Echo Commands](https://octave.org/doc/interpreter/Diary-and-Echo-Commands.html#Diary-and-Echo-Commands): |      |                                                            |
| `Comments  `                                                 |      |                                                            |
| • [Single Line Comments](https://octave.org/doc/interpreter/Single-Line-Comments.html#Single-Line-Comments): |      |                                                            |
| • [Block Comments](https://octave.org/doc/interpreter/Block-Comments.html#Block-Comments): |      |                                                            |
| • [Comments and the Help System](https://octave.org/doc/interpreter/Comments-and-the-Help-System.html#Comments-and-the-Help-System): |      |                                                            |
| `Data Types  `                                               |      |                                                            |
| • [Built-in Data Types](https://octave.org/doc/interpreter/Built_002din-Data-Types.html#Built_002din-Data-Types): |      |                                                            |
| • [User-defined Data Types](https://octave.org/doc/interpreter/User_002ddefined-Data-Types.html#User_002ddefined-Data-Types): |      |                                                            |
| • [Object Sizes](https://octave.org/doc/interpreter/Object-Sizes.html#Object-Sizes): |      |                                                            |
| `Built-in Data Types  `                                      |      |                                                            |
| • [Numeric Objects](https://octave.org/doc/interpreter/Numeric-Objects.html#Numeric-Objects): |      |                                                            |
| • [Missing Data](https://octave.org/doc/interpreter/Missing-Data.html#Missing-Data): |      |                                                            |
| • [String Objects](https://octave.org/doc/interpreter/String-Objects.html#String-Objects): |      |                                                            |
| • [Data Structure Objects](https://octave.org/doc/interpreter/Data-Structure-Objects.html#Data-Structure-Objects): |      |                                                            |
| • [Cell Array Objects](https://octave.org/doc/interpreter/Cell-Array-Objects.html#Cell-Array-Objects): |      |                                                            |
| `Numeric Data Types  `                                       |      |                                                            |
| • [Matrices](https://octave.org/doc/interpreter/Matrices.html#Matrices): |      |                                                            |
| • [Ranges](https://octave.org/doc/interpreter/Ranges.html#Ranges): |      |                                                            |
| • [Single Precision Data Types](https://octave.org/doc/interpreter/Single-Precision-Data-Types.html#Single-Precision-Data-Types): |      |                                                            |
| • [Integer Data Types](https://octave.org/doc/interpreter/Integer-Data-Types.html#Integer-Data-Types): |      |                                                            |
| • [Bit Manipulations](https://octave.org/doc/interpreter/Bit-Manipulations.html#Bit-Manipulations): |      |                                                            |
| • [Logical Values](https://octave.org/doc/interpreter/Logical-Values.html#Logical-Values): |      |                                                            |
| • [Promotion and Demotion of Data Types](https://octave.org/doc/interpreter/Promotion-and-Demotion-of-Data-Types.html#Promotion-and-Demotion-of-Data-Types): |      |                                                            |
| • [Predicates for Numeric Objects](https://octave.org/doc/interpreter/Predicates-for-Numeric-Objects.html#Predicates-for-Numeric-Objects): |      |                                                            |
| `Matrices  `                                                 |      |                                                            |
| • [Empty Matrices](https://octave.org/doc/interpreter/Empty-Matrices.html#Empty-Matrices): |      |                                                            |
| `Integer Data Types  `                                       |      |                                                            |
| • [Integer Arithmetic](https://octave.org/doc/interpreter/Integer-Arithmetic.html#Integer-Arithmetic): |      |                                                            |
| `Strings  `                                                  |      |                                                            |
| • [Escape Sequences in String Constants](https://octave.org/doc/interpreter/Escape-Sequences-in-String-Constants.html#Escape-Sequences-in-String-Constants): |      |                                                            |
| • [Character Arrays](https://octave.org/doc/interpreter/Character-Arrays.html#Character-Arrays): |      |                                                            |
| • [Creating Strings](https://octave.org/doc/interpreter/Creating-Strings.html#Creating-Strings): |      |                                                            |
| • [Comparing Strings](https://octave.org/doc/interpreter/Comparing-Strings.html#Comparing-Strings): |      |                                                            |
| • [Manipulating Strings](https://octave.org/doc/interpreter/Manipulating-Strings.html#Manipulating-Strings): |      |                                                            |
| • [String Conversions](https://octave.org/doc/interpreter/String-Conversions.html#String-Conversions): |      |                                                            |
| • [Character Class Functions](https://octave.org/doc/interpreter/Character-Class-Functions.html#Character-Class-Functions): |      |                                                            |
| `Creating Strings  `                                         |      |                                                            |
| • [Concatenating Strings](https://octave.org/doc/interpreter/Concatenating-Strings.html#Concatenating-Strings): |      |                                                            |
| • [Converting Numerical Data to Strings](https://octave.org/doc/interpreter/Converting-Numerical-Data-to-Strings.html#Converting-Numerical-Data-to-Strings): |      |                                                            |
| `Data Containers  `                                          |      |                                                            |
| • [Structures](https://octave.org/doc/interpreter/Structures.html#Structures): |      |                                                            |
| • [containers.Map](https://octave.org/doc/interpreter/containers_002eMap.html#containers_002eMap): |      |                                                            |
| • [Cell Arrays](https://octave.org/doc/interpreter/Cell-Arrays.html#Cell-Arrays): |      |                                                            |
| • [Comma Separated Lists](https://octave.org/doc/interpreter/Comma-Separated-Lists.html#Comma-Separated-Lists): |      |                                                            |
| `Structures  `                                               |      |                                                            |
| • [Basic Usage and Examples](https://octave.org/doc/interpreter/Basic-Usage-and-Examples.html#Basic-Usage-and-Examples): |      |                                                            |
| • [Structure Arrays](https://octave.org/doc/interpreter/Structure-Arrays.html#Structure-Arrays): |      |                                                            |
| • [Creating Structures](https://octave.org/doc/interpreter/Creating-Structures.html#Creating-Structures): |      |                                                            |
| • [Manipulating Structures](https://octave.org/doc/interpreter/Manipulating-Structures.html#Manipulating-Structures): |      |                                                            |
| • [Processing Data in Structures](https://octave.org/doc/interpreter/Processing-Data-in-Structures.html#Processing-Data-in-Structures): |      |                                                            |
| `Cell Arrays  `                                              |      |                                                            |
| • [Basic Usage of Cell Arrays](https://octave.org/doc/interpreter/Basic-Usage-of-Cell-Arrays.html#Basic-Usage-of-Cell-Arrays): |      |                                                            |
| • [Creating Cell Arrays](https://octave.org/doc/interpreter/Creating-Cell-Arrays.html#Creating-Cell-Arrays): |      |                                                            |
| • [Indexing Cell Arrays](https://octave.org/doc/interpreter/Indexing-Cell-Arrays.html#Indexing-Cell-Arrays): |      |                                                            |
| • [Cell Arrays of Strings](https://octave.org/doc/interpreter/Cell-Arrays-of-Strings.html#Cell-Arrays-of-Strings): |      |                                                            |
| • [Processing Data in Cell Arrays](https://octave.org/doc/interpreter/Processing-Data-in-Cell-Arrays.html#Processing-Data-in-Cell-Arrays): |      |                                                            |
| `Comma Separated Lists  `                                    |      |                                                            |
| • [Comma Separated Lists Generated from Cell Arrays](https://octave.org/doc/interpreter/Comma-Separated-Lists-Generated-from-Cell-Arrays.html#Comma-Separated-Lists-Generated-from-Cell-Arrays): |      |                                                            |
| • [Comma Separated Lists Generated from Structure Arrays](https://octave.org/doc/interpreter/Comma-Separated-Lists-Generated-from-Structure-Arrays.html#Comma-Separated-Lists-Generated-from-Structure-Arrays): |      |                                                            |
| `Variables  `                                                |      |                                                            |
| • [Global Variables](https://octave.org/doc/interpreter/Global-Variables.html#Global-Variables): |      |                                                            |
| • [Persistent Variables](https://octave.org/doc/interpreter/Persistent-Variables.html#Persistent-Variables): |      |                                                            |
| • [Status of Variables](https://octave.org/doc/interpreter/Status-of-Variables.html#Status-of-Variables): |      |                                                            |
| `Expressions  `                                              |      |                                                            |
| • [Index Expressions](https://octave.org/doc/interpreter/Index-Expressions.html#Index-Expressions): |      |                                                            |
| • [Calling Functions](https://octave.org/doc/interpreter/Calling-Functions.html#Calling-Functions): |      |                                                            |
| • [Arithmetic Ops](https://octave.org/doc/interpreter/Arithmetic-Ops.html#Arithmetic-Ops): |      |                                                            |
| • [Comparison Ops](https://octave.org/doc/interpreter/Comparison-Ops.html#Comparison-Ops): |      |                                                            |
| • [Boolean Expressions](https://octave.org/doc/interpreter/Boolean-Expressions.html#Boolean-Expressions): |      |                                                            |
| • [Assignment Ops](https://octave.org/doc/interpreter/Assignment-Ops.html#Assignment-Ops): |      |                                                            |
| • [Increment Ops](https://octave.org/doc/interpreter/Increment-Ops.html#Increment-Ops): |      |                                                            |
| • [Operator Precedence](https://octave.org/doc/interpreter/Operator-Precedence.html#Operator-Precedence): |      |                                                            |
| `Index Expressions  `                                        |      |                                                            |
| • [Advanced Indexing](https://octave.org/doc/interpreter/Advanced-Indexing.html#Advanced-Indexing): |      |                                                            |
| `Calling Functions  `                                        |      |                                                            |
| • [Call by Value](https://octave.org/doc/interpreter/Call-by-Value.html#Call-by-Value): |      |                                                            |
| • [Recursion](https://octave.org/doc/interpreter/Recursion.html#Recursion): |      |                                                            |
| • [Access via Handle](https://octave.org/doc/interpreter/Access-via-Handle.html#Access-via-Handle): |      |                                                            |
| `Boolean Expressions  `                                      |      |                                                            |
| • [Element-by-element Boolean Operators](https://octave.org/doc/interpreter/Element_002dby_002delement-Boolean-Operators.html#Element_002dby_002delement-Boolean-Operators): |      |                                                            |
| • [Short-circuit Boolean Operators](https://octave.org/doc/interpreter/Short_002dcircuit-Boolean-Operators.html#Short_002dcircuit-Boolean-Operators): |      |                                                            |
| `Evaluation  `                                               |      |                                                            |
| • [Calling a Function by its Name](https://octave.org/doc/interpreter/Calling-a-Function-by-its-Name.html#Calling-a-Function-by-its-Name): |      |                                                            |
| • [Evaluation in a Different Context](https://octave.org/doc/interpreter/Evaluation-in-a-Different-Context.html#Evaluation-in-a-Different-Context): |      |                                                            |
| `Statements  `                                               |      |                                                            |
| • [The if Statement](https://octave.org/doc/interpreter/The-if-Statement.html#The-if-Statement): |      |                                                            |
| • [The switch Statement](https://octave.org/doc/interpreter/The-switch-Statement.html#The-switch-Statement): |      |                                                            |
| • [The while Statement](https://octave.org/doc/interpreter/The-while-Statement.html#The-while-Statement): |      |                                                            |
| • [The do-until Statement](https://octave.org/doc/interpreter/The-do_002duntil-Statement.html#The-do_002duntil-Statement): |      |                                                            |
| • [The for Statement](https://octave.org/doc/interpreter/The-for-Statement.html#The-for-Statement): |      |                                                            |
| • [The break Statement](https://octave.org/doc/interpreter/The-break-Statement.html#The-break-Statement): |      |                                                            |
| • [The continue Statement](https://octave.org/doc/interpreter/The-continue-Statement.html#The-continue-Statement): |      |                                                            |
| • [The unwind_protect Statement](https://octave.org/doc/interpreter/The-unwind_005fprotect-Statement.html#The-unwind_005fprotect-Statement): |      |                                                            |
| • [The try Statement](https://octave.org/doc/interpreter/The-try-Statement.html#The-try-Statement): |      |                                                            |
| • [Continuation Lines](https://octave.org/doc/interpreter/Continuation-Lines.html#Continuation-Lines): |      |                                                            |
| `The switch Statement  `                                     |      |                                                            |
| • [Notes for the C Programmer](https://octave.org/doc/interpreter/Notes-for-the-C-Programmer.html#Notes-for-the-C-Programmer): |      |                                                            |
| `The for Statement  `                                        |      |                                                            |
| • [Looping Over Structure Elements](https://octave.org/doc/interpreter/Looping-Over-Structure-Elements.html#Looping-Over-Structure-Elements): |      |                                                            |
| `Functions and Scripts  `                                    |      |                                                            |
| • [Introduction to Function and Script Files](https://octave.org/doc/interpreter/Introduction-to-Function-and-Script-Files.html#Introduction-to-Function-and-Script-Files): |      |                                                            |
| • [Defining Functions](https://octave.org/doc/interpreter/Defining-Functions.html#Defining-Functions): |      |                                                            |
| • [Multiple Return Values](https://octave.org/doc/interpreter/Multiple-Return-Values.html#Multiple-Return-Values): |      |                                                            |
| • [Variable-length Argument Lists](https://octave.org/doc/interpreter/Variable_002dlength-Argument-Lists.html#Variable_002dlength-Argument-Lists): |      |                                                            |
| • [Ignoring Arguments](https://octave.org/doc/interpreter/Ignoring-Arguments.html#Ignoring-Arguments): |      |                                                            |
| • [Variable-length Return Lists](https://octave.org/doc/interpreter/Variable_002dlength-Return-Lists.html#Variable_002dlength-Return-Lists): |      |                                                            |
| • [Returning from a Function](https://octave.org/doc/interpreter/Returning-from-a-Function.html#Returning-from-a-Function): |      |                                                            |
| • [Default Arguments](https://octave.org/doc/interpreter/Default-Arguments.html#Default-Arguments): |      |                                                            |
| • [Function Files](https://octave.org/doc/interpreter/Function-Files.html#Function-Files): |      |                                                            |
| • [Script Files](https://octave.org/doc/interpreter/Script-Files.html#Script-Files): |      |                                                            |
| • [Function Handles Anonymous Functions Inline Functions](https://octave.org/doc/interpreter/Function-Handles-Anonymous-Functions-Inline-Functions.html#Function-Handles-Anonymous-Functions-Inline-Functions): |      |                                                            |
| • [Commands](https://octave.org/doc/interpreter/Commands.html#Commands): |      |                                                            |
| • [Organization of Functions](https://octave.org/doc/interpreter/Organization-of-Functions.html#Organization-of-Functions): |      |                                                            |
| `Function Files  `                                           |      |                                                            |
| • [Manipulating the Load Path](https://octave.org/doc/interpreter/Manipulating-the-Load-Path.html#Manipulating-the-Load-Path): |      |                                                            |
| • [Subfunctions](https://octave.org/doc/interpreter/Subfunctions.html#Subfunctions): |      |                                                            |
| • [Private Functions](https://octave.org/doc/interpreter/Private-Functions.html#Private-Functions): |      |                                                            |
| • [Nested Functions](https://octave.org/doc/interpreter/Nested-Functions.html#Nested-Functions): |      |                                                            |
| • [Overloading and Autoloading](https://octave.org/doc/interpreter/Overloading-and-Autoloading.html#Overloading-and-Autoloading): |      |                                                            |
| • [Function Locking](https://octave.org/doc/interpreter/Function-Locking.html#Function-Locking): |      |                                                            |
| • [Function Precedence](https://octave.org/doc/interpreter/Function-Precedence.html#Function-Precedence): |      |                                                            |
| `Script Files  `                                             |      |                                                            |
| • [Publish Octave Script Files](https://octave.org/doc/interpreter/Publish-Octave-Script-Files.html#Publish-Octave-Script-Files): |      |                                                            |
| • [Publishing Markup](https://octave.org/doc/interpreter/Publishing-Markup.html#Publishing-Markup): |      |                                                            |
| `Publishing Markup  `                                        |      |                                                            |
| • [Using Publishing Markup in Script Files](https://octave.org/doc/interpreter/Using-Publishing-Markup-in-Script-Files.html#Using-Publishing-Markup-in-Script-Files): |      |                                                            |
| • [Text Formatting](https://octave.org/doc/interpreter/Text-Formatting.html#Text-Formatting): |      |                                                            |
| • [Sections](https://octave.org/doc/interpreter/Sections.html#Sections): |      |                                                            |
| • [Preformatted Code](https://octave.org/doc/interpreter/Preformatted-Code.html#Preformatted-Code): |      |                                                            |
| • [Preformatted Text](https://octave.org/doc/interpreter/Preformatted-Text.html#Preformatted-Text): |      |                                                            |
| • [Bulleted Lists](https://octave.org/doc/interpreter/Bulleted-Lists.html#Bulleted-Lists): |      |                                                            |
| • [Numbered Lists](https://octave.org/doc/interpreter/Numbered-Lists.html#Numbered-Lists): |      |                                                            |
| • [Including File Content](https://octave.org/doc/interpreter/Including-File-Content.html#Including-File-Content): |      |                                                            |
| • [Including Graphics](https://octave.org/doc/interpreter/Including-Graphics.html#Including-Graphics): |      |                                                            |
| • [Including URLs](https://octave.org/doc/interpreter/Including-URLs.html#Including-URLs): |      |                                                            |
| • [Mathematical Equations](https://octave.org/doc/interpreter/Mathematical-Equations.html#Mathematical-Equations): |      |                                                            |
| • [HTML Markup](https://octave.org/doc/interpreter/HTML-Markup.html#HTML-Markup): |      |                                                            |
| • [LaTeX Markup](https://octave.org/doc/interpreter/LaTeX-Markup.html#LaTeX-Markup): |      |                                                            |
| `Function Handles Anonymous Functions Inline Functions  `    |      |                                                            |
| • [Function Handles](https://octave.org/doc/interpreter/Function-Handles.html#Function-Handles): |      |                                                            |
| • [Anonymous Functions](https://octave.org/doc/interpreter/Anonymous-Functions.html#Anonymous-Functions): |      |                                                            |
| • [Inline Functions](https://octave.org/doc/interpreter/Inline-Functions.html#Inline-Functions): |      |                                                            |
| `Errors and Warnings  `                                      |      |                                                            |
| • [Handling Errors](https://octave.org/doc/interpreter/Handling-Errors.html#Handling-Errors): |      |                                                            |
| • [Handling Warnings](https://octave.org/doc/interpreter/Handling-Warnings.html#Handling-Warnings): |      |                                                            |
| `Handling Errors  `                                          |      |                                                            |
| • [Raising Errors](https://octave.org/doc/interpreter/Raising-Errors.html#Raising-Errors): |      |                                                            |
| • [Catching Errors](https://octave.org/doc/interpreter/Catching-Errors.html#Catching-Errors): |      |                                                            |
| • [Recovering From Errors](https://octave.org/doc/interpreter/Recovering-From-Errors.html#Recovering-From-Errors): |      |                                                            |
| `Handling Warnings  `                                        |      |                                                            |
| • [Issuing Warnings](https://octave.org/doc/interpreter/Issuing-Warnings.html#Issuing-Warnings): |      |                                                            |
| • [Enabling and Disabling Warnings](https://octave.org/doc/interpreter/Enabling-and-Disabling-Warnings.html#Enabling-and-Disabling-Warnings): |      |                                                            |
| `Debugging  `                                                |      |                                                            |
| • [Entering Debug Mode](https://octave.org/doc/interpreter/Entering-Debug-Mode.html#Entering-Debug-Mode): |      |                                                            |
| • [Leaving Debug Mode](https://octave.org/doc/interpreter/Leaving-Debug-Mode.html#Leaving-Debug-Mode): |      |                                                            |
| • [Breakpoints](https://octave.org/doc/interpreter/Breakpoints.html#Breakpoints): |      |                                                            |
| • [Debug Mode](https://octave.org/doc/interpreter/Debug-Mode.html#Debug-Mode): |      |                                                            |
| • [Call Stack](https://octave.org/doc/interpreter/Call-Stack.html#Call-Stack): |      |                                                            |
| • [Profiling](https://octave.org/doc/interpreter/Profiling.html#Profiling): |      |                                                            |
| • [Profiler Example](https://octave.org/doc/interpreter/Profiler-Example.html#Profiler-Example): |      |                                                            |
| `Input and Output  `                                         |      |                                                            |
| • [Basic Input and Output](https://octave.org/doc/interpreter/Basic-Input-and-Output.html#Basic-Input-and-Output): |      |                                                            |
| • [C-Style I/O Functions](https://octave.org/doc/interpreter/C_002dStyle-I_002fO-Functions.html#C_002dStyle-I_002fO-Functions): |      |                                                            |
| `Basic Input and Output  `                                   |      |                                                            |
| • [Terminal Output](https://octave.org/doc/interpreter/Terminal-Output.html#Terminal-Output): |      |                                                            |
| • [Terminal Input](https://octave.org/doc/interpreter/Terminal-Input.html#Terminal-Input): |      |                                                            |
| • [Simple File I/O](https://octave.org/doc/interpreter/Simple-File-I_002fO.html#Simple-File-I_002fO): |      |                                                            |
| `Terminal Output  `                                          |      |                                                            |
| • [Paging Screen Output](https://octave.org/doc/interpreter/Paging-Screen-Output.html#Paging-Screen-Output): |      |                                                            |
| `Simple File I/O  `                                          |      |                                                            |
| • [Saving Data on Unexpected Exits](https://octave.org/doc/interpreter/Saving-Data-on-Unexpected-Exits.html#Saving-Data-on-Unexpected-Exits): |      |                                                            |
| `C-Style I/O Functions  `                                    |      |                                                            |
| • [Opening and Closing Files](https://octave.org/doc/interpreter/Opening-and-Closing-Files.html#Opening-and-Closing-Files): |      |                                                            |
| • [Simple Output](https://octave.org/doc/interpreter/Simple-Output.html#Simple-Output): |      |                                                            |
| • [Line-Oriented Input](https://octave.org/doc/interpreter/Line_002dOriented-Input.html#Line_002dOriented-Input): |      |                                                            |
| • [Formatted Output](https://octave.org/doc/interpreter/Formatted-Output.html#Formatted-Output): |      |                                                            |
| • [Output Conversion for Matrices](https://octave.org/doc/interpreter/Output-Conversion-for-Matrices.html#Output-Conversion-for-Matrices): |      |                                                            |
| • [Output Conversion Syntax](https://octave.org/doc/interpreter/Output-Conversion-Syntax.html#Output-Conversion-Syntax): |      |                                                            |
| • [Table of Output Conversions](https://octave.org/doc/interpreter/Table-of-Output-Conversions.html#Table-of-Output-Conversions): |      |                                                            |
| • [Integer Conversions](https://octave.org/doc/interpreter/Integer-Conversions.html#Integer-Conversions): |      |                                                            |
| • [Floating-Point Conversions](https://octave.org/doc/interpreter/Floating_002dPoint-Conversions.html#Floating_002dPoint-Conversions): |      |                                                            |
| • [Other Output Conversions](https://octave.org/doc/interpreter/Other-Output-Conversions.html#Other-Output-Conversions): |      |                                                            |
| • [Formatted Input](https://octave.org/doc/interpreter/Formatted-Input.html#Formatted-Input): |      |                                                            |
| • [Input Conversion Syntax](https://octave.org/doc/interpreter/Input-Conversion-Syntax.html#Input-Conversion-Syntax): |      |                                                            |
| • [Table of Input Conversions](https://octave.org/doc/interpreter/Table-of-Input-Conversions.html#Table-of-Input-Conversions): |      |                                                            |
| • [Numeric Input Conversions](https://octave.org/doc/interpreter/Numeric-Input-Conversions.html#Numeric-Input-Conversions): |      |                                                            |
| • [String Input Conversions](https://octave.org/doc/interpreter/String-Input-Conversions.html#String-Input-Conversions): |      |                                                            |
| • [Binary I/O](https://octave.org/doc/interpreter/Binary-I_002fO.html#Binary-I_002fO): |      |                                                            |
| • [Temporary Files](https://octave.org/doc/interpreter/Temporary-Files.html#Temporary-Files): |      |                                                            |
| • [EOF and Errors](https://octave.org/doc/interpreter/EOF-and-Errors.html#EOF-and-Errors): |      |                                                            |
| • [File Positioning](https://octave.org/doc/interpreter/File-Positioning.html#File-Positioning): |      |                                                            |
| `Plotting  `                                                 |      |                                                            |
| • [Introduction to Plotting](https://octave.org/doc/interpreter/Introduction-to-Plotting.html#Introduction-to-Plotting): |      |                                                            |
| • [High-Level Plotting](https://octave.org/doc/interpreter/High_002dLevel-Plotting.html#High_002dLevel-Plotting): |      |                                                            |
| • [Graphics Data Structures](https://octave.org/doc/interpreter/Graphics-Data-Structures.html#Graphics-Data-Structures): |      |                                                            |
| • [Advanced Plotting](https://octave.org/doc/interpreter/Advanced-Plotting.html#Advanced-Plotting): |      |                                                            |
| `High-Level Plotting  `                                      |      |                                                            |
| • [Two-Dimensional Plots](https://octave.org/doc/interpreter/Two_002dDimensional-Plots.html#Two_002dDimensional-Plots): |      |                                                            |
| • [Three-Dimensional Plots](https://octave.org/doc/interpreter/Three_002dDimensional-Plots.html#Three_002dDimensional-Plots): |      |                                                            |
| • [Plot Annotations](https://octave.org/doc/interpreter/Plot-Annotations.html#Plot-Annotations): |      |                                                            |
| • [Multiple Plots on One Page](https://octave.org/doc/interpreter/Multiple-Plots-on-One-Page.html#Multiple-Plots-on-One-Page): |      |                                                            |
| • [Multiple Plot Windows](https://octave.org/doc/interpreter/Multiple-Plot-Windows.html#Multiple-Plot-Windows): |      |                                                            |
| • [Manipulation of Plot Objects](https://octave.org/doc/interpreter/Manipulation-of-Plot-Objects.html#Manipulation-of-Plot-Objects): |      |                                                            |
| • [Manipulation of Plot Windows](https://octave.org/doc/interpreter/Manipulation-of-Plot-Windows.html#Manipulation-of-Plot-Windows): |      |                                                            |
| • [Use of the `interpreter` Property](https://octave.org/doc/interpreter/Use-of-the-interpreter-Property.html#Use-of-the-interpreter-Property): |      |                                                            |
| • [Printing and Saving Plots](https://octave.org/doc/interpreter/Printing-and-Saving-Plots.html#Printing-and-Saving-Plots): |      |                                                            |
| • [Interacting with Plots](https://octave.org/doc/interpreter/Interacting-with-Plots.html#Interacting-with-Plots): |      |                                                            |
| • [Test Plotting Functions](https://octave.org/doc/interpreter/Test-Plotting-Functions.html#Test-Plotting-Functions): |      |                                                            |
| `Two-Dimensional Plots  `                                    |      |                                                            |
| • [Axis Configuration](https://octave.org/doc/interpreter/Axis-Configuration.html#Axis-Configuration): |      |                                                            |
| • [Two-dimensional Function Plotting](https://octave.org/doc/interpreter/Two_002ddimensional-Function-Plotting.html#Two_002ddimensional-Function-Plotting): |      |                                                            |
| • [Two-dimensional Geometric Shapes](https://octave.org/doc/interpreter/Two_002ddimensional-Geometric-Shapes.html#Two_002ddimensional-Geometric-Shapes): |      |                                                            |
| `Three-Dimensional Plots  `                                  |      |                                                            |
| • [Aspect Ratio](https://octave.org/doc/interpreter/Aspect-Ratio.html#Aspect-Ratio): |      |                                                            |
| • [Three-dimensional Function Plotting](https://octave.org/doc/interpreter/Three_002ddimensional-Function-Plotting.html#Three_002ddimensional-Function-Plotting): |      |                                                            |
| • [Three-dimensional Geometric Shapes](https://octave.org/doc/interpreter/Three_002ddimensional-Geometric-Shapes.html#Three_002ddimensional-Geometric-Shapes): |      |                                                            |
| `Graphics Data Structures  `                                 |      |                                                            |
| • [Introduction to Graphics Structures](https://octave.org/doc/interpreter/Introduction-to-Graphics-Structures.html#Introduction-to-Graphics-Structures): |      |                                                            |
| • [Graphics Objects](https://octave.org/doc/interpreter/Graphics-Objects.html#Graphics-Objects): |      |                                                            |
| • [Graphics Object Properties](https://octave.org/doc/interpreter/Graphics-Object-Properties.html#Graphics-Object-Properties): |      |                                                            |
| • [Searching Properties](https://octave.org/doc/interpreter/Searching-Properties.html#Searching-Properties): |      |                                                            |
| • [Managing Default Properties](https://octave.org/doc/interpreter/Managing-Default-Properties.html#Managing-Default-Properties): |      |                                                            |
| `Graphics Object Properties  `                               |      |                                                            |
| • [Root Figure Properties](https://octave.org/doc/interpreter/Root-Figure-Properties.html#Root-Figure-Properties): |      |                                                            |
| • [Figure Properties](https://octave.org/doc/interpreter/Figure-Properties.html#Figure-Properties): |      |                                                            |
| • [Axes Properties](https://octave.org/doc/interpreter/Axes-Properties.html#Axes-Properties): |      |                                                            |
| • [Line Properties](https://octave.org/doc/interpreter/Line-Properties.html#Line-Properties): |      |                                                            |
| • [Text Properties](https://octave.org/doc/interpreter/Text-Properties.html#Text-Properties): |      |                                                            |
| • [Image Properties](https://octave.org/doc/interpreter/Image-Properties.html#Image-Properties): |      |                                                            |
| • [Patch Properties](https://octave.org/doc/interpreter/Patch-Properties.html#Patch-Properties): |      |                                                            |
| • [Surface Properties](https://octave.org/doc/interpreter/Surface-Properties.html#Surface-Properties): |      |                                                            |
| • [Light Properties](https://octave.org/doc/interpreter/Light-Properties.html#Light-Properties): |      |                                                            |
| • [Uimenu Properties](https://octave.org/doc/interpreter/Uimenu-Properties.html#Uimenu-Properties): |      |                                                            |
| • [Uibuttongroup Properties](https://octave.org/doc/interpreter/Uibuttongroup-Properties.html#Uibuttongroup-Properties): |      |                                                            |
| • [Uicontextmenu Properties](https://octave.org/doc/interpreter/Uicontextmenu-Properties.html#Uicontextmenu-Properties): |      |                                                            |
| • [Uipanel Properties](https://octave.org/doc/interpreter/Uipanel-Properties.html#Uipanel-Properties): |      |                                                            |
| • [Uicontrol Properties](https://octave.org/doc/interpreter/Uicontrol-Properties.html#Uicontrol-Properties): |      |                                                            |
| • [Uitoolbar Properties](https://octave.org/doc/interpreter/Uitoolbar-Properties.html#Uitoolbar-Properties): |      |                                                            |
| • [Uipushtool Properties](https://octave.org/doc/interpreter/Uipushtool-Properties.html#Uipushtool-Properties): |      |                                                            |
| • [Uitoggletool Properties](https://octave.org/doc/interpreter/Uitoggletool-Properties.html#Uitoggletool-Properties): |      |                                                            |
| `Advanced Plotting  `                                        |      |                                                            |
| • [Colors](https://octave.org/doc/interpreter/Colors.html#Colors): |      |                                                            |
| • [Line Styles](https://octave.org/doc/interpreter/Line-Styles.html#Line-Styles): |      |                                                            |
| • [Marker Styles](https://octave.org/doc/interpreter/Marker-Styles.html#Marker-Styles): |      |                                                            |
| • [Callbacks](https://octave.org/doc/interpreter/Callbacks.html#Callbacks): |      |                                                            |
| • [Application-defined Data](https://octave.org/doc/interpreter/Application_002ddefined-Data.html#Application_002ddefined-Data): |      |                                                            |
| • [Object Groups](https://octave.org/doc/interpreter/Object-Groups.html#Object-Groups): |      |                                                            |
| • [Transform Groups](https://octave.org/doc/interpreter/Transform-Groups.html#Transform-Groups): |      |                                                            |
| • [Graphics Toolkits](https://octave.org/doc/interpreter/Graphics-Toolkits.html#Graphics-Toolkits): |      |                                                            |
| `Object Groups  `                                            |      |                                                            |
| • [Data Sources in Object Groups](https://octave.org/doc/interpreter/Data-Sources-in-Object-Groups.html#Data-Sources-in-Object-Groups): |      |                                                            |
| • [Area Series](https://octave.org/doc/interpreter/Area-Series.html#Area-Series): |      |                                                            |
| • [Bar Series](https://octave.org/doc/interpreter/Bar-Series.html#Bar-Series): |      |                                                            |
| • [Contour Groups](https://octave.org/doc/interpreter/Contour-Groups.html#Contour-Groups): |      |                                                            |
| • [Error Bar Series](https://octave.org/doc/interpreter/Error-Bar-Series.html#Error-Bar-Series): |      |                                                            |
| • [Line Series](https://octave.org/doc/interpreter/Line-Series.html#Line-Series): |      |                                                            |
| • [Quiver Group](https://octave.org/doc/interpreter/Quiver-Group.html#Quiver-Group): |      |                                                            |
| • [Scatter Group](https://octave.org/doc/interpreter/Scatter-Group.html#Scatter-Group): |      |                                                            |
| • [Stair Group](https://octave.org/doc/interpreter/Stair-Group.html#Stair-Group): |      |                                                            |
| • [Stem Series](https://octave.org/doc/interpreter/Stem-Series.html#Stem-Series): |      |                                                            |
| • [Surface Group](https://octave.org/doc/interpreter/Surface-Group.html#Surface-Group): |      |                                                            |
| `Graphics Toolkits  `                                        |      |                                                            |
| • [Customizing Toolkit Behavior](https://octave.org/doc/interpreter/Customizing-Toolkit-Behavior.html#Customizing-Toolkit-Behavior): |      |                                                            |
| `Matrix Manipulation  `                                      |      |                                                            |
| • [Finding Elements and Checking Conditions](https://octave.org/doc/interpreter/Finding-Elements-and-Checking-Conditions.html#Finding-Elements-and-Checking-Conditions): |      |                                                            |
| • [Rearranging Matrices](https://octave.org/doc/interpreter/Rearranging-Matrices.html#Rearranging-Matrices): |      |                                                            |
| • [Special Utility Matrices](https://octave.org/doc/interpreter/Special-Utility-Matrices.html#Special-Utility-Matrices): |      |                                                            |
| • [Famous Matrices](https://octave.org/doc/interpreter/Famous-Matrices.html#Famous-Matrices): |      |                                                            |
| `Arithmetic  `                                               |      |                                                            |
| • [Exponents and Logarithms](https://octave.org/doc/interpreter/Exponents-and-Logarithms.html#Exponents-and-Logarithms): |      |                                                            |
| • [Complex Arithmetic](https://octave.org/doc/interpreter/Complex-Arithmetic.html#Complex-Arithmetic): |      |                                                            |
| • [Trigonometry](https://octave.org/doc/interpreter/Trigonometry.html#Trigonometry): |      |                                                            |
| • [Sums and Products](https://octave.org/doc/interpreter/Sums-and-Products.html#Sums-and-Products): |      |                                                            |
| • [Utility Functions](https://octave.org/doc/interpreter/Utility-Functions.html#Utility-Functions): |      |                                                            |
| • [Special Functions](https://octave.org/doc/interpreter/Special-Functions.html#Special-Functions): |      |                                                            |
| • [Rational Approximations](https://octave.org/doc/interpreter/Rational-Approximations.html#Rational-Approximations): |      |                                                            |
| • [Coordinate Transformations](https://octave.org/doc/interpreter/Coordinate-Transformations.html#Coordinate-Transformations): |      |                                                            |
| • [Mathematical Constants](https://octave.org/doc/interpreter/Mathematical-Constants.html#Mathematical-Constants): |      |                                                            |
| `Linear Algebra  `                                           |      |                                                            |
| • [Techniques Used for Linear Algebra](https://octave.org/doc/interpreter/Techniques-Used-for-Linear-Algebra.html#Techniques-Used-for-Linear-Algebra): |      |                                                            |
| • [Basic Matrix Functions](https://octave.org/doc/interpreter/Basic-Matrix-Functions.html#Basic-Matrix-Functions): |      |                                                            |
| • [Matrix Factorizations](https://octave.org/doc/interpreter/Matrix-Factorizations.html#Matrix-Factorizations): |      |                                                            |
| • [Functions of a Matrix](https://octave.org/doc/interpreter/Functions-of-a-Matrix.html#Functions-of-a-Matrix): |      |                                                            |
| • [Specialized Solvers](https://octave.org/doc/interpreter/Specialized-Solvers.html#Specialized-Solvers): |      |                                                            |
| `Vectorization and Faster Code Execution  `                  |      |                                                            |
| • [Basic Vectorization](https://octave.org/doc/interpreter/Basic-Vectorization.html#Basic-Vectorization): |      | Basic techniques for code optimization                     |
| • [Broadcasting](https://octave.org/doc/interpreter/Broadcasting.html#Broadcasting): |      | Broadcasting operations                                    |
| • [Function Application](https://octave.org/doc/interpreter/Function-Application.html#Function-Application): |      | Applying functions to arrays, cells, and structs           |
| • [Accumulation](https://octave.org/doc/interpreter/Accumulation.html#Accumulation): |      | Accumulation functions                                     |
| • [JIT Compiler](https://octave.org/doc/interpreter/JIT-Compiler.html#JIT-Compiler): |      | Just-In-Time Compiler for loops                            |
| • [Miscellaneous Techniques](https://octave.org/doc/interpreter/Miscellaneous-Techniques.html#Miscellaneous-Techniques): |      | Other techniques for speeding up code                      |
| • [Examples](https://octave.org/doc/interpreter/Examples.html#Examples): |      |                                                            |
| `Nonlinear Equations  `                                      |      |                                                            |
| • [Solvers](https://octave.org/doc/interpreter/Solvers.html#Solvers): |      |                                                            |
| • [Minimizers](https://octave.org/doc/interpreter/Minimizers.html#Minimizers): |      |                                                            |
| `Diagonal and Permutation Matrices  `                        |      |                                                            |
| • [Basic Usage](https://octave.org/doc/interpreter/Basic-Usage.html#Basic-Usage): |      | Creation and Manipulation of Diagonal/Permutation Matrices |
| • [Matrix Algebra](https://octave.org/doc/interpreter/Matrix-Algebra.html#Matrix-Algebra): |      | Linear Algebra with Diagonal/Permutation Matrices          |
| • [Function Support](https://octave.org/doc/interpreter/Function-Support.html#Function-Support): |      | Functions That Are Aware of These Matrices                 |
| • [Example Code](https://octave.org/doc/interpreter/Example-Code.html#Example-Code): |      | Examples of Usage                                          |
| • [Zeros Treatment](https://octave.org/doc/interpreter/Zeros-Treatment.html#Zeros-Treatment): |      | Differences in Treatment of Zero Elements                  |
| `Basic Usage  `                                              |      |                                                            |
| • [Creating Diagonal Matrices](https://octave.org/doc/interpreter/Creating-Diagonal-Matrices.html#Creating-Diagonal-Matrices): |      |                                                            |
| • [Creating Permutation Matrices](https://octave.org/doc/interpreter/Creating-Permutation-Matrices.html#Creating-Permutation-Matrices): |      |                                                            |
| • [Explicit and Implicit Conversions](https://octave.org/doc/interpreter/Explicit-and-Implicit-Conversions.html#Explicit-and-Implicit-Conversions): |      |                                                            |
| `Matrix Algebra  `                                           |      |                                                            |
| • [Expressions Involving Diagonal Matrices](https://octave.org/doc/interpreter/Expressions-Involving-Diagonal-Matrices.html#Expressions-Involving-Diagonal-Matrices): |      |                                                            |
| • [Expressions Involving Permutation Matrices](https://octave.org/doc/interpreter/Expressions-Involving-Permutation-Matrices.html#Expressions-Involving-Permutation-Matrices): |      |                                                            |
| `Function Support  `                                         |      |                                                            |
| • [Diagonal Matrix Functions](https://octave.org/doc/interpreter/Diagonal-Matrix-Functions.html#Diagonal-Matrix-Functions): |      |                                                            |
| • [Permutation Matrix Functions](https://octave.org/doc/interpreter/Permutation-Matrix-Functions.html#Permutation-Matrix-Functions): |      |                                                            |
| `Sparse Matrices  `                                          |      |                                                            |
| • [Basics](https://octave.org/doc/interpreter/Basics.html#Basics): |      | Creation and Manipulation of Sparse Matrices               |
| • [Sparse Linear Algebra](https://octave.org/doc/interpreter/Sparse-Linear-Algebra.html#Sparse-Linear-Algebra): |      | Linear Algebra on Sparse Matrices                          |
| • [Iterative Techniques](https://octave.org/doc/interpreter/Iterative-Techniques.html#Iterative-Techniques): |      | Iterative Techniques                                       |
| • [Real Life Example](https://octave.org/doc/interpreter/Real-Life-Example.html#Real-Life-Example): |      | Using Sparse Matrices                                      |
| `Basics  `                                                   |      |                                                            |
| • [Storage of Sparse Matrices](https://octave.org/doc/interpreter/Storage-of-Sparse-Matrices.html#Storage-of-Sparse-Matrices): |      |                                                            |
| • [Creating Sparse Matrices](https://octave.org/doc/interpreter/Creating-Sparse-Matrices.html#Creating-Sparse-Matrices): |      |                                                            |
| • [Information](https://octave.org/doc/interpreter/Information.html#Information): |      |                                                            |
| • [Operators and Functions](https://octave.org/doc/interpreter/Operators-and-Functions.html#Operators-and-Functions): |      |                                                            |
| `Operators and Functions  `                                  |      |                                                            |
| • [Sparse Functions](https://octave.org/doc/interpreter/Sparse-Functions.html#Sparse-Functions): |      |                                                            |
| • [Return Types of Operators and Functions](https://octave.org/doc/interpreter/Return-Types-of-Operators-and-Functions.html#Return-Types-of-Operators-and-Functions): |      |                                                            |
| • [Mathematical Considerations](https://octave.org/doc/interpreter/Mathematical-Considerations.html#Mathematical-Considerations): |      |                                                            |
| `Numerical Integration  `                                    |      |                                                            |
| • [Functions of One Variable](https://octave.org/doc/interpreter/Functions-of-One-Variable.html#Functions-of-One-Variable): |      |                                                            |
| • [Orthogonal Collocation](https://octave.org/doc/interpreter/Orthogonal-Collocation.html#Orthogonal-Collocation): |      |                                                            |
| • [Functions of Multiple Variables](https://octave.org/doc/interpreter/Functions-of-Multiple-Variables.html#Functions-of-Multiple-Variables): |      |                                                            |
| `Differential Equations  `                                   |      |                                                            |
| • [Ordinary Differential Equations](https://octave.org/doc/interpreter/Ordinary-Differential-Equations.html#Ordinary-Differential-Equations): |      |                                                            |
| • [Differential-Algebraic Equations](https://octave.org/doc/interpreter/Differential_002dAlgebraic-Equations.html#Differential_002dAlgebraic-Equations): |      |                                                            |
| `Ordinary Differential Equations  `                          |      |                                                            |
| • [Matlab-compatible solvers](https://octave.org/doc/interpreter/Matlab_002dcompatible-solvers.html#Matlab_002dcompatible-solvers): |      |                                                            |
| `Optimization  `                                             |      |                                                            |
| • [Linear Programming](https://octave.org/doc/interpreter/Linear-Programming.html#Linear-Programming): |      |                                                            |
| • [Quadratic Programming](https://octave.org/doc/interpreter/Quadratic-Programming.html#Quadratic-Programming): |      |                                                            |
| • [Nonlinear Programming](https://octave.org/doc/interpreter/Nonlinear-Programming.html#Nonlinear-Programming): |      |                                                            |
| • [Linear Least Squares](https://octave.org/doc/interpreter/Linear-Least-Squares.html#Linear-Least-Squares): |      |                                                            |
| `Statistics  `                                               |      |                                                            |
| • [Descriptive Statistics](https://octave.org/doc/interpreter/Descriptive-Statistics.html#Descriptive-Statistics): |      |                                                            |
| • [Statistics on Sliding Windows of Data](https://octave.org/doc/interpreter/Statistics-on-Sliding-Windows-of-Data.html#Statistics-on-Sliding-Windows-of-Data): |      |                                                            |
| • [Basic Statistical Functions](https://octave.org/doc/interpreter/Basic-Statistical-Functions.html#Basic-Statistical-Functions): |      |                                                            |
| • [Correlation and Regression Analysis](https://octave.org/doc/interpreter/Correlation-and-Regression-Analysis.html#Correlation-and-Regression-Analysis): |      |                                                            |
| • [Distributions](https://octave.org/doc/interpreter/Distributions.html#Distributions): |      |                                                            |
| • [Random Number Generation](https://octave.org/doc/interpreter/Random-Number-Generation.html#Random-Number-Generation): |      |                                                            |
| `Sets  `                                                     |      |                                                            |
| • [Set Operations](https://octave.org/doc/interpreter/Set-Operations.html#Set-Operations): |      |                                                            |
| `Polynomial Manipulations  `                                 |      |                                                            |
| • [Evaluating Polynomials](https://octave.org/doc/interpreter/Evaluating-Polynomials.html#Evaluating-Polynomials): |      |                                                            |
| • [Finding Roots](https://octave.org/doc/interpreter/Finding-Roots.html#Finding-Roots): |      |                                                            |
| • [Products of Polynomials](https://octave.org/doc/interpreter/Products-of-Polynomials.html#Products-of-Polynomials): |      |                                                            |
| • [Derivatives / Integrals / Transforms](https://octave.org/doc/interpreter/Derivatives-_002f-Integrals-_002f-Transforms.html#Derivatives-_002f-Integrals-_002f-Transforms): |      |                                                            |
| • [Polynomial Interpolation](https://octave.org/doc/interpreter/Polynomial-Interpolation.html#Polynomial-Interpolation): |      |                                                            |
| • [Miscellaneous Functions](https://octave.org/doc/interpreter/Miscellaneous-Functions.html#Miscellaneous-Functions): |      |                                                            |
| `Interpolation  `                                            |      |                                                            |
| • [One-dimensional Interpolation](https://octave.org/doc/interpreter/One_002ddimensional-Interpolation.html#One_002ddimensional-Interpolation): |      |                                                            |
| • [Multi-dimensional Interpolation](https://octave.org/doc/interpreter/Multi_002ddimensional-Interpolation.html#Multi_002ddimensional-Interpolation): |      |                                                            |
| `Geometry  `                                                 |      |                                                            |
| • [Delaunay Triangulation](https://octave.org/doc/interpreter/Delaunay-Triangulation.html#Delaunay-Triangulation): |      |                                                            |
| • [Voronoi Diagrams](https://octave.org/doc/interpreter/Voronoi-Diagrams.html#Voronoi-Diagrams): |      |                                                            |
| • [Convex Hull](https://octave.org/doc/interpreter/Convex-Hull.html#Convex-Hull): |      |                                                            |
| • [Interpolation on Scattered Data](https://octave.org/doc/interpreter/Interpolation-on-Scattered-Data.html#Interpolation-on-Scattered-Data): |      |                                                            |
| `Delaunay Triangulation  `                                   |      |                                                            |
| • [Plotting the Triangulation](https://octave.org/doc/interpreter/Plotting-the-Triangulation.html#Plotting-the-Triangulation): |      |                                                            |
| • [Identifying Points in Triangulation](https://octave.org/doc/interpreter/Identifying-Points-in-Triangulation.html#Identifying-Points-in-Triangulation): |      |                                                            |
| `Image Processing  `                                         |      |                                                            |
| • [Loading and Saving Images](https://octave.org/doc/interpreter/Loading-and-Saving-Images.html#Loading-and-Saving-Images): |      |                                                            |
| • [Displaying Images](https://octave.org/doc/interpreter/Displaying-Images.html#Displaying-Images): |      |                                                            |
| • [Representing Images](https://octave.org/doc/interpreter/Representing-Images.html#Representing-Images): |      |                                                            |
| • [Plotting on top of Images](https://octave.org/doc/interpreter/Plotting-on-top-of-Images.html#Plotting-on-top-of-Images): |      |                                                            |
| • [Color Conversion](https://octave.org/doc/interpreter/Color-Conversion.html#Color-Conversion): |      |                                                            |
| `Audio Processing  `                                         |      |                                                            |
| • [Audio File Utilities](https://octave.org/doc/interpreter/Audio-File-Utilities.html#Audio-File-Utilities): |      |                                                            |
| • [Audio Device Information](https://octave.org/doc/interpreter/Audio-Device-Information.html#Audio-Device-Information): |      |                                                            |
| • [Audio Player](https://octave.org/doc/interpreter/Audio-Player.html#Audio-Player): |      |                                                            |
| • [Audio Recorder](https://octave.org/doc/interpreter/Audio-Recorder.html#Audio-Recorder): |      |                                                            |
| • [Audio Data Processing](https://octave.org/doc/interpreter/Audio-Data-Processing.html#Audio-Data-Processing): |      |                                                            |
| `Audio Player  `                                             |      |                                                            |
| • [Playback](https://octave.org/doc/interpreter/Playback.html#Playback): |      |                                                            |
| • [Player Properties](https://octave.org/doc/interpreter/Player-Properties.html#Player-Properties): |      |                                                            |
| `Audio Recorder  `                                           |      |                                                            |
| • [Recording](https://octave.org/doc/interpreter/Recording.html#Recording): |      |                                                            |
| • [Data Retrieval](https://octave.org/doc/interpreter/Data-Retrieval.html#Data-Retrieval): |      |                                                            |
| • [Recorder Properties](https://octave.org/doc/interpreter/Recorder-Properties.html#Recorder-Properties): |      |                                                            |
| `Object Oriented Programming  `                              |      |                                                            |
| • [Creating a Class](https://octave.org/doc/interpreter/Creating-a-Class.html#Creating-a-Class): |      |                                                            |
| • [Class Methods](https://octave.org/doc/interpreter/Class-Methods.html#Class-Methods): |      |                                                            |
| • [Indexing Objects](https://octave.org/doc/interpreter/Indexing-Objects.html#Indexing-Objects): |      |                                                            |
| • [Overloading Objects](https://octave.org/doc/interpreter/Overloading-Objects.html#Overloading-Objects): |      |                                                            |
| • [Inheritance and Aggregation](https://octave.org/doc/interpreter/Inheritance-and-Aggregation.html#Inheritance-and-Aggregation): |      |                                                            |
| `Indexing Objects  `                                         |      |                                                            |
| • [Defining Indexing And Indexed Assignment](https://octave.org/doc/interpreter/Defining-Indexing-And-Indexed-Assignment.html#Defining-Indexing-And-Indexed-Assignment): |      |                                                            |
| • [Indexed Assignment Optimization](https://octave.org/doc/interpreter/Indexed-Assignment-Optimization.html#Indexed-Assignment-Optimization): |      |                                                            |
| `Overloading Objects  `                                      |      |                                                            |
| • [Function Overloading](https://octave.org/doc/interpreter/Function-Overloading.html#Function-Overloading): |      |                                                            |
| • [Operator Overloading](https://octave.org/doc/interpreter/Operator-Overloading.html#Operator-Overloading): |      |                                                            |
| • [Precedence of Objects](https://octave.org/doc/interpreter/Precedence-of-Objects.html#Precedence-of-Objects): |      |                                                            |
| `GUI Development  `                                          |      |                                                            |
| • [I/O Dialogs](https://octave.org/doc/interpreter/I_002fO-Dialogs.html#I_002fO-Dialogs): |      |                                                            |
| • [Progress Bar](https://octave.org/doc/interpreter/Progress-Bar.html#Progress-Bar): |      |                                                            |
| • [UI Elements](https://octave.org/doc/interpreter/UI-Elements.html#UI-Elements): |      |                                                            |
| • [GUI Utility Functions](https://octave.org/doc/interpreter/GUI-Utility-Functions.html#GUI-Utility-Functions): |      |                                                            |
| • [User-Defined Preferences](https://octave.org/doc/interpreter/User_002dDefined-Preferences.html#User_002dDefined-Preferences): |      |                                                            |
| `System Utilities  `                                         |      |                                                            |
| • [Timing Utilities](https://octave.org/doc/interpreter/Timing-Utilities.html#Timing-Utilities): |      |                                                            |
| • [Filesystem Utilities](https://octave.org/doc/interpreter/Filesystem-Utilities.html#Filesystem-Utilities): |      |                                                            |
| • [File Archiving Utilities](https://octave.org/doc/interpreter/File-Archiving-Utilities.html#File-Archiving-Utilities): |      |                                                            |
| • [Networking Utilities](https://octave.org/doc/interpreter/Networking-Utilities.html#Networking-Utilities): |      |                                                            |
| • [Controlling Subprocesses](https://octave.org/doc/interpreter/Controlling-Subprocesses.html#Controlling-Subprocesses): |      |                                                            |
| • [Process ID Information](https://octave.org/doc/interpreter/Process-ID-Information.html#Process-ID-Information): |      |                                                            |
| • [Environment Variables](https://octave.org/doc/interpreter/Environment-Variables.html#Environment-Variables): |      |                                                            |
| • [Current Working Directory](https://octave.org/doc/interpreter/Current-Working-Directory.html#Current-Working-Directory): |      |                                                            |
| • [Password Database Functions](https://octave.org/doc/interpreter/Password-Database-Functions.html#Password-Database-Functions): |      |                                                            |
| • [Group Database Functions](https://octave.org/doc/interpreter/Group-Database-Functions.html#Group-Database-Functions): |      |                                                            |
| • [System Information](https://octave.org/doc/interpreter/System-Information.html#System-Information): |      |                                                            |
| • [Hashing Functions](https://octave.org/doc/interpreter/Hashing-Functions.html#Hashing-Functions): |      |                                                            |
| `Networking Utilities  `                                     |      |                                                            |
| • [FTP Objects](https://octave.org/doc/interpreter/FTP-Objects.html#FTP-Objects): |      |                                                            |
| • [URL Manipulation](https://octave.org/doc/interpreter/URL-Manipulation.html#URL-Manipulation): |      |                                                            |
| • [Base64 and Binary Data Transmission](https://octave.org/doc/interpreter/Base64-and-Binary-Data-Transmission.html#Base64-and-Binary-Data-Transmission): |      |                                                            |
| `Packages  `                                                 |      |                                                            |
| • [Installing and Removing Packages](https://octave.org/doc/interpreter/Installing-and-Removing-Packages.html#Installing-and-Removing-Packages): |      |                                                            |
| • [Using Packages](https://octave.org/doc/interpreter/Using-Packages.html#Using-Packages): |      |                                                            |
| • [Administrating Packages](https://octave.org/doc/interpreter/Administrating-Packages.html#Administrating-Packages): |      |                                                            |
| • [Creating Packages](https://octave.org/doc/interpreter/Creating-Packages.html#Creating-Packages): |      |                                                            |
| `Creating Packages  `                                        |      |                                                            |
| • [The DESCRIPTION File](https://octave.org/doc/interpreter/The-DESCRIPTION-File.html#The-DESCRIPTION-File): |      |                                                            |
| • [The INDEX File](https://octave.org/doc/interpreter/The-INDEX-File.html#The-INDEX-File): |      |                                                            |
| • [PKG_ADD and PKG_DEL Directives](https://octave.org/doc/interpreter/PKG_005fADD-and-PKG_005fDEL-Directives.html#PKG_005fADD-and-PKG_005fDEL-Directives): |      |                                                            |
| • [Missing Components](https://octave.org/doc/interpreter/Missing-Components.html#Missing-Components): |      |                                                            |
| `External Code Interface  `                                  |      |                                                            |
| • [Oct-Files](https://octave.org/doc/interpreter/Oct_002dFiles.html#Oct_002dFiles): |      |                                                            |
| • [Mex-Files](https://octave.org/doc/interpreter/Mex_002dFiles.html#Mex_002dFiles): |      |                                                            |
| • [Standalone Programs](https://octave.org/doc/interpreter/Standalone-Programs.html#Standalone-Programs): |      |                                                            |
| • [Java Interface](https://octave.org/doc/interpreter/Java-Interface.html#Java-Interface): |      |                                                            |
| `Oct-Files  `                                                |      |                                                            |
| • [Getting Started with Oct-Files](https://octave.org/doc/interpreter/Getting-Started-with-Oct_002dFiles.html#Getting-Started-with-Oct_002dFiles): |      |                                                            |
| • [Matrices and Arrays in Oct-Files](https://octave.org/doc/interpreter/Matrices-and-Arrays-in-Oct_002dFiles.html#Matrices-and-Arrays-in-Oct_002dFiles): |      |                                                            |
| • [Character Strings in Oct-Files](https://octave.org/doc/interpreter/Character-Strings-in-Oct_002dFiles.html#Character-Strings-in-Oct_002dFiles): |      |                                                            |
| • [Cell Arrays in Oct-Files](https://octave.org/doc/interpreter/Cell-Arrays-in-Oct_002dFiles.html#Cell-Arrays-in-Oct_002dFiles): |      |                                                            |
| • [Structures in Oct-Files](https://octave.org/doc/interpreter/Structures-in-Oct_002dFiles.html#Structures-in-Oct_002dFiles): |      |                                                            |
| • [Sparse Matrices in Oct-Files](https://octave.org/doc/interpreter/Sparse-Matrices-in-Oct_002dFiles.html#Sparse-Matrices-in-Oct_002dFiles): |      |                                                            |
| • [Accessing Global Variables in Oct-Files](https://octave.org/doc/interpreter/Accessing-Global-Variables-in-Oct_002dFiles.html#Accessing-Global-Variables-in-Oct_002dFiles): |      |                                                            |
| • [Calling Octave Functions from Oct-Files](https://octave.org/doc/interpreter/Calling-Octave-Functions-from-Oct_002dFiles.html#Calling-Octave-Functions-from-Oct_002dFiles): |      |                                                            |
| • [Calling External Code from Oct-Files](https://octave.org/doc/interpreter/Calling-External-Code-from-Oct_002dFiles.html#Calling-External-Code-from-Oct_002dFiles): |      |                                                            |
| • [Allocating Local Memory in Oct-Files](https://octave.org/doc/interpreter/Allocating-Local-Memory-in-Oct_002dFiles.html#Allocating-Local-Memory-in-Oct_002dFiles): |      |                                                            |
| • [Input Parameter Checking in Oct-Files](https://octave.org/doc/interpreter/Input-Parameter-Checking-in-Oct_002dFiles.html#Input-Parameter-Checking-in-Oct_002dFiles): |      |                                                            |
| • [Exception and Error Handling in Oct-Files](https://octave.org/doc/interpreter/Exception-and-Error-Handling-in-Oct_002dFiles.html#Exception-and-Error-Handling-in-Oct_002dFiles): |      |                                                            |
| • [Documentation and Testing of Oct-Files](https://octave.org/doc/interpreter/Documentation-and-Testing-of-Oct_002dFiles.html#Documentation-and-Testing-of-Oct_002dFiles): |      |                                                            |
| `Sparse Matrices in Oct-Files  `                             |      |                                                            |
| • [Array and Sparse Class Differences](https://octave.org/doc/interpreter/Array-and-Sparse-Class-Differences.html#Array-and-Sparse-Class-Differences): |      |                                                            |
| • [Creating Sparse Matrices in Oct-Files](https://octave.org/doc/interpreter/Creating-Sparse-Matrices-in-Oct_002dFiles.html#Creating-Sparse-Matrices-in-Oct_002dFiles): |      |                                                            |
| • [Using Sparse Matrices in Oct-Files](https://octave.org/doc/interpreter/Using-Sparse-Matrices-in-Oct_002dFiles.html#Using-Sparse-Matrices-in-Oct_002dFiles): |      |                                                            |
| `Mex-Files  `                                                |      |                                                            |
| • [Getting Started with Mex-Files](https://octave.org/doc/interpreter/Getting-Started-with-Mex_002dFiles.html#Getting-Started-with-Mex_002dFiles): |      |                                                            |
| • [Working with Matrices and Arrays in Mex-Files](https://octave.org/doc/interpreter/Working-with-Matrices-and-Arrays-in-Mex_002dFiles.html#Working-with-Matrices-and-Arrays-in-Mex_002dFiles): |      |                                                            |
| • [Character Strings in Mex-Files](https://octave.org/doc/interpreter/Character-Strings-in-Mex_002dFiles.html#Character-Strings-in-Mex_002dFiles): |      |                                                            |
| • [Cell Arrays with Mex-Files](https://octave.org/doc/interpreter/Cell-Arrays-with-Mex_002dFiles.html#Cell-Arrays-with-Mex_002dFiles): |      |                                                            |
| • [Structures with Mex-Files](https://octave.org/doc/interpreter/Structures-with-Mex_002dFiles.html#Structures-with-Mex_002dFiles): |      |                                                            |
| • [Sparse Matrices with Mex-Files](https://octave.org/doc/interpreter/Sparse-Matrices-with-Mex_002dFiles.html#Sparse-Matrices-with-Mex_002dFiles): |      |                                                            |
| • [Calling Other Functions in Mex-Files](https://octave.org/doc/interpreter/Calling-Other-Functions-in-Mex_002dFiles.html#Calling-Other-Functions-in-Mex_002dFiles): |      |                                                            |
| `Java Interface  `                                           |      |                                                            |
| • [Making Java Classes Available](https://octave.org/doc/interpreter/Making-Java-Classes-Available.html#Making-Java-Classes-Available): |      |                                                            |
| • [How to use Java from within Octave](https://octave.org/doc/interpreter/How-to-use-Java-from-within-Octave.html#How-to-use-Java-from-within-Octave): |      |                                                            |
| • [Set up the JVM](https://octave.org/doc/interpreter/Set-up-the-JVM.html#Set-up-the-JVM): |      |                                                            |
| • [Java Interface Functions](https://octave.org/doc/interpreter/Java-Interface-Functions.html#Java-Interface-Functions): |      |                                                            |
| `Test and Demo Functions  `                                  |      |                                                            |
| • [Test Functions](https://octave.org/doc/interpreter/Test-Functions.html#Test-Functions): |      |                                                            |
| • [Demonstration Functions](https://octave.org/doc/interpreter/Demonstration-Functions.html#Demonstration-Functions): |      |                                                            |
| `Trouble  `                                                  |      |                                                            |
| • [Actual Bugs](https://octave.org/doc/interpreter/Actual-Bugs.html#Actual-Bugs): |      | Bugs we will fix later.                                    |
| • [Reporting Bugs](https://octave.org/doc/interpreter/Reporting-Bugs.html#Reporting-Bugs): |      |                                                            |
| • [How To Get Help with Octave](https://octave.org/doc/interpreter/How-To-Get-Help-with-Octave.html#How-To-Get-Help-with-Octave): |      |                                                            |
| • [How to Distinguish Between Octave and Matlab](https://octave.org/doc/interpreter/How-to-Distinguish-Between-Octave-and-Matlab.html#How-to-Distinguish-Between-Octave-and-Matlab): |      |                                                            |
| `Reporting Bugs  `                                           |      |                                                            |
| • [Bug Criteria](https://octave.org/doc/interpreter/Bug-Criteria.html#Bug-Criteria): |      |                                                            |
| • [Bug Tracker](https://octave.org/doc/interpreter/Bug-Tracker.html#Bug-Tracker): |      | Where to submit your bug report.                           |
| • [Bug Reporting](https://octave.org/doc/interpreter/Bug-Reporting.html#Bug-Reporting): |      | How to report a bug effectively.                           |
| • [Sending Patches](https://octave.org/doc/interpreter/Sending-Patches.html#Sending-Patches): |      | How to send a patch for Octave.                            |
| `Installation  `                                             |      |                                                            |
| • [Build Dependencies](https://octave.org/doc/interpreter/Build-Dependencies.html#Build-Dependencies): |      |                                                            |
| • [Running Configure and Make](https://octave.org/doc/interpreter/Running-Configure-and-Make.html#Running-Configure-and-Make): |      |                                                            |
| • [Compiling Octave with 64-bit Indexing](https://octave.org/doc/interpreter/Compiling-Octave-with-64_002dbit-Indexing.html#Compiling-Octave-with-64_002dbit-Indexing): |      |                                                            |
| • [Installation Problems](https://octave.org/doc/interpreter/Installation-Problems.html#Installation-Problems): |      |                                                            |
| `Build Dependencies  `                                       |      |                                                            |
| • [Obtaining the Dependencies Automatically](https://octave.org/doc/interpreter/Obtaining-the-Dependencies-Automatically.html#Obtaining-the-Dependencies-Automatically): |      |                                                            |
| • [Build Tools](https://octave.org/doc/interpreter/Build-Tools.html#Build-Tools): |      |                                                            |
| • [External Packages](https://octave.org/doc/interpreter/External-Packages.html#External-Packages): |      |                                                            |
| `Grammar and Parser  `                                       |      |                                                            |
| • [Keywords](https://octave.org/doc/interpreter/Keywords.html#Keywords): |      |                                                            |
| • [Parser](https://octave.org/doc/interpreter/Parser.html#Parser): |      |                                                            |

------

Next: [Preface](https://octave.org/doc/interpreter/Preface.html#Preface), Up: [(dir)](https://octave.org/doc/dir/index.html)   [[Contents](https://octave.org/doc/interpreter/#SEC_Contents)][[Index](https://octave.org/doc/interpreter/Concept-Index.html#Concept-Index)]