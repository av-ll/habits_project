# habits_project
University simple beginner object oriented python project
This README.txt has the purpose of giving instructions on how to run the program. It should work on mac and linux operating systems as well as windows.

the first step is to install anaconda or miniconda if you do not have installed it yet.

You can find it here : https://docs.conda.io/en/latest/miniconda.html

download and install it for your operating system.
 
Then clone this software’s files into a folder in your computer.

git clone https://github.com/av-ll/habits_project

On linux and mac 

open terminal/command line

cd [the directory you cloned into]
 
Run the following commands.

sudo chmod u+x dependencies.sh

(to make the file runnable)

(insert your password)

sudo ./dependencies.sh

after installing the dependencies you just start the program with

ipython habits_app.ipynb

On Windows

Install the required dependencies with

conda install -c anaconda ipython

conda install -c conda-forge freezegun

conda install jupyter

start with 

ipython habits_app.ipynb


Inside the testdata folder

 You can find a pickle file you can copy in the same folder as the python file or vice-versa in order to see some sample data and test usage.
 
 Either way to do this just open run jupyter notebook ,open the file in there and uncomment the import freezegun part and also uncomment the part that uses this library right below that import to simulate the date in the sample test data


