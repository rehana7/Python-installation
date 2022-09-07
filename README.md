# Python installation  

## Installing Python 3 in Windows

* Download the [installer](https://www.python.org/).  
Note: Should have atleast Python 3.8
* Run the Installer, check the box at the bottom of the setup window : "Add Python 3.x to PATH". 

## Verify the Python Installation
* Open the command prompt, terminal or powershell and run the command  
``` 
python --version
```
C:\Users\s545514>python --version
Python 3.10.2

## Creating Data Science Virtual Environment

To create virtual environment run the following command
``` 
python3 -m venv bd-venv 
```
```
C:\Users\s545514>python3 -m venv bd-venv
```
A copy of Python environment is created in th directory bd-venv 
``` 
C:\Users\s545514>dir bd-venv
 Volume in drive C is SSD
 Volume Serial Number is 16C5-7E45

 Directory of C:\Users\s545514\bd-venv

09/07/2022  12:07 PM    <DIR>          .
09/07/2022  12:07 PM    <DIR>          ..
09/07/2022  12:07 PM    <DIR>          Include
09/07/2022  12:07 PM    <DIR>          Lib
09/07/2022  12:07 PM                77 pyvenv.cfg
09/07/2022  12:08 PM    <DIR>          Scripts
               1 File(s)             77 bytes
               5 Dir(s)  89,725,239,296 bytes free

C:\Users\s545514>

``` 
Virtual environment is set up. Whenever we want to use python, need to activate the environment.



