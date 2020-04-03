# Table of Contents
1. [Introduction](#intro)
2. [Requirements](#requirements)
3. [Installation](#install)  
4. [Usage](#usage)
5. [Notes](#notes)
6. [Troubleshooting](#trouble)
7. [Contributing](#con)
8. [Support](#support)
9. [License](#license)  
<br>

# GPA Calculator <a name="intro"></a>  
This is a simple program that calculates your semster and/or cumulative GPA based
on your grades in the courses you took and how many hours the  various courses are.
<br>  

## Requirements <a name="requirements"></a>  
To run this software, you will need to have Python installed.
You can download that [here.](https://www.python.org/downloads/)

You will also need [WinRAR](https://www.rarlab.com/download.htm) or [7Zip](https://www.7-zip.org/) to open the .zip containing the CalculateGPA.py file.
<br>  

## Installation <a name="install"></a>  
To use this program, download the zip file from [here.](https://github.com/Grabertea/CalculateGPA/archive/master.zip)
Unzip the zip file using WinRAR or 7Zip.
<br>  

## Usage <a name="usage"></a>  

### Step 1

Open up an IDLE shell from your python installation. Click on the File tab, and select "open".

<img src="https://i.imgur.com/bSr1qgm.png">
Navigate to where the CalculateGPA.py file is located on your machine. Select it and click the open button.

<img src="https://i.imgur.com/IBvwzCo.png">
On the window that opens, click on the Run tab and select "run module".

<img src="https://i.imgur.com/ycvng63.png">

### Step 2

You will be asked if it is you first semester. Type "y" for yes and "n" for no.
```python
Is this your first semester (y/n)? 
```

If you entered "y", the program will jump to Step 3.

If you entered "n", then you will be futher prompted to enter your total number of earned credits, and your current cumulative GPA.

```python
Is this your first semester (y/n)? n
Enter total number of earned credits: 65
Enter your current cumulative GPA: 3.65
```

### Step 3

Enter the letter grade (A-F) you recieved for a specific course. See [Notes.](#notes)
```python
Enter grade (hit Enter if done): A
```

### Step 4

For the letter grade you entered in Step 3, enter the number of credit hours for that course.
```python
Enter number of credits: 3
```

### Step 5

Repeat Steps 3 and 4 for your remaining courses, then hit the ENTER key when prompted to enter your next letter grade.
Once you hit ENTER, your semester GPA and new cumulative GPA will be printed out.
```python
Enter grade (hit Enter if done): A
Enter number of credits: 3
Enter grade (hit Enter if done): B
Enter number of credits: 4
Enter grade (hit Enter if done): C
Enter number of credits: 3
Enter grade (hit Enter if done): A
Enter number of credits: 4
Enter grade (hit Enter if done): F
Enter number of credits: 1
Enter grade (hit Enter if done): 

Your semester GPA is 3.07
Your new cumulative GPA is 3.54
```
<br> 

## Notes <a name="notes"></a>  
* This does not support letter grades with a +/-, such as A+, C-, etc. 
* Hitting Enter at the beginning of step 3 without adding a grade will cause the program to crash.
* If this is your first semester, your semester and cumulative GPA will be the same.
<br>  

## Troubleshooting <a name="trouble"></a>  
If you have trouble finding IDLE on your computer, go to where your applications are stored on your machine, and search for "IDLE" or "Python".
<br>  

## Contributing <a name="con"></a>  
Source code located [here.](https://github.com/Grabertea/CalculateGPA)
You can submit a pull request, or email me at 
grabertea@appstate.edu with any suggestions you have.
<br>  

## Support <a name="support"></a>  
If you run into any problems, you 
can email me at grabertea@appstate.edu
<br>

## License <a name="license"></a>  
[MIT](https://choosealicense.com/licenses/mit/)
