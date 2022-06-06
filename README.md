# Vega
This repository will be used as a virtual classroom for learning python. It will follow the book "Python for Everybody" by Dr. Charles R. Severance which can be found here: http://do1.dr-chuck.com/pythonlearn/EN_us/pythonlearn.pdf

The class is intended for a limited number of students at any given point (~4 max). Students will be enrolled by personal invitation only (unless I find a way to accomodate a large number).

The intent of this class is to give a very personalized learning experience to students as I will be personally reviewing and critiquing the code being submitted with an emphasis on having the students "learn how to learn"

## Required software
- [Anaconda Navigator](https://www.anaconda.com/)
- [Git](https://git-scm.com/downloads)

## Cloning this repository
1. Open your device's terminal / command prompt / git bash
2. Navigate to the directory you wish to use
    - When you open your terminal window, you will likely start on `~/Users/<your-name>`
    - To navigate to a more suitable directory, you can use the `cd <path>` command
    - I would recommend a directory such as Documents, so navigate there by entering the command `cd Documents`
3. Clone this repository
    - Once you have navigated to your desired directory for this project, enter one of the following commands:

      `git clone https://github.com/jjaime2/vega.git`
      
      or
      
      `git clone git@github.com:jjaime2/vega.git`
      
## Creating your personal branch
1. Open your device's terminal / command prompt / git bash
2. Navigate to the `vega` directory
    - e.g. `cd Documents/vega`
3. Once you are in the `vega` directory, enter the following command: `git checkout -b student/<firstname-lastname>`
4. Finally, enter the following command to make your branch available remotely: `git push --set-upstream origin student/<firstname-lastname>`

## Creating a new Spyder Project
1. Open Anaconda Navigator and install/open Spyder
2. With Spyder open, navigator to **Projects -> New Project...**
3. Choose **Existing Directory**
4. Click on the folder icon to the right of **Location**
5. Navigate to the directory where you cloned this repository
    - This will be in `~/Users/<your-name>/Documents/` if you followed the recommendation when cloning the repository
6. Click on the `vega` directory and then click on **Select Folder**
7. Back on the **Create new project** window, click on **Create** to finish

## Navigating your Spyder Project
After creating your new Spyder Project from the contents of the `vega` directory, you should notice that a new window appears on the far left when you open Spyder. This window shows a hierarchy of the files we'll be using for this class starting with `vega` at the very top. If you expand `vega`, you should find another directory named `assignments` which will contain blank `.py` files that correspond to a particular chapter and exercise number from the book. As a student, you will be modifying these files to complete the exercises as you read the book. If a `.py` file does not exist for a particular chapter/exercise from the book, I do not expect you to provide a code-based solution. If you wish to complete those exercises anyway, feel free to, but I will not be reviewing things like multiple-choice exercises.

## Completing Assignments
Assignments will be completed by modifying the existing blank `.py` files corresponding to each chapter/exercise from the book. I suggest that you thoroughly test your solution before finishing so I can give accurate feedback. It is perfectly fine if your implementation does not behave as the book suggests as long as you have personally verified that you have exhausted your options. This class is intended to also introduce you to the concept of code review which I will provide when your assignment has been submitted.

## Submitting Assignments
WIP
