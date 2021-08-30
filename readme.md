# Binomial class

In this exercise, I extended the distributions package with a new class called Binomial.  
Inside the folder called 4a_binomial_package, there is another folder and these files:
* distributions, which contains the code for the distributions package including Gaussiandistribution.py and Generaldistribution.py code.
* setup.py, a file needed for building Python packages with pip.
* test.py unit tests to help you debug your code.
* numbers.txt and numbers_binomial.txt, which are data files used as part of the unit tests.
* Binomialdistribution.py and Binomialdistribution_challenge.py. Choose one of these files for completing the exercise. Binomialdistribution.py includes more of the code already set up for you. In Binomialdistribution_challenge.py, you'll have to write all of the code from scratch. Both files contain instructions with TODOS to fill out.

When you're ready to test out your code, follow these steps:
1. pip** install your distributions package**. In the terminal, make sure you are in the 4a_binomial_package directory. If not, navigate there by entering the following at the command line:
```Python
cd 4a_binomial_package
pip install
```
2. Run the unit tests. Enter the following.
```Python
python -m unittest test
```
3. incase you add more features or change the functions in the folder after pip installing the package, Python will not know about the changes. When you make changes to the package files, you'll need to run the following:
```Python
pip install --upgrade 
```
