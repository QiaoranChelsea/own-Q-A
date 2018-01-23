# Q: how to install Plugin in Sublime
Recently, I am coding Idris in Sublime, but unfortunately, sublime didn't recognize idris source file by default. Then, I search a lot about how to make it recognize a new language, finding that there are a lot of fancy packages and themes in Sublime we can install such as SublimeLinter ... 
The following step illustrates how to install package by taking install idris-sublime as example.

## 1. Install Sublime (Skip this step if you've already installed one )
  - Go to website https://www.sublimetext.com 
  - Follow the instruction to install sublimetext editor

## 2. Install Sublime Package Control
  - Open your sublime
  - go to menu named *Tools* and you will see install package control
  - install it by clicking this line

## 3. Add Repository to Sublime Package Control
  - For MAC OS, type 'command + shift + p' to open command pallet
  - Type "repository" and choose "Package Control: Add Repository" in the list
  - Then you will see a textarea in the bottom, copy paste the package url. For example, the url for idris-sublime is (https://github.com/idris-hackers/idris-sublime)  

## 4. Install the Package
  - Now, open Command pallet again by clicking `Command + shift + p`
  - Type or select "Package Control: Install Package"
  - Choose your package name. For example, I'll choose idris-sublime in this case.

## Close the Sublime and Reopen it
  - Now you are good to go :)
