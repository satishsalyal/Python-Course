# Python Course 

## Course Information

| Item | Details |
|------|---------|
| Course | Python |

## Table of Contents

- [Introduction](#introduction)
- [Course Information](#course-information)
- [1 VS Code, PyCharm and Jupyter](#1-vs-code-pycharm-and-jupyter)
  - [1.1 What Are These?](#11-what-are-these)
  - [1.2 Key Differences](#12-key-differences)
  - [1.3 Visual Studio Code (VS Code)](#13-visual-studio-code-vs-code)
    - [1.3.1 Overview](#131-overview)
    - [1.3.2 Features](#132-features)
    - [1.3.3 Installation (VS Code)](#133-installation-vs-code)
  - [1.4 PyCharm (Overview)](#14-pycharm-overview)
    - [1.4.1 Overview](#141-overview)
    - [1.4.2 Features](#142-features)
    - [1.4.3 Installation (PyCharm)](#143-installation-pycharm)
  - [1.5 Jupyter Notebook (Overview)](#15-jupyter-notebook-overview)
    - [1.5.1 Overview](#151-overview)
    - [1.5.2 Features](#152-features)
    - [1.5.3 Installation (Jupyter)](#153-installation-jupyter)
  - [1.6 Which One to Use?](#16-which-one-to-use)
  - [1.7 Key Takeaways](#17-key-takeaways)
- [2 PyCharm](#2-pycharm)
  - [2.1 What is PyCharm?](#21-what-is-pycharm)
  - [2.2 Key Features](#22-key-features)
  - [2.3 Versions of PyCharm](#23-versions-of-pycharm)
  - [2.4 System Requirements](#24-system-requirements)
  - [2.5 Installation Steps](#25-installation-steps)
  - [2.6 Flow Diagram (Installation Process)](#26-flow-diagram-installation-process)
  - [2.7 PyCharm User Interface Overview](#27-pycharm-user-interface-overview)
  - [2.8 Running a Python Program](#28-running-a-python-program)
  - [2.9 Use Cases](#29-use-cases)
  - [2.10 Key Takeaways](#210-key-takeaways)
- [3 Jupyter Notebook](#3-jupyter-notebook)
  - [3.1 What is Jupyter Notebook?](#31-what-is-jupyter-notebook)
  - [3.2 Key Features](#32-key-features)
  - [3.3 Components of Jupyter Notebook](#33-components-of-jupyter-notebook)
  - [3.4 Installation Steps](#34-installation-steps)
  - [3.5 Flow Diagram (Working Process)](#35-flow-diagram-working-process)
  - [3.6 Using Jupyter Notebook](#36-using-jupyter-notebook)
  - [3.7 Example](#37-example)
  - [3.8 Use Cases](#38-use-cases)
  - [3.9 Tips](#39-tips)
  - [3.10 Key Takeaways](#310-key-takeaways)
- [4 Python Syntax](#4-python-syntax)
  - [4.1 What is Syntax?](#41-what-is-syntax)
  - [4.2 General Rules of Python Syntax](#42-general-rules-of-python-syntax)
  - [4.3 Basic Structure of a Python Program](#43-basic-structure-of-a-python-program)
  - [4.4 Tokens in Python](#44-tokens-in-python)
  - [4.5 Python Keywords](#45-python-keywords)
  - [4.6 Python Identifiers](#46-python-identifiers)
  - [4.7 Python Statements and Lines](#47-python-statements-and-lines)
  - [4.8 Key Takeaways](#48-key-takeaways)
- [5 Python Indentation](#5-python-indentation)
  - [5.1 What is Indentation?](#51-what-is-indentation)
  - [5.2 Indentation Rules](#52-indentation-rules)
  - [5.3 Visualization of Indentation](#53-visualization-of-indentation)
  - [5.4 Correct vs Incorrect Indentation](#54-correct-vs-incorrect-indentation)
  - [5.5 Common Indentation Errors](#55-common-indentation-errors)
  - [5.6 Flow Diagram (How Indentation Works)](#56-flow-diagram-how-indentation-works)
  - [5.7 More Examples](#57-more-examples)
  - [5.8 Key Takeaways](#58-key-takeaways)
- [6 Python Data Types](#6-python-data-types)
  - [6.1 What are Data Types?](#61-what-are-data-types)
  - [6.2 Types of Data in Python](#62-types-of-data-in-python)
  - [6.3 Built-in Data Types with Examples](#63-built-in-data-types-with-examples)
  - [6.4 Integer (int)](#64-integer-int)
  - [6.5 Float (float)](#65-float-float)
  - [6.6 String (str)](#66-string-str)
  - [6.7 Boolean (bool)](#67-boolean-bool)
  - [6.8 List (list)](#68-list-list)
  - [6.9 Tuple (tuple)](#69-tuple-tuple)
  - [6.10 Set (set)](#610-set-set)
  - [6.11 Dictionary (dict)](#611-dictionary-dict)
  - [6.12 NoneType (None)](#612-nonetype-none)
  - [6.13 Type Checking](#613-type-checking)
  - [6.14 Flow Diagram of Data Types](#614-flow-diagram-of-data-types)
  - [6.15 Key Takeaways](#615-key-takeaways)
- [7 Python Operators (Detailed)](#7-python-operators-detailed)
  - [7.1 Comparison Operators *(source section 4)*](#71-comparison-operators-source-section-4)
  - [7.2 Logical Operators *(source section 5)*](#72-logical-operators-source-section-5)
  - [7.3 Assignment Operators *(source section 6)*](#73-assignment-operators-source-section-6)
  - [7.4 Key Takeaways](#74-key-takeaways)
- [8 Python Input and Output](#8-python-input-and-output)
  - [8.1 What is Input and Output?](#81-what-is-input-and-output)
  - [8.2 Basic Syntax](#82-basic-syntax)
  - [8.3 Flow Diagram](#83-flow-diagram)
  - [8.4 Simple Input and Output](#84-simple-input-and-output)
  - [8.5 Input with Type Conversion](#85-input-with-type-conversion)
  - [8.6 Different Ways to Take Input](#86-different-ways-to-take-input)
  - [8.7 Output Formatting](#87-output-formatting)
  - [8.8 Taking Multiple Inputs – Examples](#88-taking-multiple-inputs--examples)
  - [8.9 Important Points](#89-important-points)
  - [8.10 Common Errors in Input and Output](#810-common-errors-in-input-and-output)
  - [8.11 Key Takeaways](#811-key-takeaways)
- [9 Python Strings](#9-python-strings)
  - [9.1 What is a String?](#91-what-is-a-string)
  - [9.2 Creating Strings](#92-creating-strings)
  - [9.3 String Representation](#93-string-representation)
  - [9.4 Indexing in Strings](#94-indexing-in-strings)
  - [9.5 Slicing in Strings](#95-slicing-in-strings)
  - [9.6 String Length](#96-string-length)
  - [9.7 String Concatenation](#97-string-concatenation)
  - [9.8 String Repetition](#98-string-repetition)
  - [9.9 Checking Membership](#99-checking-membership)
  - [9.10 Common String Methods (1) – Case Conversion Methods](#910-common-string-methods-1--case-conversion-methods)
  - [9.11 Common String Methods (2) – Search and Count Methods](#911-common-string-methods-2--search-and-count-methods)
  - [9.12 Common String Methods (3) – Modify and Split Methods](#912-common-string-methods-3--modify-and-split-methods)
  - [9.13 String Formatting](#913-string-formatting)
  - [9.14 Useful String Methods (More)](#914-useful-string-methods-more)
  - [9.15 Key Takeaways](#915-key-takeaways)
- [10 Python Conditional Statements (Part 1)](#10-python-conditional-statements-part-1)
  - [10.1 What are Conditional Statements?](#101-what-are-conditional-statements)
  - [10.2 Syntax of if Statement](#102-syntax-of-if-statement)
  - [10.3 if Statement – Example](#103-if-statement--example)
  - [10.4 if Statement – Another Example](#104-if-statement--another-example)
  - [10.5 if-else Statement](#105-if-else-statement)
  - [10.6 if-else Statement – Example](#106-if-else-statement--example)
  - [10.7 if-else Statement – Another Example](#107-if-else-statement--another-example)
  - [10.8 Indentation in Conditional Statements](#108-indentation-in-conditional-statements)
  - [10.9 if-else with Input – Example](#109-if-else-with-input--example)
  - [10.10 Multiple Conditions using if-else (Basic)](#1010-multiple-conditions-using-if-else-basic)
  - [10.11 Key Takeaways](#1011-key-takeaways)
- [11 Python Conditional Statements (Part 2)](#11-python-conditional-statements-part-2)
  - [11.1 if-elif-else Statement](#111-if-elif-else-statement)
  - [11.2 Example of if-elif-else](#112-example-of-if-elif-else)
  - [11.3 Check Eligibility Example](#113-check-eligibility-example)
  - [11.4 Nested if Statement](#114-nested-if-statement)
  - [11.5 Nested if Example: Check Age Category](#115-nested-if-example-check-age-category)
  - [11.6 Nested if with Multiple Conditions](#116-nested-if-with-multiple-conditions)
  - [11.7 Nested if-elif-else Example](#117-nested-if-elif-else-example)
  - [11.8 Real-life Example: Login System](#118-real-life-example-login-system)
  - [11.9 Key Takeaways](#119-key-takeaways)
- [12 Python Pattern Programs](#12-python-pattern-programs)
  - [12.1 What are Pattern Programs?](#121-what-are-pattern-programs)
  - [12.2 General Structure using for Loop](#122-general-structure-using-for-loop)
  - [12.3 General Structure using while Loop](#123-general-structure-using-while-loop)
  - [12.4 Star Patterns](#124-star-patterns)
  - [12.5 Number Patterns](#125-number-patterns)
  - [12.6 Character Patterns](#126-character-patterns)
  - [12.7 Key Takeaways](#127-key-takeaways)
  - [12.8 Practice Questions](#128-practice-questions)
  - [12.9 Tips for Better Patterns](#129-tips-for-better-patterns)
- [13 Python Lists](#13-python-lists)
  - [13.1 What is a List?](#131-what-is-a-list)
  - [13.2 Creating Lists](#132-creating-lists)
  - [13.3 List Representation](#133-list-representation)
  - [13.4 Accessing Elements](#134-accessing-elements)
  - [13.5 Slicing in Lists](#135-slicing-in-lists)
  - [13.6 Modifying Elements](#136-modifying-elements)
  - [13.7 Adding Elements](#137-adding-elements)
  - [13.8 Removing Elements](#138-removing-elements)
  - [13.9 List Methods (Common)](#139-list-methods-common)
  - [13.10 List Built-in Functions](#1310-list-built-in-functions)
  - [13.11 List Comprehension](#1311-list-comprehension)
  - [13.12 Nested Lists](#1312-nested-lists)
  - [13.13 Iterating through a List](#1313-iterating-through-a-list)
  - [13.14 Useful Examples](#1314-useful-examples)
  - [13.15 Key Takeaways](#1315-key-takeaways)
- [14 Python Sets](#14-python-sets)
  - [14.1 What is a Set?](#141-what-is-a-set)
  - [14.2 Creating a Set](#142-creating-a-set)
  - [14.3 Set Representation](#143-set-representation)
  - [14.4 Accessing Elements in a Set](#144-accessing-elements-in-a-set)
  - [14.5 Adding Elements](#145-adding-elements)
  - [14.6 Removing Elements](#146-removing-elements)
  - [14.7 Removing Elements – Examples](#147-removing-elements--examples)
  - [14.8 Set Methods (Common)](#148-set-methods-common)
  - [14.9 Updating a Set](#149-updating-a-set)
  - [14.10 Set Operations (Mathematical)](#1410-set-operations-mathematical)
  - [14.11 Set Operations – Examples](#1411-set-operations--examples)
  - [14.12 Set Comprehension](#1412-set-comprehension)
  - [14.13 Important Points](#1413-important-points)
  - [14.14 Practice Questions](#1414-practice-questions)
  - [14.15 Real-World Applications](#1415-real-world-applications)
  - [14.16 Key Takeaways](#1416-key-takeaways)
- [15 Python File Handling](#15-python-file-handling)
  - [15.1 What is File Handling?](#151-what-is-file-handling)
  - [15.2 Types of Files](#152-types-of-files)
  - [15.3 File Modes](#153-file-modes)
  - [15.4 Opening and Closing a File](#154-opening-and-closing-a-file)
  - [15.5 Writing to a File](#155-writing-to-a-file)
  - [15.6 Reading from a File](#156-reading-from-a-file)
  - [15.7 Reading Specific Content](#157-reading-specific-content)
  - [15.8 Appending to a File](#158-appending-to-a-file)
  - [15.9 File Handling with Different Types](#159-file-handling-with-different-types)
  - [15.10 File and Directory Operations](#1510-file-and-directory-operations)
  - [15.11 Working with Paths](#1511-working-with-paths)
  - [15.12 Working with Binary Files](#1512-working-with-binary-files)
  - [15.13 Real-World Example – Log File](#1513-real-world-example--log-file)
  - [15.14 Common Errors](#1514-common-errors)
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
- [17 Python Object-Oriented Programming (OOP)](#17-python-object-oriented-programming-oop)
  - [17.1 What is OOP?](#171-what-is-oop)
  - [17.2 Class and Object](#172-class-and-object)
  - [17.3 Constructor (`__init__`)](#173-constructor-__init__)
  - [17.4 Instance and Class Variables](#174-instance-and-class-variables)
  - [17.5 Methods in a Class](#175-methods-in-a-class)
  - [17.6 Types of Methods – Example](#176-types-of-methods--example)
  - [17.7 Encapsulation](#177-encapsulation)
  - [17.8 Inheritance](#178-inheritance)
  - [17.9 Types of Inheritance](#179-types-of-inheritance)
  - [17.10 Method Overriding (Polymorphism)](#1710-method-overriding-polymorphism)
  - [17.11 Polymorphism](#1711-polymorphism)
  - [17.12 Abstraction](#1712-abstraction)
  - [17.13 Special (Magic) Methods](#1713-special-magic-methods)
  - [17.14 Real-World Example](#1714-real-world-example)
  - [17.15 Key Takeaways](#1715-key-takeaways)
- [18 Python Exception Handling](#18-python-exception-handling)
  - [18.1 What is an Exception?](#181-what-is-an-exception)
  - [18.2 Why Exception Handling?](#182-why-exception-handling)
  - [18.3 Common Built-in Exceptions](#183-common-built-in-exceptions)
  - [18.4 Basic try-except Block](#184-basic-try-except-block)
  - [18.5 Try-Except-Else](#185-try-except-else)
  - [18.6 Try-Except-Finally](#186-try-except-finally)
  - [18.7 Multiple Except Blocks](#187-multiple-except-blocks)
  - [18.8 Catching Multiple Exceptions](#188-catching-multiple-exceptions)
  - [18.9 Raising Exceptions](#189-raising-exceptions)
  - [18.10 Custom Exception](#1810-custom-exception)
  - [18.11 Exception Handling Flowchart](#1811-exception-handling-flowchart)
  - [18.12 Nested Try-Except](#1812-nested-try-except)
  - [18.13 Using Finally for Resource Cleanup](#1813-using-finally-for-resource-cleanup)
  - [18.14 Best Practices](#1814-best-practices)
  - [18.15 Key Takeaways](#1815-key-takeaways)
- [19 Appendix A: Source Image Index](#19-appendix-a-source-image-index)
- [20 Appendix B: Content Verification Summary](#20-appendix-b-content-verification-summary)

---

## 1 VS Code, PyCharm and Jupyter

*Source image: [912151032_1841547860496924_1176882838050537686_n.png](images/912151032_1841547860496924_1176882838050537686_n.png)*

### 1.1 What Are These?

- These are **code editors / IDEs** used to write, run and manage Python programs.
- They help in **coding, debugging, running programs and managing projects**.
- Each tool has different features and is used for different purposes.

### 1.2 Key Differences

| Tool | Type | Best For | Special Feature |
|------|------|----------|-----------------|
| VS Code | Code Editor | General coding (lightweight) | Extensions, fast, customizable |
| PyCharm | IDE | Professional development (large projects) | Advanced tools, debugging, built-in features |
| Jupyter | Notebook | Data science, learning, experiments | Interactive cells, easy visualization |

### 1.3 Visual Studio Code (VS Code)

#### 1.3.1 Overview

- A lightweight and powerful **code editor** by **Microsoft**.
- Supports multiple programming languages including **Python**.
- Highly customizable with **extensions**.
- Suitable for beginners and professionals.

#### 1.3.2 Features

- Fast and lightweight
- Supports extensions
- Integrated terminal
- Git integration
- Debugger
- Customizable themes

#### 1.3.3 Installation (VS Code)

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

### 1.4 PyCharm (Overview)

#### 1.4.1 Overview

- A powerful IDE by **JetBrains** specially designed for Python.
- Provides advanced tools for professional development.
- Suitable for **large projects**.
- Free **Community Edition** and paid **Professional Edition**.

#### 1.4.2 Features

- Smart code completion
- Advanced debugging
- Built-in tools for testing
- Virtual environment support
- Database tools
- Code analysis and refactoring

#### 1.4.3 Installation (PyCharm)

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

### 1.5 Jupyter Notebook (Overview)

#### 1.5.1 Overview

- An open-source web application.
- Used mainly for **data science, research and learning**.
- Allows you to write and run code in **interactive cells**.
- Supports visualization, equations and rich output.

#### 1.5.2 Features

- Interactive coding environment
- Run code cell by cell
- Supports data visualization
- Easy to share notebooks
- Good for Python learning and experimentation

#### 1.5.3 Installation (Jupyter)

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

### 1.6 Which One to Use?

- Use **VS Code** → if you want a lightweight, flexible and general purpose editor.
- Use **PyCharm** → if you are working on large Python projects and want advanced features.

> [!WARNING]
> **Verify:** The source image is cropped at the bottom. The "Which One to Use?" list (a third bullet for Jupyter is likely present) and the "Summary" section are only partly visible. The visible part of the Summary reads: *"All three tools are useful and widely used. VS Code is simple and fast."* The remaining lines (PyCharm and Jupyter) are cut off.

### 1.7 Key Takeaways

- VS Code, PyCharm and Jupyter are tools used to write, run and manage Python programs.
- VS Code is a lightweight, extensible code editor; PyCharm is a full IDE for large projects; Jupyter is a notebook for interactive work.
- All three are useful and widely used.

---

## 2 PyCharm

*Source image: [912225366_1498650025527139_720286302038420067_n.png](images/912225366_1498650025527139_720286302038420067_n.png)*

### 2.1 What is PyCharm?

- PyCharm is a powerful and professional **Integrated Development Environment (IDE)** for Python developed by **JetBrains**.
- It provides **advanced tools** for coding, debugging, testing and project management.
- Suitable for both beginners and professional developers.
- It is specially designed for Python development with smart code completion, refactoring and built-in tools.

### 2.2 Key Features

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

### 2.3 Versions of PyCharm

| Community Edition (Free) | Professional Edition (Paid) |
|--------------------------|-----------------------------|
| Open source | All features of Community |
| Basic Python development features | Web development tools (Django, Flask) |
| Suitable for students and beginners | Database support |
| | Scientific tools |
| | Remote development |
| | More advanced features |

### 2.4 System Requirements

| Requirement | Details |
|-------------|---------|
| Operating System | Windows 10/11, macOS 10.15+, Linux (64-bit) |
| RAM | Minimum 4 GB (8 GB recommended) |
| Storage | Minimum 2.5 GB free space |
| Python | Pre-installed or can be installed during setup |

### 2.5 Installation Steps

1. Visit the official website: <https://www.jetbrains.com/pycharm/>
2. Download Community Edition (free) or Professional Edition.
3. Run the installer (.exe / .dmg / .tar.gz).
4. Follow the installation steps and choose installation location.
5. Launch PyCharm after installation.
6. Select or add Python interpreter.
7. Create a new project and start coding.

### 2.6 Flow Diagram (Installation Process)

```text
Visit JetBrains Website → Download PyCharm Installer → Run Installer → Follow Setup Steps
    → Open PyCharm → Add Python Interpreter → Create New Project
```

### 2.7 PyCharm User Interface Overview

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

### 2.8 Running a Python Program

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

### 2.9 Use Cases

- Web development (Django, Flask)
- Data science and machine learning
- Scientific computing
- Project development
- Competitive programming
- Python automation and scripting
- Professional software development *(partially cut off in the source image)*

> [!WARNING]
> **Verify:** The bottom of the source image is cropped; the final step text of "Running a Python Program" and further Use Cases (if any) are not fully visible.

### 2.10 Key Takeaways

- PyCharm is a JetBrains IDE designed specifically for Python.
- It comes in a free **Community** and a paid **Professional** edition.
- Typical workflow: install → add interpreter → create project → write code → run (Shift + F10).

---

## 3 Jupyter Notebook

*Source image: [910417690_1128530079592166_3480844957796041387_n.png](images/910417690_1128530079592166_3480844957796041387_n.png)*

### 3.1 What is Jupyter Notebook?

- Jupyter Notebook is an **open-source web-based interactive environment** used to write and run Python code in **cells**.
- It allows you to write code, add text (Markdown), equations, images and visualizations in the same document.
- It is widely used in **data science, research, machine learning** and **education**.
- It supports multiple programming languages (Python, R, Julia, etc.), but Python is most commonly used.

### 3.2 Key Features

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

### 3.3 Components of Jupyter Notebook

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

### 3.4 Installation Steps

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

### 3.5 Flow Diagram (Working Process)

```text
Install Python → Install Jupyter (pip install jupyter) → Run (jupyter notebook)
   → Browser opens with Jupyter Dashboard → Create / Open a Notebook
   → Write and run code cell by cell → View output (text, tables, graphs, images)
```

### 3.6 Using Jupyter Notebook

1. Launch Jupyter Notebook.
2. In the browser, you will see the Jupyter Dashboard.
3. Click on **New → Python 3 (ipykernel)** to create a new notebook.
4. Write your Python code in a cell.
5. Press **Shift + Enter** to run the cell.
6. The output will be displayed below the cell.

### 3.7 Example

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

### 3.8 Use Cases

- Data analysis and visualization
- Machine learning model development
- Scientific computing and research
- Teaching and learning Python
- Exploratory data analysis (EDA)
- Project documentation and reporting
- Sharing code with others
- Interactive experiments and prototyping

### 3.9 Tips

- Use Markdown cells to write notes.
- Use **Shift + Enter** to run code.
- Use clear comments in your code.
- You can export notebook as HTML, PDF, etc.
- Install useful libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, etc.

### 3.10 Key Takeaways

- Jupyter Notebook is an open-source, interactive, cell-based environment.
- Install with `pip install jupyter` and start with `jupyter notebook`.
- Use **Shift + Enter** to run a cell; output appears below the cell.
- Widely used for data analysis, machine learning, teaching and sharing code.

---

## 4 Python Syntax

*Source image: [905960814_1481818451676435_7517671516028661993_n.png](images/905960814_1481818451676435_7517671516028661993_n.png)*

### 4.1 What is Syntax?

- Syntax refers to the **set of rules** that define the **structure** of a Python program.
- These rules tell us how to write **valid** Python code.
- If we do not follow the correct syntax, the interpreter will show an **error** (`SyntaxError`).
- Python has a clean syntax which is similar to English and easy to understand.

### 4.2 General Rules of Python Syntax

- Python is case sensitive (`age` and `Age` are different).
- Use proper indentation (more in next page).
- Use quotes for strings (single `' '` or double `" "`).
- Statements are usually written in separate lines.
- Comments start with `#` and are ignored by Python.
- Use meaningful variable names.
- End of statement is usually a new line (no semicolon required).

### 4.3 Basic Structure of a Python Program

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

### 4.4 Tokens in Python

| Token Type | Example | Meaning |
|------------|---------|---------|
| Keywords | `if`, `else`, `for` | Reserved words |
| Identifiers | `name`, `age` | User-defined names |
| Literals | `10`, `3.14`, `"text"` | Fixed values |
| Operators | `+`, `-`, `*`, `/` | Perform operations |
| Separators | `( )`, `[ ]`, `{ }`, `,` | Separate elements |
| Comments | `# This is a comment` | Ignored by Python |

### 4.5 Python Keywords

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

### 4.6 Python Identifiers

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

### 4.7 Python Statements and Lines

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

### 4.8 Key Takeaways

- Syntax is the set of rules defining the structure of a Python program; breaking them raises `SyntaxError`.
- Python is case sensitive and uses `#` for comments.
- Identifiers cannot start with a digit, cannot be keywords and cannot contain spaces or special characters (other than `_`).
- One statement per line is the recommended style.

---

## 5 Python Indentation

*Source image: [910494528_1456743733310738_2470051104257098533_n.png](images/910494528_1456743733310738_2470051104257098533_n.png)*

### 5.1 What is Indentation?

- Indentation means giving **space** at the beginning of a line of code.
- In Python, indentation is used to **define** a block of code (e.g., inside `if`, `for`, `while`, function, class).
- Python does **not use** `{ }` like other languages. It uses **indentation** to show blocks.
- Proper indentation makes the code readable and organized.

### 5.2 Indentation Rules

- Use **4 spaces** per indentation level (recommended).
- Be consistent (use either spaces or tabs).
- Do not mix spaces and tabs.
- All statements at the same level must have the same indentation.
- A new block starts after a colon (`:`) and is indented.
- When the block ends, indentation stops.

### 5.3 Visualization of Indentation

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

### 5.4 Correct vs Incorrect Indentation

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

### 5.5 Common Indentation Errors

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

### 5.6 Flow Diagram (How Indentation Works)

```text
Start → Write a block statement (e.g., if, for, while)
      → Press Enter and indent by 4 spaces
      → Write all statements inside that block
      → When block ends, remove indentation → End
```

### 5.7 More Examples

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

### 5.8 Key Takeaways

- Python uses indentation (not `{ }`) to define blocks.
- Use 4 spaces per level; never mix tabs and spaces.
- A block starts after a colon (`:`); when it ends, indentation stops.
- Wrong indentation causes `IndentationError`.

---

## 6 Python Data Types

*Source image: [907385142_1145736798215783_373596534573549846_n.png](images/907385142_1145736798215783_373596534573549846_n.png)*

### 6.1 What are Data Types?

- A **data type** specifies the **type of value** a variable can store in Python.
- It tells the interpreter how to store and handle the data in memory.
- Python **automatically detects** the data type (we do not need to declare it).
- Different data types are used for different **purposes**.

### 6.2 Types of Data in Python

```text
Python Data Types
├── Built-in Data Types  : int, float, str, bool, list, tuple, set, dict, NoneType
├── User-defined Data Types : class, Objects
└── Special Data Types   : NoneType
```

### 6.3 Built-in Data Types with Examples

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

### 6.4 Integer (int)

- Stores whole numbers (positive, negative and zero).
- No decimal part.

```python
a = 10
b = -5
c = 0
print(a, b, c)
# Output: 10 -5 0
```

### 6.5 Float (float)

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

### 6.6 String (str)

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

### 6.7 Boolean (bool)

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

### 6.8 List (list)

- Ordered collection of items.
- Mutable (can be changed).
- Allows duplicate values.

```python
nums = [1, 2, 3, 4]
nums.append(5)
print(nums)
# Output: [1, 2, 3, 4, 5]
```

### 6.9 Tuple (tuple)

- Ordered collection of items.
- Immutable (cannot be changed).
- Allows duplicate values.

```python
point = (10, 20)
print(point[0])
# Output: 10
```

### 6.10 Set (set)

- Unordered collection.
- Mutable (add/remove items).
- Does not allow duplicates.

```python
s = {1, 2, 2, 3}
s.add(4)
print(s)
# Output: {1, 2, 3, 4}
```

### 6.11 Dictionary (dict)

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

### 6.12 NoneType (None)

- Represents the absence of a value.
- Used when a variable has no value.

```python
x = None
print(x)
# Output: None
```

### 6.13 Type Checking

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

### 6.14 Flow Diagram of Data Types

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

### 6.15 Key Takeaways

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

---

## 7 Python Operators (Detailed)

*Source image: [912669198_4521595798079271_435637893235892345_n.png](images/912669198_4521595798079271_435637893235892345_n.png)*

> [!NOTE]
> The supplied image is labelled **"Page 2"** of the Operators material and starts at section 4 (Comparison Operators). Sections 1–3 (Page 1) were **not included** among the supplied images, so they are not part of these notes. The original section numbers (4, 5, 6) are shown below for reference.

### 7.1 Comparison Operators *(source section 4)*

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

### 7.2 Logical Operators *(source section 5)*

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

### 7.3 Assignment Operators *(source section 6)*

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

### 7.4 Key Takeaways

- Comparison operators compare two values and return `True` or `False`.
- Logical operators `and`, `or`, `not` combine or reverse Boolean results.
- Assignment operators (`+=`, `-=`, `*=`, `/=`, `//=`, `%=`, `**=`) combine an operation with assignment.

---

## 8 Python Input and Output

*Source image: [911466229_1850593116014153_2429232507120213180_n.png](images/911466229_1850593116014153_2429232507120213180_n.png)*

### 8.1 What is Input and Output?

- **Input** means taking data from the user into the program.
- **Output** means displaying the result to the user.
- In Python, we use built-in functions `input()` for input and `print()` for output.
- Input helps the program to work with different user data and makes it interactive.

### 8.2 Basic Syntax

| | Syntax | Description |
|---|--------|-------------|
| **Input** | `variable = input("message")` | Reads input from the user (Always returns a string) |
| **Output** | `print(value1, value2, ...)` | Displays output on the screen |

### 8.3 Flow Diagram

```text
Start → Take input using input() → Process the data (if needed)
      → Display output using print() → End
```

### 8.4 Simple Input and Output

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

### 8.5 Input with Type Conversion

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

### 8.6 Different Ways to Take Input

| Method | Example | Description |
|--------|---------|-------------|
| Single input | `name = input("Enter name: ")` | Takes one value |
| Multiple input in one line | `a, b = input().split()` | Takes multiple values separated by space |
| Multiple input with type conversion | `a, b = map(int, input().split())` | Takes multiple integer values |
| Input of a list | `lst = list(map(int, input().split()))` | Takes a list of integers |
| Input of a string line | `line = input()` | Takes a full line as string |

### 8.7 Output Formatting

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

### 8.8 Taking Multiple Inputs – Examples

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

### 8.9 Important Points

- `input()` always takes input as a string.
- Use type conversion (`int()`, `float()`, etc.) when needed.
- Use `input().split()` for multiple inputs.
- Use `map()` for multiple inputs with type conversion.
- Use f-strings for clean and readable output.
- Input makes the program interactive.
- Always give a meaningful message to the user.
- *(One more point is cut off in the source image; the visible fragment reads: "we can take input of any data type by converting it…")*

### 8.10 Common Errors in Input and Output

| Error | Example | Reason | Solution |
|-------|---------|--------|----------|
| `ValueError` | `int("abc")` | Cannot convert string to integer | Use valid numeric input |
| `TypeError` | `"Hello" + 5` | Cannot add string and integer | Convert integer to string using `str(5)` |
| `IndexError` | `lst[5]` | Index out of range | Check valid index |

> [!WARNING]
> **Verify:** The table in the source image is cropped; further rows (if any) are not visible.

### 8.11 Key Takeaways

- `input()` reads text (always a string); `print()` displays output.
- Convert input with `int()`, `float()`, etc. when numbers are needed.
- `input().split()` and `map()` take multiple values in one line.
- f-strings are the recommended way to format output.

---

## 9 Python Strings

*Source image: [911722457_1137176358893774_141241251677816285_n.png](images/911722457_1137176358893774_141241251677816285_n.png)*

*Tagline: "Strings are sequence of characters used to store text data."* — **Working with Text Data in Python**

### 9.1 What is a String?

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

### 9.2 Creating Strings

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

### 9.3 String Representation

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

### 9.4 Indexing in Strings

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

### 9.5 Slicing in Strings

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

### 9.6 String Length

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

### 9.7 String Concatenation

We can join (concatenate) two or more strings using the `+` operator.

```python
s1 = 'Hello'
s2 = 'Python'
s3 = s1 + ' ' + s2
print(s3)
```

Output: `Hello Python`

### 9.8 String Repetition

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

### 9.9 Checking Membership

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

### 9.10 Common String Methods (1) – Case Conversion Methods

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

### 9.11 Common String Methods (2) – Search and Count Methods

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

### 9.12 Common String Methods (3) – Modify and Split Methods

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

### 9.13 String Formatting

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

### 9.14 Useful String Methods (More)

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

### 9.15 Key Takeaways

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

## 10 Python Conditional Statements (Part 1)

*Source image: [911054339_1692674209249008_569622205817745419_n.png](images/911054339_1692674209249008_569622205817745419_n.png)*

**Make Decisions in a Program**

### 10.1 What are Conditional Statements?

- Conditional statements are used to make decisions in a program.
- They allow the program to execute a block of code based on a condition (True/False).
- In Python, we use `if`, `if-else` and `if-elif-else`.
- Conditions are based on comparison and logical operators.
- They help in making the program **dynamic** and **smart**.

> [!IMPORTANT]
> The program checks a condition and decides which block of code to execute.

### 10.2 Syntax of if Statement

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

### 10.3 if Statement – Example

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

### 10.4 if Statement – Another Example

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

### 10.5 if-else Statement

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

### 10.6 if-else Statement – Example

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

### 10.7 if-else Statement – Another Example

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

### 10.8 Indentation in Conditional Statements

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

### 10.9 if-else with Input – Example

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

### 10.10 Multiple Conditions using if-else (Basic)

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

### 10.11 Key Takeaways

- Conditional statements allow decision making.
- `if` executes when condition is True.
- `if-else` provides two possible paths.
- Condition can be a single statement or a complex expression.
- Python executes only one block (`if` or `else`) based on the condition.
- Use meaningful conditions to make programs dynamic.
- Memory hook from the source: **THINK → CHECK → DECIDE**.

> [!WARNING]
> **Verify:** The Key Points section is cropped at the bottom of the source image; one or more further points (left column) may be missing.

---

## 11 Python Conditional Statements (Part 2)

*Source image: [912910042_1772812510497511_2441295447055638473_n.png](images/912910042_1772812510497511_2441295447055638473_n.png)*

**Multiple Conditions and Nested Conditions**

### 11.1 if-elif-else Statement

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

### 11.2 Example of if-elif-else

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

### 11.3 Check Eligibility Example

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

### 11.4 Nested if Statement

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

### 11.5 Nested if Example: Check Age Category

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

### 11.6 Nested if with Multiple Conditions

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

### 11.7 Nested if-elif-else Example

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

### 11.8 Real-life Example: Login System

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

### 11.9 Key Takeaways

- `if-elif-else` is used for multiple conditions.
- Conditions are checked from top to bottom.
- Nested `if` is used when conditions are dependent.
- Indentation is very important in nested statements.
- `else` block is optional.
- We can nest `if-elif-else` inside each other.
- Helps in handling complex conditions.
- Python uses indentation (spaces) to define blocks *(sentence cropped in the source image)*.
- Memory hook from the source: **CONDITIONS CREATE LOGIC IN YOUR PROGRAM!**

---

## 12 Python Pattern Programs

*Source image: [913163566_1831168741770324_3631393540688622593_n.png](images/913163566_1831168741770324_3631393540688622593_n.png)*

**Using Loops (for, while, nested loops)** — *"Practice Patterns to Build Logic"*

> [!NOTE]
> This lecture uses `for` and `while` loops. A separate lecture on loops was not among the supplied images, so the loop syntax is covered here only as shown on this page.

### 12.1 What are Pattern Programs?

- Pattern programs are used to print different shapes using symbols, numbers or characters.
- They help in understanding the use of **nested loops**.
- Improve logical thinking and problem-solving skills.
- Common in interviews and competitive exams.

### 12.2 General Structure using for Loop

**Syntax:**

```python
for i in range(n):
    for j in range(n):
        # print pattern
```

**Flow Diagram:** Start → Outer loop (i) → Inner loop (j) → Print pattern → End

### 12.3 General Structure using while Loop

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

### 12.4 Star Patterns

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

### 12.5 Number Patterns

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

### 12.6 Character Patterns

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

### 12.7 Key Takeaways

- Use nested loops for pattern programs.
- Control the number of rows and columns using loops.
- Use spaces for proper alignment.
- You can print numbers, characters or symbols.
- *(Further key points are cropped in the source image.)*

### 12.8 Practice Questions

1. Print a hollow triangle.
2. Print a butterfly pattern.
3. Print a number pyramid.
4. Print a mirrored right triangle.
5. *(Further questions, if any, are cropped in the source image.)*

### 12.9 Tips for Better Patterns

- Always visualize the pattern before coding.
- Use nested loops with proper indentation.
- Focus on the relationship between rows and columns.
- Try writing the pattern on paper first.
- *(Further tips, if any, are cropped in the source image.)*

---

## 13 Python Lists

*Source image: [912290857_2898417180536572_5045525791695421_n.png](images/912290857_2898417180536572_5045525791695421_n.png)*

**Ordered, Mutable and Versatile Data Structure** — *"Lists are used to store multiple items in a single variable."*

### 13.1 What is a List?

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

### 13.2 Creating Lists

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

### 13.3 List Representation

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

### 13.4 Accessing Elements

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

### 13.5 Slicing in Lists

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

### 13.6 Modifying Elements

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

### 13.7 Adding Elements

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

### 13.8 Removing Elements

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

### 13.9 List Methods (Common)

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

### 13.10 List Built-in Functions

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

### 13.11 List Comprehension

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

### 13.12 Nested Lists

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

### 13.13 Iterating through a List

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

### 13.14 Useful Examples

1. Create a list of first 10 natural numbers.
2. Find the sum of all elements in a list.
3. Find the largest number in a list.
4. Remove all even numbers from a list.
5. Create a list of squares of even numbers from 1 to 10.

### 13.15 Key Takeaways

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

---

## 14 Python Sets

*Source images: [912822264_1295647442717892_757876294258786212_n.png](images/912822264_1295647442717892_757876294258786212_n.png) and [912822264_1295647442717892_757876294258786212_n__1_.png](images/912822264_1295647442717892_757876294258786212_n__1_.png)*

> [!NOTE]
> The two supplied "Python Sets" images are **identical duplicates**; their content is included once below.

**Unordered, Mutable (Unique Elements) Collection** — *"Sets store unique elements and are useful for removing duplicates."*

### 14.1 What is a Set?

- A set is an **unordered** collection of **unique** elements.
- Elements are written inside curly braces `{ }`.
- Sets do **not** allow duplicate values.
- Sets are **mutable** (elements can be added or removed).
- Sets are used for mathematical operations like union, intersection, etc.

**Syntax:**

```python
set_name = {item1, item2, item3, ...}
```

### 14.2 Creating a Set

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

### 14.3 Set Representation

Sets are unordered, so elements may appear in any order.

```python
s = {10, 20, 30, 40}
```

The set holds the elements 10, 20, 30 and 40. **The order of elements may change when printed.**

### 14.4 Accessing Elements in a Set

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

### 14.5 Adding Elements

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

### 14.6 Removing Elements

We can remove elements using `remove()`, `discard()` and `pop()`.

| Method | Description |
|--------|-------------|
| `remove(x)` | Removes element x. Raises error if not found. |
| `discard(x)` | Removes element x. No error if not found. |
| `pop()` | Removes and returns an arbitrary element. |
| `clear()` | Removes all elements. |

### 14.7 Removing Elements – Examples

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

### 14.8 Set Methods (Common)

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

### 14.9 Updating a Set

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

### 14.10 Set Operations (Mathematical)

- Sets support mathematical operations like union, intersection, difference etc.
- Useful for data analysis and problem solving.

| Operation | Symbol | Method | Meaning |
|-----------|--------|--------|---------|
| Union | `\|` | `union()` | Elements in A or B |
| Intersection | `&` | `intersection()` | Common elements |
| Difference | `-` | `difference()` | Elements in A not in B |
| Symmetric Diff. | `^` | `symmetric_difference()` | Elements in A or B but not both |

### 14.11 Set Operations – Examples

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

### 14.12 Set Comprehension

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

### 14.13 Important Points

- Sets are unordered collections of unique elements.
- Duplicate elements are automatically removed.
- Sets are mutable (can be changed).
- Indexing and slicing are not supported.
- Use `add()`, `update()`, `remove()`, `discard()`, `pop()`, `clear()`.
- Sets support mathematical operations.
- Set comprehension provides a concise way to create sets.

### 14.14 Practice Questions

1. Create a set of first 5 natural numbers.
2. Add 6, 7, 8 to the set `{1, 2, 3, 4, 5}`.
3. Remove the element 3 from the set `{1, 2, 3, 4}`.
4. Find the union and intersection of two sets.
5. Create a set using set comprehension for squares of numbers from 1 to 10.
6. Check if a number exists in a set.

> [!WARNING]
> **Verify:** The bottom of the source image is cropped; further practice questions (if any) are not visible.

### 14.15 Real-World Applications

- Removing duplicate records
- Finding common items between datasets
- Membership testing (e.g., checking users)
- Data analysis and machine learning
- Fast lookup of elements
- *(One more application is partly cropped in the source image.)*

### 14.16 Key Takeaways

- A set stores unique, unordered elements in `{ }`; an empty set must be created with `set()`.
- Sets are mutable but do not support indexing or slicing.
- Set operations (`|`, `&`, `-`, `^`) work like mathematical set operations.

---

## 15 Python File Handling

*Source image: [912607550_1440663747714422_7714185856196194925_n.png](images/912607550_1440663747714422_7714185856196194925_n.png)*

**Read, Write and Work with Files Easily** — *"File handling helps us store data permanently in files like .txt, .csv, .json, etc."*

### 15.1 What is File Handling?

- File handling allows us to work with files stored on disk.
- We can create, read, write, update and delete files.
- Files store data permanently even after the program ends.
- Python provides built-in functions to handle files easily.

```text
Python Program  <── Read / Write ──>  File on Disk
(Data is stored permanently in a file)
```

### 15.2 Types of Files

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

### 15.3 File Modes

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

### 15.4 Opening and Closing a File

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

### 15.5 Writing to a File

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

### 15.6 Reading from a File

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

### 15.7 Reading Specific Content

- `read(n)` → reads n characters.
- `readline()` → reads one line.
- `readlines()` → returns a list of all lines.

```python
with open("sample.txt", "r") as f:
    print(f.read(5))        # first 5 characters
    print(f.readline())     # next line
    print(f.readlines())    # remaining lines as list
```

### 15.8 Appending to a File

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

### 15.9 File Handling with Different Types

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

### 15.10 File and Directory Operations

We can check if a file exists, get its size, rename or delete a file using the `os` module.

```python
import os
print(os.path.exists("sample.txt"))    # True
print(os.path.getsize("sample.txt"))   # size
os.rename("old.txt", "new.txt")        # rename
os.remove("new.txt")                   # delete file
```

### 15.11 Working with Paths

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

### 15.12 Working with Binary Files

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

### 15.13 Real-World Example – Log File

We can create a log file to store application events.

```python
from datetime import datetime
with open("app.log", "a") as f:
    now = datetime.now()
    f.write(f"[{now}] Application started.\n")
```

Each time you run the program, a new entry is added in the log file.

### 15.14 Common Errors

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

### 15.15 Key Takeaways

- Files store data permanently.
- Use `open()` with correct mode.
- Use `with` statement (best practice).
- Text, CSV, JSON and binary files can be handled.
- Use `os` or `pathlib` for path operations.
- Handle exceptions while working with files.
- File handling is widely used in real-world applications like logging, configuration, data storage, etc. *(final words partly cropped in the source image)*.

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

## 17 Python Object-Oriented Programming (OOP)

*Source image: [913213599_2000875744217024_6880538126704627468_n.png](images/913213599_2000875744217024_6880538126704627468_n.png)*

**Organize Code with Real-World Concepts** — *"OOP helps us model real-world problems using classes and objects."*

### 17.1 What is OOP?

- OOP is a programming paradigm based on the concept of "objects".
- It helps us organize code in a structured and reusable way.
- It models real-world entities using classes and objects.
- Main features: **Encapsulation, Abstraction, Inheritance, Polymorphism.**

**Real-World Example:** A **Car (Object)** has *Color, Brand, Speed, Start(), Stop()*.

### 17.2 Class and Object

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

### 17.3 Constructor (`__init__`)

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

### 17.4 Instance and Class Variables

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

### 17.5 Methods in a Class

Methods are functions defined inside a class.

| Type | Description | Example |
|------|-------------|---------|
| Instance Method | Works with object (`self`) | `def show(self)` |
| Class Method | Works with class (`cls`) | `@classmethod` `def show(cls)` |
| Static Method | Does not use `self` or `cls` | `@staticmethod` `def info()` |

### 17.6 Types of Methods – Example

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

### 17.7 Encapsulation

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

### 17.8 Inheritance

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

### 17.9 Types of Inheritance

| Type | Diagram | Example |
|------|---------|---------|
| Single Inheritance | A → B | `class A: pass` / `class B(A): pass` |
| Multiple Inheritance | A, B → C | `class A: pass` / `class B: pass` / `class C(A, B): pass` |
| Multilevel Inheritance | A → B → C | `class A: pass` / `class B(A): pass` / `class C(B): pass` |
| Hierarchical Inheritance | A → B, A → C | `class A: pass` / `class B(A): pass` / `class C(A): pass` |

### 17.10 Method Overriding (Polymorphism)

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

### 17.11 Polymorphism

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

### 17.12 Abstraction

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

### 17.13 Special (Magic) Methods

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

### 17.14 Real-World Example

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

### 17.15 Key Takeaways

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

---

## 18 Python Exception Handling

*Source image: [913216772_1171968175353884_7142889038801298485_n.png](images/913216772_1171968175353884_7142889038801298485_n.png)*

**Handle Errors Gracefully and Make Robust Programs** — *"Exception handling helps us manage runtime errors and prevents the program from crashing."*

### 18.1 What is an Exception?

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

### 18.2 Why Exception Handling?

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

### 18.3 Common Built-in Exceptions

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

### 18.4 Basic try-except Block

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

### 18.5 Try-Except-Else

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

### 18.6 Try-Except-Finally

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

### 18.7 Multiple Except Blocks

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

### 18.8 Catching Multiple Exceptions

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

### 18.9 Raising Exceptions

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

### 18.10 Custom Exception

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

### 18.11 Exception Handling Flowchart

```text
Start → Execute try block → Exception occurs?
          ├── Yes → Execute except block ─┐
          └── No  → Execute else block ───┤
                                          ↓
                          Execute finally block → End
```

### 18.12 Nested Try-Except

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

### 18.13 Using Finally for Resource Cleanup

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

### 18.14 Best Practices

- Use specific exception types.
- Avoid using bare `except`.
- Provide meaningful error messages.
- Use `finally` for cleanup.
- Do not ignore exceptions.
- Log exceptions for debugging.
- Create custom exceptions when needed.
- Keep `try` block minimal.
- *(A further point is cropped in the source image.)*

### 18.15 Key Takeaways

- Exception handling prevents program crash.
- Use `try`, `except`, `else`, `finally`.
- Many built-in exceptions are available.
- We can raise custom exceptions.
- Use specific exception types.
- `finally` block always runs.
- Exception handling improves code reliability and maintainability.

---

## 19 Appendix A: Source Image Index

| No. | Source image file | Topic in these notes |
|-----|-------------------|----------------------|
| 1 | `905960814_1481818451676435_7517671516028661993_n.png` | Python Syntax |
| 2 | `907385142_1145736798215783_373596534573549846_n.png` | Python Data Types |
| 3 | `907385199_2311696312711627_7632425416422047544_n.png` | Modules and Packages – Part A |
| 4 | `910417690_1128530079592166_3480844957796041387_n.png` | Jupyter Notebook |
| 5 | `910494528_1456743733310738_2470051104257098533_n.png` | Python Indentation |
| 6 | `911054339_1692674209249008_569622205817745419_n.png` | Conditional Statements (Part 1) |
| 7 | `911466229_1850593116014153_2429232507120213180_n.png` | Input and Output |
| 8 | `911722457_1137176358893774_141241251677816285_n.png` | Strings |
| 9 | `912151032_1841547860496924_1176882838050537686_n.png` | VS Code, PyCharm and Jupyter |
| 10 | `912225366_1498650025527139_720286302038420067_n.png` | PyCharm |
| 11 | `912290857_2898417180536572_5045525791695421_n.png` | Lists |
| 12 | `912607550_1440663747714422_7714185856196194925_n.png` | File Handling |
| 13 | `912661601_1854501082248613_3486402625889950332_n.png` | Modules and Packages – Part B |
| 14 | `912669198_4521595798079271_435637893235892345_n.png` | Operators (Page 2) |
| 15 | `912822264_1295647442717892_757876294258786212_n__1_.png` | Sets (duplicate of no. 16) |
| 16 | `912822264_1295647442717892_757876294258786212_n.png` | Sets (duplicate of no. 15) |
| 17 | `912910042_1772812510497511_2441295447055638473_n.png` | Conditional Statements (Part 2) |
| 18 | `913163566_1831168741770324_3631393540688622593_n.png` | Pattern Programs |
| 19 | `913213599_2000875744217024_6880538126704627468_n.png` | Object-Oriented Programming |
| 20 | `913216772_1171968175353884_7142889038801298485_n.png` | Exception Handling |

## 20 Appendix B: Content Verification Summary

**Sequencing.** The images were supplied in no particular order. They have been arranged for teaching: tools → syntax → data types → operators → input/output → strings → decision making → patterns → collections → files → modules → OOP → exceptions (exceptions come last because custom exceptions use classes, and the file-handling examples are used in the exception examples).

**Duplicates.** Images 15 and 16 (Sets) are identical and are merged. The two "Modules and Packages" images overlap but each has unique examples, so both are kept (Part A and Part B). "VS Code / PyCharm / Jupyter", "PyCharm" and "Jupyter Notebook" overlap partly and are kept as separate lectures.

**Not in the supplied images.** Operators Page 1 (sections 1–3, e.g. arithmetic operators), and dedicated lectures on loops, tuples, dictionaries and functions were not supplied. They are therefore not included.

**Cropped images.** Several source images are cut off at the bottom edge (Data Types, Input/Output, Strings, Conditional Statements, Pattern Programs, Lists, Sets, File Handling, Modules, OOP, Exception Handling, PyCharm, VS Code/PyCharm/Jupyter). Text that could not be read is marked with *"cropped in the source image"* and with a **Verify** note.

**Items flagged for verification** (marked `[!WARNING]` in the notes):

- Strings – output of `s[::2]` (`Ptorgamn` in the image vs. `Pto rgamn` in standard Python).
- Conditional Statements (Part 2) – `if num >= 3::` read as `if num >= 0:`.
- Pattern Programs – `print(i, ...)` vs. the printed output of the Inverted Number Triangle; small-print Diamond Alphabet code.
- Modules and Packages (Part A) – `random.shuffle()` output shown as `[shuffled list]` (it returns `None` in standard Python).
- OOP – `c.display()` in the image, corrected to `s.display()`.
- Exception Handling – code after `finally:` in the resource-cleanup example is cropped.
- Indentation – inconsistent-indentation example shows only two lines in the image.
- Jupyter – `plt.xlabel` / `plt.ylabel` arguments partly hidden.
