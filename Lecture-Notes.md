# Python Course – Lecture Notes (Topic-wise)


## Table of Contents

- [Introduction](#introduction)
- [Course Information](#course-information)
- [1 Python Introduction](#1-python-introduction)
  - [1.1 What is Python?](#11-what-is-python)
  - [1.2 Key Features of Python](#12-key-features-of-python)
  - [1.3 Applications of Python](#13-applications-of-python)
  - [1.4 How Python Works?](#14-how-python-works)
  - [1.5 Python vs Other Languages](#15-python-vs-other-languages)
  - [1.6 Key Takeaways](#16-key-takeaways)
- [2 Installation and Development Tools](#2-installation-and-development-tools)
  - [2.1 Python Installation](#21-python-installation)
    - [2.1.1 Prerequisites](#211-prerequisites)
    - [2.1.2 Download Python](#212-download-python)
    - [2.1.3 Installation on Windows](#213-installation-on-windows)
    - [2.1.4 Installation on macOS](#214-installation-on-macos)
    - [2.1.5 Installation on Linux (Ubuntu)](#215-installation-on-linux-ubuntu)
    - [2.1.6 Verify Installation](#216-verify-installation)
    - [2.1.7 Key Takeaways](#217-key-takeaways)
  - [2.2 VS Code vs PyCharm vs Jupyter](#22-vs-code-vs-pycharm-vs-jupyter)
    - [2.2.1 What Are These?](#221-what-are-these)
    - [2.2.2 Key Differences](#222-key-differences)
    - [2.2.3 Visual Studio Code (VS Code)](#223-visual-studio-code-vs-code)
      - [2.2.3.1 Overview](#2231-overview)
      - [2.2.3.2 Features](#2232-features)
      - [2.2.3.3 Installation (VS Code)](#2233-installation-vs-code)
    - [2.2.4 PyCharm (Overview)](#224-pycharm-overview)
      - [2.2.4.1 Overview](#2241-overview)
      - [2.2.4.2 Features](#2242-features)
      - [2.2.4.3 Installation (PyCharm)](#2243-installation-pycharm)
    - [2.2.5 Jupyter Notebook (Overview)](#225-jupyter-notebook-overview)
      - [2.2.5.1 Overview](#2251-overview)
      - [2.2.5.2 Features](#2252-features)
      - [2.2.5.3 Installation (Jupyter)](#2253-installation-jupyter)
    - [2.2.6 Which One to Use?](#226-which-one-to-use)
    - [2.2.7 Key Takeaways](#227-key-takeaways)
  - [2.3 Visual Studio Code (VS Code)](#23-visual-studio-code-vs-code)
    - [2.3.1 What is VS Code?](#231-what-is-vs-code)
    - [2.3.2 Key Features](#232-key-features)
    - [2.3.3 Installation Steps](#233-installation-steps)
    - [2.3.4 Flow Diagram (Installation & Setup)](#234-flow-diagram-installation--setup)
    - [2.3.5 User Interface Overview](#235-user-interface-overview)
    - [2.3.6 Installing Python Extension](#236-installing-python-extension)
    - [2.3.7 Running Python Code](#237-running-python-code)
    - [2.3.8 Use Cases](#238-use-cases)
    - [2.3.9 Key Takeaways](#239-key-takeaways)
  - [2.4 PyCharm](#24-pycharm)
    - [2.4.1 What is PyCharm?](#241-what-is-pycharm)
    - [2.4.2 Key Features](#242-key-features)
    - [2.4.3 Versions of PyCharm](#243-versions-of-pycharm)
    - [2.4.4 System Requirements](#244-system-requirements)
    - [2.4.5 Installation Steps](#245-installation-steps)
    - [2.4.6 Flow Diagram (Installation Process)](#246-flow-diagram-installation-process)
    - [2.4.7 PyCharm User Interface Overview](#247-pycharm-user-interface-overview)
    - [2.4.8 Running a Python Program](#248-running-a-python-program)
    - [2.4.9 Use Cases](#249-use-cases)
    - [2.4.10 Key Takeaways](#2410-key-takeaways)
  - [2.5 Jupyter Notebook](#25-jupyter-notebook)
    - [2.5.1 What is Jupyter Notebook?](#251-what-is-jupyter-notebook)
    - [2.5.2 Key Features](#252-key-features)
    - [2.5.3 Components of Jupyter Notebook](#253-components-of-jupyter-notebook)
    - [2.5.4 Installation Steps](#254-installation-steps)
    - [2.5.5 Flow Diagram (Working Process)](#255-flow-diagram-working-process)
    - [2.5.6 Using Jupyter Notebook](#256-using-jupyter-notebook)
    - [2.5.7 Example](#257-example)
    - [2.5.8 Use Cases](#258-use-cases)
    - [2.5.9 Tips](#259-tips)
    - [2.5.10 Key Takeaways](#2510-key-takeaways)
- [3 Python Syntax and Indentation](#3-python-syntax-and-indentation)
  - [3.1 Python Syntax](#31-python-syntax)
    - [3.1.1 What is Syntax?](#311-what-is-syntax)
    - [3.1.2 General Rules of Python Syntax](#312-general-rules-of-python-syntax)
    - [3.1.3 Basic Structure of a Python Program](#313-basic-structure-of-a-python-program)
    - [3.1.4 Tokens in Python](#314-tokens-in-python)
    - [3.1.5 Python Keywords](#315-python-keywords)
    - [3.1.6 Python Identifiers](#316-python-identifiers)
    - [3.1.7 Python Statements and Lines](#317-python-statements-and-lines)
    - [3.1.8 Key Takeaways](#318-key-takeaways)
  - [3.2 Python Indentation](#32-python-indentation)
    - [3.2.1 What is Indentation?](#321-what-is-indentation)
    - [3.2.2 Indentation Rules](#322-indentation-rules)
    - [3.2.3 Visualization of Indentation](#323-visualization-of-indentation)
    - [3.2.4 Correct vs Incorrect Indentation](#324-correct-vs-incorrect-indentation)
    - [3.2.5 Common Indentation Errors](#325-common-indentation-errors)
    - [3.2.6 Flow Diagram (How Indentation Works)](#326-flow-diagram-how-indentation-works)
    - [3.2.7 More Examples](#327-more-examples)
    - [3.2.8 Key Takeaways](#328-key-takeaways)
- [4 Keywords and Identifiers](#4-keywords-and-identifiers)
  - [4.1 Python Keywords](#41-python-keywords)
    - [4.1.1 What are Keywords?](#411-what-are-keywords)
    - [4.1.2 List of Python Keywords (Total 35)](#412-list-of-python-keywords-total-35)
    - [4.1.3 Using Keywords in a Program](#413-using-keywords-in-a-program)
    - [4.1.4 Keywords Cannot be Used as Identifiers](#414-keywords-cannot-be-used-as-identifiers)
    - [4.1.5 Common Python Keywords and Their Use](#415-common-python-keywords-and-their-use)
    - [4.1.6 Variations in the combined sheet](#416-variations-in-the-combined-sheet)
    - [4.1.7 Key Takeaways](#417-key-takeaways)
  - [4.2 Python Identifiers](#42-python-identifiers)
    - [4.2.1 What are Identifiers?](#421-what-are-identifiers)
    - [4.2.2 Rules for Identifiers](#422-rules-for-identifiers)
    - [4.2.3 Valid vs Invalid Identifiers](#423-valid-vs-invalid-identifiers)
    - [4.2.4 Examples of Identifiers](#424-examples-of-identifiers)
    - [4.2.5 Different Naming Styles](#425-different-naming-styles)
    - [4.2.6 Case Sensitivity](#426-case-sensitivity)
    - [4.2.7 Variations in the combined sheet](#427-variations-in-the-combined-sheet)
    - [4.2.8 Key Takeaways](#428-key-takeaways)
- [5 Data Types and Type Conversion](#5-data-types-and-type-conversion)
  - [5.1 Python Data Types](#51-python-data-types)
    - [5.1.1 What are Data Types?](#511-what-are-data-types)
    - [5.1.2 Types of Data in Python](#512-types-of-data-in-python)
    - [5.1.3 Built-in Data Types with Examples](#513-built-in-data-types-with-examples)
    - [5.1.4 Integer (int)](#514-integer-int)
    - [5.1.5 Float (float)](#515-float-float)
    - [5.1.6 String (str)](#516-string-str)
    - [5.1.7 Boolean (bool)](#517-boolean-bool)
    - [5.1.8 List (list)](#518-list-list)
    - [5.1.9 Tuple (tuple)](#519-tuple-tuple)
    - [5.1.10 Set (set)](#5110-set-set)
    - [5.1.11 Dictionary (dict)](#5111-dictionary-dict)
    - [5.1.12 NoneType (None)](#5112-nonetype-none)
    - [5.1.13 Type Checking](#5113-type-checking)
    - [5.1.14 Flow Diagram of Data Types](#5114-flow-diagram-of-data-types)
    - [5.1.15 Key Takeaways](#5115-key-takeaways)
  - [5.2 Python Type Conversion / Type Casting](#52-python-type-conversion--type-casting)
    - [5.2.1 What is Type Conversion?](#521-what-is-type-conversion)
    - [5.2.2 Types of Type Conversion](#522-types-of-type-conversion)
    - [5.2.3 Implicit Type Conversion](#523-implicit-type-conversion)
    - [5.2.4 Type Hierarchy in Implicit Conversion](#524-type-hierarchy-in-implicit-conversion)
    - [5.2.5 Explicit Type Conversion (Type Casting)](#525-explicit-type-conversion-type-casting)
    - [5.2.6 Common Type Conversion Functions with Examples](#526-common-type-conversion-functions-with-examples)
    - [5.2.7 Examples of Explicit Conversion](#527-examples-of-explicit-conversion)
    - [5.2.8 Flow Diagram of Type Conversion](#528-flow-diagram-of-type-conversion)
    - [5.2.9 Important Points](#529-important-points)
    - [5.2.10 Common Type Conversion Errors](#5210-common-type-conversion-errors)
    - [5.2.11 Key Takeaways](#5211-key-takeaways)
- [6 Operators](#6-operators)
  - [6.1 Python Operators (Overview) – Page 1](#61-python-operators-overview--page-1)
    - [6.1.1 What are Operators?](#611-what-are-operators)
    - [6.1.2 Types of Operators in Python](#612-types-of-operators-in-python)
    - [6.1.3 Arithmetic Operators](#613-arithmetic-operators)
    - [6.1.4 Key Takeaways](#614-key-takeaways)
  - [6.2 Python Operators (Detailed) – Page 2](#62-python-operators-detailed--page-2)
    - [6.2.1 Comparison Operators *(source section 4)*](#621-comparison-operators-source-section-4)
    - [6.2.2 Logical Operators *(source section 5)*](#622-logical-operators-source-section-5)
    - [6.2.3 Assignment Operators *(source section 6)*](#623-assignment-operators-source-section-6)
    - [6.2.4 Key Takeaways](#624-key-takeaways)
  - [6.3 Other Operators, Comments and Basic Programs – Page 3](#63-other-operators-comments-and-basic-programs--page-3)
    - [6.3.1 Membership Operators *(source section 7)*](#631-membership-operators-source-section-7)
    - [6.3.2 Identity Operators *(source section 8)*](#632-identity-operators-source-section-8)
    - [6.3.3 Bitwise Operators *(source section 9)*](#633-bitwise-operators-source-section-9)
    - [6.3.4 Comments in Python *(source section 10)*](#634-comments-in-python-source-section-10)
    - [6.3.5 Basic Programs in Python *(source section 11)*](#635-basic-programs-in-python-source-section-11)
    - [6.3.6 Key Takeaways](#636-key-takeaways)
- [7 Input and Output](#7-input-and-output)
  - [7.1 Python Input and Output – Overview](#71-python-input-and-output--overview)
    - [7.1.1 What is Input and Output?](#711-what-is-input-and-output)
    - [7.1.2 Basic Syntax](#712-basic-syntax)
    - [7.1.3 Flow Diagram](#713-flow-diagram)
    - [7.1.4 Simple Input and Output](#714-simple-input-and-output)
    - [7.1.5 Input with Type Conversion](#715-input-with-type-conversion)
    - [7.1.6 Different Ways to Take Input](#716-different-ways-to-take-input)
    - [7.1.7 Output Formatting](#717-output-formatting)
    - [7.1.8 Taking Multiple Inputs – Examples](#718-taking-multiple-inputs--examples)
    - [7.1.9 Important Points](#719-important-points)
    - [7.1.10 Common Errors in Input and Output](#7110-common-errors-in-input-and-output)
    - [7.1.11 Key Takeaways](#7111-key-takeaways)
  - [7.2 Python Input and Output – Detailed Guide](#72-python-input-and-output--detailed-guide)
    - [7.2.1 What is Input and Output?](#721-what-is-input-and-output)
    - [7.2.2 Basic Input and Output](#722-basic-input-and-output)
    - [7.2.3 Input Function Details](#723-input-function-details)
    - [7.2.4 Type Conversion with Input](#724-type-conversion-with-input)
    - [7.2.5 Taking Different Types of Input](#725-taking-different-types-of-input)
    - [7.2.6 Multiple Inputs in One Line](#726-multiple-inputs-in-one-line)
    - [7.2.7 Formatted Output with print()](#727-formatted-output-with-print)
    - [7.2.8 Controlling Output with `end`](#728-controlling-output-with-end)
    - [7.2.9 Escape Sequences in Output](#729-escape-sequences-in-output)
    - [7.2.10 User-Friendly Programs](#7210-user-friendly-programs)
    - [7.2.11 Common Errors and Solutions](#7211-common-errors-and-solutions)
    - [7.2.12 Key Takeaways](#7212-key-takeaways)
- [8 Python Strings](#8-python-strings)
  - [8.1 What is a String?](#81-what-is-a-string)
  - [8.2 Creating Strings](#82-creating-strings)
  - [8.3 String Representation](#83-string-representation)
  - [8.4 Indexing in Strings](#84-indexing-in-strings)
  - [8.5 Slicing in Strings](#85-slicing-in-strings)
  - [8.6 String Length](#86-string-length)
  - [8.7 String Concatenation](#87-string-concatenation)
  - [8.8 String Repetition](#88-string-repetition)
  - [8.9 Checking Membership](#89-checking-membership)
  - [8.10 Common String Methods (1) – Case Conversion Methods](#810-common-string-methods-1--case-conversion-methods)
  - [8.11 Common String Methods (2) – Search and Count Methods](#811-common-string-methods-2--search-and-count-methods)
  - [8.12 Common String Methods (3) – Modify and Split Methods](#812-common-string-methods-3--modify-and-split-methods)
  - [8.13 String Formatting](#813-string-formatting)
  - [8.14 Useful String Methods (More)](#814-useful-string-methods-more)
  - [8.15 Key Takeaways](#815-key-takeaways)
- [9 Conditional Statements and Loops](#9-conditional-statements-and-loops)
  - [9.1 Python Conditional Statements (Part 1)](#91-python-conditional-statements-part-1)
    - [9.1.1 What are Conditional Statements?](#911-what-are-conditional-statements)
    - [9.1.2 Syntax of if Statement](#912-syntax-of-if-statement)
    - [9.1.3 if Statement – Example](#913-if-statement--example)
    - [9.1.4 if Statement – Another Example](#914-if-statement--another-example)
    - [9.1.5 if-else Statement](#915-if-else-statement)
    - [9.1.6 if-else Statement – Example](#916-if-else-statement--example)
    - [9.1.7 if-else Statement – Another Example](#917-if-else-statement--another-example)
    - [9.1.8 Indentation in Conditional Statements](#918-indentation-in-conditional-statements)
    - [9.1.9 if-else with Input – Example](#919-if-else-with-input--example)
    - [9.1.10 Multiple Conditions using if-else (Basic)](#9110-multiple-conditions-using-if-else-basic)
    - [9.1.11 Key Takeaways](#9111-key-takeaways)
  - [9.2 Python Conditional Statements (Part 2)](#92-python-conditional-statements-part-2)
    - [9.2.1 if-elif-else Statement](#921-if-elif-else-statement)
    - [9.2.2 Example of if-elif-else](#922-example-of-if-elif-else)
    - [9.2.3 Check Eligibility Example](#923-check-eligibility-example)
    - [9.2.4 Nested if Statement](#924-nested-if-statement)
    - [9.2.5 Nested if Example: Check Age Category](#925-nested-if-example-check-age-category)
    - [9.2.6 Nested if with Multiple Conditions](#926-nested-if-with-multiple-conditions)
    - [9.2.7 Nested if-elif-else Example](#927-nested-if-elif-else-example)
    - [9.2.8 Real-life Example: Login System](#928-real-life-example-login-system)
    - [9.2.9 Key Takeaways](#929-key-takeaways)
  - [9.3 Python Loops (Part 1)](#93-python-loops-part-1)
    - [9.3.1 What are Loops?](#931-what-are-loops)
    - [9.3.2 Types of Loops](#932-types-of-loops)
    - [9.3.3 Flow Diagram of Loop (General)](#933-flow-diagram-of-loop-general)
    - [9.3.4 for Loop (Basic)](#934-for-loop-basic)
    - [9.3.5 for Loop with range()](#935-for-loop-with-range)
    - [9.3.6 Iterating over Different Sequences](#936-iterating-over-different-sequences)
    - [9.3.7 Nested for Loop](#937-nested-for-loop)
    - [9.3.8 Common Examples using for Loop](#938-common-examples-using-for-loop)
    - [9.3.9 Looping with Step Value](#939-looping-with-step-value)
    - [9.3.10 Key Takeaways](#9310-key-takeaways)
  - [9.4 Python Loops (Part 2)](#94-python-loops-part-2)
    - [9.4.1 while Loop](#941-while-loop)
    - [9.4.2 break Statement](#942-break-statement)
    - [9.4.3 continue Statement](#943-continue-statement)
    - [9.4.4 pass Statement](#944-pass-statement)
    - [9.4.5 Loop else Statement](#945-loop-else-statement)
    - [9.4.6 Nested Loops](#946-nested-loops)
    - [9.4.7 Pattern Programs](#947-pattern-programs)
    - [9.4.8 Key Takeaways](#948-key-takeaways)
  - [9.5 Python Conditional Statements and Loops (Summary)](#95-python-conditional-statements-and-loops-summary)
    - [9.5.1 What are Conditional Statements?](#951-what-are-conditional-statements)
    - [9.5.2 if Statement](#952-if-statement)
    - [9.5.3 if-else Statement](#953-if-else-statement)
    - [9.5.4 if-elif-else Statement](#954-if-elif-else-statement)
    - [9.5.5 Nested if Statement](#955-nested-if-statement)
    - [9.5.6 Flowchart of Nested if](#956-flowchart-of-nested-if)
    - [9.5.7 for Loop](#957-for-loop)
    - [9.5.8 while Loop](#958-while-loop)
    - [9.5.9 Nested Loops](#959-nested-loops)
    - [9.5.10 range() Function](#9510-range-function)
    - [9.5.11 Loop Control Statements](#9511-loop-control-statements)
    - [9.5.12 Loop else](#9512-loop-else)
    - [9.5.13 Pattern Programs (Using Loops)](#9513-pattern-programs-using-loops)
    - [9.5.14 Common Examples](#9514-common-examples)
    - [9.5.15 Key Takeaways](#9515-key-takeaways)
- [10 Python Pattern Programs](#10-python-pattern-programs)
  - [10.1 What are Pattern Programs?](#101-what-are-pattern-programs)
  - [10.2 General Structure using for Loop](#102-general-structure-using-for-loop)
  - [10.3 General Structure using while Loop](#103-general-structure-using-while-loop)
  - [10.4 Star Patterns](#104-star-patterns)
  - [10.5 Number Patterns](#105-number-patterns)
  - [10.6 Character Patterns](#106-character-patterns)
  - [10.7 Key Takeaways](#107-key-takeaways)
  - [10.8 Practice Questions](#108-practice-questions)
  - [10.9 Tips for Better Patterns](#109-tips-for-better-patterns)
- [11 Python Data Structures Overview](#11-python-data-structures-overview)
  - [11.1 What are Data Structures?](#111-what-are-data-structures)
  - [11.2 Python Strings](#112-python-strings)
  - [11.3 String Indexing and Slicing](#113-string-indexing-and-slicing)
  - [11.4 String Methods](#114-string-methods)
  - [11.5 Lists](#115-lists)
  - [11.6 List Operations](#116-list-operations)
  - [11.7 List Slicing and Comprehension](#117-list-slicing-and-comprehension)
  - [11.8 Tuples](#118-tuples)
  - [11.9 Tuple Operations](#119-tuple-operations)
  - [11.10 Sets](#1110-sets)
  - [11.11 Set Operations](#1111-set-operations)
  - [11.12 Dictionaries](#1112-dictionaries)
  - [11.13 Dictionary Methods](#1113-dictionary-methods)
  - [11.14 Nested Data Structures](#1114-nested-data-structures)
  - [11.15 Key Takeaways](#1115-key-takeaways)
- [12 Lists](#12-lists)
  - [12.1 Python Lists](#121-python-lists)
    - [12.1.1 What is a List?](#1211-what-is-a-list)
    - [12.1.2 Creating Lists](#1212-creating-lists)
    - [12.1.3 List Representation](#1213-list-representation)
    - [12.1.4 Accessing Elements](#1214-accessing-elements)
    - [12.1.5 Slicing in Lists](#1215-slicing-in-lists)
    - [12.1.6 Modifying Elements](#1216-modifying-elements)
    - [12.1.7 Adding Elements](#1217-adding-elements)
    - [12.1.8 Removing Elements](#1218-removing-elements)
    - [12.1.9 List Methods (Common)](#1219-list-methods-common)
    - [12.1.10 List Built-in Functions](#12110-list-built-in-functions)
    - [12.1.11 List Comprehension](#12111-list-comprehension)
    - [12.1.12 Nested Lists](#12112-nested-lists)
    - [12.1.13 Iterating through a List](#12113-iterating-through-a-list)
    - [12.1.14 Useful Examples](#12114-useful-examples)
    - [12.1.15 Key Takeaways](#12115-key-takeaways)
  - [12.2 Python Data Structures (Part 2): Lists](#122-python-data-structures-part-2-lists)
    - [12.2.1 What is a List?](#1221-what-is-a-list)
    - [12.2.2 Accessing Elements in a List](#1222-accessing-elements-in-a-list)
    - [12.2.3 List Slicing](#1223-list-slicing)
    - [12.2.4 List Methods (Add Elements)](#1224-list-methods-add-elements)
    - [12.2.5 List Methods (Remove Elements)](#1225-list-methods-remove-elements)
    - [12.2.6 Other Useful Methods](#1226-other-useful-methods)
    - [12.2.7 List Comprehension](#1227-list-comprehension)
    - [12.2.8 Nested Lists](#1228-nested-lists)
    - [12.2.9 List with Different Data Types](#1229-list-with-different-data-types)
    - [12.2.10 Mutable vs Immutable](#12210-mutable-vs-immutable)
    - [12.2.11 Useful Examples](#12211-useful-examples)
    - [12.2.12 Key Takeaways](#12212-key-takeaways)
- [13 Python Sets](#13-python-sets)
  - [13.1 What is a Set?](#131-what-is-a-set)
  - [13.2 Creating a Set](#132-creating-a-set)
  - [13.3 Set Representation](#133-set-representation)
  - [13.4 Accessing Elements in a Set](#134-accessing-elements-in-a-set)
  - [13.5 Adding Elements](#135-adding-elements)
  - [13.6 Removing Elements](#136-removing-elements)
  - [13.7 Removing Elements – Examples](#137-removing-elements--examples)
  - [13.8 Set Methods (Common)](#138-set-methods-common)
  - [13.9 Updating a Set](#139-updating-a-set)
  - [13.10 Set Operations (Mathematical)](#1310-set-operations-mathematical)
  - [13.11 Set Operations – Examples](#1311-set-operations--examples)
  - [13.12 Set Comprehension](#1312-set-comprehension)
  - [13.13 Important Points](#1313-important-points)
  - [13.14 Practice Questions](#1314-practice-questions)
  - [13.15 Real-World Applications](#1315-real-world-applications)
  - [13.16 Key Takeaways](#1316-key-takeaways)
- [14 Python Dictionaries](#14-python-dictionaries)
  - [14.1 What is a Dictionary?](#141-what-is-a-dictionary)
  - [14.2 Creating a Dictionary](#142-creating-a-dictionary)
  - [14.3 Dictionary Representation](#143-dictionary-representation)
  - [14.4 Accessing Elements](#144-accessing-elements)
  - [14.5 Adding and Updating Elements](#145-adding-and-updating-elements)
  - [14.6 Removing Elements](#146-removing-elements)
  - [14.7 Dictionary Methods (Common)](#147-dictionary-methods-common)
  - [14.8 Dictionary Methods – Examples](#148-dictionary-methods--examples)
  - [14.9 Dictionary Comprehension](#149-dictionary-comprehension)
  - [14.10 Nested Dictionary](#1410-nested-dictionary)
  - [14.11 Dictionary with Different Data Types](#1411-dictionary-with-different-data-types)
  - [14.12 Dictionary vs List / Tuple / Set](#1412-dictionary-vs-list--tuple--set)
  - [14.13 Iterating through a Dictionary](#1413-iterating-through-a-dictionary)
  - [14.14 Practice Questions](#1414-practice-questions)
  - [14.15 Key Takeaways](#1415-key-takeaways)
- [15 Python Functions](#15-python-functions)
  - [15.1 What is a Function?](#151-what-is-a-function)
  - [15.2 Creating a Function](#152-creating-a-function)
  - [15.3 Function with Parameters](#153-function-with-parameters)
  - [15.4 Types of Arguments](#154-types-of-arguments)
  - [15.5 Default Arguments](#155-default-arguments)
  - [15.6 Variable Length Arguments](#156-variable-length-arguments)
  - [15.7 Return Statement](#157-return-statement)
  - [15.8 Scope of Variables](#158-scope-of-variables)
  - [15.9 Global Keyword](#159-global-keyword)
  - [15.10 Lambda Functions (Anonymous)](#1510-lambda-functions-anonymous)
  - [15.11 Built-in Functions](#1511-built-in-functions)
  - [15.12 Recursion (Function Calling Itself)](#1512-recursion-function-calling-itself)
  - [15.13 Function in Real-World Use](#1513-function-in-real-world-use)
  - [15.14 Practice Questions](#1514-practice-questions)
  - [15.15 Key Takeaways](#1515-key-takeaways)
- [16 Python Modules and Packages](#16-python-modules-and-packages)
  - [16.1 Part A – Modules and Packages (Overview)](#161-part-a--modules-and-packages-overview)
    - [16.1.1 What is a Module?](#1611-what-is-a-module)
    - [16.1.2 Using a Module](#1612-using-a-module)
    - [16.1.3 Different Ways to Import](#1613-different-ways-to-import)
    - [16.1.4 Built-in Modules](#1614-built-in-modules)
    - [16.1.5 Example: math Module](#1615-example-math-module)
    - [16.1.6 Example: random Module](#1616-example-random-module)
    - [16.1.7 Creating Your Own Module](#1617-creating-your-own-module)
    - [16.1.8 Using Your Own Module](#1618-using-your-own-module)
    - [16.1.9 Python Packages](#1619-python-packages)
    - [16.1.10 Using a Package](#16110-using-a-package)
    - [16.1.11 Installing External Packages](#16111-installing-external-packages)
    - [16.1.12 Popular External Packages](#16112-popular-external-packages)
    - [16.1.13 Viewing Installed Packages](#16113-viewing-installed-packages)
    - [16.1.14 Uninstalling a Package](#16114-uninstalling-a-package)
    - [16.1.15 Key Points (Part A)](#16115-key-points-part-a)
  - [16.2 Part B – Modules and Packages (Extended)](#162-part-b--modules-and-packages-extended)
    - [16.2.1 What is a Module?](#1621-what-is-a-module)
    - [16.2.2 Creating and Using Modules](#1622-creating-and-using-modules)
    - [16.2.3 Importing Modules](#1623-importing-modules)
    - [16.2.4 Built-in Modules](#1624-built-in-modules)
    - [16.2.5 Examples of Built-in Modules](#1625-examples-of-built-in-modules)
    - [16.2.6 What is a Package?](#1626-what-is-a-package)
    - [16.2.7 Creating a Package](#1627-creating-a-package)
    - [16.2.8 Subpackages](#1628-subpackages)
    - [16.2.9 The `__init__.py` File](#1629-the-__init__py-file)
    - [16.2.10 Installing External Modules](#16210-installing-external-modules)
    - [16.2.11 Popular External Modules](#16211-popular-external-modules)
    - [16.2.12 Module Search Path](#16212-module-search-path)
    - [16.2.13 Advantages](#16213-advantages)
    - [16.2.14 Common Errors](#16214-common-errors)
    - [16.2.15 Key Points (Part B)](#16215-key-points-part-b)
  - [16.3 Key Takeaways](#163-key-takeaways)
- [17 Python File Handling](#17-python-file-handling)
  - [17.1 What is File Handling?](#171-what-is-file-handling)
  - [17.2 Types of Files](#172-types-of-files)
  - [17.3 File Modes](#173-file-modes)
  - [17.4 Opening and Closing a File](#174-opening-and-closing-a-file)
  - [17.5 Writing to a File](#175-writing-to-a-file)
  - [17.6 Reading from a File](#176-reading-from-a-file)
  - [17.7 Reading Specific Content](#177-reading-specific-content)
  - [17.8 Appending to a File](#178-appending-to-a-file)
  - [17.9 File Handling with Different Types](#179-file-handling-with-different-types)
  - [17.10 File and Directory Operations](#1710-file-and-directory-operations)
  - [17.11 Working with Paths](#1711-working-with-paths)
  - [17.12 Working with Binary Files](#1712-working-with-binary-files)
  - [17.13 Real-World Example – Log File](#1713-real-world-example--log-file)
  - [17.14 Common Errors](#1714-common-errors)
  - [17.15 Key Takeaways](#1715-key-takeaways)
- [18 Object-Oriented Programming](#18-object-oriented-programming)
  - [18.1 Python Object-Oriented Programming (OOP)](#181-python-object-oriented-programming-oop)
    - [18.1.1 What is OOP?](#1811-what-is-oop)
    - [18.1.2 Class and Object](#1812-class-and-object)
    - [18.1.3 Constructor (`__init__`)](#1813-constructor-__init__)
    - [18.1.4 Instance and Class Variables](#1814-instance-and-class-variables)
    - [18.1.5 Methods in a Class](#1815-methods-in-a-class)
    - [18.1.6 Types of Methods – Example](#1816-types-of-methods--example)
    - [18.1.7 Encapsulation](#1817-encapsulation)
    - [18.1.8 Inheritance](#1818-inheritance)
    - [18.1.9 Types of Inheritance](#1819-types-of-inheritance)
    - [18.1.10 Method Overriding (Polymorphism)](#18110-method-overriding-polymorphism)
    - [18.1.11 Polymorphism](#18111-polymorphism)
    - [18.1.12 Abstraction](#18112-abstraction)
    - [18.1.13 Special (Magic) Methods](#18113-special-magic-methods)
    - [18.1.14 Real-World Example](#18114-real-world-example)
    - [18.1.15 Key Takeaways](#18115-key-takeaways)
  - [18.2 Python OOP – Practical Guide](#182-python-oop--practical-guide)
    - [18.2.1 What is OOP?](#1821-what-is-oop)
    - [18.2.2 Class and Object](#1822-class-and-object)
    - [18.2.3 Constructor (`__init__`)](#1823-constructor-__init__)
    - [18.2.4 Instance and Class Variables](#1824-instance-and-class-variables)
    - [18.2.5 Methods in a Class](#1825-methods-in-a-class)
    - [18.2.6 Encapsulation](#1826-encapsulation)
    - [18.2.7 Inheritance](#1827-inheritance)
    - [18.2.8 Types of Inheritance](#1828-types-of-inheritance)
    - [18.2.9 Polymorphism](#1829-polymorphism)
    - [18.2.10 Method Overloading](#18210-method-overloading)
    - [18.2.11 Abstraction](#18211-abstraction)
    - [18.2.12 Special (Magic) Methods](#18212-special-magic-methods)
    - [18.2.13 Operator Overloading](#18213-operator-overloading)
    - [18.2.14 Practical Example: Student Management](#18214-practical-example-student-management)
    - [18.2.15 Key Takeaways](#18215-key-takeaways)
  - [18.3 Python Inheritance and Polymorphism](#183-python-inheritance-and-polymorphism)
    - [18.3.1 What is Inheritance?](#1831-what-is-inheritance)
    - [18.3.2 Syntax of Inheritance](#1832-syntax-of-inheritance)
    - [18.3.3 Single Inheritance](#1833-single-inheritance)
    - [18.3.4 Multiple Inheritance](#1834-multiple-inheritance)
    - [18.3.5 Multilevel Inheritance](#1835-multilevel-inheritance)
    - [18.3.6 Hierarchical Inheritance](#1836-hierarchical-inheritance)
    - [18.3.7 Hybrid Inheritance](#1837-hybrid-inheritance)
    - [18.3.8 Method Overriding](#1838-method-overriding)
    - [18.3.9 `super()` Function](#1839-super-function)
    - [18.3.10 Polymorphism](#18310-polymorphism)
    - [18.3.11 Polymorphism using Functions](#18311-polymorphism-using-functions)
    - [18.3.12 Polymorphism using Operators](#18312-polymorphism-using-operators)
    - [18.3.13 `isinstance()` and `issubclass()`](#18313-isinstance-and-issubclass)
    - [18.3.14 Real-World Example: Bank Account](#18314-real-world-example-bank-account)
    - [18.3.15 Key Takeaways](#18315-key-takeaways)
- [19 Python Exception Handling](#19-python-exception-handling)
  - [19.1 What is an Exception?](#191-what-is-an-exception)
  - [19.2 Why Exception Handling?](#192-why-exception-handling)
  - [19.3 Common Built-in Exceptions](#193-common-built-in-exceptions)
  - [19.4 Basic try-except Block](#194-basic-try-except-block)
  - [19.5 Try-Except-Else](#195-try-except-else)
  - [19.6 Try-Except-Finally](#196-try-except-finally)
  - [19.7 Multiple Except Blocks](#197-multiple-except-blocks)
  - [19.8 Catching Multiple Exceptions](#198-catching-multiple-exceptions)
  - [19.9 Raising Exceptions](#199-raising-exceptions)
  - [19.10 Custom Exception](#1910-custom-exception)
  - [19.11 Exception Handling Flowchart](#1911-exception-handling-flowchart)
  - [19.12 Nested Try-Except](#1912-nested-try-except)
  - [19.13 Using Finally for Resource Cleanup](#1913-using-finally-for-resource-cleanup)
  - [19.14 Best Practices](#1914-best-practices)
  - [19.15 Key Takeaways](#1915-key-takeaways)
- [20 Python Advanced Topics](#20-python-advanced-topics)
  - [20.1 List Comprehension](#201-list-comprehension)
  - [20.2 Dictionary Comprehension](#202-dictionary-comprehension)
  - [20.3 Generator and Iterator](#203-generator-and-iterator)
  - [20.4 Lambda Functions](#204-lambda-functions)
  - [20.5 map(), filter() and reduce()](#205-map-filter-and-reduce)
  - [20.6 Decorators](#206-decorators)
  - [20.7 Context Managers (with statement)](#207-context-managers-with-statement)
  - [20.8 Regular Expressions (re module)](#208-regular-expressions-re-module)
  - [20.9 Date and Time (datetime module)](#209-date-and-time-datetime-module)
  - [20.10 JSON Handling](#2010-json-handling)
  - [20.11 Working with APIs (requests module)](#2011-working-with-apis-requests-module)
  - [20.12 Multithreading](#2012-multithreading)
  - [20.13 Multiprocessing](#2013-multiprocessing)
  - [20.14 Virtual Environment](#2014-virtual-environment)
  - [20.15 Key Takeaways](#2015-key-takeaways)
- [21 Appendix A: Source Image Index](#21-appendix-a-source-image-index)
- [22 Appendix B: Content Verification Summary](#22-appendix-b-content-verification-summary)

---

## 1 Python Introduction

*Source image: [image1.png](images/image1.png)*

### 1.1 What is Python?

- Python is a **high-level, general-purpose, interpreted and object-oriented** programming language.
- It is **easy to learn** and has **simple syntax**.
- It was created by **Guido van Rossum** and first released in **1991**.
- Python is widely used in web development, data science, machine learning, artificial intelligence, automation, scientific computing and more.

### 1.2 Key Features of Python

- **Simple** and **readable** syntax
- **Interpreted** language (no compilation required)
- **High-level** language
- **Object-oriented** and multi-paradigm
- Large standard library
- **Open-source** and free
- **Portable** (works on Windows, macOS, Linux)
- Extensive community support
- Used in multiple domains (Web, AI/ML, Data Science, etc.)

### 1.3 Applications of Python

| | | | |
|---|---|---|---|
| Web Development | Data Science | Machine Learning | Artificial Intelligence |
| Automation & Scripting | Scientific Computing | Desktop Applications | Game Development |

### 1.4 How Python Works?

```text
.py Python Source Code (text file)
   → Python Interpreter
   → Bytecode (.pyc)
   → Python Virtual Machine (PVM)
   → Output (Execution Result)
```

### 1.5 Python vs Other Languages

| Feature | Python | Java | C++ | JavaScript |
|---------|--------|------|-----|------------|
| Ease of Learning | Very Easy | Moderate | Difficult | Moderate |
| Type | Interpreted | Compiled | Compiled | Interpreted |
| Syntax | Simple | Complex | Complex | Moderate |
| Use Cases | Web, Data Science, AI/ML, Automation | Enterprise Applications | System Programming | Web Development |
| Platform | Cross-platform | Cross-platform | Cross-platform | Cross-platform |

### 1.6 Key Takeaways

- Python is a high-level, interpreted, general-purpose and object-oriented language created by Guido van Rossum (first released 1991).
- Source code (`.py`) is run by the interpreter, which produces bytecode (`.pyc`) executed by the Python Virtual Machine.
- Python is simple, portable, open-source and used across many domains.

---

## 2 Installation and Development Tools

*This topic combines 5 source sheets, kept as separate parts below: **Python Installation**; **VS Code vs PyCharm vs Jupyter**; **Visual Studio Code (VS Code)**; **PyCharm**; **Jupyter Notebook**.*

### 2.1 Python Installation

*Source image: [914587568_1032655613198294_5139468293251605398_n.png](images/914587568_1032655613198294_5139468293251605398_n.png)*

#### 2.1.1 Prerequisites

- A computer with Windows / macOS / Linux
- Stable internet connection
- Admin permission (for installation)
- At least 1–2 GB free disk space
- Recommended RAM: 4 GB or more

#### 2.1.2 Download Python

- Visit the official website: <https://www.python.org>
- Click on the "Downloads" button.
- Choose the latest stable version (e.g., Python 3.12.x).

#### 2.1.3 Installation on Windows

1. Run the downloaded installer (`python-3.12.x-amd64.exe`).
2. Check the option: ☑ **Add Python to PATH**.
3. Click on "Install Now".
4. Wait for installation to complete.
5. Click on "Close".

**Setup window shown in the image ("Python 3.12.2 (64-bit) Setup"):**

- *Install Python 3.12.2 (64-bit)* – Select **Install Now** to install Python with default settings, or choose **Customize** to enable or disable features.
- **Install Now** – `C:\Users\...\AppData\Local\Programs\Python\Python312`; includes IDLE, pip and documentation; creates shortcuts and file associations.
- **Customize installation** – choose location and features.
- ☐ Use admin privileges when installing py.exe
- ☑ **Add python to PATH** (highlighted)
- Cancel button

#### 2.1.4 Installation on macOS

1. Visit <https://www.python.org>
2. Download macOS installer (`.pkg`)
3. Open the installer and follow the steps
4. Python will be installed in `/usr/local/bin`
5. Verify installation in Terminal

```text
$ python3 --version
Python 3.12.2
$ which python3
/usr/local/bin/python3
```

#### 2.1.5 Installation on Linux (Ubuntu)

1. Open Terminal
2. Update package list: `sudo apt update`
3. Install Python: `sudo apt install python3`
4. Check version: `python3 --version`

```text
$ sudo apt update
$ sudo apt install python3
$ python3 --version
Python 3.12.2
```

#### 2.1.6 Verify Installation

Open Command Prompt / Terminal and run:

```bash
python --version
```

or

```bash
python3 --version
```

```text
$ python --version
Python 3.12.2
```

#### 2.1.7 Key Takeaways

- Download Python from <https://www.python.org>.
- On Windows, tick **Add Python to PATH** before clicking **Install Now**.
- On Linux (Ubuntu) use `sudo apt install python3`; on macOS use the `.pkg` installer.
- Verify with `python --version` or `python3 --version`.

### 2.2 VS Code vs PyCharm vs Jupyter

*Source image: [912151032_1841547860496924_1176882838050537686_n.png](images/912151032_1841547860496924_1176882838050537686_n.png)*

#### 2.2.1 What Are These?

- These are **code editors / IDEs** used to write, run and manage Python programs.
- They help in **coding, debugging, running programs and managing projects**.
- Each tool has different features and is used for different purposes.

#### 2.2.2 Key Differences

| Tool | Type | Best For | Special Feature |
|------|------|----------|-----------------|
| VS Code | Code Editor | General coding (lightweight) | Extensions, fast, customizable |
| PyCharm | IDE | Professional development (large projects) | Advanced tools, debugging, built-in features |
| Jupyter | Notebook | Data science, learning, experiments | Interactive cells, easy visualization |

#### 2.2.3 Visual Studio Code (VS Code)

##### 2.2.3.1 Overview

- A lightweight and powerful **code editor** by **Microsoft**.
- Supports multiple programming languages including **Python**.
- Highly customizable with **extensions**.
- Suitable for beginners and professionals.

##### 2.2.3.2 Features

- Fast and lightweight
- Supports extensions
- Integrated terminal
- Git integration
- Debugger
- Customizable themes

##### 2.2.3.3 Installation (VS Code)

1. Visit <https://code.visualstudio.com>
2. Download the installer for your OS (Windows / macOS / Linux).
3. Run the installer and follow the steps.
4. Open VS Code.
5. Install "Python" extension from Extensions Marketplace.

**Screenshots shown in the source image:**

- Editor window: Explorer panel with `MYPROJECT > main.py`, and the code below on line 2.

```python
print("Hello Python!")
```

- Extensions Marketplace: search box "Python" → result **Python – Microsoft** with an **Install** button.

#### 2.2.4 PyCharm (Overview)

##### 2.2.4.1 Overview

- A powerful IDE by **JetBrains** specially designed for Python.
- Provides advanced tools for professional development.
- Suitable for **large projects**.
- Free **Community Edition** and paid **Professional Edition**.

##### 2.2.4.2 Features

- Smart code completion
- Advanced debugging
- Built-in tools for testing
- Virtual environment support
- Database tools
- Code analysis and refactoring

##### 2.2.4.3 Installation (PyCharm)

1. Visit <https://www.jetbrains.com/pycharm>
2. Download **Community Edition** (free) or **Professional Edition**.
3. Run the installer and follow the steps.
4. Open PyCharm and create a new Python project.

**Screenshots shown in the source image:**

- Editor window: project `pythonProject` with `venv`, `main.py`, External Libraries.

```python
def greet():
    print("Hello Python!")

greet()
```

- "Welcome to PyCharm" screen with buttons: **New Project**, **Open**, **Get from VCS**.

#### 2.2.5 Jupyter Notebook (Overview)

##### 2.2.5.1 Overview

- An open-source web application.
- Used mainly for **data science, research and learning**.
- Allows you to write and run code in **interactive cells**.
- Supports visualization, equations and rich output.

##### 2.2.5.2 Features

- Interactive coding environment
- Run code cell by cell
- Supports data visualization
- Easy to share notebooks
- Good for Python learning and experimentation

##### 2.2.5.3 Installation (Jupyter)

1. Install Python (if not installed).
2. Open Command Prompt / Terminal.
3. Run the command:

   ```bash
   pip install jupyter
   ```

4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

**Screenshots shown in the source image:**

- A notebook cell `In [1]:` containing the following code, followed by a line plot:

```python
import matplotlib.pyplot as plt
plt.plot([1,2,3,4],[1,4,9,16])
plt.show()
```

- The Jupyter dashboard with tabs **Files**, **Running**, **Clusters** and buttons **New**, **Upload**.

#### 2.2.6 Which One to Use?

- Use **VS Code** → if you want a lightweight, flexible and general purpose editor.
- Use **PyCharm** → if you are working on large Python projects and want advanced features.

> [!WARNING]
> **Verify:** The source image is cropped at the bottom. The "Which One to Use?" list (a third bullet for Jupyter is likely present) and the "Summary" section are only partly visible. The visible part of the Summary reads: *"All three tools are useful and widely used. VS Code is simple and fast."* The remaining lines (PyCharm and Jupyter) are cut off.

#### 2.2.7 Key Takeaways

- VS Code, PyCharm and Jupyter are tools used to write, run and manage Python programs.
- VS Code is a lightweight, extensible code editor; PyCharm is a full IDE for large projects; Jupyter is a notebook for interactive work.
- All three are useful and widely used.

### 2.3 Visual Studio Code (VS Code)

*Source image: [914572447_2259503431296376_1688452425397689166_n.png](images/914572447_2259503431296376_1688452425397689166_n.png)*

#### 2.3.1 What is VS Code?

- VS Code is a free, open-source and lightweight code editor developed by **Microsoft**.
- It is used to write, run, debug and manage code for multiple programming languages including **Python**.
- It is highly customizable with extensions.
- It is suitable for beginners as well as professional developers.

#### 2.3.2 Key Features

- Free and open source
- Lightweight and fast
- Supports multiple programming languages
- Integrated terminal
- Built-in debugging tools
- Extensions marketplace
- Git integration
- Customizable themes and settings
- Suitable for web development, data science, AI/ML, and more

#### 2.3.3 Installation Steps

1. Visit the official website: <https://code.visualstudio.com>
2. Download the installer for your OS (Windows / macOS / Linux)
3. Run the installer and follow the on-screen steps
4. Open VS Code after installation
5. Install Python extension (from Extensions Marketplace)

#### 2.3.4 Flow Diagram (Installation & Setup)

```text
Download VS Code → Install VS Code → Open VS Code
   → Install Python Extension → Start Writing and Running Python Code
```

#### 2.3.5 User Interface Overview

| Component | Description (as labelled) |
|-----------|---------------------------|
| Activity Bar | Explorer, Search, Source Control, Extensions |
| Explorer | Manage Files and Folders |
| Editor Tabs | Open Files |
| Run / Debug Buttons | Run and debug the current file |
| Code Editor | Write Code Here |
| Integrated Terminal | Run Commands |

The screenshot shows a project `PYTHON_PROJECT` with `main.py` containing:

```python
print("Hello, Python!")
```

and a terminal prompt `PS C:\Users>`.

#### 2.3.6 Installing Python Extension

1. Click on the **Extensions** icon.
2. Search for "Python".
3. Click on **Install** (extension "Python – Microsoft").
4. After installation, the Python extension will be added.

#### 2.3.7 Running Python Code

1. Open a new file and save it as `main.py`.
2. Write a simple Python program.
3. Click on the **Run** button or use the terminal.
4. Output will be displayed in the terminal.

**Example (`main.py`):**

```python
print("Hello, Python!")
```

```text
PS C:\Python> python main.py
Hello, Python!
```

#### 2.3.8 Use Cases

- Python development
- Web development (HTML, CSS, JS)
- Data science and machine learning
- Project development
- Competitive programming
- Learning and practicing coding *(list may continue beyond the cropped edge of the source image)*

#### 2.3.9 Key Takeaways

- VS Code is a free, open-source, lightweight Microsoft editor extended through the Extensions Marketplace.
- For Python, install the **Python extension**, save a file as `main.py` and run it from the Run button or the integrated terminal.

### 2.4 PyCharm

*Source image: [912225366_1498650025527139_720286302038420067_n.png](images/912225366_1498650025527139_720286302038420067_n.png)*

#### 2.4.1 What is PyCharm?

- PyCharm is a powerful and professional **Integrated Development Environment (IDE)** for Python developed by **JetBrains**.
- It provides **advanced tools** for coding, debugging, testing and project management.
- Suitable for both beginners and professional developers.
- It is specially designed for Python development with smart code completion, refactoring and built-in tools.

#### 2.4.2 Key Features

- Intelligent code completion
- Smart error detection
- Advanced debugging tools
- Built-in testing framework (pytest, unittest)
- Integrated terminal
- Database tools
- Web development support (Django, Flask)
- Version control integration (Git)
- Scientific tools and Jupyter support
- Professional project management
- Available in Community (free) and Professional (paid) editions

#### 2.4.3 Versions of PyCharm

| Community Edition (Free) | Professional Edition (Paid) |
|--------------------------|-----------------------------|
| Open source | All features of Community |
| Basic Python development features | Web development tools (Django, Flask) |
| Suitable for students and beginners | Database support |
| | Scientific tools |
| | Remote development |
| | More advanced features |

#### 2.4.4 System Requirements

| Requirement | Details |
|-------------|---------|
| Operating System | Windows 10/11, macOS 10.15+, Linux (64-bit) |
| RAM | Minimum 4 GB (8 GB recommended) |
| Storage | Minimum 2.5 GB free space |
| Python | Pre-installed or can be installed during setup |

#### 2.4.5 Installation Steps

1. Visit the official website: <https://www.jetbrains.com/pycharm/>
2. Download Community Edition (free) or Professional Edition.
3. Run the installer (.exe / .dmg / .tar.gz).
4. Follow the installation steps and choose installation location.
5. Launch PyCharm after installation.
6. Select or add Python interpreter.
7. Create a new project and start coding.

#### 2.4.6 Flow Diagram (Installation Process)

```text
Visit JetBrains Website → Download PyCharm Installer → Run Installer → Follow Setup Steps
    → Open PyCharm → Add Python Interpreter → Create New Project
```

#### 2.4.7 PyCharm User Interface Overview

The source image shows a labelled screenshot of the PyCharm window with these parts:

| Component | Description (as labelled) |
|-----------|---------------------------|
| Menu Bar | File, Edit, View, Navigate, Code, Refactor, Run, Tools, VCS, Window, Help |
| Run/Debug Buttons | Buttons at the top right of the window to run and debug the program |
| Project Tool Window | Manage Files and Folders (shows `pythonProject`, `venv`, `main.py`, External Libraries, Scratches and Consoles) |
| Editor | Write Code Here |
| Integrated Terminal | Run Commands |

Code and terminal shown in the screenshot:

```python
print("Hello, PyCharm!")
```

```text
PS C:\pythonProject> python main.py
Hello, PyCharm!
```

#### 2.4.8 Running a Python Program

1. Create a new project (File → New Project).
2. Select Python interpreter.
3. Create a Python file (e.g., `main.py`).
4. Write your code.
5. Click on Run button or press **Shift + F10**.
6. Output will be displayed in the Run/Terminal *(text is cut off in the source image)*.

**Example:**

```python
print("Hello, PyCharm!")
```

**Output (Run window):**

```text
Hello, PyCharm!

Process finished with exit code 0
```

#### 2.4.9 Use Cases

- Web development (Django, Flask)
- Data science and machine learning
- Scientific computing
- Project development
- Competitive programming
- Python automation and scripting
- Professional software development *(partially cut off in the source image)*

> [!WARNING]
> **Verify:** The bottom of the source image is cropped; the final step text of "Running a Python Program" and further Use Cases (if any) are not fully visible.

#### 2.4.10 Key Takeaways

- PyCharm is a JetBrains IDE designed specifically for Python.
- It comes in a free **Community** and a paid **Professional** edition.
- Typical workflow: install → add interpreter → create project → write code → run (Shift + F10).

### 2.5 Jupyter Notebook

*Source image: [910417690_1128530079592166_3480844957796041387_n.png](images/910417690_1128530079592166_3480844957796041387_n.png)*

#### 2.5.1 What is Jupyter Notebook?

- Jupyter Notebook is an **open-source web-based interactive environment** used to write and run Python code in **cells**.
- It allows you to write code, add text (Markdown), equations, images and visualizations in the same document.
- It is widely used in **data science, research, machine learning** and **education**.
- It supports multiple programming languages (Python, R, Julia, etc.), but Python is most commonly used.

#### 2.5.2 Key Features

- **Open-source** and free
- **Interactive** coding (run code cell by cell)
- Supports **Markdown** (text, headings, lists)
- Display outputs like tables, graphs, images
- Easy to visualize data and results
- Supports multiple languages
- Widely used in data science and ML
- Share and export notebooks (HTML, PDF, etc.)
- Supports mathematical equations (LaTeX syntax)
- Simple and beginner friendly

#### 2.5.3 Components of Jupyter Notebook

| Component | Description |
|-----------|-------------|
| Menu Bar | File, Edit, View, Insert, Cell, Kernel, Help |
| Toolbar | Run, Stop, etc. |
| Kernel | Select Python (e.g., *Python 3 (ipykernel)*) |
| Code Cell | Write and run Python code |
| Markdown Cell | Add text, headings, lists, equations, images |
| Output Cell | Shows result of code |

**Example shown in the screenshot:**

```python
print("Hello, Jupyter!")
```

```text
Hello, Jupyter!
```

#### 2.5.4 Installation Steps

1. Install Python (if not installed, download from <https://www.python.org>).
2. Open Command Prompt / Terminal.
3. Run the command:

   ```bash
   pip install jupyter
   ```

4. Wait for the installation to complete.
5. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

#### 2.5.5 Flow Diagram (Working Process)

```text
Install Python → Install Jupyter (pip install jupyter) → Run (jupyter notebook)
   → Browser opens with Jupyter Dashboard → Create / Open a Notebook
   → Write and run code cell by cell → View output (text, tables, graphs, images)
```

#### 2.5.6 Using Jupyter Notebook

1. Launch Jupyter Notebook.
2. In the browser, you will see the Jupyter Dashboard.
3. Click on **New → Python 3 (ipykernel)** to create a new notebook.
4. Write your Python code in a cell.
5. Press **Shift + Enter** to run the cell.
6. The output will be displayed below the cell.

#### 2.5.7 Example

Notebook: `Untitled.ipynb`

**In [1]:**

```python
# Simple Python program
print("Hello, Jupyter!")
```

```text
Hello, Jupyter!
```

**In [2]:**

```python
# Create a list and display
numbers = [1, 2, 3, 4, 5]
print(numbers)
```

```text
[1, 2, 3, 4, 5]
```

**In [3]:**

```python
# Plot a graph
import matplotlib.pyplot as plt
x = [1, 2, 3, 4, 5]
y = [2, 4, 6, 8, 10]
plt.plot(x, y, marker='o')
plt.title("Simple Line Plot")
plt.xlabel("X")
plt.ylabel("Y")
plt.show()
```

*Output:* a graph titled **Simple Line Plot** (a straight line through the points).

> [!WARNING]
> **Verify:** In the source image the `plt.xlabel(...)` and `plt.ylabel(...)` lines are partly hidden behind the graph; `"X"` and `"Y"` are inferred from the visible characters.

#### 2.5.8 Use Cases

- Data analysis and visualization
- Machine learning model development
- Scientific computing and research
- Teaching and learning Python
- Exploratory data analysis (EDA)
- Project documentation and reporting
- Sharing code with others
- Interactive experiments and prototyping

#### 2.5.9 Tips

- Use Markdown cells to write notes.
- Use **Shift + Enter** to run code.
- Use clear comments in your code.
- You can export notebook as HTML, PDF, etc.
- Install useful libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, etc.

#### 2.5.10 Key Takeaways

- Jupyter Notebook is an open-source, interactive, cell-based environment.
- Install with `pip install jupyter` and start with `jupyter notebook`.
- Use **Shift + Enter** to run a cell; output appears below the cell.
- Widely used for data analysis, machine learning, teaching and sharing code.

---

## 3 Python Syntax and Indentation

*This topic combines 2 source sheets, kept as separate parts below: **Python Syntax**; **Python Indentation**.*

### 3.1 Python Syntax

*Source image: [905960814_1481818451676435_7517671516028661993_n.png](images/905960814_1481818451676435_7517671516028661993_n.png)*

#### 3.1.1 What is Syntax?

- Syntax refers to the **set of rules** that define the **structure** of a Python program.
- These rules tell us how to write **valid** Python code.
- If we do not follow the correct syntax, the interpreter will show an **error** (`SyntaxError`).
- Python has a clean syntax which is similar to English and easy to understand.

#### 3.1.2 General Rules of Python Syntax

- Python is case sensitive (`age` and `Age` are different).
- Use proper indentation (more in next page).
- Use quotes for strings (single `' '` or double `" "`).
- Statements are usually written in separate lines.
- Comments start with `#` and are ignored by Python.
- Use meaningful variable names.
- End of statement is usually a new line (no semicolon required).

#### 3.1.3 Basic Structure of a Python Program

```python
# This is a comment
name = "Python"
print("Hello, " + name)
```

| Line | Code | Meaning |
|------|------|---------|
| 1 | `# This is a comment` | Comment (ignored by Python) |
| 2 | `name = "Python"` | Variable assignment |
| 3 | `print("Hello, " + name)` | Output statement |

#### 3.1.4 Tokens in Python

| Token Type | Example | Meaning |
|------------|---------|---------|
| Keywords | `if`, `else`, `for` | Reserved words |
| Identifiers | `name`, `age` | User-defined names |
| Literals | `10`, `3.14`, `"text"` | Fixed values |
| Operators | `+`, `-`, `*`, `/` | Perform operations |
| Separators | `( )`, `[ ]`, `{ }`, `,` | Separate elements |
| Comments | `# This is a comment` | Ignored by Python |

#### 3.1.5 Python Keywords

> [!IMPORTANT]
> Python has **35 keywords** (reserved words) which **cannot be used as variable names**.

**Some Important Keywords:**

| | | | | |
|---|---|---|---|---|
| `True` | `False` | `None` | `if` | `else` |
| `elif` | `for` | `while` | `break` | `continue` |
| `def` | `class` | `return` | `try` | `except` |
| `import` | `from` | `as` | `with` | `pass` |
| `global` | `nonlocal` | `and` | `or` | `not` |
| `in` | `is` | `lambda` | `yield` | `del` |

#### 3.1.6 Python Identifiers

An **identifier** is a name given to a variable, function, class, etc.

**Rules for Identifiers**

- Can start with a letter (a–z, A–Z) or underscore (`_`).
- Can contain letters, digits (0–9) and underscore.
- Cannot start with a digit.
- Cannot be a keyword.
- Case sensitive (`age` and `Age` are different).

**Valid and Invalid Examples**

| Valid Identifiers | Invalid Identifiers | Reason |
|-------------------|---------------------|--------|
| `name` | `2name` | starts with digit |
| `_value` | `total-marks` | contains `-` |
| `total_marks` | `class` | keyword |
| `student1` | `first name` | contains space |
| `age2` | `@value` | contains special character |

#### 3.1.7 Python Statements and Lines

- A Python program is a collection of statements.
- Generally, one statement is written in one line.
- Multiple statements can be written in one line using `;` (semicolon) but it is **not recommended**.

**Example:**

```python
a = 10
b = 20
print(a + b)
x = 5; y = 6; print(x + y)   # multiple statements
```

#### 3.1.8 Key Takeaways

- Syntax is the set of rules defining the structure of a Python program; breaking them raises `SyntaxError`.
- Python is case sensitive and uses `#` for comments.
- Identifiers cannot start with a digit, cannot be keywords and cannot contain spaces or special characters (other than `_`).
- One statement per line is the recommended style.

### 3.2 Python Indentation

*Source image: [910494528_1456743733310738_2470051104257098533_n.png](images/910494528_1456743733310738_2470051104257098533_n.png)*

#### 3.2.1 What is Indentation?

- Indentation means giving **space** at the beginning of a line of code.
- In Python, indentation is used to **define** a block of code (e.g., inside `if`, `for`, `while`, function, class).
- Python does **not use** `{ }` like other languages. It uses **indentation** to show blocks.
- Proper indentation makes the code readable and organized.

#### 3.2.2 Indentation Rules

- Use **4 spaces** per indentation level (recommended).
- Be consistent (use either spaces or tabs).
- Do not mix spaces and tabs.
- All statements at the same level must have the same indentation.
- A new block starts after a colon (`:`) and is indented.
- When the block ends, indentation stops.

#### 3.2.3 Visualization of Indentation

```python
if age >= 18:
    print("You are an adult")
    for i in range(3):
        print(i)
    print("Done")
else:
    print("You are a minor")
```

| Level | Meaning |
|-------|---------|
| No indentation | Outside block (`if age >= 18:` and `else:`) |
| 1 level indentation | Inside `if` |
| 2 level indentation | Inside `for` |

#### 3.2.4 Correct vs Incorrect Indentation

**Correct Indentation**

```python
for i in range(3):
    print(i)
    print("Hello")
```

Both `print()` statements are inside the `for` loop (same indentation level).

**Incorrect Indentation**

```python
for i in range(3):
        print(i)
    print("Hello")
```

`print("Hello")` is outside the `for` loop (different indentation level).

> [!NOTE]
> In the source image the incorrect example shows the third line at a smaller indentation than the second line. The exact number of spaces is not readable, so the layout above is representative.

#### 3.2.5 Common Indentation Errors

**1. IndentationError**

```python
if True:
print("Hello")
```

```text
IndentationError: expected an indented block
```

**2. Unexpected Indent**

```python
print("Hello")
    print("World")
```

```text
IndentationError: unexpected indent
```

**3. Inconsistent Indentation**

```python
if True:
        print("Hello")
    print("World")
```

```text
IndentationError: unindent does not match any outer indentation level
```

> [!WARNING]
> **Verify:** In the source image, example 3 shows only two code lines (`if True:` and an indented `print("Hello")`) together with the error message. The second `print("World")` line above is added only to illustrate how this error arises; please check against the original.

#### 3.2.6 Flow Diagram (How Indentation Works)

```text
Start → Write a block statement (e.g., if, for, while)
      → Press Enter and indent by 4 spaces
      → Write all statements inside that block
      → When block ends, remove indentation → End
```

#### 3.2.7 More Examples

**if-else Statement**

```python
age = 20
if age >= 18:
    print("Adult")
else:
    print("Minor")
```

**for Loop**

```python
for i in range(3):
    print(i)
    print("Loop running")

print("Outside loop")
```

**Function Definition**

```python
def greet():
    print("Hello")
    print("Welcome")

greet()   # function call
```

#### 3.2.8 Key Takeaways

- Python uses indentation (not `{ }`) to define blocks.
- Use 4 spaces per level; never mix tabs and spaces.
- A block starts after a colon (`:`); when it ends, indentation stops.
- Wrong indentation causes `IndentationError`.

---

## 4 Keywords and Identifiers

*This topic combines 2 source sheets, kept as separate parts below: **Python Keywords**; **Python Identifiers**.*

### 4.1 Python Keywords

*Source images: [913360589_1776235893450096_7919834115611546755_n.png](images/913360589_1776235893450096_7919834115611546755_n.png) (Keywords) and [913811109_1077684801952358_6312331083628683047_n.png](images/913811109_1077684801952358_6312331083628683047_n.png) (left half of the combined "Keywords + Identifiers" sheet)*

> [!NOTE]
> The combined sheet repeats the Keywords page with slightly different examples. The shared content is given once; the differences are listed under *Variations in the combined sheet*.

#### 4.1.1 What are Keywords?

- Keywords are **special and reserved** words in Python.
- These words have a **fixed meaning** and are used to perform specific tasks.
- Keywords **cannot be used** as variable names, function names, class names or any other identifiers.
- All keywords are written in **lowercase**.

> [!IMPORTANT]
> Keywords are reserved words with predefined meaning.

#### 4.1.2 List of Python Keywords (Total 35)

| | | | | |
|---|---|---|---|---|
| `False` | `class` | `finally` | `is` | `return` |
| `None` | `continue` | `for` | `lambda` | `try` |
| `True` | `def` | `from` | `nonlocal` | `while` |
| `and` | `del` | `global` | `not` | `with` |
| `as` | `elif` | `if` | `or` | `yield` |
| `assert` | `else` | `import` | `pass` | |
| `break` | `except` | `in` | `raise` | |

**Total 35 Keywords**

> [!WARNING]
> **Verify:** The source grid shows **33** words although the heading says "Total 35". The two words missing from the grid are `async` and `await`, which are part of Python's keyword list.

#### 4.1.3 Using Keywords in a Program

```python
age = 20
if age >= 18:
    print("You are an adult")
else:
    print("You are a minor")
```

`if` and `else` are keywords, used to make decisions in a program.

#### 4.1.4 Keywords Cannot be Used as Identifiers

```python
if = 10     # Invalid
print(if)
```

```text
SyntaxError: cannot assign to keyword 'if'
```

#### 4.1.5 Common Python Keywords and Their Use

| Keyword | Purpose / Use | Example |
|---------|---------------|---------|
| `if` | Conditional execution | `if x > 0:` |
| `else` | Alternative block | `else :` |
| `for` | Loop over a sequence | `for i in range(5):` |
| `while` | Repeated execution | `while x < 10:` |
| `def` | Define a function | `def greet():` |
| `class` | Define a class | `class Student:` |
| `try` | Handle exceptions | `try :` |
| `import` | Import a module | `import math` |
| `return` | Return value from function | `return x` |

#### 4.1.6 Variations in the combined sheet

- Section title: **"Trying to Use a Keyword as a Variable"** – same code (`if = 10  # ❌ Invalid`, `print(if)`) and the same `SyntaxError: cannot assign to keyword 'if'`, with the note *"Keywords cannot be used as variable names."*
- Example program shown with 4 lines:

```python
if age >= 18:
    print("Adult")
else:
    print("Minor")
```

- Annotations: *"if, else are keywords"* and *"Used to make decision in program"*.
- Table title: **"Some Common Keywords and Their Use"**; the table is the same, with the column heading **Use** and the last row described as "Return from function".
- Callout: *"Reserved words with special meaning"*.

#### 4.1.7 Key Takeaways

- Keywords are reserved words.
- They have a fixed meaning.
- Total 35 keywords in Python.
- All keywords are in lowercase.
- Cannot be used as variable, function or class names.
- Used to perform specific tasks like loop, condition, import, etc.
- Helps in writing structured and meaningful code.

### 4.2 Python Identifiers

*Source images: [915876783_1056230370770536_7707649899261796656_n.png](images/915876783_1056230370770536_7707649899261796656_n.png) (Identifiers) and [913811109_1077684801952358_6312331083628683047_n.png](images/913811109_1077684801952358_6312331083628683047_n.png) (right half of the combined sheet)*

> [!NOTE]
> The identifiers material also appears briefly in the *Python Syntax* lecture. The combined sheet is a shorter version of this page; its differences are listed at the end.

#### 4.2.1 What are Identifiers?

- Identifiers are names given to **variables, functions, classes, modules** or any other objects in Python.
- They are used to **uniquely identify** a value or entity in a program.
- Identifiers allow us to give **meaningful names** so that the code becomes readable and easy to understand.

**Diagram:** *Identifier* → `student_name` ("Identifier is a name") → *Value* `10` ("It stores a value in memory").

#### 4.2.2 Rules for Identifiers

1. Can start with a letter (a–z, A–Z) or underscore (`_`)
2. Can contain letters, digits (0–9) and underscore (`_`)
3. Case sensitive (`age` and `Age` are different)
4. Can be of any length
5. Should be meaningful and descriptive
6. ❌ Cannot start with a digit
7. ❌ Cannot contain special characters like `@`, `#`, `$`, `%`, etc.
8. ❌ Cannot be a Python keyword
9. ❌ No spaces are allowed

#### 4.2.3 Valid vs Invalid Identifiers

| Valid Identifiers | Invalid Identifiers | Reason |
|-------------------|---------------------|--------|
| `name` | `2name` | starts with digit |
| `_value` | `total-marks` | contains `-` |
| `age2` | `first name` | contains space |
| `total_marks` | `@value` | special character |
| `student_name` | `class` | keyword |
| `x` | `%marks` | special character |
| `num1` | `my score` | contains space |
| `_count` | `!value` | special character |
| `data2026` | `for` | keyword |
| `calculateSum` | `data#1` | special character |

#### 4.2.4 Examples of Identifiers

```python
student_name = "Aman"      # Descriptive variable name (using underscore)
age = 20                   # Simple variable name
total_marks = 95.5         # Identifier with underscore between words
is_valid = True            # Boolean variable
firstValue = 100           # camelCase identifier
_private = "hidden"        # Identifier starting with underscore
print(student_name)        # Using identifier in print()
```

#### 4.2.5 Different Naming Styles

| Style | Examples | Description |
|-------|----------|-------------|
| `snake_case` | `total_marks`, `student_name` | Words separated by underscore (most common) |
| `camelCase` | `firstValue`, `calculateSum` | First word small, next word capital |
| `PascalCase` | `StudentData`, `CarDetails` | Each word capital (used for classes) |

#### 4.2.6 Case Sensitivity

```python
age = 10
Age = 20
print(age)    # 10
print(Age)    # 20
```

`age` and `Age` are two different identifiers.

#### 4.2.7 Variations in the combined sheet

- Valid list has 9 entries (no `calculateSum`); invalid list has 8 entries (no `for` and `data#1`).
- Examples (5 lines): `student_name = "Aman"`, `age = 20`, `total_marks = 95.5`, `is_valid = True`, `firstValue = 100`, labelled *variable identifier* (×4) and *camelCase identifier*.
- Section "Types of Naming Conventions" – same three styles as above.
- Rules are the same, listed as 5 "can" rules and 4 "cannot" rules.

#### 4.2.8 Key Takeaways

- Identifiers are user-defined names.
- Used for variables, functions, classes, etc.
- Follow naming rules.
- Case sensitive.
- Cannot be a keyword.
- Should be meaningful and descriptive.

---

## 5 Data Types and Type Conversion

*This topic combines 2 source sheets, kept as separate parts below: **Python Data Types**; **Python Type Conversion / Type Casting**.*

### 5.1 Python Data Types

*Source image: [907385142_1145736798215783_373596534573549846_n.png](images/907385142_1145736798215783_373596534573549846_n.png)*

#### 5.1.1 What are Data Types?

- A **data type** specifies the **type of value** a variable can store in Python.
- It tells the interpreter how to store and handle the data in memory.
- Python **automatically detects** the data type (we do not need to declare it).
- Different data types are used for different **purposes**.

#### 5.1.2 Types of Data in Python

```text
Python Data Types
├── Built-in Data Types  : int, float, str, bool, list, tuple, set, dict, NoneType
├── User-defined Data Types : class, Objects
└── Special Data Types   : NoneType
```

#### 5.1.3 Built-in Data Types with Examples

| Data Type | Example (Syntax) | Output | Description |
|-----------|------------------|--------|-------------|
| `int` | `x = 10` | `10` | Integer number (positive, negative, zero) |
| `float` | `pi = 3.14` | `3.14` | Decimal number |
| `str` | `name = "Python"` | `Python` | Text (string) |
| `bool` | `is_valid = True` | `True` | Boolean value (True/False) |
| `list` | `nums = [1, 2, 3]` | `[1, 2, 3]` | Ordered, mutable collection |
| `tuple` | `point = (10, 20)` | `(10, 20)` | Ordered, immutable collection |
| `set` | `s = {1, 2, 3}` | `{1, 2, 3}` | Unordered, unique elements |
| `dict` | `student = {"name": "Ram", "age": 20}` | `{'name': 'Ram', 'age': 20}` | Key-value pairs |
| `NoneType` | `x = None` | `None` | Represents no value |

#### 5.1.4 Integer (int)

- Stores whole numbers (positive, negative and zero).
- No decimal part.

```python
a = 10
b = -5
c = 0
print(a, b, c)
# Output: 10 -5 0
```

#### 5.1.5 Float (float)

- Stores decimal numbers.
- Used for real numbers.

```python
pi = 3.14
temp = 36.5
print(pi)
print(temp)
# Output: 3.14
# Output: 36.5
```

#### 5.1.6 String (str)

- Stores text (characters).
- Can be written in single, double or triple quotes.

```python
name = "Python"
msg = 'Hello!'
text = """Multi
line string"""
print(name)
# Output: Python
```

#### 5.1.7 Boolean (bool)

- Stores `True` or `False`.
- Used in conditions and logical operations.

```python
a = True
b = False
print(a)
print(b)
# Output: True
# Output: False
```

#### 5.1.8 List (list)

- Ordered collection of items.
- Mutable (can be changed).
- Allows duplicate values.

```python
nums = [1, 2, 3, 4]
nums.append(5)
print(nums)
# Output: [1, 2, 3, 4, 5]
```

#### 5.1.9 Tuple (tuple)

- Ordered collection of items.
- Immutable (cannot be changed).
- Allows duplicate values.

```python
point = (10, 20)
print(point[0])
# Output: 10
```

#### 5.1.10 Set (set)

- Unordered collection.
- Mutable (add/remove items).
- Does not allow duplicates.

```python
s = {1, 2, 2, 3}
s.add(4)
print(s)
# Output: {1, 2, 3, 4}
```

#### 5.1.11 Dictionary (dict)

- Stores data in key-value pairs.
- Ordered (Python 3.7+).
- Mutable (can be changed).

```python
student = {
    "name": "Ram",
    "age": 20
}
print(student)
# Output: {'name': 'Ram', 'age': 20}
```

#### 5.1.12 NoneType (None)

- Represents the absence of a value.
- Used when a variable has no value.

```python
x = None
print(x)
# Output: None
```

#### 5.1.13 Type Checking

Use the `type()` function to check the data type.

```python
a = 10
b = 3.14
c = "Hello"
d = True
e = [1, 2, 3]
print(type(a))   # <class 'int'>
print(type(b))   # <class 'float'>
print(type(c))   # <class 'str'>
print(type(d))   # <class 'bool'>
print(type(e))   # <class 'list'>
```

> [!WARNING]
> **Verify:** The source image is cropped below the last `print(type(e))` line; further lines (if any) are not visible.

#### 5.1.14 Flow Diagram of Data Types

```text
Python Data Types
├── Numeric Types   → int, float
├── Text Type       → str
├── Sequence Types  → list, tuple, set
├── Mapping Type    → dict
└── Special Type    → NoneType
```

> [!NOTE]
> The source flow diagram places `set` under "Sequence Types" together with `list` and `tuple`; in standard Python terminology `set` is an unordered collection and not a sequence. The diagram is reproduced here as given in the source.

#### 5.1.15 Key Takeaways

- Python has multiple built-in data types.
- Type is automatically detected.
- Use `type()` to check data type.
- `int` for whole numbers.
- `float` for decimal numbers.
- `str` for text data.
- `bool` for True/False.
- `list`, `tuple`, `set` for collections.
- `dict` for key-value pairs.
- `None` for no value.

### 5.2 Python Type Conversion / Type Casting

*Source image: [914068665_1133145396247751_3718880786210411619_n.png](images/914068665_1133145396247751_3718880786210411619_n.png)*

#### 5.2.1 What is Type Conversion?

- Type conversion (type casting) means **changing a value from one data type to another** data type.
- It is useful when we want to perform operations between different types of data.
- Python provides built-in functions to convert from one type to another.

#### 5.2.2 Types of Type Conversion

```text
Type Conversion
├── Implicit Conversion (Automatic) – done automatically by Python; also called type coercion
└── Explicit Conversion (Manual)    – done manually using built-in functions like int(), float(), str(), list(), etc.
```

#### 5.2.3 Implicit Type Conversion

- Python automatically converts a smaller data type to a larger data type to avoid loss of data.
- This happens when we perform operations between different data types.

```python
a = 10          # int
b = 3.14        # float
c = a + b       # int -> float (automatic)
print(c)        # Output: 13.14
```

#### 5.2.4 Type Hierarchy in Implicit Conversion

| `int` | → | `float` | → | `complex` |
|-------|---|---------|---|-----------|
| Smaller type | | Larger type | | Largest type |

Python automatically converts a smaller type to a larger type in this order: **int → float → complex**.

#### 5.2.5 Explicit Type Conversion (Type Casting)

- In explicit conversion, we manually convert a value from one data type to another using built-in functions.
- Useful when we want to convert the data type according to our requirement.
- **Common functions:** `int()`, `float()`, `str()`, `bool()`, `list()`

#### 5.2.6 Common Type Conversion Functions with Examples

| Function | Converts To | Example | Output | Description |
|----------|-------------|---------|--------|-------------|
| `int()` | Integer | `int(3.8)` | `3` | Converts to integer (decimal part removed) |
| `float()` | Float | `float(10)` | `10.0` | Converts to float |
| `str()` | String | `str(123)` | `'123'` | Converts to string |
| `bool()` | Boolean | `bool(1)` | `True` | Converts to boolean |
| `list()` | List | `list('abc')` | `['a', 'b', 'c']` | Converts to list |
| `tuple()` | Tuple | `tuple([1, 2, 3])` | `(1, 2, 3)` | Converts to tuple |
| `set()` | Set | `set([1, 2, 2, 3])` | `{1, 2, 3}` | Converts to set (removes duplicates) |
| `dict()` | Dictionary | `dict([('a', 1), ('b', 2)])` | `{'a': 1, 'b': 2}` | Converts to dictionary |

#### 5.2.7 Examples of Explicit Conversion

**1. Integer to Float**

```python
a = 10
b = float(a)
print(b)      # Output: 10.0
```

**2. Float to Integer**

```python
a = 3.99
b = int(a)
print(b)      # Output: 3
```

**3. Integer to String**

```python
a = 100
b = str(a)
print(b)
print(type(b))
# Output: '100'
# Output: <class 'str'>
```

**4. String to Integer**

```python
a = "25"
b = int(a)
print(b)
print(type(b))
# Output: 25
# Output: <class 'int'>
```

**5. String to List**

```python
a = "Python"
b = list(a)
print(b)
# Output: ['P', 'y', 't', 'h', 'o', 'n']
```

**6. List to Tuple**

```python
a = [1, 2, 3]
b = tuple(a)
print(b)
# Output: (1, 2, 3)
```

#### 5.2.8 Flow Diagram of Type Conversion

```text
Implicit Conversion (Automatic):
Start → Operation between different data types
      → Python automatically converts smaller type to larger type
      → Result in larger data type → End

Explicit Conversion (Manual):
Start → Choose built-in function (int(), float(), str(), etc.)
      → Pass the value to convert
      → Get value in desired data type → End
```

#### 5.2.9 Important Points

- Implicit conversion is done automatically by Python.
- Explicit conversion is done manually using built-in functions.
- `int()` removes the decimal part (does not round).
- `str()` converts any value to string.
- `list()`, `tuple()`, `set()`, `dict()` change collection types.
- Conversion may fail if data is in an invalid format (e.g., `int("abc")`) *(sentence continues beyond the cropped edge of the source image)*.

#### 5.2.10 Common Type Conversion Errors

**1.**

```python
a = "abc"
b = int(a)     # Invalid
#print(b)
```

```text
ValueError: invalid literal for int() with base 10: 'abc'
```

**2.**

```python
a = 10
b = list(a)    # Invalid
#print(b)
```

```text
TypeError: 'int' object is not iterable
```

#### 5.2.11 Key Takeaways

- Implicit conversion (type coercion) follows int → float → complex.
- Explicit conversion uses `int()`, `float()`, `str()`, `bool()`, `list()`, `tuple()`, `set()`, `dict()`.
- Invalid conversions raise `ValueError` or `TypeError`.

---

## 6 Operators

*This topic combines 3 source sheets, kept as separate parts below: **Python Operators (Overview) – Page 1**; **Python Operators (Detailed) – Page 2**; **Other Operators, Comments and Basic Programs – Page 3**.*

### 6.1 Python Operators (Overview) – Page 1

*Source image: [917045627_1619786622643103_1054252101265427733_n.png](images/917045627_1619786622643103_1054252101265427733_n.png)*

> [!NOTE]
> The Operators material is spread over three pages: **Page 1** (this lecture, sections 1–3), **Page 2** (*Python Operators (Detailed)*, sections 4–6) and **Page 3** (*Other Operators, Comments and Basic Programs*, sections 7–11).

#### 6.1.1 What are Operators?

- Operators are **special symbols** used to perform operations on variables and values.
- They help us perform arithmetic, comparison, logical, assignment, membership, identity and bitwise operations.
- Python provides different types of operators for different purposes.

**Operator Syntax:** `operand1 operator operand2` (Value – Operator – Value)

#### 6.1.2 Types of Operators in Python

| Type | Operators |
|------|-----------|
| Arithmetic Operators | `+ - * / // % **` |
| Comparison Operators | `== != > < >= <=` |
| Logical Operators | `and`, `or`, `not` |
| Assignment Operators | `=`, `+=`, `==` †, `*=`, `/=`, `//=` etc. |
| Membership Operators | `in`, `not in` |
| Identity Operators | `is`, `is not` |
| Bitwise Operators | `&`, `\|`, `^`, `~`, `<<`, `>>` |

> [!WARNING]
> **Verify:** In the source image the assignment operators are printed as `(= += == *= /= //= etc.)`. The third item (`==`, marked †) is a comparison operator; it is most likely meant to be `-=`.

#### 6.1.3 Arithmetic Operators

| Operator | Name | Example | Output | Description |
|----------|------|---------|--------|-------------|
| `+` | Addition | `5 + 3` | 8 | Adds two numbers |
| `-` | Subtraction | `5 - 3` | 2 | Subtracts two numbers |
| `*` | Multiplication | `5 * 3` | 15 | Multiplies two numbers |
| `/` | Division | `5 / 2` | 2.5 | Returns float quotient |
| `//` | Floor Division | `5 // 2` | 2 | Returns integer quotient |
| `%` | Modulus | `5 % 2` | 1 | Returns remainder |
| `**` | Exponentiation | `5 ** 2` | 25 | Returns power |

**Example Code**

```python
a = 10
b = 3
print(a + b)     # 13
print(a - b)     # 7
print(a * b)     # 30
print(a / b)     # 3.333...
print(a // b)    # 3
print(a % b)     # 1
print(a ** b)    # 1000
```

**Flow Diagram (Arithmetic)**

```text
Start → Take two numbers a and b → Perform operation (+, -, *, /, //, %, **)
      → Display result → End
```

#### 6.1.4 Key Takeaways

- Operators are symbols that act on operands (`operand1 operator operand2`).
- Python has seven groups of operators: arithmetic, comparison, logical, assignment, membership, identity and bitwise.
- `/` always returns a float; `//` returns the integer quotient; `%` returns the remainder; `**` is the power operator.

### 6.2 Python Operators (Detailed) – Page 2

*Source image: [912669198_4521595798079271_435637893235892345_n.png](images/912669198_4521595798079271_435637893235892345_n.png)*

> [!NOTE]
> This is **Page 2** of the Operators material (sections 4–6). Page 1 (*Python Operators (Overview)*, sections 1–3) and Page 3 (*Other Operators, Comments and Basic Programs*, sections 7–11) are the neighbouring lectures. The original section numbers (4, 5, 6) are kept below for reference.

#### 6.2.1 Comparison Operators *(source section 4)*

| Operator | Name | Example | Output | Description |
|----------|------|---------|--------|-------------|
| `==` | Equal to | `5 == 3` | False | Checks if values are equal |
| `!=` | Not equal to | `5 != 3` | True | Checks if values are not equal |
| `>` | Greater than | `5 > 3` | True | Checks if left is greater |
| `<` | Less than | `5 < 3` | False | Checks if left is smaller |
| `>=` | Greater than or equal | `5 >= 3` | True | Checks if left is greater or equal |
| `<=` | Less than or equal | `5 <= 3` | False | Checks if left is smaller or equal |

**Example Code**

```python
a = 5
b = 3
print(a == b)    # False
print(a != b)    # True
print(a > b)     # True
print(a < b)     # False
print(a >= b)    # True
print(a <= b)    # False
```

**Flow Diagram (Comparison)**

```text
Start → Take two values a and b → Compare using operator (==, !=, >, <, >=, <=)
      → Result (True/False) → End
```

#### 6.2.2 Logical Operators *(source section 5)*

| Operator | Name | Example | Output | Description |
|----------|------|---------|--------|-------------|
| `and` | Logical AND | `True and False` | False | True if both are True |
| `or` | Logical OR | `True or False` | True | True if at least one is True |
| `not` | Logical NOT | `not True` | False | Reverses the result |

**Example Code**

```python
a = True
b = False
print(a and b)   # False
print(a or b)    # True
print(not a)     # False
```

**Truth Table for Logical Operators**

| A | B | A and B | A or B | not A |
|---|---|---------|--------|-------|
| True | True | True | True | False |
| True | False | False | True | False |
| False | True | False | True | True |
| False | False | False | False | True |

#### 6.2.3 Assignment Operators *(source section 6)*

| Operator | Example | Same as | Description |
|----------|---------|---------|-------------|
| `=` | `x = 5` | `x = 5` | Assigns value |
| `+=` | `x += 3` | `x = x + 3` | Add and assign |
| `-=` | `x -= 3` | `x = x - 3` | Subtract and assign |
| `*=` | `x *= 3` | `x = x * 3` | Multiply and assign |
| `/=` | `x /= 3` | `x = x / 3` | Divide and assign |
| `//=` | `x //= 3` | `x = x // 3` | Floor divide and assign |
| `%=` | `x %= 3` | `x = x % 3` | Modulus and assign |
| `**=` | `x **= 3` | `x = x ** 3` | Power and assign |

**Example Code**

```python
x = 10
x += 5     # 15
x -= 3     # 12
x *= 2     # 24
x /= 6     # 4.0
x //= 2    # 2.0
x %= 2     # 0.0
x **= 3    # 0.0
print(x)
```

> [!NOTE]
> The final `print(x)` output is not visible in the source image (cropped). Following the comments, the value of `x` at the end is `0.0`.

#### 6.2.4 Key Takeaways

- Comparison operators compare two values and return `True` or `False`.
- Logical operators `and`, `or`, `not` combine or reverse Boolean results.
- Assignment operators (`+=`, `-=`, `*=`, `/=`, `//=`, `%=`, `**=`) combine an operation with assignment.

### 6.3 Other Operators, Comments and Basic Programs – Page 3

*Source image: [913283532_1074515708941374_8667906599056243279_n.png](images/913283532_1074515708941374_8667906599056243279_n.png)*

#### 6.3.1 Membership Operators *(source section 7)*

| Operator | Example | Output | Description |
|----------|---------|--------|-------------|
| `in` | `'a' in 'apple'` | True | Returns True if value exists |
| `not in` | `'z' not in 'apple'` | True | Returns True if value does not exist |

**Example Code**

```python
s = "python"
print('p' in s)            # True
print('z' in s)            # False
print('py' in s)           # True
print(5 in [1, 2, 5])      # True
print(3 not in [1, 2, 5])  # True
```

**Explanation**

- Used to check the presence of a value in (string, list, tuple, set, dictionary).
- Returns True or False.

#### 6.3.2 Identity Operators *(source section 8)*

| Operator | Example | Output | Description |
|----------|---------|--------|-------------|
| `is` | `a is b` | True/False | True if both refer to same object |
| `is not` | `a is not b` | True/False | True if both refer to different objects |

**Example Code**

```python
a = [1, 2, 3]
b = a
c = [1, 2, 3]

print(a is b)       # True
print(a is c)       # False
print(a is not c)   # True
```

**Explanation**

- Checks if two variables point to the same memory location (object).
- Useful in object comparison.

#### 6.3.3 Bitwise Operators *(source section 9)*

| Operator | Name | Example | Output | Description |
|----------|------|---------|--------|-------------|
| `&` | AND | `5 & 3` | 1 | Bitwise AND |
| `\|` | OR | `5 \| 3` | 7 | Bitwise OR |
| `^` | XOR | `5 ^ 3` | 6 | Bitwise XOR |
| `~` | NOT | `~5` | -6 | Bitwise NOT |
| `<<` | Left Shift | `5 << 1` | 10 | Shift left by n bits |
| `>>` | Right Shift | `5 >> 1` | 2 | Shift right by n bits |

**Example Code**

```python
a = 5          # 0101
b = 3          # 0011
print(a & b)   # 1   (0001)
print(a | b)   # 7   (0111)
print(a ^ b)   # 6   (0110)
print(~a)      # -6  (Two's complement)
print(a << 1)  # 10  (1010)
print(a >> 1)  # 2   (0010)
```

> [!WARNING]
> **Verify:** In the source image the NOT example is printed as `-5` in the table and `print(-a)` in the code. Since the output is `-6` (two's complement), they have been read as `~5` and `print(~a)`.

**Flow Diagram (Bitwise)**

```text
Start → Take two integers a and b → Apply bitwise operator (&, |, ^, ~, <<, >>)
      → Display result → End
```

#### 6.3.4 Comments in Python *(source section 10)*

- Comments are used to add notes in the code.
- They help to explain the logic and make code readable.
- Comments are ignored by the interpreter.
- Python supports two types of comments:

| Type | Syntax | Example |
|------|--------|---------|
| Single-line comment | `# comment` | `# This is a comment` |
| Multi-line comment | `''' comment '''` or `"""comment"""` | `"""This is a multi-line comment"""` |

#### 6.3.5 Basic Programs in Python *(source section 11)*

1. Print a message
2. Take user input and display
3. Add two numbers
4. Find square and cube of a number
5. Check even or odd
6. Find largest of two numbers
7. Calculate area of circle
8. Convert temperature (C to F)
9. Find sum of first n natural numbers
10. Print a simple pattern (star pattern)

> [!WARNING]
> **Verify:** The list is cropped at the bottom of the source image; item 10 is partly cut and further items (if any) are not visible.

#### 6.3.6 Key Takeaways

- Membership operators (`in`, `not in`) check presence in a sequence or collection.
- Identity operators (`is`, `is not`) compare whether two names refer to the same object.
- Bitwise operators work on the binary representation of integers.
- `#` starts a single-line comment; triple quotes are used for multi-line comments.

---

## 7 Input and Output

*This topic combines 2 source sheets, kept as separate parts below: **Python Input and Output – Overview**; **Python Input and Output – Detailed Guide**.*

### 7.1 Python Input and Output – Overview

*Source image: [911466229_1850593116014153_2429232507120213180_n.png](images/911466229_1850593116014153_2429232507120213180_n.png)*

#### 7.1.1 What is Input and Output?

- **Input** means taking data from the user into the program.
- **Output** means displaying the result to the user.
- In Python, we use built-in functions `input()` for input and `print()` for output.
- Input helps the program to work with different user data and makes it interactive.

#### 7.1.2 Basic Syntax

| | Syntax | Description |
|---|--------|-------------|
| **Input** | `variable = input("message")` | Reads input from the user (Always returns a string) |
| **Output** | `print(value1, value2, ...)` | Displays output on the screen |

#### 7.1.3 Flow Diagram

```text
Start → Take input using input() → Process the data (if needed)
      → Display output using print() → End
```

#### 7.1.4 Simple Input and Output

**Example 1: Single Input**

```python
name = input("Enter your name: ")
print("Hello", name)
```

Output:

```text
Enter your name: Aman
Hello Aman
```

**Example 2: Multiple Input**

```python
age = input("Enter your age: ")
city = input("Enter your city: ")
print("Age:", age)
print("City:", city)
```

Output:

```text
Enter your age: 20
Enter your city: Raipur
Age: 20
City: Raipur
```

#### 7.1.5 Input with Type Conversion

- `input()` always returns a **string**.
- If we need an integer, float, etc., we have to convert it using type casting.

**Example:**

```python
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
sum = num1 + num2
print("Sum:", sum)
```

Output:

```text
Enter first number: 10
Enter second number: 20
Sum: 30
```

**Type Conversion**

| Function | Converts to |
|----------|-------------|
| `int()` | integer |
| `float()` | float |
| `str()` | string |
| `bool()` | boolean |
| `list()` | list |
| `tuple()` | tuple |
| `dict()` | dictionary |

#### 7.1.6 Different Ways to Take Input

| Method | Example | Description |
|--------|---------|-------------|
| Single input | `name = input("Enter name: ")` | Takes one value |
| Multiple input in one line | `a, b = input().split()` | Takes multiple values separated by space |
| Multiple input with type conversion | `a, b = map(int, input().split())` | Takes multiple integer values |
| Input of a list | `lst = list(map(int, input().split()))` | Takes a list of integers |
| Input of a string line | `line = input()` | Takes a full line as string |

#### 7.1.7 Output Formatting

- We can format output in different ways.
- Use commas, `+` operator, or f-strings for better output.

**1. Using Commas**

```python
name = "Aman"
age = 20
print("Name:", name, "Age:", age)
```

Output: `Name: Aman Age: 20`

**2. Using `+` Operator**

```python
name = "Aman"
print("Hello " + name)
```

Output: `Hello Aman`

**3. Using f-strings (Recommended)**

```python
name = "Aman"
age = 20
print(f"My name is {name} and I am {age} years old")
```

Output: `My name is Aman and I am 20 years old`

> [!NOTE]
> In the source image the f-string line is slightly garbled (`f°My name is {name} and I am { {age} years old`). It has been corrected to valid f-string syntax.

#### 7.1.8 Taking Multiple Inputs – Examples

**Example 1: Two Integers**

```python
a, b = map(int, input("Enter two numbers: ").split())
print("a =", a)
print("b =", b)
print("Sum =", a + b)
```

```text
Enter two numbers: 5 7
a = 5
b = 7
Sum = 12
```

**Example 2: List input**

```python
numbers = list(map(int, input("Enter numbers: ").split()))
print("List:", numbers)
print("Sum:", sum(numbers))
```

```text
Enter numbers: 1 2 3 4 5
List: [1, 2, 3, 4, 5]
Sum: 15
```

**Example 3: Input with string and integer**

```python
name, age = input("Enter name and age: ").split()
age = int(age)
print("Name:", name)
print("Age:", age)
print("After 5 years:", age + 5)
```

```text
Enter name and age: Aman 20
Name: Aman
Age: 20
After 5 years: 25
```

#### 7.1.9 Important Points

- `input()` always takes input as a string.
- Use type conversion (`int()`, `float()`, etc.) when needed.
- Use `input().split()` for multiple inputs.
- Use `map()` for multiple inputs with type conversion.
- Use f-strings for clean and readable output.
- Input makes the program interactive.
- Always give a meaningful message to the user.
- *(One more point is cut off in the source image; the visible fragment reads: "we can take input of any data type by converting it…")*

#### 7.1.10 Common Errors in Input and Output

| Error | Example | Reason | Solution |
|-------|---------|--------|----------|
| `ValueError` | `int("abc")` | Cannot convert string to integer | Use valid numeric input |
| `TypeError` | `"Hello" + 5` | Cannot add string and integer | Convert integer to string using `str(5)` |
| `IndexError` | `lst[5]` | Index out of range | Check valid index |

> [!WARNING]
> **Verify:** The table in the source image is cropped; further rows (if any) are not visible.

#### 7.1.11 Key Takeaways

- `input()` reads text (always a string); `print()` displays output.
- Convert input with `int()`, `float()`, etc. when numbers are needed.
- `input().split()` and `map()` take multiple values in one line.
- f-strings are the recommended way to format output.

### 7.2 Python Input and Output – Detailed Guide

*Source image: [915549190_1151093520834320_204868997677325419_n.png](images/915549190_1151093520834320_204868997677325419_n.png)*

**Taking Input from User and Displaying Output** — *"input() takes data from user and print() displays output."*

> [!NOTE]
> This is the second Input/Output sheet. The first one (*Python Input and Output – Overview*) is in the previous lecture; both are kept because each contains unique examples.

#### 7.2.1 What is Input and Output?

- Input means taking data from the user.
- Output means displaying the result on the screen.
- In Python, we use `input()` for input and `print()` for output.
- `input()` always takes input as a string, so we may need to convert it to the desired data type.
- These functions are widely used in real-world programs.

**Syntax:**

```python
input()    # to take input from user
print()    # to display output
```

*Flow:* User Input (keyboard) → Program → Output on Screen.

#### 7.2.2 Basic Input and Output

**Example 1: Taking a string input**

```python
name = input("Enter your name: ")
print("Hello", name)
```

```text
Input:  Enter your name: Aakash
Output: Hello Aakash
```

**Example 2: Taking multiple inputs**

```python
a = input("Enter first value: ")
b = input("Enter second value: ")
print("Values are:", a, b)
```

```text
Input:  Enter first value: 10
        Enter second value: 20
Output: Values are: 10 20
```

#### 7.2.3 Input Function Details

- `input()` always returns data in **string** format.
- We can provide a message (prompt) inside `input()`.
- The user types the value and presses Enter.
- To use the value in calculations, we need to convert it to int, float, or other types.

**Syntax:**

```python
variable = input("message")
```

*Flow:* Display Prompt → User Types Value → Input Stored as String.

**Example:**

```python
city = input("Enter your city: ")
print(type(city))
```

```text
Enter your city: Raipur
<class 'str'>
```

#### 7.2.4 Type Conversion with Input

- `input()` takes input as a string.
- Use `int()`, `float()`, or other functions to convert it into the desired type.
- This is necessary for calculations.

| Function | Convert to | Example |
|----------|-----------|---------|
| `int()` | Integer | `int(input("Enter number: "))` |
| `float()` | Float | `float(input("Enter value: "))` |
| `str()` | String | `str(10)` → `"10"` |
| `bool()` | Boolean | `bool(input())` |
| `list()` | List | `list("abc")` → `['a', 'b', 'c']` |

**Example:**

```python
age = int(input("Enter your age: "))
print("You are", age, "years old")
```

```text
Input:  Enter your age: 20
Output: You are 20 years old
```

#### 7.2.5 Taking Different Types of Input

**Integer Input**

```python
num = int(input("Enter a number: "))
print("Square is:", num**2)
```

```text
Input:  Enter a number: 5
Output: Square is: 25
```

**Float Input**

```python
price = float(input("Enter price: "))
print("Price with GST:", price * 1.18)
```

```text
Input:  Enter price: 100.5
Output: Price with GST: 118.59
```

**Boolean-like Input**

```python
flag = input("Enter (yes/no): ")
if flag.lower() == "yes":
    print("You selected Yes")
```

```text
Input:  Enter (yes/no): yes
Output: You selected Yes
```

#### 7.2.6 Multiple Inputs in One Line

- We can take multiple inputs in a single line using `split()`.
- By default, `split()` separates inputs by space.
- We can also use a different separator.

**Example 1: (Space separated)**

```python
a, b = input("Enter two numbers: ").split()
a = int(a)
b = int(b)
print("Sum:", a + b)
```

```text
Input:  Enter two numbers: 10 20
Output: Sum: 30
```

**Example 2: (Comma separated)**

```python
x, y = input("Enter values (comma separated): ").split(",")
x = int(x)
y = int(y)
print("Values:", x, y)
```

```text
Input:  Enter values (comma separated): 5,15
Output: Values: 5 15
```

#### 7.2.7 Formatted Output with print()

- We can display output in different formats.
- Use commas, f-strings, or `format()` method.
- We can also control the end character.

**Example 1: Using commas**

```python
name = "Aakash"
age = 20
print("Name:", name, "Age:", age)
```

```text
Name: Aakash Age: 20
```

**Example 2: Using f-strings (Recommended)**

```python
name = "Raipur"
marks = 95
print(f"City: {name}, Marks: {marks}")
```

```text
City: Raipur, Marks: 95
```

**Example 3: Using `format()` method**

```python
a = 10
b = 20
print("Sum = {} and Product = {}".format(a+b, a*b))
```

```text
Sum = 10 and Product = 200
```

> [!WARNING]
> **Verify:** In the source image the `format()` arguments are small and unclear, and the printed output shows `Sum = 10`. With `a + b` the sum would be `30`. Please check the original line.

#### 7.2.8 Controlling Output with `end`

- By default, `print()` moves to a new line.
- We can change this using the `end` parameter.

**Example 1: Printing in same line**

```python
print("Hello", end=" ")
print("World")
```

```text
Hello World
```

**Example 2: Custom separator**

```python
print("A", end="-")
print("B", end="-")
print("C")
```

```text
A-B-C
```

**Example 3: New line (default)**

```python
print("Line 1")
print("Line 2")
```

```text
Line 1
Line 2
```

#### 7.2.9 Escape Sequences in Output

- Escape sequences are special characters used in strings.
- They help to format the output.

| Escape Sequence | Meaning |
|-----------------|---------|
| `\n` | New line |
| `\t` | Tab space |
| `\"` | Double quote |
| `\'` | Single quote |
| `\\` | Backslash |
| `\r` | Carriage return |
| `\b` | Backspace |

**Example:**

```python
print("Hello\nPython")
print("Name:\tAakash")
print("He said, \"Python is fun\"")
```

```text
Hello
Python
Name:   Aakash
He said, "Python is fun"
```

#### 7.2.10 User-Friendly Programs

- Use `input()` and `print()` to make interactive programs.
- Show clear messages to the user.
- Example: Calculate area of a circle.

```python
r = float(input("Enter radius: "))
area = 3.1416 * r * r
print("Area of circle:", area)
```

> [!WARNING]
> **Verify:** The Input/Output boxes of this example are cropped at the bottom of the source image.

#### 7.2.11 Common Errors and Solutions

| Error | Cause | Solution |
|-------|-------|----------|
| `ValueError` | Trying to convert non-numeric string to int/float | Check input or use try-except |
| `TypeError` | Using string in mathematical operations | Convert to int/float before calculation |
| *(third row cropped)* | `input()` expects … | Run in proper … |

#### 7.2.12 Key Takeaways

- `input()` takes input from the user.
- `print()` displays output on the screen.
- `input()` always returns a string.
- Use type conversion for calculations.
- Multiple inputs can be taken using `split()`.
- Use f-strings or `format()` for better output.
- Use `end` to control new line behavior.
- Escape sequences help in formatting output.

---

## 8 Python Strings

*Source image: [911722457_1137176358893774_141241251677816285_n.png](images/911722457_1137176358893774_141241251677816285_n.png)*

*Tagline: "Strings are sequence of characters used to store text data."* — **Working with Text Data in Python**

### 8.1 What is a String?

- A string is a sequence of characters enclosed in single quotes (`' '`), double quotes (`" "`) or triple quotes (`''' '''`).
- Strings are **immutable** (cannot be changed).
- They can contain letters, digits, symbols and spaces.
- Strings are widely used for text processing.

| Examples | Valid Strings |
|----------|---------------|
| `'Hello'` | `'A'` |
| `"Python"` | `"123"` |
| `'''Multi-line string'''` | `'Python@2026'` |
| | `' '` (space) |

### 8.2 Creating Strings

- We can create a string using single, double or triple quotes.
- Triple quotes are used for multi-line strings.

```python
s1 = 'Hello'
s2 = "Python"
s3 = '''This is a
multi-line string.'''
print(s1)
print(s2)
print(s3)
```

Output:

```text
Hello
Python
This is a
multi-line string.
```

### 8.3 String Representation

- A string is a sequence of characters with an index.
- Indexing starts from **0**.
- We can also use **negative indexing** (starting from -1).

| Character | P | y | t | h | o | n |
|-----------|---|---|---|---|---|---|
| Positive Index | 0 | 1 | 2 | 3 | 4 | 5 |
| Negative Index | -6 | -5 | -4 | -3 | -2 | -1 |

```python
s = 'Python'
print(s[0])    # first character
print(s[-1])   # last character
```

Output:

```text
P
n
```

### 8.4 Indexing in Strings

- Access individual characters using index.
- Positive index: from left to right (0, 1, 2, …).
- Negative index: from right to left (-1, -2, …).

```python
s = 'Python'
print(s[1])    # 2nd character
print(s[4])    # 5th character
print(s[-2])   # 2nd last character
```

Output:

```text
y
o
o
```

### 8.5 Slicing in Strings

- Extract a part of string using slice operator `[:]`.
- Syntax: `string[start : stop : step]`
- `start`: inclusive, `stop`: exclusive.

```python
s = 'Python Programming'
print(s[0:6])      # Python
print(s[7:18])     # Programming
print(s[:6])       # from start
print(s[7:])       # till end
print(s[::2])      # every 2nd char
```

Output (as shown in the source image):

```text
Python
Programming
Python
Programming
Ptorgamn
```

> [!WARNING]
> **Verify:** The source image shows `Ptorgamn` as the output of `s[::2]`. For `'Python Programming'`, standard Python returns `'Pto rgamn'` (it includes a space character). Please check this line against the original.

### 8.6 String Length

We can find the length of a string using the `len()` function.

```python
s = 'Python'
print(len(s))
s2 = 'Hello World'
print(len(s2))
```

Output:

```text
6
11
```

### 8.7 String Concatenation

We can join (concatenate) two or more strings using the `+` operator.

```python
s1 = 'Hello'
s2 = 'Python'
s3 = s1 + ' ' + s2
print(s3)
```

Output: `Hello Python`

### 8.8 String Repetition

- We can repeat a string using the `*` operator.
- It creates multiple copies of the string.

```python
s = 'Hi '
print(s * 3)
print('-' * 10)
```

Output:

```text
Hi Hi Hi
----------
```

### 8.9 Checking Membership

We can check if a substring exists in a string using `in` and `not in` operators.

```python
s = 'Python Programming'
print('Python' in s)
print('Java' in s)
print('Java' not in s)
```

Output:

```text
True
False
True
```

### 8.10 Common String Methods (1) – Case Conversion Methods

| Method | Description | Example |
|--------|-------------|---------|
| `lower()` | Converts to lowercase | `'PYTHON'.lower()` |
| `upper()` | Converts to uppercase | `'python'.upper()` |
| `capitalize()` | First letter uppercase | `'python'.capitalize()` |
| `title()` | First letter of each word uppercase | `'python programming'.title()` |
| `swapcase()` | Swaps case | `'PyThOn'.swapcase()` |

```python
s = 'Python Programming'
print(s.upper())
print(s.lower())
print(s.title())
```

Output:

```text
PYTHON PROGRAMMING
python programming
Python Programming
```

### 8.11 Common String Methods (2) – Search and Count Methods

| Method | Description | Example |
|--------|-------------|---------|
| `find()` | Returns index (-1 if not found) | `s.find('P')` |
| `index()` | Returns index (error if not found) | `s.index('P')` |
| `count()` | Counts occurrences | `s.count('o')` |
| `startswith()` | Checks starting part | `s.startswith('Py')` |
| `endswith()` | Checks ending part | `s.endswith('ing')` |

```python
s = 'Python Programming'
print(s.find('Pro'))
print(s.count('o'))
print(s.startswith('Py'))
print(s.endswith('ing'))
```

Output:

```text
7
2
True
True
```

### 8.12 Common String Methods (3) – Modify and Split Methods

| Method | Description | Example |
|--------|-------------|---------|
| `replace()` | Replaces substring | `s.replace('Python', 'Java')` |
| `split()` | Splits into list | `s.split()` |
| `strip()` | Removes leading/trailing spaces | `s.strip()` |
| `lstrip()` | Removes leading spaces | `s.lstrip()` |
| `rstrip()` | Removes trailing spaces | `s.rstrip()` |
| `join()` | Joins list into string | `'-'.join(['a', 'b', 'c'])` |

```python
s = '  Python  '
print(s.strip())
s2 = 'a b c'
print(s2.split())
print('-'.join(['a', 'b', 'c']))
```

Output:

```text
Python
['a', 'b', 'c']
a-b-c
```

### 8.13 String Formatting

We can format strings using different methods:

1. **f-strings** (recommended)
2. **`format()` method**
3. **`%` operator** (older method)

```python
name = 'Aakash'
age = 20
print(f"Name: {name}, Age: {age}")
```

Output:

```text
Name: Aakash, Age: 20
```

**Using `format()` method:**

```python
print("Name: {}, Age: {}".format(name, age))
```

Output: `Name: Aakash…` *(cut off in the source image)*

> [!WARNING]
> **Verify:** The `format()` example and its output are cropped at the bottom of the source image; the code line above is reconstructed from the visible fragment.

### 8.14 Useful String Methods (More)

| Method | Description | Example |
|--------|-------------|---------|
| `isalpha()` | Checks if all characters are alphabets | `'abc'.isalpha()` |
| `isdigit()` | Checks if all are digits | `'123'.isdigit()` |
| `isalnum()` | Checks if alphanumeric | `'abc123'.isalnum()` |
| `isspace()` | Checks if all are spaces | `'   '.isspace()` |
| `isupper()` | Checks if all uppercase | `'ABC'.isupper()` |
| `islower()` | Checks if all lowercase | `'abc'.islower()` |

```python
s = 'Python123'
print(s.isalnum())
```

Output: `True`

### 8.15 Key Takeaways

- String is a sequence of characters.
- Strings are immutable.
- Use single, double or triple quotes.
- Indexing starts from 0 and supports negative indexing.
- Slicing helps to extract a part of string.
- `len()` gives the length of string.
- `+` is used for concatenation, `*` for repetition.
- `in` and `not in` check membership.
- Python provides many useful string methods.
- Strings are widely used in real-world programs *(the sentence continues beyond the cropped edge of the source image)*.

---

## 9 Conditional Statements and Loops

*This topic combines 5 source sheets, kept as separate parts below: **Python Conditional Statements (Part 1)**; **Python Conditional Statements (Part 2)**; **Python Loops (Part 1)**; **Python Loops (Part 2)**; **Python Conditional Statements and Loops (Summary)**.*

### 9.1 Python Conditional Statements (Part 1)

*Source image: [911054339_1692674209249008_569622205817745419_n.png](images/911054339_1692674209249008_569622205817745419_n.png)*

**Make Decisions in a Program**

#### 9.1.1 What are Conditional Statements?

- Conditional statements are used to make decisions in a program.
- They allow the program to execute a block of code based on a condition (True/False).
- In Python, we use `if`, `if-else` and `if-elif-else`.
- Conditions are based on comparison and logical operators.
- They help in making the program **dynamic** and **smart**.

> [!IMPORTANT]
> The program checks a condition and decides which block of code to execute.

#### 9.1.2 Syntax of if Statement

```python
if condition:
    # block of code
    # executed when
    # condition is True
```

**Flow Diagram**

```text
Start → Is condition True?
          ├── Yes → Execute if block ─┐
          └── No  → Skip if block ────┴→ End
```

#### 9.1.3 if Statement – Example

**Example 1: Check adult or not**

```python
age = 18
if age >= 18:
    print("You are an adult")
```

Output:

```text
You are an adult
```

**Flow Diagram:** Start → `age >= 18 ?` → Yes: Print "You are an adult" / No: (skip) → End

#### 9.1.4 if Statement – Another Example

**Example 2: Check positive number**

```python
num = 10
if num > 0:
    print("Positive number")
```

Output:

```text
Positive number
```

**Flow Diagram:** Start → `num > 0 ?` → Yes: Print "Positive number" / No: (skip) → End

#### 9.1.5 if-else Statement

**Syntax:**

```python
if condition:
    # block if True
else:
    # block if False
```

**Flow Diagram**

```text
Start → Is condition True?
          ├── Yes → Execute if block ───┐
          └── No  → Execute else block ─┴→ End
```

#### 9.1.6 if-else Statement – Example

**Example: Check even or odd**

```python
num = int(input("Enter a number: "))
if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")
```

Output:

```text
Enter a number: 7
Odd number
```

#### 9.1.7 if-else Statement – Another Example

**Example: Check largest of two numbers**

```python
a = 15
b = 8
if a > b:
    print("a is larger")
else:
    print("b is larger")
```

Output:

```text
a is larger
```

#### 9.1.8 Indentation in Conditional Statements

- Indentation is very important in Python.
- All statements inside the `if` and `else` blocks must be indented at the same level.
- Python uses indentation (spaces) to define blocks of code.

**Correct Indentation**

```python
if x > 3:
    print("Correct")
    print("Inside if block")
```

**Incorrect Indentation**

```python
if x > 3:
    print("Wrong")
  print("Indentation Error")
```

> [!NOTE]
> In the source image, the second line of the incorrect example is indented less than the first. The exact spacing is not legible; the example above is representative.

#### 9.1.9 if-else with Input – Example

```python
marks = int(input("Enter marks: "))
if marks >= 40:
    print("Pass")
else:
    print("Fail")
```

Output:

```text
Enter marks: 82
Pass
```

#### 9.1.10 Multiple Conditions using if-else (Basic)

```python
num = int(input("Enter a number: "))
if num > 0:
    print("Positive")
else:
    print("Negative or Zero")
```

Output:

```text
Enter a number: -5
Negative or Zero
```

#### 9.1.11 Key Takeaways

- Conditional statements allow decision making.
- `if` executes when condition is True.
- `if-else` provides two possible paths.
- Condition can be a single statement or a complex expression.
- Python executes only one block (`if` or `else`) based on the condition.
- Use meaningful conditions to make programs dynamic.
- Memory hook from the source: **THINK → CHECK → DECIDE**.

> [!WARNING]
> **Verify:** The Key Points section is cropped at the bottom of the source image; one or more further points (left column) may be missing.

### 9.2 Python Conditional Statements (Part 2)

*Source image: [912910042_1772812510497511_2441295447055638473_n.png](images/912910042_1772812510497511_2441295447055638473_n.png)*

**Multiple Conditions and Nested Conditions**

#### 9.2.1 if-elif-else Statement

- Used when we have **multiple** conditions to check.
- Conditions are checked from top to bottom.
- The first **True** condition is executed.
- If none of the conditions are True, the **else** block is executed.

**Syntax:**

```python
if condition1:
    # block 1
elif condition2:
    # block 2
elif condition3:
    # block 3
else:
    # block 4
```

**Flow Diagram**

```text
Start → condition1 True? ── Yes → Block 1 ─┐
            │ No                            │
        condition2 True? ── Yes → Block 2 ─┤
            │ No                            ├→ End
        condition3 True? ── Yes → Block 3 ─┤
            │ No                            │
        Else Block ────────────────────────┘
```

#### 9.2.2 Example of if-elif-else

**Example: Find Grade**

```python
marks = int(input("Enter marks: "))
if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
elif marks >= 60:
    print("Grade C")
elif marks >= 40:
    print("Grade D")
else:
    print("Grade F")
```

Output (Example):

```text
Enter marks: 82
Grade B
```

**Explanation:**

- If marks ≥ 90 → Grade A
- If marks ≥ 75 → Grade B
- If marks ≥ 60 → Grade C
- If marks ≥ 40 → Grade D
- Otherwise → Grade F

#### 9.2.3 Check Eligibility Example

```python
age = int(input("Enter age: "))
if age >= 18:
    print("Eligible to vote")
elif age >= 13:
    print("Teenager")
else:
    print("Not eligible")
```

Output (Example):

```text
Enter age: 15
Teenager
```

#### 9.2.4 Nested if Statement

- An `if` statement inside another `if` statement.
- Used when conditions are dependent.
- Helps in checking multiple conditions step by step.

**Syntax:**

```python
if condition1:
    if condition2:
        # block
    else:
        # block
else:
    # block
```

**Flow Diagram**

```text
Start → condition1 True?
          ├── Yes → condition2 True?
          │            ├── Yes → Block 1 ─┐
          │            └── No  → Block 2 ─┤
          └── No  → Block 3 ─────────────┴→ End
```

#### 9.2.5 Nested if Example: Check Age Category

```python
age = int(input("Enter age: "))

if age >= 18:
    if age >= 60:
        print("Senior Citizen")
    else:
        print("Adult")
else:
    if age >= 13:
        print("Teenager")
    else:
        print("Child")
```

Output (Example):

```text
Enter age: 65
Senior Citizen
```

#### 9.2.6 Nested if with Multiple Conditions

```python
num = int(input("Enter a number: "))
if num >= 0:
    if num == 0:
        print("Zero")
    else:
        print("Positive Number")
else:
    print("Negative Number")
```

Output (Example):

```text
Enter a number: -5
Negative Number
```

> [!WARNING]
> **Verify:** In the source image the first condition is printed as `if num >= 3::` (unclear/typo). It is read here as `if num >= 0:` because this matches the program logic and the printed output. Please confirm against the original.

#### 9.2.7 Nested if-elif-else Example

```python
marks = int(input("Enter marks: "))
if marks >= 75:
    if marks >= 90:
        print("Excellent")
    else:
        print("Good")
elif marks >= 50:
    print("Average")
else:
    print("Fail")
```

Output (Example):

```text
Enter marks: 82
Good
```

**Explanation:**

- If marks ≥ 90 → Excellent
- If 75 ≤ marks < 90 → Good
- If 50 ≤ marks < 75 → Average
- If marks < 50 → Fail

#### 9.2.8 Real-life Example: Login System

```python
username = input("Enter username: ")
password = input("Enter password: ")
if username == "admin":
    if password == "1234":
        print("Login Successful")
    else:
        print("Incorrect Password")
else:
    print("Invalid Username")
```

Output (Example):

```text
Enter username: admin
Enter password: 1234
Login Successful
```

#### 9.2.9 Key Takeaways

- `if-elif-else` is used for multiple conditions.
- Conditions are checked from top to bottom.
- Nested `if` is used when conditions are dependent.
- Indentation is very important in nested statements.
- `else` block is optional.
- We can nest `if-elif-else` inside each other.
- Helps in handling complex conditions.
- Python uses indentation (spaces) to define blocks *(sentence cropped in the source image)*.
- Memory hook from the source: **CONDITIONS CREATE LOGIC IN YOUR PROGRAM!**

### 9.3 Python Loops (Part 1)

*Source image: [916323326_997408003435596_1955084023146934269_n.png](images/916323326_997408003435596_1955084023146934269_n.png)*

**Repeat a Block of Code Multiple Times** — *"Loops make your program short, efficient and powerful."*

#### 9.3.1 What are Loops?

- Loops are used to execute a block of code **repeatedly**.
- They help in performing **repetitive tasks** easily.
- Python has two types of loops:
  1. **`for` loop** – used when the number of iterations is known.
  2. **`while` loop** – used when the number of iterations is not known.

#### 9.3.2 Types of Loops

```text
Python Loops
├── for loop   – Used when iterations are known
└── while loop – Used when iterations are not known
```

#### 9.3.3 Flow Diagram of Loop (General)

```text
Start → Condition True?
          ├── Yes → Execute block of code → (back to the condition)
          └── No  → Exit loop → End
```

#### 9.3.4 for Loop (Basic)

**Syntax:**

```python
for variable in sequence:
    # block of code
```

**Example:**

```python
for i in range(5):
    print(i)
```

```text
0
1
2
3
4
```

**Flow Diagram:** Start → Initialize i → Is i in sequence? → Yes: Execute block of code → Increment i (repeat) / No: End.

#### 9.3.5 for Loop with range()

**Syntax:**

```python
for variable in range(start, stop, step):
    # block of code
```

**Example 1: `range(stop)`**

```python
for i in range(5):
    print(i)
```

Output: `0 1 2 3 4` (one per line)

**Example 2: `range(start, stop)`**

```python
for i in range(2, 6):
    print(i)
```

Output: `2 3 4 5`

**Example 3: `range(start, stop, step)`**

```python
for i in range(1, 10, 2):
    print(i)
```

Output: `1 3 5 7 9`

#### 9.3.6 Iterating over Different Sequences

**List**

```python
fruits = ["apple", "banana", "mango"]
for fruit in fruits:
    print(fruit)
```

Output: `apple` / `banana` / `mango`

**Tuple**

```python
nums = (10, 20, 30)
for n in nums:
    print(n)
```

Output: `10` / `20` / `30`

**String**

```python
for ch in "Python":
    print(ch)
```

Output: `P` / `y` / `t` / `h` / `o` / `n` (one character per line)

#### 9.3.7 Nested for Loop

**Syntax:**

```python
for i in range(m):
    for j in range(n):
        # block of code
```

**Example:**

```python
for i in range(3):
    for j in range(4):
        print(i, j)
```

```text
0 0
0 1
0 2
0 3
1 0
1 1
1 2
1 3
2 0
2 1
2 2
2 3
```

**Flow Diagram:** Start → Outer loop (i) → Inner loop (j) → Execute block of code → Next j → Next i → End.

#### 9.3.8 Common Examples using for Loop

**1. Sum of first n numbers**

```python
n = int(input("Enter n: "))
sum = 0
for i in range(1, n+1):
    sum += i
print("Sum =", sum)
```

```text
Enter n: 5
Sum = 15
```

**2. Factorial of a number**

```python
n = int(input("Enter n: "))
fact = 1
for i in range(1, n+1):
    fact *= i
print("Factorial =", fact)
```

```text
Enter n: 5
Factorial = 120
```

**3. Print multiplication table**

```python
n = int(input("Enter n: "))
for i in range(1, 11):
    print(n, "x", i, "=", n*i)
```

Output (n = 3):

```text
3 x 1 = 3
3 x 2 = 6
3 x 3 = 9
...
3 x 10 = 30
```

#### 9.3.9 Looping with Step Value

**Example: Print even numbers**

```python
for i in range(0, 10, 2):
    print(i)
```

Output: `0 2 4 6 8`

**Example: Print odd numbers**

```python
for i in range(1, 10, 2):
    print(i)
```

Output: `1 3 5 7 9`

#### 9.3.10 Key Takeaways

- `for` loop is used when the number of iterations is known.
- `range()` is used to generate a sequence of numbers.
- We can iterate over lists, tuples, strings, ranges, etc.
- Nested `for` loops are used for multi-dimensional data (like matrices, patterns).
- The loop variable automatically takes values from the sequence.
- Indentation is important inside the loop.
- `for` loop can be used for calculations, patterns, searching, etc.
- Use meaningful variable names.
- Python's `for` loop is simple and easy to use.
- Memory hook from the source: **PRACTICE LOOPS TO WRITE EFFICIENT PROGRAMS** *(partly cropped)*.

### 9.4 Python Loops (Part 2)

*Source image: [913462751_1194719699554271_5691050946260098258_n.png](images/913462751_1194719699554271_5691050946260098258_n.png)*

**Control Statements, while Loop, Loop else and Pattern Programs** — *"Small loops create big possibilities."*

#### 9.4.1 while Loop

- The `while` loop is used to execute a block of code as long as the condition is **True**.
- The number of iterations is **not known in advance**.
- It is useful when we don't know how many times to repeat.

**Syntax:**

```python
while condition:
    # block of code
```

**Example: Print numbers from 1 to 5**

```python
i = 1
while i <= 5:
    print(i)
    i += 1
```

```text
1
2
3
4
5
```

**Flow Diagram:** Start → Initialize variable → Is condition True? → Yes: Execute block of code → Update variable (repeat) / No: End.

#### 9.4.2 break Statement

- The `break` statement is used to **terminate the loop immediately** when a condition is met.
- It exits from the nearest enclosing loop.

**Syntax:** `break`

**Example: Stop loop when number is 5**

```python
for i in range(10):
    if i == 5:
        break
    print(i)
```

```text
0
1
2
3
4
```

**Flow Diagram:** Start → For / While Loop → Is break condition True? → Yes: Exit loop immediately → End / No: continue the loop.

#### 9.4.3 continue Statement

- The `continue` statement is used to **skip the current iteration** and continue with the next iteration.

**Syntax:** `continue`

**Example: Skip even numbers**

```python
for i in range(1, 6):
    if i % 2 == 0:
        continue
    print(i)
```

```text
1
3
5
```

**Flow Diagram:** Start → For / While Loop → Is continue condition True? → Yes: Skip current iteration → Next iteration / No: Execute remaining code → Next iteration → End.

#### 9.4.4 pass Statement

- The `pass` statement does nothing.
- It is used as a placeholder when a statement is required syntactically but you don't want to write any code yet.

**Syntax:** `pass`

**Example: Empty loop using pass**

```python
for i in range(5):
    pass
print("Loop completed")
```

```text
Loop completed
```

**Use Cases:**

1. **Empty functions**

   ```python
   def my_function():
       pass
   ```

2. **Empty classes**

   ```python
   class MyClass:
       pass
   ```

3. **Empty loop**

   ```python
   for i in range(5):
       pass
   ```

4. To avoid indentation error when code is not written yet.

#### 9.4.5 Loop else Statement

- The `else` block with a loop executes when the loop completes normally (i.e., it is **not terminated by a `break`**).
- If the loop is terminated by `break`, the `else` block is skipped.

**Example 1: else without break**

```python
for i in range(3):
    print(i)
else:
    print("Loop completed")
```

```text
0
1
2
Loop completed
```

**Example 2: else with break**

```python
for i in range(3):
    if i == 1:
        break
    print(i)
else:
    print("Loop completed")
```

```text
0
```

**Flow Diagram (Loop else):** Start → For / While Loop → Is condition True? → Yes: Execute block of code → Is break used? → Yes: Skip else block / No: continue loop → When the condition becomes False (No): Execute else block → End.

#### 9.4.6 Nested Loops

- A loop inside another loop is called a **nested loop**.
- Used for patterns, tables and multi-dimensional data.

**Example: Print multiplication table (1 to 3)**

```python
for i in range(1, 4):
    for j in range(1, 4):
        print(i, "x", j, "=", i*j)
    print()
```

```text
1 x 1 = 1
1 x 2 = 2
1 x 3 = 3

2 x 1 = 2
2 x 2 = 4
2 x 3 = 6

3 x 1 = 3
3 x 2 = 6
3 x 3 = 9
```

#### 9.4.7 Pattern Programs

*Common patterns using loops*

**1. Right Triangle**

```python
n = 5
for i in range(1, n+1):
    print("*" * i)
```

```text
*
**
***
****
*****
```

**2. Inverted Triangle**

```python
n = 5
for i in range(n, 0, -1):
    print("*" * i)
```

```text
*****
****
***
**
*
```

**3. Number Pattern**

```python
n = 5
for i in range(1, n+1):
    print(i, end=" ")
```

```text
1 2 3 4 5
```

**4. Pyramid Pattern**

```python
n = 5
for i in range(1, n+1):
    print(" " * (n-i) + "*" * i)
```

```text
    *
   **
  ***
 ****
*****
```

> [!NOTE]
> The pyramid output in the source image is small; the output above is what the printed code produces.

**5. Floyd's Triangle**

```python
n = 5
num = 1
for i in range(1, n+1):
    for j in range(i):
        print(num, end=" ")
        num += 1
    print()
```

```text
1
2 3
4 5 6
7 8 9 10
11 12 13 14 15
```

#### 9.4.8 Key Takeaways

- `while` loop is used when the number of iterations is not known.
- `break` terminates the loop immediately.
- `continue` skips the current iteration.
- `pass` does nothing (placeholder).
- Nested loops are useful for patterns and multi-dimensional data.
- `range()` is commonly used with `for` loop.
- Loops make the program short, efficient and powerful.
- Memory hook from the source: **PRACTICE LOOPS TO BUILD BETTER** *(partly cropped)*.

> [!WARNING]
> **Verify:** The Key Points section of the source image is cropped; one point (appears to be about meaningful variable names or `pass`) is only partly visible.

### 9.5 Python Conditional Statements and Loops (Summary)

*Source image: [916621664_4625806814354734_3759864615385362655_n.png](images/916621664_4625806814354734_3759864615385362655_n.png)*

**Decision Making and Repetition in Python** — *"Used to make decisions and repeat a block of code."*

#### 9.5.1 What are Conditional Statements?

- Conditional statements are used to execute different blocks of code based on a condition.
- They help in decision making.
- Conditions return either `True` or `False`.
- Commonly used: `if`, `if-else`, `if-elif-else`.

**Syntax (if):**

```python
if condition:
    # code to execute
    # if condition is True
```

**Flow:** Start → Condition → True: Execute Block / False: Skip Block → Next.

#### 9.5.2 if Statement

Executes a block of code if the condition is True.

```python
if condition:
    # code to execute
```

**Example:**

```python
age = 18
if age >= 18:
    print("You are eligible to vote")
```

```text
You are eligible to vote
```

#### 9.5.3 if-else Statement

Executes one block if the condition is True and another block if False.

```python
if condition:
    # code if True
else:
    # code if False
```

**Example:**

```python
age = 16
if age >= 18:
    print("You can vote")
else:
    print("You cannot vote")
```

```text
You cannot vote
```

#### 9.5.4 if-elif-else Statement

- Used to check multiple conditions sequentially.
- Executes the first block with `True` condition.

```python
if condition1:
    # block 1
elif condition2:
    # block 2
else:
    # block 3
```

**Example:**

```python
marks = 75
if marks >= 90:
    print("Grade A")
elif marks >= 60:
    print("Grade B")
else:
    print("Grade C")
```

```text
Grade B
```

#### 9.5.5 Nested if Statement

- An `if` statement inside another `if` statement.
- Used for complex conditions.

```python
if condition1:
    if condition2:
        # block
    else:
        # block
else:
    # block
```

**Example:**

```python
age = 20
if age >= 18:
    if age >= 60:
        print("Senior Citizen")
    else:
        print("Adult")
else:
    print("Minor")
```

```text
Adult
```

#### 9.5.6 Flowchart of Nested if

```text
Start → Condition 1 True?
          ├── True  → Condition 2 True?
          │              ├── True  → Block A ─┐
          │              └── False → Block B ─┤
          └── False → Block C ────────────────┴→ Next
```

*Example condition:* 1. `age >= 18 ?` 2. `age >= 60 ?` — the output depends on both conditions.

#### 9.5.7 for Loop

- Used to iterate over a sequence (list, tuple, string, range, etc.).
- Executes a block multiple times.

```python
for variable in sequence:
    # code to execute
```

**Example:**

```python
for i in range(1, 6):
    print(i)
```

Output: `1 2 3 4 5` (one per line)

#### 9.5.8 while Loop

- Repeats a block of code as long as the condition is True.
- Useful when the number of iterations is not fixed.

```python
while condition:
    # code to execute
```

**Example:**

```python
i = 1
while i <= 5:
    print(i)
    i += 1
```

Output: `1 2 3 4 5` (one per line)

#### 9.5.9 Nested Loops

- A loop inside another loop.
- Useful for patterns and matrix operations.

**Example:**

```python
for i in range(1, 4):
    for j in range(1, 4):
        print(i, j, end=" ")
    print()
```

Output (as shown in the source image):

```text
1 1 2 3
2 1 2 3
3 1 2 3
```

> [!WARNING]
> **Verify:** For the code shown, standard Python prints `1 1 1 2 1 3` on the first row (each `i, j` pair). The output in the image (`1 1 2 3 / 2 1 2 3 / 3 1 2 3`) would result from printing `i` once and then `j` values. Please check against the original.

#### 9.5.10 range() Function

- Generates a sequence of numbers.
- Syntax: `range(start, stop, step)`

**Example:**

```python
for i in range(2, 10, 2):
    print(i)
```

Output (as shown in the source image): `2 4 6 5`

> [!WARNING]
> **Verify:** The last value looks like `5` in the image; the correct output of this code is `2 4 6 8`.

**Note:**

- `start`: starting value (inclusive)
- `stop`: ending value (exclusive)
- `step`: difference between numbers (default is 1)

#### 9.5.11 Loop Control Statements

- `break` → Terminates the loop.
- `continue` → Skips current iteration.
- `pass` → Does nothing (placeholder).

| Statement | Description | Example |
|-----------|-------------|---------|
| `break` | Exits the loop completely. | `for i in range(5):` / `if i == 3:` / `break` / `print(i)` |
| `continue` | Skips the current iteration. | `for i in range(5):` / `if i == 3:` / `continue` / `print(i)` |
| `pass` | Does nothing. Used as a placeholder. | `for i in range(5):` / `pass` |

#### 9.5.12 Loop else

The `else` block with a loop executes when the loop completes normally (without `break`).

**Example 1:**

```python
for i in range(3):
    print(i)
else:
    print("Loop completed")
```

```text
0
1
2
Loop completed
```

**Example 2:**

```python
for i in range(3):
    if i == 1:
        break
    print(i)
else:
    print("This will not run")
```

```text
0
This will not run (not printed)
```

> [!NOTE]
> In Example 2 the image labels the second line as "(not printed)": the `else` block is skipped because the loop ended with `break`, so only `0` is printed.

#### 9.5.13 Pattern Programs (Using Loops)

**Example 1: Right-Angled Triangle**

```python
for i in range(1, 6):
    print("*" * i)
```

```text
*
**
***
```

**Example 2: Inverted Triangle**

```python
for i in range(5, 0, -1):
    print("*" * i)
```

```text
*****
****
***
```

**Example 3: Number Pattern**

```python
for i in range(1, 6):
    print(" ".join(str(j) for j in range(1, i+1)))
```

```text
1
1 2
1 2 3
```

> [!WARNING]
> **Verify:** The outputs of these examples are cropped after the first three rows in the source image, and the code of Example 3 is garbled in the image (`for for j in range(1, i+1)`); it is reconstructed above.

#### 9.5.14 Common Examples

1. Sum of first n natural numbers.
2. Factorial of a number.
3. Check prime number.
4. Print multiplication table.
5. Reverse a number.
6. Count digits in a number.
7. Find Fibonacci series.
8. Check palindrome. *(list may continue beyond the cropped edge)*

#### 9.5.15 Key Takeaways

- Conditional statements help in decision making.
- Use `if`, `if-else`, `if-elif-else` for multiple conditions.
- Loops are used to repeat a block of code.
- `for` loop is used with a sequence.
- `while` loop runs until the condition is False.
- `break`, `continue` and `pass` control the loop execution.
- `else` with loop executes when no `break` occurs.

---

## 10 Python Pattern Programs

*Source image: [913163566_1831168741770324_3631393540688622593_n.png](images/913163566_1831168741770324_3631393540688622593_n.png)*

**Using Loops (for, while, nested loops)** — *"Practice Patterns to Build Logic"*

> [!NOTE]
> This lecture uses `for` and `while` loops; the loop syntax is covered in the preceding lectures *Python Loops (Part 1)* and *Python Loops (Part 2)*.

### 10.1 What are Pattern Programs?

- Pattern programs are used to print different shapes using symbols, numbers or characters.
- They help in understanding the use of **nested loops**.
- Improve logical thinking and problem-solving skills.
- Common in interviews and competitive exams.

### 10.2 General Structure using for Loop

**Syntax:**

```python
for i in range(n):
    for j in range(n):
        # print pattern
```

**Flow Diagram:** Start → Outer loop (i) → Inner loop (j) → Print pattern → End

### 10.3 General Structure using while Loop

**Syntax:**

```python
i = 1
while i <= n:
    j = 1
    while j <= n:
        # print pattern
        j += 1
    i += 1
```

### 10.4 Star Patterns

**1. Right Triangle**

```python
n = 5
for i in range(1, n+1):
    for j in range(i):
        print("*", end=" ")
    print()
```

```text
*
* *
* * *
* * * *
* * * * *
```

**2. Inverted Triangle**

```python
n = 5
for i in range(n, 0, -1):
    for j in range(i):
        print("*", end=" ")
    print()
```

```text
* * * * *
* * * *
* * *
* *
*
```

**3. Pyramid**

```python
n = 5
for i in range(1, n+1):
    for j in range(n-i):
        print(" ", end=" ")
    for j in range(2*i-1):
        print("*", end=" ")
    print()
```

```text
        *
      * * *
    * * * * *
  * * * * * * *
* * * * * * * * *
```

**4. Inverted Pyramid**

```python
n = 5
for i in range(n, 0, -1):
    for j in range(n-i):
        print(" ", end=" ")
    for j in range(2*i-1):
        print("*", end=" ")
    print()
```

```text
* * * * * * * * *
  * * * * * * *
    * * * * *
      * * *
        *
```

**5. Diamond Pattern**

```python
n = 5
for i in range(1, n+1):
    for j in range(n-i):
        print(" ", end=" ")
    for j in range(2*i-1):
        print("*", end=" ")
    print()
for i in range(n-1, 0, -1):
    for j in range(n-i):
        print(" ", end=" ")
    for j in range(2*i-1):
        print("*", end=" ")
    print()
```

```text
        *
      * * *
    * * * * *
  * * * * * * *
* * * * * * * * *
  * * * * * * *
    * * * * *
      * * *
        *
```

> [!NOTE]
> The star-pattern output drawings in the source image are small and approximate (the Pyramid and Inverted Pyramid are drawn in a compact form). The outputs above show the shapes that the printed code produces; the code is as shown in the image.

### 10.5 Number Patterns

**1. Number Triangle**

```python
n = 5
for i in range(1, n+1):
    for j in range(1, i+1):
        print(j, end=" ")
    print()
```

```text
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
```

**2. Inverted Number Triangle**

```python
n = 5
for i in range(n, 0, -1):
    for j in range(1, i+1):
        print(i, end=" ")
    print()
```

```text
1 2 3 4 5
1 2 3 4
1 2 3
1 2
1
```

> [!WARNING]
> **Verify:** The source image shows `print(i, end=" ")` in this program, but the output printed beside it (`1 2 3 4 5 / 1 2 3 4 / …`) is what `print(j, end=" ")` would produce. Please check the original line.

**3. Floyd's Triangle**

```python
n = 5
num = 1
for i in range(1, n+1):
    for j in range(i):
        print(num, end=" ")
        num += 1
    print()
```

```text
1
2 3
4 5 6
7 8 9 10
11 12 13 14 15
```

**4. Pascal's Triangle**

```python
n = 5
for i in range(n):
    for j in range(n-i-1):
        print(" ", end=" ")
    num = 1
    for j in range(i+1):
        print(num, end=" ")
        num = num * (i - j) // (j + 1)
    print()
```

```text
        1
      1 1
    1 2 1
  1 3 3 1
1 4 6 4 1
```

**5. Square Number Pattern**

```python
n = 5
for i in range(1, n+1):
    for j in range(1, n+1):
        print(i, end=" ")
    print()
```

```text
1 1 1 1 1
2 2 2 2 2
3 3 3 3 3
4 4 4 4 4
5 5 5 5 5
```

> [!NOTE]
> In the source image, the Square Number Pattern output is shown with each row repeating the row number five times.

### 10.6 Character Patterns

**1. Alphabet Triangle**

```python
n = 5
for i in range(1, n+1):
    for j in range(i):
        print(chr(64 + j + 1), end=" ")
    print()
```

```text
A
A B
A B C
A B C D
A B C D E
```

**2. Repeated Alphabet**

```python
n = 5
for i in range(1, n+1):
    for j in range(i):
        print(chr(64 + i), end=" ")
    print()
```

```text
A
B B
C C C
D D D D
E E E E E
```

**3. Inverted Alphabet Triangle**

```python
n = 5
for i in range(n, 0, -1):
    for j in range(i):
        print(chr(64 + j + 1), end=" ")
    print()
```

```text
A B C D E
A B C D
A B C
A B
A
```

**4. Diamond Alphabet**

```python
n = 5
for i in range(1, n+1):
    for j in range(n-i):
        print(" ", end=" ")
    for j in range(i):
        print(chr(64 + j + 1), end=" ")
    print()
for i in range(n-1, 0, -1):
    for j in range(n-i):
        print(" ", end=" ")
    for j in range(i):
        print(chr(64 + j + 1), end=" ")
    print()
```

```text
        A
      A B
    A B C
  A B C D
A B C D E
  A B C D
    A B C
      A B
        A
```

> [!WARNING]
> **Verify:** The Diamond Alphabet code is printed in very small text in the source image. The code above is the closest legible reading; the output shape follows the image.

**5. Hollow Square**

```python
n = 5
for i in range(n):
    for j in range(n):
        if i == 0 or i == n-1 or j == 0 or j == n-1:
            print("*", end=" ")
        else:
            print(" ", end=" ")
    print()
```

```text
* * * * *
*       *
*       *
*       *
* * * * *
```

### 10.7 Key Takeaways

- Use nested loops for pattern programs.
- Control the number of rows and columns using loops.
- Use spaces for proper alignment.
- You can print numbers, characters or symbols.
- *(Further key points are cropped in the source image.)*

### 10.8 Practice Questions

1. Print a hollow triangle.
2. Print a butterfly pattern.
3. Print a number pyramid.
4. Print a mirrored right triangle.
5. *(Further questions, if any, are cropped in the source image.)*

### 10.9 Tips for Better Patterns

- Always visualize the pattern before coding.
- Use nested loops with proper indentation.
- Focus on the relationship between rows and columns.
- Try writing the pattern on paper first.
- *(Further tips, if any, are cropped in the source image.)*

---

## 11 Python Data Structures Overview

*Source image: [913240555_1963945394989376_1621481622466644759_n.png](images/913240555_1963945394989376_1621481622466644759_n.png)*

**Store, Organize and Work with Data Efficiently** — *"Data structures help us store, manage and manipulate data in an organized way."*

### 11.1 What are Data Structures?

- Data structures are ways to store and organize data in memory.
- They help us handle data efficiently.
- Python provides several built-in data structures.

**Common Data Structures in Python:** String `""`, List `[ ]`, Tuple `( )`, Set `{ }`, Dictionary `{ : }`.

### 11.2 Python Strings

- A string is a sequence of characters enclosed in single (`'`) or double (`"`) quotes.
- Strings are **immutable**.
- We can perform various operations on strings.

```python
s = "Python"
print(s)
print(len(s))
print(s[0])
print(s[-1])
```

```text
Python
6
P
n
```

**Common String Operations**

```python
s.lower()              # convert to lowercase
s.upper()              # convert to uppercase
s.strip()              # remove spaces
s.replace("a", "b")    # replace text
s.split()              # split into list
```

### 11.3 String Indexing and Slicing

- **Indexing:** Accessing a single character.
- **Slicing:** Get a substring from a string.

| Character | P | y | t | h | o | n |
|-----------|---|---|---|---|---|---|
| Index | 0 | 1 | 2 | 3 | 4 | 5 |
| Negative index | -6 | -5 | -4 | -3 | -2 | -1 |

```python
s = "Python"
print(s[0])      # first character
print(s[1:4])    # slicing
print(s[-1])     # last character
print(s[::-1])   # reverse string
```

```text
P
yth
n
nohtyP
```

### 11.4 String Methods

Python provides many built-in string methods. These help in modifying and processing strings.

| Method | Description |
|--------|-------------|
| `lower()` | Converts to lowercase |
| `upper()` | Converts to uppercase |
| `strip()` | Removes leading/trailing spaces |
| `replace(a, b)` | Replaces a with b |
| `split()` | Splits string into list |
| `join()` | Joins list into string |
| `find()` | Returns index of substring |
| `count()` | Counts occurrences |
| `startswith()` | Checks if string starts with given text |
| `endswith()` | Checks if string ends with given text |

### 11.5 Lists

- A list is an ordered collection of items.
- Lists are **mutable** (can be changed).
- Lists can store different types of data.

```python
fruits = ["apple", "banana", "mango"]
print(fruits)
print(fruits[0])
fruits.append("orange")
print(fruits)
```

```text
['apple', 'banana', 'mango']
apple
['apple', 'banana', 'mango', 'orange']
```

> List allows duplicate values and is mutable.

### 11.6 List Operations

We can add, remove and modify elements in a list. Useful list methods:

| Method | Description |
|--------|-------------|
| `append(x)` | Adds an element at the end |
| `insert(i, x)` | Inserts element at index i |
| `remove(x)` | Removes first occurrence of x |
| `pop()` | Removes and returns last element |
| `sort()` | Sorts the list |
| `reverse()` | Reverses the list |
| `len()` | Returns number of elements |
| `clear()` | Removes all elements |

### 11.7 List Slicing and Comprehension

- List slicing is similar to string slicing.
- List comprehension provides a short way to create lists.

```python
nums = [1, 2, 3, 4, 5]
print(nums[1:4])                    # slicing
squares = [x**2 for x in nums]
print(squares)                      # list comprehension
```

```text
[2, 3, 4]
[1, 4, 9, 16, 25]
```

> List comprehension creates new lists in a single line.

### 11.8 Tuples

- A tuple is an ordered collection of items.
- Tuples are **immutable** (cannot be changed).
- Used to store fixed data.

```python
t = (1, 2, 3, "Python")
print(t)
print(t[0])
print(len(t))
```

```text
(1, 2, 3, 'Python')
1
4
```

> Tuples use `()` and are immutable.

### 11.9 Tuple Operations

We can access, count and find elements in a tuple. Although tuples are immutable, we can still perform some operations.

| Method | Description |
|--------|-------------|
| `count(x)` | Returns number of occurrences of x |
| `index(x)` | Returns index of first occurrence |
| `len()` | Returns number of elements |
| `+` | Concatenation (creates new tuple) |
| `*` | Repetition (creates new tuple) |
| `in` | Checks if element exists |

### 11.10 Sets

- A set is an unordered collection of unique items.
- Sets do not allow duplicate values.
- Sets are **mutable**.

```python
s = {1, 2, 3, 3, 4}
print(s)
s.add(5)
s.remove(2)
print(s)
```

```text
{1, 2, 3, 4}
{1, 3, 4, 5}
```

> Sets use `{ }` and automatically remove duplicates.

### 11.11 Set Operations

Sets support mathematical set operations. Very useful in real-world applications.

| Operation | Example | Output |
|-----------|---------|--------|
| Union (`\|`) | `a \| b` | `{1, 2, 3, 4, 5}` |
| Intersection (`&`) | `a & b` | `{3}` |
| Difference (`-`) | `a - b` | `{1, 2}` |
| Symmetric Diff (`^`) | `a ^ b` | `{1, 2, 4, 5}` |
| Subset (`<=`) | `a <= b` | True / False |
| Superset (`>=`) | `a >= b` | True / False |

```python
a = {1, 2, 3}
b = {3, 4, 5}
print(a | b)
```

```text
{1, 2, 3, 4, 5}
```

### 11.12 Dictionaries

- A dictionary stores data in `key:value` pairs.
- Keys must be unique and immutable.
- Dictionaries are **mutable**.

```python
student = {"name": "Aakash",
           "age": 20, "course": "Python"}
print(student["name"])
student["age"] = 21
student["city"] = "Raipur"
print(student)
```

```text
Aakash
{'name': 'Aakash', 'age': 21, 'course': 'Python', 'city': 'Raipur'}
```

> Dictionary uses `{ }` and stores data in `key:value` pairs.

### 11.13 Dictionary Methods

We can add, remove and access items using built-in methods.

| Method | Description |
|--------|-------------|
| `keys()` | Returns all keys |
| `values()` | Returns all values |
| `items()` | Returns key-value pairs |
| `get(key)` | Returns value (no error if key not found) |
| `update()` | Updates dictionary with new data |
| `pop(key)` | Removes key and value |
| `popitem()` | Removes last inserted item |
| `clear()` | Removes all items |

> [!WARNING]
> **Verify:** The table is cropped at the bottom of the source image; at least one more row (probably `copy()`) is not visible.

### 11.14 Nested Data Structures

We can create combinations of data structures (list inside list, dictionary inside list, etc.).

```python
students = [
    {"name": "Aakash", "marks": [85, 90]},
    {"name": "Riya", "marks": [78, 88]}
]
print(students[0]["name"])
print(students[1]["marks"][0])
```

```text
Aakash
78
```

> Nested data structures help us store complex real-world data.

> [!WARNING]
> **Verify:** The second output line is cropped in the source image; `78` follows from the code.

### 11.15 Key Takeaways

- Strings are immutable, lists are mutable.
- Tuples store fixed data, sets store unique data.
- Dictionaries store `key:value` pairs.
- List comprehension makes code shorter.
- Sets are useful for mathematical operations.
- Dictionaries provide fast data access.
- Nested data structures are used in real-world applications.
- Choose the right data structure based on the problem.
- Data structures help in writing efficient and organized *(sentence continues beyond the cropped edge)*.

---

## 12 Lists

*This topic combines 2 source sheets, kept as separate parts below: **Python Lists**; **Python Data Structures (Part 2): Lists**.*

### 12.1 Python Lists

*Source image: [912290857_2898417180536572_5045525791695421_n.png](images/912290857_2898417180536572_5045525791695421_n.png)*

**Ordered, Mutable and Versatile Data Structure** — *"Lists are used to store multiple items in a single variable."*

#### 12.1.1 What is a List?

- A list is an ordered collection of items.
- Items can be of any data type (`int`, `float`, `string`, etc.).
- Lists are **mutable** (can be changed).
- Lists are defined using square brackets `[ ]`.
- Items are separated by commas.

```python
fruits = ["apple", "banana", "mango"]
print(fruits)
```

Output:

```text
['apple', 'banana', 'mango']
```

#### 12.1.2 Creating Lists

- We can create lists with different data types.
- A list can be empty.
- Lists can contain duplicate values.

```python
l1 = [1, 2, 3, 4]                 # integers
l2 = ["Python", "Java", "C++"]
l3 = [1, "Aakash", 3.14, True]
l4 = []                           # empty list
l5 = [10, 20, 10, 30]             # duplicate values
```

Output:

```text
l1: [1, 2, 3, 4]
l2: ['Python', 'Java', 'C++']
l3: [1, 'Aakash', 3.14, True]
l4: []
l5: [10, 20, 10, 30]
```

#### 12.1.3 List Representation

| Index | 0 | 1 | 2 | 3 | 4 |
|-------|---|---|---|---|---|
| Elements | 10 | 20 | 30 | 40 | 50 |

**List Indices**

- Positive index: 0, 1, 2, … (left to right)
- Negative index: -1, -2, -3, … (right to left)

```python
nums = [10, 20, 30, 40, 50]
print(nums[0])    # first element
print(nums[-1])   # last element
print(nums[-2])   # second last
```

Output:

```text
10
50
40
```

#### 12.1.4 Accessing Elements

- We can access elements using index.
- Index starts from 0.
- We can use negative indexing.

```python
colors = ["red", "green", "blue", "yellow"]
print(colors[0])
print(colors[2])    # third element
print(colors[-1])   # last element
print(colors[-2])   # second last
```

> [!NOTE]
> The source image does not print the output for this example. Based on the code the output would be `red`, `blue`, `yellow`, `blue`.

#### 12.1.5 Slicing in Lists

- We can extract a part of the list using slicing.
- Syntax: `list[start : stop : step]`
- `start`: inclusive, `stop`: exclusive.

```python
nums = [10, 20, 30, 40, 50, 60]
print(nums[1:4])    # 2nd to 4th element
print(nums[:3])     # from start to index 2
print(nums[3:])     # from index 3 to end
print(nums[::2])    # every 2nd element
print(nums[::-1])   # reverse list
```

Output:

```text
[20, 30, 40]
[10, 20, 30]
[40, 50, 60]
[10, 30, 50]
[60, 50, 40, 30, 20, 10]
```

#### 12.1.6 Modifying Elements

Lists are mutable, so we can change, add or remove elements.

```python
nums = [10, 20, 30]
nums[1] = 200      # modify element
print(nums)
nums[0] = 100
print(nums)
```

Output:

```text
[10, 200, 30]
[100, 200, 30]
```

#### 12.1.7 Adding Elements

We can add elements using `append()`, `insert()` and `extend()`.

| Method | Description | Example |
|--------|-------------|---------|
| `append(x)` | Adds an element at end | `l.append(10)` |
| `insert(i, x)` | Adds at specific index | `l.insert(1, 20)` |
| `extend(iterable)` | Adds multiple elements | `l.extend([1,2,3])` |

```python
nums = [10, 20, 30]
nums.append(40)
nums.insert(1, 15)
nums.extend([50, 60])
print(nums)
```

Output:

```text
[10, 15, 20, 30, 40, 50, 60]
```

#### 12.1.8 Removing Elements

We can remove elements using `remove()`, `pop()` and `clear()`.

| Method | Description | Example |
|--------|-------------|---------|
| `remove(x)` | Removes first occurrence | `l.remove(10)` |
| `pop()` | Removes last element | `l.pop()` |
| `pop(i)` | Removes element at index | `l.pop(1)` |
| `clear()` | Removes all elements | `l.clear()` |

```python
nums = [10, 20, 30, 40]
nums.remove(20)
print(nums)
nums.pop()
print(nums)
nums.clear()
print(nums)
```

Output:

```text
[10, 30, 40]
[10, 30]
[]
```

#### 12.1.9 List Methods (Common)

| Method | Description |
|--------|-------------|
| `append(x)` | Adds element at end |
| `insert(i, x)` | Adds element at index |
| `extend(iterable)` | Adds multiple elements |
| `remove(x)` | Removes first occurrence |
| `pop([i])` | Removes element (last or index) |
| `clear()` | Removes all elements |
| `index(x)` | Returns index of first occurrence |
| `count(x)` | Returns count of element |
| `sort()` | Sorts list (ascending) |
| `reverse()` | Reverses list |
| `copy()` | Returns a copy of list |

#### 12.1.10 List Built-in Functions

We can use built-in functions with lists.

| Function | Description | Example |
|----------|-------------|---------|
| `len()` | Returns length | `len(l)` |
| `min()` | Smallest element | `min(l)` |
| `max()` | Largest element | `max(l)` |
| `sum()` | Sum of elements | `sum(l)` |
| `sorted()` | Returns a sorted list | `sorted(l)` |

```python
marks = [85, 92, 78, 96, 88]
print(len(marks))
print(min(marks))
print(max(marks))
print(sum(marks))
print(sorted(marks))
```

Output:

```text
5
78
96
439
[78, 85, 88, 92, 96]
```

#### 12.1.11 List Comprehension

A short and easy way to create lists. Syntax: `[expression for item in iterable]`

**Example 1: Squares of numbers**

```python
squares = [x**2 for x in range(1, 6)]
print(squares)
```

Output: `[1, 4, 9, 16, 25]`

**Example 2: Even numbers**

```python
evens = [x for x in range(1, 11) if x % 2 == 0]
print(evens)
```

Output: `[2, 4, 6, 8, 10]`

**Example 3: Convert to upper case**

```python
words = [w.upper() for w in ["python", "sims"]]
print(words)
```

Output: `['PYTHON', 'SIMS']`

#### 12.1.12 Nested Lists

- A list can contain another list as an element.
- Useful for matrix and multi-dimensional data.

```python
matrix = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
print(matrix)
print(matrix[0])        # first row
print(matrix[1][2])     # element at row 1, col 2
```

Output:

```text
[[1, 2, 3], [4, 5, 6], [7, 8, 9]]
[1, 2, 3]
6
```

#### 12.1.13 Iterating through a List

We can use a `for` loop to access all elements.

```python
fruits = ["apple", "banana", "mango"]
for fruit in fruits:
    print(fruit)
```

Output:

```text
apple
banana
mango
```

> [!NOTE]
> The output is partly cropped in the source image (`apple`, `banana…` visible); the full output follows from the code.

#### 12.1.14 Useful Examples

1. Create a list of first 10 natural numbers.
2. Find the sum of all elements in a list.
3. Find the largest number in a list.
4. Remove all even numbers from a list.
5. Create a list of squares of even numbers from 1 to 10.

#### 12.1.15 Key Takeaways

- Lists are ordered and mutable.
- Defined using square brackets `[ ]`.
- Items can be of any data type.
- Supports negative indexing.
- We can add, remove and modify elements.
- List slicing helps to extract a part of the list.
- Many useful built-in methods and functions.
- List comprehension provides a short way to create lists.
- Lists are widely used in real-world applications.

> [!WARNING]
> **Verify:** The bottom edge of the source image is cropped, so the last Key Points line(s) and any items after "Useful Examples" no. 5 may be incomplete.

### 12.2 Python Data Structures (Part 2): Lists

*Source image: [916944782_2110656162952548_369922476097955852_n.png](images/916944782_2110656162952548_369922476097955852_n.png)*

**Lists in Python** — *"Lists are flexible, mutable and widely used data structure in Python."*

> [!NOTE]
> This is the second Lists sheet. The first one (*Python Lists*) appears earlier; each has unique examples, so both are kept.

#### 12.2.1 What is a List?

- A list is an ordered collection of items.
- Items can be of different data types.
- Lists are **mutable** (can be changed).
- Lists are written inside square brackets `[]`.
- Elements are separated by commas.

**Syntax:**

```python
list_name = [item1, item2, item3, ...]
```

**Example:**

```python
fruits = ["apple", "banana", "mango"]
nums = [1, 2, 3, 4]
mixed = [1, "Python", 3.5, True]
```

**List Representation**

| Index | 0 | 1 | 2 | 3 | 4 |
|-------|---|---|---|---|---|
| Elements | 10 | 20 | 30 | 40 | 50 |

#### 12.2.2 Accessing Elements in a List

- We can access list elements using index.
- Indexing starts from 0.
- Negative indexing is also allowed.

```python
list1 = [10, 20, 30, 40, 50]
print(list1[0])      # 10
print(list1[2])      # 30
print(list1[-1])     # 50
print(list1[:-2])    # 40
```

```text
10
30
50
40
```

> [!WARNING]
> **Verify:** The last line is printed in the image as `print(list1[:-2])  # 40`. The slice `[:-2]` would return `[10, 20, 30]`; the comment and output `40` match `list1[-2]`. Please check the original.

#### 12.2.3 List Slicing

- Slicing is used to access a part of the list.
- Syntax: `list[start:end:step]`

```python
nums = [10, 20, 30, 40, 50]
print(nums[1:4])    # [20, 30, 40]
print(nums[:3])     # [10, 20, 30]
print(nums[3:])     # [40, 50]
print(nums[::2])    # [10, 30, 50]
print(nums[::-1])   # [50, 40, 30, 20, 10]
```

#### 12.2.4 List Methods (Add Elements)

| Method | Description | Example |
|--------|-------------|---------|
| `append(x)` | Adds an element at the end | `lst.append(10)` |
| `insert(i, x)` | Inserts element at index i | `lst.insert(1, 20)` |
| `extend(iterable)` | Adds multiple elements | `lst.extend([30, 40])` |

```python
lst = [10, 20, 30]
lst.append(40)
lst.insert(1, 15)
lst.extend([50, 60])
print(lst)
```

```text
[10, 15, 20, 30, 40, 50, 60]
```

#### 12.2.5 List Methods (Remove Elements)

| Method | Description | Example |
|--------|-------------|---------|
| `remove(x)` | Removes first occurrence | `lst.remove(20)` |
| `pop()` | Removes last element | `lst.pop()` |
| `pop(i)` | Removes element at index i | `lst.pop(1)` |
| `clear()` | Removes all elements | `lst.clear()` |

```python
lst = [10, 20, 30, 40, 50]
lst.remove(30)
lst.pop()
lst.pop(1)
print(lst)
```

```text
[10, 40]
```

#### 12.2.6 Other Useful Methods

| Method | Description | Example |
|--------|-------------|---------|
| `index(x)` | Returns index of element | `lst.index(20)` |
| `count(x)` | Counts occurrences | `lst.count(10)` |
| `sort()` | Sorts the list (ascending) | `lst.sort()` |
| `reverse()` | Reverses the list | `lst.reverse()` |
| `copy()` | Returns a shallow copy | `lst.copy()` |

```python
lst = [50, 10, 30, 20, 10]
print(lst.index(30))   # 2
print(lst.count(10))   # 2
lst.sort()
print(lst)             # [10, 10, 20, 30, 50]
lst.reverse()
print(lst)             # [50, 30, 20, 10, 10]
```

#### 12.2.7 List Comprehension

- A shorter way to create a new list.
- More concise and readable.

**Syntax:**

```python
[expression for item in iterable if condition]
```

**Example 1: (Square of numbers)**

```python
squares = [x**2 for x in range(1, 6)]
print(squares)
```

Output: `[1, 4, 9, 16, 25]`

**Example 2: (Even numbers)**

```python
even = [x for x in range(1, 11) if x % 2 == 0]
print(even)
```

Output: `[2, 4, 6, 8, 10]`

#### 12.2.8 Nested Lists

- A list can contain another list.
- Useful for representing 2D data like matrices.

```python
matrix = [[1, 2, 3],
          [4, 5, 6],
          [7, 8, 9]]
print(matrix[0][1])   # 2
print(matrix[2][0])   # 7
```

```text
2
7
```

**Matrix Representation**

| | | | |
|---|---|---|---|
| `matrix[0]` → | 1 | 2 | 3 |
| `matrix[1]` → | 4 | 5 | 6 |
| `matrix[2]` → | 7 | 8 | 9 |

#### 12.2.9 List with Different Data Types

A list can store elements of different data types.

```python
mixed = [1, "Python", 3.5, True, [10, 20]]
print(mixed)
print(type(mixed))
```

```text
[1, 'Python', 3.5, True, [10, 20]]
<class 'list'>
```

#### 12.2.10 Mutable vs Immutable

| | List (Mutable) | String / Tuple (Immutable) |
|---|:---:|:---:|
| Can be changed | ✅ | ❌ |
| Can add elements | ✅ | ❌ |
| Can remove elements | ✅ | ❌ |
| Can modify elements | ✅ | ❌ |
| Example | `lst = [1, 2, 3]` | `s = "Python"` |

#### 12.2.11 Useful Examples

**1. Sum of elements in a list**

```python
numbers = [10, 20, 30, 40]
total = sum(numbers)
print(total)
```

Output: `100`

**2. Find maximum and minimum**

```python
numbers = [10, 5, 20, 8]
print(max(numbers))
print(min(numbers))
```

Output: `20` and `5` *(second value cropped in the source image)*

**3. Create a new list with words length**

```python
words = ["cat", "elephant", "dog"]
lengths = [len(word) for word in words]
print(lengths)
```

Output: `[3, 8, 3]`

#### 12.2.12 Key Takeaways

- Lists are ordered and mutable.
- Indexing starts from 0 (negative indexing allowed).
- Lists can store different data types.
- Many built-in methods are available.
- List comprehension makes code shorter.
- Nested lists are useful for 2D data.
- Lists are widely used in real-world applications *(sentence partly cropped)*.

---

## 13 Python Sets

*Source images: [912822264_1295647442717892_757876294258786212_n.png](images/912822264_1295647442717892_757876294258786212_n.png) and [912822264_1295647442717892_757876294258786212_n__1_.png](images/912822264_1295647442717892_757876294258786212_n__1_.png)*

> [!NOTE]
> The two supplied "Python Sets" images are **identical duplicates**; their content is included once below.

**Unordered, Mutable (Unique Elements) Collection** — *"Sets store unique elements and are useful for removing duplicates."*

### 13.1 What is a Set?

- A set is an **unordered** collection of **unique** elements.
- Elements are written inside curly braces `{ }`.
- Sets do **not** allow duplicate values.
- Sets are **mutable** (elements can be added or removed).
- Sets are used for mathematical operations like union, intersection, etc.

**Syntax:**

```python
set_name = {item1, item2, item3, ...}
```

### 13.2 Creating a Set

```python
# Empty set
s1 = set()
print(s1)

# Set with elements
s2 = {1, 2, 3, 4, 5}
print(s2)

# Set with mixed data types
s3 = {1, "Python", 3.5, True}
print(s3)
```

Output:

```text
set()
{1, 2, 3, 4, 5}
{1, 3.5, 'Python', True}
```

### 13.3 Set Representation

Sets are unordered, so elements may appear in any order.

```python
s = {10, 20, 30, 40}
```

The set holds the elements 10, 20, 30 and 40. **The order of elements may change when printed.**

### 13.4 Accessing Elements in a Set

- We cannot access elements using **index**.
- Sets are unordered, so indexing and slicing are not supported.
- We can check if an element exists using `in` operator.

```python
s = {10, 20, 30, 40}
print(20 in s)   # True
print(50 in s)   # False
```

Output:

```text
True
False
```

### 13.5 Adding Elements

We can add a single element using `add()`.

```python
s = {10, 20, 30}
s.add(40)
s.add(50)
print(s)
```

Output: `{50, 20, 40, 10, 30}`

> [!NOTE]
> Elements may appear in any order.

### 13.6 Removing Elements

We can remove elements using `remove()`, `discard()` and `pop()`.

| Method | Description |
|--------|-------------|
| `remove(x)` | Removes element x. Raises error if not found. |
| `discard(x)` | Removes element x. No error if not found. |
| `pop()` | Removes and returns an arbitrary element. |
| `clear()` | Removes all elements. |

### 13.7 Removing Elements – Examples

```python
s = {10, 20, 30, 40, 50}
s.remove(20)          # removes 20
print(s)

s.discard(100)        # no error
print(s)

popped = s.pop()      # removes and returns
print(popped)
print(s)

s.clear()             # removes all elements
print(s)
```

Output:

```text
{50, 40, 10, 30}
{50, 40, 10, 30}
50
{40, 10, 30}
set()
```

### 13.8 Set Methods (Common)

| Method | Description |
|--------|-------------|
| `add(x)` | Adds an element. |
| `update(iterable)` | Adds multiple elements. |
| `remove(x)` | Removes element (error if not found). |
| `discard(x)` | Removes element (no error). |
| `pop()` | Removes and returns arbitrary element. |
| `clear()` | Removes all elements. |
| `copy()` | Returns a copy of the set. |
| `union()` | Returns union of sets. |
| `intersection()` | Returns intersection of sets. |
| `difference()` | Returns difference of sets. |
| `symmetric_difference()` | Returns symmetric difference. |
| `issubset()` | Checks if set is subset of another. |
| `issuperset()` | Checks if set is superset of another. |

### 13.9 Updating a Set

We can add multiple elements using `update()`.

```python
s = {1, 2, 3}
s.update([4, 5, 6])
print(s)
s.update({7, 8})
print(s)
s.update("ab")      # adds 'a' and 'b'
print(s)
```

Output:

```text
{1, 2, 3, 4, 5, 6}
{1, 2, 3, 4, 5, 6, 7, 8}
{1, 2, 3, 4, 5, 6, 7, 8, 'a', 'b'}
```

### 13.10 Set Operations (Mathematical)

- Sets support mathematical operations like union, intersection, difference etc.
- Useful for data analysis and problem solving.

| Operation | Symbol | Method | Meaning |
|-----------|--------|--------|---------|
| Union | `\|` | `union()` | Elements in A or B |
| Intersection | `&` | `intersection()` | Common elements |
| Difference | `-` | `difference()` | Elements in A not in B |
| Symmetric Diff. | `^` | `symmetric_difference()` | Elements in A or B but not both |

### 13.11 Set Operations – Examples

```python
A = {1, 2, 3, 4}
B = {3, 4, 5, 6}
print("A:", A)
print("B:", B)
print("Union:", A | B)
print("Intersection:", A & B)
print("Difference (A-B):", A - B)
print("Difference (B-A):", B - A)
print("Symmetric Diff:", A ^ B)
```

Output:

```text
A: {1, 2, 3, 4}
B: {3, 4, 5, 6}
Union: {1, 2, 3, 4, 5, 6}
Intersection: {3, 4}
Difference (A-B): {1, 2}
Difference (B-A): {5, 6}
Symmetric Diff: {1, 2, 5, 6}
```

### 13.12 Set Comprehension

We can create a set using set comprehension.

**Syntax:**

```python
{expression for item in iterable if condition}
```

**Example:**

```python
s = {x**2 for x in range(1, 6)}
print(s)
```

Output: `{1, 4, 9, 16, 25}`

### 13.13 Important Points

- Sets are unordered collections of unique elements.
- Duplicate elements are automatically removed.
- Sets are mutable (can be changed).
- Indexing and slicing are not supported.
- Use `add()`, `update()`, `remove()`, `discard()`, `pop()`, `clear()`.
- Sets support mathematical operations.
- Set comprehension provides a concise way to create sets.

### 13.14 Practice Questions

1. Create a set of first 5 natural numbers.
2. Add 6, 7, 8 to the set `{1, 2, 3, 4, 5}`.
3. Remove the element 3 from the set `{1, 2, 3, 4}`.
4. Find the union and intersection of two sets.
5. Create a set using set comprehension for squares of numbers from 1 to 10.
6. Check if a number exists in a set.

> [!WARNING]
> **Verify:** The bottom of the source image is cropped; further practice questions (if any) are not visible.

### 13.15 Real-World Applications

- Removing duplicate records
- Finding common items between datasets
- Membership testing (e.g., checking users)
- Data analysis and machine learning
- Fast lookup of elements
- *(One more application is partly cropped in the source image.)*

### 13.16 Key Takeaways

- A set stores unique, unordered elements in `{ }`; an empty set must be created with `set()`.
- Sets are mutable but do not support indexing or slicing.
- Set operations (`|`, `&`, `-`, `^`) work like mathematical set operations.

---

## 14 Python Dictionaries

*Source image: [913243751_1035513369576633_6888401660523142133_n.png](images/913243751_1035513369576633_6888401660523142133_n.png)*

**Key-Value Pair Data Structure** — *"Dictionary stores data in key-value pairs."*

### 14.1 What is a Dictionary?

- A dictionary is an unordered collection of **key-value pairs**.
- Keys are **unique** and **immutable** (string, number, tuple).
- Values can be of any data type.
- Dictionaries are **mutable** (can be changed).
- Defined inside curly braces `{ }`.

> [!NOTE]
> The source calls dictionaries "unordered", while the *Python Data Types* lecture notes that dictionaries keep insertion order in Python 3.7+. Both statements are reproduced as given in their sources.

**Syntax:**

```python
dict_name = {key1: value1, key2: value2, ...}
```

### 14.2 Creating a Dictionary

```python
# Empty dictionary
d1 = {}
print(d1)

# Dictionary with values
d2 = {"name": "Aakash",
      "age": 20,
      "city": "Raipur"}
print(d2)

# Using dict() constructor
d3 = dict(name="Python", version=3.12)
print(d3)
```

```text
{}
{'name': 'Aakash', 'age': 20, 'city': 'Raipur'}
{'name': 'Python', 'version': 3.12}
```

### 14.3 Dictionary Representation

```text
Dictionary
├── Keys:   'name'      'age'    'city'
└── Values: 'Aakash'     20      'Raipur'
```

Each key is mapped to a value using `:` (colon).

**Example:** `d = {'name': 'Aakash', 'age': 20}`

### 14.4 Accessing Elements

- We can access values using **key**.
- If key does not exist, it gives an error (`KeyError`).
- Use `get()` method to avoid error.

```python
d = {"name": "Aakash", "age": 20}
print(d["name"])                # direct access
print(d.get("age"))             # using get()
print(d.get("city", "Not Found"))
```

```text
Aakash
20
Not Found
```

### 14.5 Adding and Updating Elements

- We can add new key-value pairs.
- If key already exists, the value is updated.

```python
d = {"name": "Aakash", "age": 20}
d["city"] = "Raipur"    # add new
d["age"] = 21           # update value
print(d)
```

```text
{'name': 'Aakash', 'age': 21, 'city': 'Raipur'}
```

### 14.6 Removing Elements

We can remove elements using `pop()`, `popitem()`, `del` and `clear()`.

| Method | Description |
|--------|-------------|
| `pop(key)` | Removes element with the specified key and returns its value. |
| `popitem()` | Removes and returns the last inserted key-value pair. |
| `del dict[key]` | Removes element with the key. |
| `clear()` | Removes all elements. |

```python
d = {"a": 1, "b": 2, "c": 3}
print(d.pop("b"))    # removes and returns 2
print(d)
```

```text
2
{'a': 1, 'c': 3}
```

### 14.7 Dictionary Methods (Common)

| Method | Description |
|--------|-------------|
| `keys()` | Returns all keys. |
| `values()` | Returns all values. |
| `items()` | Returns all key-value pairs. |
| `get(key)` | Returns value for key (no error). |
| `update()` | Adds or updates elements. |
| `pop(key)` | Removes element with key. |
| `popitem()` | Removes last inserted item. |
| `clear()` | Removes all elements. |
| `copy()` | Returns a copy of dictionary. |
| `fromkeys()` | Creates dictionary with specified keys. |

### 14.8 Dictionary Methods – Examples

**Example 1**

```python
d = {"a": 1, "b": 2, "c": 3}
print(d.keys())
print(d.values())
print(d.items())
```

```text
dict_keys(['a', 'b', 'c'])
dict_values([1, 2, 3])
dict_items([('a', 1), ('b', 2), ('c', 3)])
```

**Example 2**

```python
d1 = {"x": 10}
d1.update({"y": 20, "z": 30})
print(d1)
```

```text
{'x': 10, 'y': 20, 'z': 30}
```

**Example 3**

```python
d2 = dict.fromkeys(['p', 'q', 'r'], 0)
print(d2)
```

```text
{'p': 0, 'q': 0, 'r': 0}
```

### 14.9 Dictionary Comprehension

- A short and concise way to create dictionaries.
- Syntax: `{key_expr: value_expr for item in iterable}`

**Example:**

```python
squares = {x: x**2 for x in range(1, 6)}
print(squares)
```

```text
{1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
```

**Example:**

```python
# Create dictionary from two lists
keys = ['name', 'age', 'city']
values = ["Aakash", 20, "Raipur"]
d = {k: v for k, v in zip(keys, values)}
print(d)
```

```text
{'name': 'Aakash', 'age': 20, 'city': 'Raipur'}
```

### 14.10 Nested Dictionary

A dictionary can contain another dictionary as a value.

```python
student = {
    "name": "Aakash",
    "marks": {"Math": 95, "Science": 90}
}
print(student)
print(student["marks"]["Math"])
```

```text
{'name': 'Aakash', 'marks': {'Math': 95, 'Science': 90}}
95
```

### 14.11 Dictionary with Different Data Types

Values in a dictionary can be of any data type.

```python
d = {
    "name": "Aakash",                           # string
    "age": 20,                                  # integer
    "height": 5.8,                              # float
    "is_student": True,                         # boolean
    "subjects": ["Math", "CS"],                 # list
    "address": {"city": "Raipur", "pin": 492001}  # dict
}
print(d)
```

```text
{'name': 'Aakash', 'age': 20, 'height': 5.8, 'is_student': True, 'subjects': ['Math', 'CS'], 'address': {'city': 'Raipur', 'pin': 492001}}
```

### 14.12 Dictionary vs List / Tuple / Set

| Feature | Dictionary | List | Tuple | Set |
|---------|------------|------|-------|-----|
| Structure | Key-Value | Ordered | Ordered | Unordered |
| Mutable | Yes | Yes | No | Yes |
| Duplicates | Keys unique | Yes | Yes | No |
| Indexing | By key | By index | By index | Not supported |
| Syntax | `{key: value}` | `[ ]` | `( )` | `{ }` |
| Use case | Fast lookup | Ordered data | Fixed data | Unique items |

### 14.13 Iterating through a Dictionary

We can iterate through keys, values or key-value pairs.

```python
d = {"a": 1, "b": 2, "c": 3}

# Iterate through keys
for k in d:
    print(k, "=", d[k])
```

```text
a = 1
b = 2
c = 3
```

```python
# Using items()
# (code and output cropped in the source image)
```

> [!WARNING]
> **Verify:** The "Using `items()`" part of this lecture is cropped at the bottom of the source image (only the heading and the first output line `a = 1` are visible).

### 14.14 Practice Questions

1. Create a dictionary with your name, age and city.
2. Add a new key "course" with value "Python".
3. Update your age to a new value.
4. Remove the "city" key and print the dictionary.
5. Create a dictionary of squares for numbers 1 to 5 using dictionary comprehension.
6. Create a nested dictionary to store marks of 3 subjects. *(list may continue beyond the cropped edge)*

### 14.15 Key Takeaways

- Dictionary is an unordered collection of key-value pairs.
- Keys are unique and immutable.
- Values can be of any data type.
- Dictionaries are mutable.
- Access elements using keys and `get()`.
- Common methods: `keys()`, `values()`, `items()`, `update()`, `pop()`, `clear()`, `copy()`.
- Supports nested dictionaries *(final lines cropped in the source image)*.

---

## 15 Python Functions

*Source image: [914714352_1649384756730473_1267661082653159759_n.png](images/914714352_1649384756730473_1267661082653159759_n.png)*

**Modular Code, Reusability and Better Organization** — *"Functions make code reusable, clean and easy to maintain."*

### 15.1 What is a Function?

- A function is a block of code that performs a specific task.
- It runs only when called.
- Helps in code reusability, better organization and reduces complexity.
- Built-in functions (e.g. `print()`, `len()`) and user-defined functions.

**Syntax (User-defined):**

```python
def function_name(parameters):
    # code to execute
    return value    # (optional)
```

### 15.2 Creating a Function

- We use the `def` keyword to create a function.
- Indentation is important.

```python
def greet():
    print("Hello, Welcome to Python!")
```

**Calling the function:**

```python
greet()    # Output: Hello, Welcome to Python!
```

*Flow:* Function Definition → Function Call → Output (Execution).

### 15.3 Function with Parameters

- Parameters are values passed to a function.
- They make the function more flexible.

**Example (Single parameter):**

```python
def greet(name):
    print("Hello,", name)

greet("Aakash")
```

```text
Hello, Aakash
```

**Example (Multiple parameters):**

```python
def add(a, b):
    return a + b

print(add(10, 20))
```

```text
30
```

### 15.4 Types of Arguments

| Type | Description | Example |
|------|-------------|---------|
| Positional | Passed in order | `greet("Aakash", 20)` |
| Keyword | Passed using parameter name | `greet(name="Aakash")` |
| Default | Default value if not provided | `def greet(name="Guest")` |
| Variable length | Accepts multiple values | `def add(*args)` |
| Keyword variable length | Accepts multiple key-value pairs | `def show(**kwargs)` |

### 15.5 Default Arguments

- A default value is used when no argument is passed.
- It avoids errors and makes the function more flexible.

```python
def greet(name="Guest"):
    print("Hello,", name)

greet()
greet("Aakash")
```

```text
Hello, Guest
Hello, Aakash
```

### 15.6 Variable Length Arguments

**`*args` (Non-keyword variable length)** – collects multiple values as a tuple.

```python
def add(*args):
    return sum(args)

print(add(10, 20, 30))
```

```text
60
```

**`**kwargs` (Keyword variable length)** – collects multiple key-value pairs as a dictionary.

```python
def show(**kwargs):
    for key, value in kwargs.items():
        print(key, "=", value)

show(name="Aakash", age=20)
```

```text
name = Aakash
age = 20
```

### 15.7 Return Statement

- A function can return a value using `return`.
- If no `return` is used, the function returns `None`.

```python
def square(n):
    return n * n

print(square(5))
```

```text
25
```

**Multiple return values (as tuple):**

```python
def operations(a, b):
    return a + b, a - b

print(operations(10, 5))
```

```text
(15, 5)
```

### 15.8 Scope of Variables

- Variables inside a function are **local** (internal to that function).
- Variables outside are **global**.

```python
x = 10          # global variable

def show():
    x = 5       # local variable
    print("Inside function:", x)

show()
print("Outside function:", x)
```

```text
Inside function: 5
Outside function: 10
```

### 15.9 Global Keyword

- Used to modify a global variable inside a function.
- Without `global`, a new local variable is created.

**Example:**

```python
x = 10

def change():
    global x
    x = 50

change()
print(x)
```

```text
50
```

**Without global:**

```python
x = 10

def change():
    x = 50      # local

change()
print(x)
```

```text
10
```

### 15.10 Lambda Functions (Anonymous)

- Small, single-line functions without a name.
- Mostly used for short and simple operations.

**Syntax:**

```python
lambda arguments: expression
```

**Example:**

```python
square = lambda x: x * x
print(square(5))
```

```text
25
```

### 15.11 Built-in Functions

- Python provides many built-in functions.
- Examples: `print()`, `len()`, `type()`, `max()`, `min()`, `sum()`, `sorted()`, etc.

| Function | Description | Example |
|----------|-------------|---------|
| `len()` | Length of object | `len("Python")` → 6 |
| `type()` | Data type | `type(10)` → `<class 'int'>` |
| `max()` | Maximum value | `max(10, 20, 30)` → 30 |
| `min()` | Minimum value | `min(10, 20, 30)` → 10 |
| `sum()` | Sum of values | `sum([1, 2, 3])` → 6 |
| `sorted()` | Sorted list | `sorted([3, 1, 2])` → `[1, 2, 3]` |

### 15.12 Recursion (Function Calling Itself)

- A function can call itself (recursion).
- Useful for problems like factorial, Fibonacci, etc.

**Example: Factorial using recursion**

```python
def fact(n):
    if n == 0:
        return 1
    else:
        return n * fact(n - 1)

print(fact(5))
```

```text
120
```

### 15.13 Function in Real-World Use

- Functions are used in large programs.
- They make code modular and reusable.

```python
def calculate_area(r):
    return 3.1416 * r * r

radius = 7
area = calculate_area(radius)
print("Area of circle:", area)
```

```text
Area of circle: 153.9384
```

### 15.14 Practice Questions

1. Create a function to find the given number is even or odd.
2. Create a function to find the largest of three numbers.
3. Write a function to calculate simple interest (P, R, T as parameters).
4. Create a function using default argument to greet a user.
5. Write a function using `*args` to find the sum of numbers.
6. Write a function using `**kwargs` to display student data.
7. Write a recursive function to find Fibonacci series.
8. Create a lambda function to find the square of a number.
9. Write a function to check if a string is a palindrome. *(list may continue beyond the cropped edge)*

### 15.15 Key Takeaways

- Functions help in code reusability.
- Use `def` keyword to create a function.
- Parameters make functions flexible.
- Default arguments avoid errors.
- `*args` collects multiple values (tuple).
- `**kwargs` collects key-value pairs (dict).
- `return` is used to send a value back.
- Variables inside function are local.
- Use `global` keyword to modify global variables.
- Lambda functions are single-line and anonymous.
- Recursion is useful for complex problems.

---

## 16 Python Modules and Packages

**Organize, Reuse and Manage Code Efficiently**

> [!NOTE]
> Two different "Modules and Packages" images were supplied. They overlap, but each contains unique examples, so both are kept as **Part A** and **Part B** below.

### 16.1 Part A – Modules and Packages (Overview)

*Source image: [907385199_2311696312711627_7632425416422047544_n.png](images/907385199_2311696312711627_7632425416422047544_n.png)* — *"Modules and packages help us organize code and reuse it in different programs."*

#### 16.1.1 What is a Module?

- A module is a Python file (`.py`) that contains functions, classes and variables.
- It helps us organize code and reuse it.
- We can create our own modules or use built-in modules.

**Example (`mymodule.py`):**

```python
def add(a, b):
    return a + b

pi = 3.1416
```

#### 16.1.2 Using a Module

- We use the `import` keyword to use a module.
- We can access functions and variables defined in a module.
- Syntax: `import module_name`

**Example (using `mymodule.py`):**

```python
import mymodule
print(mymodule.add(5, 3))
print(mymodule.pi)
```

Output:

```text
8
3.1416
```

> [!NOTE]
> We use `module_name.function_name` to access the members.

#### 16.1.3 Different Ways to Import

| Type | Syntax | Example |
|------|--------|---------|
| Import entire module | `import module` | `import math` → `print(math.sqrt(25))` |
| Import specific function | `from module import function` | `from math import sqrt` → `print(sqrt(25))` |
| Import with alias | `import module as alias` | `import math as m` → `print(m.sqrt(25))` |
| Import multiple functions | `from module import f1, f2` | `from math import sqrt, pi` |
| Import all members (not recommended) | `from module import *` | `from math import *` → `print(sqrt(25))` |

#### 16.1.4 Built-in Modules

- Python provides many built-in modules that we can use directly.
- Some commonly used modules:

| Module | Purpose |
|--------|---------|
| `math` | Mathematical functions |
| `random` | Generate random numbers |
| `datetime` | Work with date and time |
| `os` | Interact with operating system |
| `sys` | System related functions |
| `time` | Time related functions |
| `re` | Regular expressions |
| `json` | Work with JSON data |
| `csv` | Read and write CSV files |

#### 16.1.5 Example: math Module

- The `math` module provides mathematical functions and constants.
- We need to import it before using.

```python
import math
print(math.sqrt(16))
print(math.pow(2, 3))
print(math.pi)
print(math.factorial(5))
```

Output:

```text
4.0
8.0
3.141592653589793
120
```

**Some Useful Functions:**

| Function | Description |
|----------|-------------|
| `sqrt(x)` | Square root |
| `pow(x, y)` | x raised to the power y |
| `ceil(x)` | Round up |
| `floor(x)` | Round down |
| `factorial(x)` | Factorial of a number |
| `pi`, `e` | Mathematical constants |

#### 16.1.6 Example: random Module

- The `random` module is used to generate random numbers.
- Useful for games, simulations, etc.

```python
import random
print(random.randint(1, 10))
print(random.random())
print(random.choice(["A", "B", "C"]))
print(random.shuffle([1, 2, 3, 4]))
```

Output (as shown in the source image):

```text
5
0.7963
B
[shuffled list]
```

> [!WARNING]
> **Verify:** `random.shuffle()` shuffles **in place** and returns `None`, so `print(random.shuffle([1, 2, 3, 4]))` prints `None` in standard Python. The source image shows `[shuffled list]` as the output. Random values (`5`, `0.7963`, `B`) will also differ on every run.

**Some Useful Functions:**

| Function | Description |
|----------|-------------|
| `randint(a, b)` | Random integer between a and b |
| `random()` | Random float between 0 and 1 |
| `choice(seq)` | Random element from sequence |
| `shuffle(seq)` | Shuffle the sequence (in-place) |
| `sample(seq, n)` | Random sample of n elements |

#### 16.1.7 Creating Your Own Module

- We can create a module by saving our code in a `.py` file.
- Then we can import it into other programs.

**Example (`mymodule.py`):**

```python
def greet(name):
    return f"Hello, {name}!"

def square(x):
    return x ** 2

PI = 3.14
```

> [!NOTE]
> Save this code in a file named `mymodule.py`.

#### 16.1.8 Using Your Own Module

- Import the module and use its functions and variables.
- We can also use **alias** to shorten the name.

**Example (`main.py`):**

```python
import mymodule as m
print(m.greet("Aakash"))
print(m.square(5))
print(m.PI)
```

Output:

```text
Hello, Aakash!
25
3.14
```

> [!NOTE]
> Make sure `mymodule.py` is in the same folder or Python path.

#### 16.1.9 Python Packages

- A package is a collection of related modules in a directory.
- A package contains an `__init__.py` file (may be empty).

```text
mypackage/
├── __init__.py
├── module1.py
├── module2.py
└── subpackage/
    ├── __init__.py
    └── module3.py
```

> Packages help in organizing large projects with multiple modules.

#### 16.1.10 Using a Package

- We use dot notation to import modules from a package.
- If the package is in the same project, it can be imported directly.

```python
from mypackage import module1
module1.greet("Python")

from mypackage.subpackage import module3
module3.show()
```

Output:

```text
Hello Python
[Output of module3.show()]
```

#### 16.1.11 Installing External Packages

- We can install external packages using **pip**.
- Syntax:

```bash
pip install package_name
```

**Example:**

```bash
pip install numpy
```

- Once installed, we can import and use it in our program.

#### 16.1.12 Popular External Packages

| Package | Purpose |
|---------|---------|
| `numpy` | Numerical computing |
| `pandas` | Data analysis and manipulation |
| `matplotlib` | Data visualization |
| `scipy` | Scientific computing |
| `requests` | HTTP requests (API calls) |
| `flask` | Web development (microframework) |
| `django` | Full-stack web framework |
| `beautifulsoup4` | Web scraping |
| `tensorflow` | Machine learning |
| `opencv-python` | Image processing |

#### 16.1.13 Viewing Installed Packages

We can see all installed packages using:

```bash
pip list
```

Sample output shown in the source image:

```text
Package     Version
numpy       1.26.0
pandas      2.1.1
matplotlib  3.8.0
requests    2.31.0
```

> [!WARNING]
> **Verify:** The list is cropped at the bottom of the source image; further packages may follow.

#### 16.1.14 Uninstalling a Package

We can uninstall a package using:

```bash
pip uninstall package_name
```

**Example:**

```bash
pip uninstall numpy
```

> This will remove the package from your Python environment.

#### 16.1.15 Key Points (Part A)

- Modules help in code reusability.
- Use `import` to access modules.
- Python has many built-in modules.
- We can create our own modules.
- Packages are collections of modules.
- Use `pip` to install external packages.
- Third-party packages extend Python's functionality.
- Keep code organized using modules and packages.
- *Useful in real-world and large projects* *(partly cropped in the source image)*.

### 16.2 Part B – Modules and Packages (Extended)

*Source image: [912661601_1854501082248613_3486402625889950332_n.png](images/912661601_1854501082248613_3486402625889950332_n.png)* — *"Modules help us organize code and use functionality from other files."*

#### 16.2.1 What is a Module?

- A module is a Python file (`.py`) containing functions, variables and classes.
- It helps to organize code in separate files.
- We can reuse the code by importing modules.
- Python has many built-in modules.

**Example: `math_utils.py`**

```python
def add(a, b):
    return a + b

def square(n):
    return n * n
```

> This file is a module. We can import and use its functions in another file.

#### 16.2.2 Creating and Using Modules

- Create a `.py` file with functions, variables, etc.
- Import the module using `import` keyword.
- Use module name to access its members.

**`math_utils.py`**

```python
def add(a, b):
    return a + b

def square(n):
    return n * n

pi = 3.14159
```

**`main.py`**

```python
import math_utils

print(math_utils.add(5, 3))
print(math_utils.square(4))
print(math_utils.pi)
```

Output:

```text
8
16
3.14159
```

#### 16.2.3 Importing Modules

| Syntax | Description |
|--------|-------------|
| `import module_name` | Imports the whole module |
| `import module_name as alias` | Imports with an alias name |
| `from module import name` | Imports a specific function, variable or class |
| `from module import *` | Imports all names (not recommended) |

**Examples:**

```python
import math
print(math.sqrt(16))     # 4.0

import math as m
print(m.pi)              # 3.14159

from math import factorial
print(factorial(5))      # 120
```

#### 16.2.4 Built-in Modules

- Python provides many built-in modules.
- We just need to import and use them.
- No need to install anything.

| Module | Use |
|--------|-----|
| `math` | Mathematical functions |
| `random` | Random number generation |
| `datetime` | Date and time operations |
| `os` | Operating system related tasks |
| `sys` | System specific parameters |
| `json` | Work with JSON data |
| `re` | Regular expressions |
| `statistics` | Statistical functions |
| `time` | Time related functions |

#### 16.2.5 Examples of Built-in Modules

**1. math module** *(Square root, factorial, pi value)*

```python
import math
print(math.sqrt(25))        # 5.0
print(math.factorial(4))    # 24
print(math.pi)              # 3.14159
```

**2. random module** *(Random numbers and choices)*

```python
import random
print(random.randint(1, 100))
print(random.choice(["red", "green", "blue"]))
```

**3. datetime module** *(Current date and time)*

```python
from datetime import datetime
date = datetime.now()
print(date)
```

**4. os module** *(File and directory operations)*

```python
import os
print(os.getcwd())     # current directory
print(os.listdir())    # list of files
```

#### 16.2.6 What is a Package?

- A package is a collection of related modules in a directory.
- It can contain multiple `.py` files and a special file `__init__.py`.
- Packages are useful for large projects.

```text
mypackage/
├── __init__.py
├── module1.py
├── module2.py
└── submodule/
    ├── __init__.py
    └── module3.py
```

> This is a package containing multiple modules. The `__init__.py` file tells Python that this directory is a package.

#### 16.2.7 Creating a Package

- Create a folder (package name).
- Add an `__init__.py` file (can be empty).
- Add modules inside the folder.
- Import and use modules.

```text
mypackage/
├── __init__.py
├── math_ops.py
└── string_ops.py
```

**`mypackage/math_ops.py`**

```python
def add(a, b):
    return a + b
```

**`main.py`**

```python
from mypackage import math_ops
print(math_ops.add(5, 3))
```

#### 16.2.8 Subpackages

- A package can contain subpackages.
- Useful for better organization.

```text
science/
├── __init__.py
├── maths/
│   ├── __init__.py
│   └── algebra.py
└── physics/
    ├── __init__.py
    └── mechanics.py
```

**`science/maths/algebra.py`**

```python
def square(n):
    return n * n
```

**`main.py`**

```python
from science.maths import algebra
print(algebra.square(6))
```

Output: `36`

#### 16.2.9 The `__init__.py` File

- A special file that makes a directory a Python package.
- It can be empty, or it can contain initialization code.
- We can also define what to import.

**`mypackage/__init__.py`**

```python
# import selected modules
from .math_ops import add, square
__all__ = ["add", "square"]
```

**`main.py`**

```python
from mypackage import add, square
print(add(2, 3))
print(square(4))
```

Output:

```text
5
16
```

#### 16.2.10 Installing External Modules

- Python has thousands of modules available on **PyPI (Python Package Index)**.
- We can install them using `pip`.
- Example: `numpy`, `pandas`, `matplotlib`, etc.

**Command:**

```bash
pip install package_name
```

**Example:**

```bash
pip install numpy
pip install pandas
pip install matplotlib
```

**Verify Installation:**

```python
import numpy
print(numpy.__version__)
```

#### 16.2.11 Popular External Modules

| Module | Use |
|--------|-----|
| `numpy` | Numerical computing |
| `pandas` | Data analysis and manipulation |
| `matplotlib` | Data visualization |
| `seaborn` | Statistical data visualization |
| `requests` | HTTP requests (API) |
| `flask` | Web development |
| `django` | Web framework (advanced) |
| `scikit-learn` | Machine learning |
| `opencv-python` | Image processing |
| `beautifulsoup4` | Web scraping |
| `fastapi` | Modern web framework |

#### 16.2.12 Module Search Path

- Python searches for modules in a list of directories stored in `sys.path`.
- We can view the search path using:

```python
import sys
print(sys.path)
```

> It includes the current directory, Python installation directory, and directories from environment variables.

#### 16.2.13 Advantages

- Code reusability
- Better organization
- Easier to maintain and debug
- Helps in working on large projects *(list partly cropped in the source image)*

#### 16.2.14 Common Errors

- `ModuleNotFoundError` → Module not installed or wrong path.
- `ImportError` → Cannot import name.
- `AttributeError` → Module has no attribute.
- `Circular import` → Two modules importing each other *(text partly cropped in the source image)*.

#### 16.2.15 Key Points (Part B)

- A module is a single Python file.
- A package is a collection of modules.
- Use `import` to access modules.
- Python provides many built-in modules.
- Use `pip` to install external modules.
- The `__init__.py` file makes a directory a package *(sentence partly cropped in the source image)*.

> [!WARNING]
> **Verify:** The bottom of the Part B source image is cropped, so "Advantages", "Common Errors" and "Key Points" may contain further items that are not visible.

### 16.3 Key Takeaways

- A module is a single `.py` file; a package is a directory of modules with an `__init__.py` file.
- Use `import`, `import … as …` or `from … import …` to bring in module members.
- Built-in modules need no installation; external modules are installed with `pip install`.
- Python searches for modules in `sys.path`.

---

## 17 Python File Handling

*Source image: [912607550_1440663747714422_7714185856196194925_n.png](images/912607550_1440663747714422_7714185856196194925_n.png)*

**Read, Write and Work with Files Easily** — *"File handling helps us store data permanently in files like .txt, .csv, .json, etc."*

### 17.1 What is File Handling?

- File handling allows us to work with files stored on disk.
- We can create, read, write, update and delete files.
- Files store data permanently even after the program ends.
- Python provides built-in functions to handle files easily.

```text
Python Program  <── Read / Write ──>  File on Disk
(Data is stored permanently in a file)
```

### 17.2 Types of Files

- **Text Files** (`.txt`) – store plain text.
- **CSV Files** (`.csv`) – store tabular data.
- **JSON Files** (`.json`) – store structured data (key-value pairs).
- **Binary Files** (`.jpg`, `.png`, `.pdf`, `.mp4`, etc.) – store non-text data.

| File Type | Extension | Example Use |
|-----------|-----------|-------------|
| Text File | `.txt` | Notes, logs, text data |
| CSV File | `.csv` | Tabular data (Excel) |
| JSON File | `.json` | Configuration, API data |
| Binary File | `.jpg`, `.png` | Images, videos, PDFs |
| Python File | `.py` | Python source code |

### 17.3 File Modes

We use different modes while opening a file.

| Mode | Description | File Pointer |
|------|-------------|--------------|
| `'r'` | Read (default) | Start of file |
| `'w'` | Write (creates new or truncates existing) | Start of file |
| `'a'` | Append (adds at end) | End of file |
| `'x'` | Create new file (error if exists) | Start of file |
| `'b'` | Binary mode | As per mode |
| `'t'` | Text mode (default) | As per mode |
| `'+'` | Read and write | Start of file |

```python
f = open("example.txt", "r")
# open file in read mode
```

### 17.4 Opening and Closing a File

- Use `open()` to open a file.
- Use `close()` to close a file.
- Better way: use `with` statement (it automatically closes the file).

**Using `open()` and `close()`**

```python
f = open("test.txt", "r")
print(f.read())
f.close()
```

**Using `with` statement (recommended)**

```python
with open("test.txt", "r") as f:
    print(f.read())
```

### 17.5 Writing to a File

- Use `'w'` mode to write (creates/truncates file).
- Use `write()` to write data.
- Use `writelines()` to write multiple lines.

```python
f = open("sample.txt", "w")
f.write("Hello, Python!\n")
f.write("File handling is easy.\n")
f.close()
```

**Using `with`:**

```python
with open("sample.txt", "w") as f:
    f.write("Hello, Python!\n")
    f.writelines(["Line 1\n", "Line 2\n"])
```

### 17.6 Reading from a File

- Use `'r'` mode to read.
- We can read the entire file or line by line.

```python
with open("sample.txt", "r") as f:
    data = f.read()      # read entire file
    print(data)
```

**Line by line:**

```python
with open("sample.txt", "r") as f:
    for line in f:
        print(line, end="")
```

### 17.7 Reading Specific Content

- `read(n)` → reads n characters.
- `readline()` → reads one line.
- `readlines()` → returns a list of all lines.

```python
with open("sample.txt", "r") as f:
    print(f.read(5))        # first 5 characters
    print(f.readline())     # next line
    print(f.readlines())    # remaining lines as list
```

### 17.8 Appending to a File

- Use `'a'` mode to add data at the end.
- Existing content is not deleted.

```python
with open("sample.txt", "a") as f:
    f.write("This line is appended.\n")
    f.write("Another line.\n")
```

| Before appending | After appending |
|------------------|-----------------|
| `Hello, Python!` | `Hello, Python!` |
| `File handling is easy.` | `File handling is easy.` |
| | `This line is appended.` |
| | `Another line.` |

### 17.9 File Handling with Different Types

**Text File example (.txt)**

```python
with open("notes.txt", "w") as f:
    f.write("This is a text file.")
```

**CSV File example (.csv)**

```python
import csv
with open("data.csv", "w", newline="") as f:
    writer = csv.writer(f)
    writer.writerow(["Name", "Age"])
    writer.writerow(["Aakash", 20])
```

**JSON File example (.json)**

```python
import json
data = {"name": "Aakash", "age": 20}
with open("data.json", "w") as f:
    json.dump(data, f, indent=4)
```

### 17.10 File and Directory Operations

We can check if a file exists, get its size, rename or delete a file using the `os` module.

```python
import os
print(os.path.exists("sample.txt"))    # True
print(os.path.getsize("sample.txt"))   # size
os.rename("old.txt", "new.txt")        # rename
os.remove("new.txt")                   # delete file
```

### 17.11 Working with Paths

- Use `os.path` or `pathlib` for path operations.
- Useful for cross-platform compatibility.

**Using `os.path`:**

```python
import os
print(os.path.basename("folder/file.txt"))
print(os.path.dirname("folder/file.txt"))
print(os.path.join("folder", "file.txt"))
```

**Using `pathlib`:**

```python
from pathlib import Path
p = Path("folder/file.txt")
print(p.name)       # file.txt
print(p.parent)     # folder
print(p.exists())   # True
```

### 17.12 Working with Binary Files

- Use `'rb'` and `'wb'` modes for binary files.
- Useful for images, videos, PDFs, etc.

**Example – Writing (copy image):**

```python
with open("image.jpg", "rb") as src:
    with open("copy.jpg", "wb") as dst:
        dst.write(src.read())
```

> [!NOTE]
> Reads and writes binary data without changing it.

### 17.13 Real-World Example – Log File

We can create a log file to store application events.

```python
from datetime import datetime
with open("app.log", "a") as f:
    now = datetime.now()
    f.write(f"[{now}] Application started.\n")
```

Each time you run the program, a new entry is added in the log file.

### 17.14 Common Errors

- `FileNotFoundError` – file does not exist.
- `PermissionError` – no access to file.
- `IsADirectoryError` – trying to open a directory.

**Example:**

```python
try:
    with open("wrong.txt", "r") as f:
        print(f.read())
except FileNotFoundError:
    print("Error: File not found!")
```

> [!WARNING]
> **Verify:** The last line of this example is partly cropped in the source image; `print("Error: File not found!")` is reconstructed from the visible fragment.

### 17.15 Key Takeaways

- Files store data permanently.
- Use `open()` with correct mode.
- Use `with` statement (best practice).
- Text, CSV, JSON and binary files can be handled.
- Use `os` or `pathlib` for path operations.
- Handle exceptions while working with files.
- File handling is widely used in real-world applications like logging, configuration, data storage, etc. *(final words partly cropped in the source image)*.

---

## 18 Object-Oriented Programming

*This topic combines 3 source sheets, kept as separate parts below: **Python Object-Oriented Programming (OOP)**; **Python OOP – Practical Guide**; **Python Inheritance and Polymorphism**.*

### 18.1 Python Object-Oriented Programming (OOP)

*Source image: [913213599_2000875744217024_6880538126704627468_n.png](images/913213599_2000875744217024_6880538126704627468_n.png)*

**Organize Code with Real-World Concepts** — *"OOP helps us model real-world problems using classes and objects."*

#### 18.1.1 What is OOP?

- OOP is a programming paradigm based on the concept of "objects".
- It helps us organize code in a structured and reusable way.
- It models real-world entities using classes and objects.
- Main features: **Encapsulation, Abstraction, Inheritance, Polymorphism.**

**Real-World Example:** A **Car (Object)** has *Color, Brand, Speed, Start(), Stop()*.

#### 18.1.2 Class and Object

- A class is a **blueprint** for creating objects.
- An object is an **instance** of a class.

**Syntax:**

```python
class ClassName:
    # attributes
    # methods
```

**Example:**

```python
class Car:
    def __init__(self, brand, color):
        self.brand = brand
        self.color = color

    def show(self):
        print(f"Brand: {self.brand}")
        print(f"Color: {self.color}")

# creating object
c = Car("Toyota", "Red")
c.show()
```

Output:

```text
Brand: Toyota
Color: Red
```

> Here `Car` is a class and `c` is an object of the class `Car`.

#### 18.1.3 Constructor (`__init__`)

- A constructor is a special method that is automatically called when an object is created.
- In Python, the constructor method name is `__init__()`.

**Example:**

```python
class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def display(self):
        print(f"Name: {self.name}")
        print(f"Age: {self.age}")

s = Student("Aakash", 20)
s.display()
```

Output:

```text
Name: Aakash
Age: 20
```

> `__init__()` is a constructor which initializes the object.

> [!WARNING]
> **Verify:** The source image ends this example with `c.display()`, but the object is named `s`. The line is written as `s.display()` above, which is the working version.

#### 18.1.4 Instance and Class Variables

- **Instance variables** are unique for each object.
- **Class variables** are shared among all objects.

```python
class Student:
    school_name = "SIMS"      # class variable

    def __init__(self, name):
        self.name = name      # instance variable

s1 = Student("Aakash")
s2 = Student("Riya")
print(s1.name, s2.name)       # Aakash Riya
print(Student.school_name)    # SIMS
```

#### 18.1.5 Methods in a Class

Methods are functions defined inside a class.

| Type | Description | Example |
|------|-------------|---------|
| Instance Method | Works with object (`self`) | `def show(self)` |
| Class Method | Works with class (`cls`) | `@classmethod` `def show(cls)` |
| Static Method | Does not use `self` or `cls` | `@staticmethod` `def info()` |

#### 18.1.6 Types of Methods – Example

```python
class Demo:
    class_var = "Python"

    def instance_method(self):
        print("Instance method")

    @classmethod
    def class_method(cls):
        print("Class method")

    @staticmethod
    def static_method():
        print("Static method")

d = Demo()
d.instance_method()      # Instance method
Demo.class_method()      # Class method
Demo.static_method()     # Static method
```

Output:

```text
Instance method
Class method
Static method
```

#### 18.1.7 Encapsulation

- Encapsulation means wrapping data and methods into a single unit (class).
- It restricts direct access to data using private variables (`__x`).

```python
class BankAccount:
    def __init__(self, balance):
        self.__balance = balance      # private variable

    def deposit(self, amount):
        self.__balance += amount

    def get_balance(self):
        return self.__balance

acc = BankAccount(1000)
acc.deposit(500)
print(acc.get_balance())
```

Output: `1500`

> We cannot access `__balance` directly outside the class.

#### 18.1.8 Inheritance

- Inheritance allows a class to inherit properties and methods from another class.
- It promotes code reusability.

```python
class Animal:
    def sound(self):
        print("Animal makes sound")

class Dog(Animal):
    def sound(self):
        print("Dog barks")

obj = Dog()
obj.sound()
```

Output: `Dog barks`

> `Dog` class inherits from `Animal` class.

```text
Animal (sound())
    ↓
Dog (sound())
```

#### 18.1.9 Types of Inheritance

| Type | Diagram | Example |
|------|---------|---------|
| Single Inheritance | A → B | `class A: pass` / `class B(A): pass` |
| Multiple Inheritance | A, B → C | `class A: pass` / `class B: pass` / `class C(A, B): pass` |
| Multilevel Inheritance | A → B → C | `class A: pass` / `class B(A): pass` / `class C(B): pass` |
| Hierarchical Inheritance | A → B, A → C | `class A: pass` / `class B(A): pass` / `class C(A): pass` |

#### 18.1.10 Method Overriding (Polymorphism)

- When a child class provides a specific implementation of a method that is already defined in the parent class.
- It is a type of polymorphism.

```python
class Parent:
    def show(self):
        print("Parent class method")

class Child(Parent):
    def show(self):
        print("Child class method")

obj = Child()
obj.show()
```

Output: `Child class method`

#### 18.1.11 Polymorphism

- Polymorphism means "many forms".
- Same method name behaves differently in different classes.

```python
class Cat:
    def speak(self):
        print("Cat meows")

class Dog:
    def speak(self):
        print("Dog barks")

for animal in [Cat(), Dog()]:
    animal.speak()
```

Output:

```text
Cat meows
Dog barks
```

> Same method name (`speak`) behaves differently for different objects.

#### 18.1.12 Abstraction

- Abstraction means hiding internal details and showing only essential features.
- In Python, abstraction can be achieved using abstract classes (ABC module).

```python
from abc import ABC, abstractmethod

class Vehicle(ABC):
    @abstractmethod
    def start(self):
        pass

class Car(Vehicle):
    def start(self):
        print("Car started")

c = Car()
c.start()
```

Output: `Car started`

> Abstract class forces child class to implement the method.

#### 18.1.13 Special (Magic) Methods

Python provides many special methods (dunder methods) for operator overloading and customization.

| Method | Purpose | Example |
|--------|---------|---------|
| `__init__()` | Constructor | `obj = Class()` |
| `__str__()` | String representation | `print(obj)` |
| `__len__()` | Length of object | `len(obj)` |
| `__add__()` | Addition operator | `obj1 + obj2` |
| `__eq__()` | Equality check | `obj1 == obj2` |

> [!WARNING]
> **Verify:** The last row (`__eq__()`) is partly cropped in the source image; "Equality check" and `obj1 == obj2` are inferred from the visible fragments.

#### 18.1.14 Real-World Example

Let's create a Student class with encapsulation, inheritance and method overriding.

```python
class Person:
    def __init__(self, name):
        self.name = name

    def show(self):
        print(f"Name: {self.name}")

class Student(Person):
    def __init__(self, name, marks):
        super().__init__(name)
        self.__marks = marks

    def show(self):
        print(f"Name: {self.name}, Marks: {self.__marks}")

s = Student("Riya", 85)
s.show()
```

Output:

```text
Name: Riya, Marks: 85
```

> [!WARNING]
> **Verify:** The source image is cropped at this example. The final lines `s = Student("Riya", 85)` and `s.show()` are completed from the visible fragment `s = Student("Riya", 85)` and the printed output.

#### 18.1.15 Key Takeaways

- OOP helps in organizing code.
- Class is a blueprint, object is an instance.
- Constructor (`__init__`) initializes objects.
- Instance and class variables store data.
- Encapsulation protects data.
- Inheritance allows code reusability.
- Polymorphism allows same method in different forms.
- Abstraction hides internal details.
- Special methods provide extra functionality.
- OOP is useful for building real-world applications *(sentence partly cropped in the source image)*.

### 18.2 Python OOP – Practical Guide

*Source image: [914173004_1793507131885562_315668360539298013_n.png](images/914173004_1793507131885562_315668360539298013_n.png)*

**Build Real-World Applications with Reusable and Modular Code** — *"OOP helps us write clean, reusable and easy-to-maintain code."*

> [!NOTE]
> This is the second OOP sheet. The first one (*Python Object-Oriented Programming (OOP)*) is the previous lecture. This sheet repeats many topics with different examples and adds *Method Overloading*, *Operator Overloading* and a *Student Management* example.

#### 18.2.1 What is OOP?

- OOP (Object Oriented Programming) is a programming paradigm based on the concept of objects and classes.
- It helps us organize code in a more structured and real-world way.
- Main concepts: **Class, Object, Encapsulation, Inheritance, Polymorphism, Abstraction.**

**Real-World Example:** Car (Object) – *Properties:* color, model, speed; *Methods:* start(), stop(), accelerate().

#### 18.2.2 Class and Object

- A class is a blueprint for creating objects.
- An object is an instance of a class.

```python
class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def show(self):
        print(f"Name: {self.name}")
        print(f"Age: {self.age}")

# creating an object
s1 = Student("Aakash", 20)
s1.show()
```

```text
Name: Aakash
Age: 20
```

#### 18.2.3 Constructor (`__init__`)

- The `__init__()` method is a constructor.
- It is automatically called when an object is created.
- It is used to initialize the object's attributes.

```python
class Book:
    def __init__(self, title, author):
        self.title = title
        self.author = author

    def display(self):
        print(f"Title: {self.title}")
        print(f"Author: {self.author}")

b = Book("Python", "Guido")
b.display()
```

```text
Title: Python
Author: Guido
```

> [!WARNING]
> **Verify:** The source image ends this example with `d.display()`, but the object is named `b`. It is written as `b.display()` above.

#### 18.2.4 Instance and Class Variables

- Instance variables are unique for each object.
- Class variables are shared by all objects of the class.

```python
class Student:
    school = "SIMS"            # class variable

    def __init__(self, name):
        self.name = name       # instance variable

s1 = Student("Aakash")
s2 = Student("Riya")
print(s1.name, s2.name)
print(Student.school)
```

```text
Aakash Riya
SIMS
```

*Callouts:* **Class Variable** (same for all) · **Instance Variable** (unique for each object).

#### 18.2.5 Methods in a Class

- Methods are functions defined inside a class.
- They operate on the object's data.

```python
class Calculator:
    def add(self, a, b):
        return a + b

    def sub(self, a, b):
        return a - b

c = Calculator()
print("Add:", c.add(10, 5))
print("Sub:", c.sub(10, 5))
```

```text
Add: 15
Sub: 5
```

#### 18.2.6 Encapsulation

- Encapsulation means binding data and methods together in a single unit.
- We can make variables private using double underscore (`__`) to restrict direct access.

```python
class BankAccount:
    def __init__(self, balance):
        self.__balance = balance      # private variable

    def get_balance(self):
        return self.__balance

acc = BankAccount(10000)
print(acc.get_balance())
# print(acc.__balance)   # Error (not accessible)
```

```text
10000
```

#### 18.2.7 Inheritance

- Inheritance allows a new class to inherit properties and methods from an existing class.
- It helps in code reusability.

```python
class Animal:
    def sound(self):
        print("Animal makes a sound")

class Dog(Animal):
    def sound(self):
        print("Dog barks")

d = Dog()
d.sound()
```

```text
Dog barks
```

#### 18.2.8 Types of Inheritance

Single, Multiple, Multilevel, Hierarchical and Hybrid inheritance.

| Type | Diagram |
|------|---------|
| Single | A → B |
| Multiple | A, B → C |
| Multilevel | A → B → C |
| Hierarchical | A → B, A → C |
| Hybrid | A (top) with C and D below *(diagram as drawn in the image)* |

#### 18.2.9 Polymorphism

- Polymorphism means "many forms".
- The same method name can have different behaviour in different classes.
- It can be achieved using method overriding and method overloading.

**Example (Method Overriding):**

```python
class Animal:
    def sound(self):
        print("Animal sound")

class Cat(Animal):
    def sound(self):
        print("Cat meows")

a = Cat()
a.sound()
```

```text
Cat meows
```

#### 18.2.10 Method Overloading

- Python does not support method overloading directly.
- We can achieve it using default arguments or variable length arguments (`*args`).

**Example (using default arguments):**

```python
class Calculator:
    def add(self, a, b=0, c=0):
        return a + b + c

c = Calculator()
print(c.add(5))
print(c.add(5, 10))
print(c.add(5, 10, 15))
```

```text
5
15
30
```

#### 18.2.11 Abstraction

- Abstraction means hiding the implementation details and showing only essential features.
- In Python, we can achieve abstraction using abstract classes (`abc` module).

```python
from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def area(self):
        pass

class Circle(Shape):
    def __init__(self, r):
        self.r = r

    def area(self):
        return 3.14 * self.r * self.r

c = Circle(5)
print(c.area())
```

```text
78.5
```

#### 18.2.12 Special (Magic) Methods

- Python provides special methods (dunder methods) to define the behaviour of objects.
- Examples: `__str__`, `__repr__`, `__len__`, `__add__`, etc.

**Example (`__str__` and `__len__`):**

```python
class Person:
    def __init__(self, name):
        self.name = name

    def __str__(self):
        return f"Person: {self.name}"

    def __len__(self):
        return len(self.name)

p = Person("Aakash")
print(p)
print(len(p))
```

```text
Person: Aakash
6
```

#### 18.2.13 Operator Overloading

- We can change the behaviour of operators for user-defined objects.
- We can do this using special methods like `__add__`, `__sub__`, etc.

**Example (using `__add__`):**

```python
class Point:
    def __init__(self, x, y):
        self.x = x
        self.y = y

    def __add__(self, other):
        return Point(self.x + other.x, self.y + other.y)

    def __str__(self):
        return f"({self.x}, {self.y})"

p1 = Point(2, 3)
p2 = Point(4, 5)
print(p1 + p2)
```

```text
(6, 8)
```

#### 18.2.14 Practical Example: Student Management

A complete example using class, object, methods and multiple concepts.

```python
class Student:
    school = "SIMS"

    def __init__(self, name, age):
        self.name = name
        self.age = age

    def info(self):
        print(f"Name: {self.name}, Age: {self.age}, School: {Student.school}")

s = Student("Riya", 21)
s.info()
```

```text
Name: Riya, Age: 21, School: SIMS
```

> [!WARNING]
> **Verify:** The output line is cropped in the source image after `Age: 21,`; `School: SIMS` is completed from the code.

#### 18.2.15 Key Takeaways

- OOP is based on objects and classes.
- Helps in writing clean, modular and reusable code.
- Supports real-world modeling.
- Main concepts: Encapsulation, Inheritance, Polymorphism, Abstraction.
- Python provides powerful built-in features for OOP.
- Use special methods to customize object behaviour.
- Inheritance helps in code reusability.
- Polymorphism allows same method with different behaviour.
- Abstraction hides implementation details.
- OOP is widely used in real-world applications like web apps, games, and software systems.

### 18.3 Python Inheritance and Polymorphism

*Source image: [915078776_1491019392925655_3253313825503408403_n.png](images/915078776_1491019392925655_3253313825503408403_n.png)*

**Reuse Code and Build Flexible Applications** — *"Inheritance allows code reuse and polymorphism provides flexibility."*

#### 18.3.1 What is Inheritance?

- Inheritance allows a new class (**child class**) to inherit properties and methods from an existing class (**parent class**).
- It helps in code reusability.
- The parent class is also called **base class** and the child class is called **derived class**.
- The child class can also add new features or modify existing ones.

*Diagram:* Parent Class (Base Class) → Child Class (Derived Class).

#### 18.3.2 Syntax of Inheritance

```python
class ParentClass:
    # parent class attributes and methods
    pass

class ChildClass(ParentClass):
    # child class attributes and methods
    pass
```

- The child class inherits all the accessible members of the parent class.
- We can create our own methods and attributes in the child class.

#### 18.3.3 Single Inheritance

- One child class inherits from one parent class.
- Most commonly used type of inheritance.

```python
class Animal:
    def sound(self):
        print("Animal makes a sound")

class Dog(Animal):
    def sound(self):
        print("Dog barks")

d = Dog()
d.sound()
```

```text
Dog barks
```

#### 18.3.4 Multiple Inheritance

- A child class inherits from more than one parent class.
- It can inherit features from multiple sources.

```python
class Father:
    def skills(self):
        print("Father: Teaching skills")

class Mother:
    def skills(self):
        print("Mother: Caring skills")

class Child(Father, Mother):
    pass

c = Child()
c.skills()
```

```text
Father: Teaching skills
```

#### 18.3.5 Multilevel Inheritance

- A class is derived from another derived class.
- It forms a chain of inheritance.

```python
class Grandparent:
    def show(self):
        print("Grandparent")

class Parent(Grandparent):
    def display(self):
        print("Parent")

class Child(Parent):
    def show_child(self):
        print("Child")

obj = Child()
obj.show()
obj.display()
obj.show_child()
```

```text
Grandparent
Parent
Child
```

*Diagram:* Grandparent → Parent → Child.

#### 18.3.6 Hierarchical Inheritance

Multiple child classes inherit from the same parent class.

```python
class Vehicle:
    def display(self):
        print("Vehicle")

class Car(Vehicle):
    def show(self):
        print("Car")

class Bike(Vehicle):
    def show(self):
        print("Bike")

c = Car()
b = Bike()
c.display()
c.show()
b.display()
b.show()
```

```text
Vehicle
Car
Vehicle
Bike
```

#### 18.3.7 Hybrid Inheritance

- Combination of two or more types of inheritance.
- More complex structure.

*Diagram:* A → B and A → C; B → D and C → D.

#### 18.3.8 Method Overriding

- When a child class provides a specific implementation of a method already defined in the parent class.
- The method in the child class overrides the method in the parent class.

```python
class Parent:
    def display(self):
        print("Parent class method")

class Child(Parent):
    def display(self):
        print("Child class method")

obj = Child()
obj.display()
```

```text
Child class method
```

#### 18.3.9 `super()` Function

- The `super()` function is used to call the method of the parent class from the child class.
- It is useful when we want to extend the parent class method.

```python
class Parent:
    def show(self):
        print("Parent method")

class Child(Parent):
    def show(self):
        super().show()
        print("Child method")

obj = Child()
obj.show()
```

```text
Parent method
Child method
```

#### 18.3.10 Polymorphism

- Polymorphism means "many forms".
- Same method name can behave differently in different classes.
- Achieved using method overriding.

```python
class Cat:
    def sound(self):
        print("Cat meows")

class Dog:
    def sound(self):
        print("Dog barks")

for animal in [Cat(), Dog()]:
    animal.sound()
```

```text
Cat meows
Dog barks
```

#### 18.3.11 Polymorphism using Functions

A same function can work with different objects (duck typing).

```python
def animal_sound(animal):
    animal.sound()

class Cat:
    def sound(self):
        print("Meow")

class Dog:
    def sound(self):
        print("Bark")

animal_sound(Cat())
animal_sound(Dog())
```

```text
Meow
Bark
```

#### 18.3.12 Polymorphism using Operators

The `+` operator behaves differently for integers and strings (operator overloading).

**Example (Built-in):**

```python
print(5 + 3)            # addition
print("Hello " + "Python")   # concatenation
```

```text
8
Hello Python
```

#### 18.3.13 `isinstance()` and `issubclass()`

- `isinstance()` checks whether an object is an instance of a class.
- `issubclass()` checks whether a class is a subclass of another class.

```python
class A:
    pass

class B(A):
    pass

obj = B()
print(isinstance(obj, B))   # True
print(isinstance(obj, A))   # True
print(issubclass(B, A))     # True
```

```text
True
True
True
```

> [!NOTE]
> The heading in the source image reads "isisntance() and issubclass()"; the spelling has been corrected.

#### 18.3.14 Real-World Example: Bank Account

Using inheritance to create a savings and current account.

```python
class BankAccount:
    def __init__(self, balance):
        self.balance = balance

    def show_balance(self):
        print("Balance:", self.balance)

class SavingsAccount(BankAccount):
    def add_interest(self, amount):
        self.balance += amount

acc = SavingsAccount(1000)
acc.add_interest(200)
acc.show_balance()
```

```text
Balance: 1200
```

#### 18.3.15 Key Takeaways

- Inheritance helps in code reusability.
- Types: Single, Multiple, Multilevel, Hierarchical, Hybrid.
- Method overriding provides specific behaviour.
- `super()` is used to call parent class methods.
- Polymorphism means many forms.
- Same method name can behave differently in different classes.
- Polymorphism can be achieved using method overriding and operator overloading.
- `isinstance()` and `issubclass()` help in checking class relationships.
- Inheritance and polymorphism are widely used in real-world applications.

---

## 19 Python Exception Handling

*Source image: [913216772_1171968175353884_7142889038801298485_n.png](images/913216772_1171968175353884_7142889038801298485_n.png)*

**Handle Errors Gracefully and Make Robust Programs** — *"Exception handling helps us manage runtime errors and prevents the program from crashing."*

### 19.1 What is an Exception?

- An exception is a **runtime error** that occurs during the execution of a program.
- It disrupts the normal flow of the program.
- Exception handling helps us handle these errors gracefully without crashing the program.

**Example (Error without handling):**

```python
print(10 / 0)
```

Output:

```text
ZeroDivisionError: division by zero
```

### 19.2 Why Exception Handling?

- Prevents program from crashing.
- Provides meaningful error messages.
- Helps in debugging.
- Improves program reliability.
- Supports clean and professional code.

**Without Handling**

```python
print(10/0)
print("End")
```

```text
ZeroDivisionError: division by zero
```

**With Handling**

```python
try:
    print(10/0)
except ZeroDivisionError:
    print("Cannot divide by zero")
print("End")
```

```text
Cannot divide by zero
End
```

### 19.3 Common Built-in Exceptions

| Exception | Description |
|-----------|-------------|
| `ZeroDivisionError` | Division by zero |
| `TypeError` | Operation on incompatible types |
| `ValueError` | Invalid value |
| `NameError` | Variable not defined |
| `IndexError` | Index out of range |
| `KeyError` | Key not found in dictionary |
| `FileNotFoundError` | File does not exist |
| `ImportError` | Module not found |
| `AttributeError` | Invalid attribute reference |
| `OverflowError` | Result too large |
| `MemoryError` | Out of memory |

### 19.4 Basic try-except Block

- We use `try` to write the code that may raise an exception.
- We use `except` to handle the exception.

```python
try:
    x = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
```

Output:

```text
Cannot divide by zero!
```

### 19.5 Try-Except-Else

The `else` block runs if no exception occurs.

```python
try:
    num = int(input("Enter a number: "))
    print("Square:", num*num)
except ValueError:
    print("Invalid input!")
else:
    print("No error occurred!")
```

Output (Input: 5):

```text
Enter a number: 5
Square: 25
No error occurred!
```

### 19.6 Try-Except-Finally

The `finally` block always runs (whether exception occurs or not).

```python
try:
    f = open("test.txt", "r")
    print("File opened")
except FileNotFoundError:
    print("File not found!")
finally:
    print("This will always run")
```

Output:

```text
File not found!
This will always run
```

### 19.7 Multiple Except Blocks

We can handle different types of exceptions separately.

```python
try:
    a = int(input("Enter a: "))
    b = int(input("Enter b: "))
    print(a / b)
except ZeroDivisionError:
    print("Cannot divide by zero!")
except ValueError:
    print("Please enter valid numbers!")
```

Output (Input: 5, 0):

```text
Enter a: 5
Enter b: 0
Cannot divide by zero!
```

### 19.8 Catching Multiple Exceptions

We can catch multiple exceptions in a single `except` block using a tuple.

```python
try:
    x = int(input("Enter a number: "))
    result = 10 / x
except (ValueError, ZeroDivisionError):
    print("Invalid input or division by zero!")
```

Output (Input: 0):

```text
Enter a number: 0
Invalid input or division by zero!
```

### 19.9 Raising Exceptions

- We can raise our own exceptions using the `raise` keyword.
- Useful for custom error handling.

```python
def check_age(age):
    if age < 18:
        raise ValueError("Age must be 18 or above")
    else:
        print("Age is valid")

check_age(16)
```

Output:

```text
ValueError: Age must be 18 or above
```

### 19.10 Custom Exception

We can create our own exception classes by inheriting from `Exception`.

```python
class NegativeAgeError(Exception):
    pass

def check_age(age):
    if age < 0:
        raise NegativeAgeError("Age cannot be negative")
    print("Age is:", age)

check_age(-5)
```

Output:

```text
NegativeAgeError: Age cannot be negative
```

### 19.11 Exception Handling Flowchart

```text
Start → Execute try block → Exception occurs?
          ├── Yes → Execute except block ─┐
          └── No  → Execute else block ───┤
                                          ↓
                          Execute finally block → End
```

### 19.12 Nested Try-Except

We can use `try-except` inside another `try-except`.

```python
try:
    a = int(input("Enter a: "))
    try:
        b = int(input("Enter b: "))
        print(a / b)
    except ZeroDivisionError:
        print("Inner: Cannot divide by zero!")
except ValueError:
    print("Outer: Invalid input!")
```

Output (Input: 5, 0):

```text
Enter a: 5
Enter b: 0
Inner: Cannot divide by zero!
```

### 19.13 Using Finally for Resource Cleanup

`finally` is useful for closing files, database connections, etc.

```python
try:
    f = open("data.txt", "r")
    print(f.read())
except FileNotFoundError:
    print("File not found!")
finally:
    # closing code (cropped in the source image)
```

Output:

```text
File not found!
Closing file...
```

> [!WARNING]
> **Verify:** The code in the source image is cropped after `finally:`. The printed output (`Closing file...`) indicates the `finally` block prints that message; the exact code is not visible, so it is left as a comment above (the snippet is not runnable until the line is completed).

### 19.14 Best Practices

- Use specific exception types.
- Avoid using bare `except`.
- Provide meaningful error messages.
- Use `finally` for cleanup.
- Do not ignore exceptions.
- Log exceptions for debugging.
- Create custom exceptions when needed.
- Keep `try` block minimal.
- *(A further point is cropped in the source image.)*

### 19.15 Key Takeaways

- Exception handling prevents program crash.
- Use `try`, `except`, `else`, `finally`.
- Many built-in exceptions are available.
- We can raise custom exceptions.
- Use specific exception types.
- `finally` block always runs.
- Exception handling improves code reliability and maintainability.

---

## 20 Python Advanced Topics

*Source image: [917342410_1501174672215185_5511122367714413286_n.png](images/917342410_1501174672215185_5511122367714413286_n.png)*

**Powerful Features for Real-World Development** — *"Advanced Python helps you write efficient, scalable and professional code."*

### 20.1 List Comprehension

- A short and concise way to create lists.
- More readable and faster than loops.
- Can also be used with conditions.

**Syntax:**

```python
[expression for item in iterable
 if condition]
```

**Example:**

```python
numbers = [1, 2, 3, 4, 5]
squares = [x**2 for x in numbers]
print(squares)
```

```text
[1, 4, 9, 16, 25]
```

### 20.2 Dictionary Comprehension

- Create dictionaries in a single line.
- Useful for data transformation.
- Can include conditions.

**Syntax:**

```python
{key: value for item in iterable
 if condition}
```

**Example:**

```python
squares = {x: x**2 for x in range(1, 6)}
print(squares)
```

```text
{1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
```

> [!NOTE]
> The output in the source image is slightly garbled (`{1: 12: 4, 3: 9, 4; 16, 5: 25}`); it has been corrected to the output of the code.

### 20.3 Generator and Iterator

- Generators generate values on the fly.
- They save memory (do not store all values).
- Use `yield` instead of `return`.

**Generator Function**

```python
def count(n):
    for i in range(n):
        yield i

for x in count(5):
    print(x)
```

Output: `0 1 2 3 4`

**Iterator Example**

```python
nums = [1, 2, 3]
it = iter(nums)
print(next(it))
print(next(it))
print(next(it))
```

Output: `1 2 3`

### 20.4 Lambda Functions

- A small, anonymous function.
- Used for short and simple operations.
- Useful with `map()`, `filter()`, `sorted()` etc.

**Syntax:**

```python
lambda arguments: expression
```

**Example:**

```python
square = lambda x: x * x
print(square(5))
```

```text
25
```

### 20.5 map(), filter() and reduce()

- `map()` → applies a function to all items.
- `filter()` → filters items based on condition.
- `reduce()` → applies a function cumulatively.

**map()**

```python
nums = [1, 2, 3]
result = list(map(lambda x: x*x, nums))
print(result)
```

Output: `[1, 4, 9]`

**filter()**

```python
nums = [1, 2, 3, 4, 5]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

Output: `[2, 4]`

**reduce()**

```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

Output: `10`

### 20.6 Decorators

- Decorators modify the behaviour of a function.
- Useful for logging, authentication, measuring time etc.

**Syntax:**

```python
@decorator_function
def function_name():
    pass
```

**Example:**

```python
def decorator(func):
    def wrapper():
        print("Before call")
        func()
        print("After call")
    return wrapper

@decorator
def greet():
    print("Hello, Python!")

greet()
```

```text
Before call
Hello, Python!
After call
```

### 20.7 Context Managers (with statement)

- Automatically manage resources (like files, database connections).
- No need to close manually.
- Commonly used with files.

**Syntax:**

```python
with open("file.txt", "r") as f:
    # work with file
```

**Example:**

```python
with open("example.txt", "w") as f:
    f.write("Hello, Python!")
```

> File is automatically closed after block execution.

### 20.8 Regular Expressions (re module)

- Used for pattern matching in text.
- Useful for searching, validation, and data extraction.

**Syntax:**

```python
import re
re.function(pattern, string)
```

**Common Functions:** `re.search()`, `re.findall()`, `re.sub()`, `re.split()`, `re.match()`

**Example:**

```python
import re
text = "My email is aakash@gmail.com"
pattern = r"\w+@\w+\.\w+"
result = re.findall(pattern, text)
print(result)
```

```text
['aakash@gmail.com']
```

### 20.9 Date and Time (datetime module)

- Used to work with dates and time.
- Useful for real-world applications.

**Example:**

```python
from datetime import datetime, timedelta

# current date and time
now = datetime.now()
print("Current:", now)

# date formatting
print(now.strftime("%d-%m-%Y"))

# add days
date_after = now + timedelta(days=5)
print("After 5 days:", date_after)
```

```text
Current: 2026-10-01 14:25:30.123
01-10-2026
After 5 days: 2026-10-06 14:25:30.123
```

### 20.10 JSON Handling

- JSON is used to store and exchange data.
- Python provides the `json` module to work with JSON.

**Python to JSON (Serialize)**

```python
import json
data = {"name": "Aakash", "age": 20}
json_str = json.dumps(data)
print(json_str)
```

```text
{"name": "Aakash", "age": 20}
```

**JSON to Python (Deserialize)**

```python
import json
json_str = '{"name": "Aakash", "age": 20}'
data = json.loads(json_str)
print(data["name"])
```

```text
Aakash
```

> [!NOTE]
> The last line of the deserialize example is slightly garbled in the source image (`sornt(data["name"])`); it is read as `print(data["name"])`, which matches the output `Aakash`.

### 20.11 Working with APIs (requests module)

- Used to send HTTP requests and work with web APIs.
- Common methods: **GET, POST, PUT, DELETE**

**Example:**

```python
import requests

# GET request
response = requests.get(
    "https://jsonplaceholder.typicode.com/users/1"
)
data = response.json()
print(data["name"])
```

```text
Leanne Graham
```

### 20.12 Multithreading

- Run multiple tasks simultaneously using threads.
- Useful for I/O-bound tasks (file download, API calls).

**Example:**

```python
import threading
import time

def task():
    for i in range(5):
        print("Task running:", i)
        time.sleep(1)

thread = threading.Thread(target=task)
thread.start()
thread.join()
```

```text
Task running: 0
Task running: 1
Task running: 2
...
```

### 20.13 Multiprocessing

- Run multiple processes (bypasses GIL).
- Useful for CPU-bound tasks.

**Example:**

```python
from multiprocessing import Process

def task():
    for i in range(5):
        print("Process running:", i)

p = Process(target=task)
p.start()
p.join()
```

```text
Process running: 0
Process running: 1
...
```

### 20.14 Virtual Environment

- Isolates project dependencies.
- Avoids version conflicts.
- Common tools: `venv`, `pip`, `requirements.txt`.

**Commands:**

```bash
# create virtual environment
python -m venv myenv

# activate (Windows)
myenv\Scripts\activate

# activate (Linux/Mac)
source myenv/bin/activate

# install package
pip install package_name
```

**Project Structure:**

```text
my_project/
├── myenv/
├── app.py
└── requirements.txt
```

> [!WARNING]
> **Verify:** The command list is cropped at the bottom of the source image after `pip install package_name`.

### 20.15 Key Takeaways

- List and dictionary comprehensions make code short.
- Generators save memory.
- Lambda functions are useful for small functions.
- `map()`, `filter()`, `reduce()` work with iterables.
- Decorators modify function behaviour.
- Use `with` statement for resource management.
- Regular expressions help in text processing.
- `datetime` module works with date and time.
- JSON and `requests` module are useful for real-world data.
- Multithreading and multiprocessing run tasks in parallel.
- Virtual environments keep projects organized.
- These advanced topics help in building scalable and *(sentence cropped in the source image)*.

---

## 21 Appendix A: Source Image Index

**Batch 1 (images 1–20)**

| No. | Source image file | Sheet / part in these notes |
|-----|-------------------|----------------------|
| 1 | `905960814_1481818451676435_7517671516028661993_n.png` | Python Syntax |
| 2 | `907385142_1145736798215783_373596534573549846_n.png` | Python Data Types |
| 3 | `907385199_2311696312711627_7632425416422047544_n.png` | Modules and Packages – Part A |
| 4 | `910417690_1128530079592166_3480844957796041387_n.png` | Jupyter Notebook |
| 5 | `910494528_1456743733310738_2470051104257098533_n.png` | Python Indentation |
| 6 | `911054339_1692674209249008_569622205817745419_n.png` | Conditional Statements (Part 1) |
| 7 | `911466229_1850593116014153_2429232507120213180_n.png` | Input and Output – Overview |
| 8 | `911722457_1137176358893774_141241251677816285_n.png` | Strings |
| 9 | `912151032_1841547860496924_1176882838050537686_n.png` | VS Code vs PyCharm vs Jupyter |
| 10 | `912225366_1498650025527139_720286302038420067_n.png` | PyCharm |
| 11 | `912290857_2898417180536572_5045525791695421_n.png` | Lists |
| 12 | `912607550_1440663747714422_7714185856196194925_n.png` | File Handling |
| 13 | `912661601_1854501082248613_3486402625889950332_n.png` | Modules and Packages – Part B |
| 14 | `912669198_4521595798079271_435637893235892345_n.png` | Operators (Detailed) – Page 2 |
| 15 | `912822264_1295647442717892_757876294258786212_n__1_.png` | Sets (duplicate of no. 16) |
| 16 | `912822264_1295647442717892_757876294258786212_n.png` | Sets (duplicate of no. 15) |
| 17 | `912910042_1772812510497511_2441295447055638473_n.png` | Conditional Statements (Part 2) |
| 18 | `913163566_1831168741770324_3631393540688622593_n.png` | Pattern Programs |
| 19 | `913213599_2000875744217024_6880538126704627468_n.png` | Object-Oriented Programming (OOP) |
| 20 | `913216772_1171968175353884_7142889038801298485_n.png` | Exception Handling |

**Batch 2 (images 21–40)**

| No. | Source image file | Sheet / part in these notes |
|-----|-------------------|----------------------|
| 21 | `913240555_1963945394989376_1621481622466644759_n.png` | Data Structures (Part 1): Overview |
| 22 | `913243751_1035513369576633_6888401660523142133_n.png` | Dictionaries |
| 23 | `913283532_1074515708941374_8667906599056243279_n.png` | Other Operators, Comments and Basic Programs – Page 3 |
| 24 | `913360589_1776235893450096_7919834115611546755_n.png` | Keywords |
| 25 | `913462751_1194719699554271_5691050946260098258_n.png` | Loops (Part 2) |
| 26 | `913811109_1077684801952358_6312331083628683047_n.png` | Keywords + Identifiers (combined sheet; merged into both lectures) |
| 27 | `914068665_1133145396247751_3718880786210411619_n.png` | Type Conversion / Type Casting |
| 28 | `914173004_1793507131885562_315668360539298013_n.png` | OOP – Practical Guide |
| 29 | `914572447_2259503431296376_1688452425397689166_n.png` | Visual Studio Code (VS Code) |
| 30 | `914587568_1032655613198294_5139468293251605398_n.png` | Python Installation |
| 31 | `914714352_1649384756730473_1267661082653159759_n.png` | Functions |
| 32 | `915038639_1501559435177974_5691446280889856523_n.png` | Python Introduction |
| 33 | `915078776_1491019392925655_3253313825503408403_n.png` | Inheritance and Polymorphism |
| 34 | `915549190_1151093520834320_204868997677325419_n.png` | Input and Output – Detailed Guide |
| 35 | `915876783_1056230370770536_7707649899261796656_n.png` | Identifiers |
| 36 | `916323326_997408003435596_1955084023146934269_n.png` | Loops (Part 1) |
| 37 | `916621664_4625806814354734_3759864615385362655_n.png` | Conditional Statements and Loops (Summary) |
| 38 | `916944782_2110656162952548_369922476097955852_n.png` | Data Structures (Part 2): Lists |
| 39 | `917045627_1619786622643103_1054252101265427733_n.png` | Operators (Overview) – Page 1 |
| 40 | `917342410_1501174672215185_5511122367714413286_n.png` | Advanced Topics |

## 22 Appendix B: Content Verification Summary

**Arrangement.** The 40 images were supplied in no particular order. They are grouped **topic-wise** into 20 topics, and the topics follow a teaching sequence (setup → language basics → operators and I/O → control flow → data structures → functions, modules and files → OOP → exceptions → advanced topics). When several sheets cover one topic (for example Operators Pages 1–3, the two Lists sheets, or the three OOP sheets), they are placed together as separate parts of that topic, so no unique example is lost.

**Duplicates.** Images 15 and 16 (Sets) are identical and merged. The combined Keywords + Identifiers sheet (image 26) is merged into the Keywords and Identifiers parts, with its differences listed.

**Notes.** The Operators material is split over Pages 1, 2 and 3 (three parts of one topic). Tuples are covered only inside *Data Structures (Part 1): Overview*; there is no separate tuple sheet in the images.

**Cropped images.** Many source images are cut off at the bottom edge. Text that could not be read is marked *"cropped in the source image"* and with a **Verify** note.

**Items flagged for verification** (marked `[!WARNING]` in the notes):

- Strings – output of `s[::2]` (`Ptorgamn` in the image vs. `Pto rgamn` in standard Python).
- Keywords – the grid lists 33 words although the title says 35 (`async` and `await` are missing).
- Conditional Statements (Part 2) – `if num >= 3::` read as `if num >= 0:`.
- Conditional Statements and Loops (Summary) – nested-loop output, `range(2, 10, 2)` output (`5` instead of `8`), and the garbled code of the number-pattern example.
- Pattern Programs – `print(i, ...)` vs. the printed output of the Inverted Number Triangle; small-print Diamond Alphabet code.
- Operators (Overview) – assignment operators list shows `==` where `-=` is expected; Bitwise NOT shown as `-5` / `print(-a)` instead of `~5` / `print(~a)`.
- Input and Output (Detailed) – the `format()` example prints `Sum = 10` although the code adds `a + b`.
- Data Structures / Lists (Part 2) – `list1[:-2]` shown with output `40` (matches `list1[-2]`).
- Modules and Packages (Part A) – `random.shuffle()` output shown as `[shuffled list]` (it returns `None` in standard Python).
- OOP – `c.display()` (first sheet) and `d.display()` (second sheet) in the images were corrected to the object names used.
- Exception Handling – code after `finally:` in the resource-cleanup example is cropped.
- Indentation – inconsistent-indentation example shows only two lines in the image.
- Jupyter – `plt.xlabel` / `plt.ylabel` arguments partly hidden.
