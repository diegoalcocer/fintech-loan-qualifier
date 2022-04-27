# Fintech | iQualify

<!-- ![iQualify: Loan Qualifier](img/iQualify.jpeg) -->
<img style="padding-bottom:20px" src="img/iQualify.jpeg" alt="iQualify: Loan Qualifier" width="150">


The loan qualifier is a **fintech** project implemented in *Python*. It has a user friendly interface (CLI) and handles CSV files.

---

## Technologies

This project is developed using **Python**. It uses different libraries to give a great *user experience* and interaction. **iQualify** analizes the data you input then reads and generates *CSV* files.

🎉 It runs on Windows, Linux/Unix, macOS, and more.

---

## Installation Guide
To run **iQualify**, you need to have *Python* installed on your machine, for more information please visit the [official site](https://www.python.org/downloads/)

📚 To make the *loan qualifier* user friendly, this project imports the following libraries, that need to be installed before running the app
* [questionary](https://github.com/tmbo/questionary)  
```bash
$ pip install questionary
```
* [fire](https://github.com/google/python-fire)
```bash
$ pip install fire
```
⚡ **Important:** If you are using ***conda environments***, remember to activate the desired environment by typing:

```bash
$ conda activate <environment_name>
```
---

## Usage

Clone the app from this repository to start using it. 

![iQualify: Loan Qualifier](img/capture_1_clone.png)

You will find multiple folders with code and a folder for the data (called data 😅). After you have cloned the app, go to the terminal, and navigate to the root folder (📁 **loan_qualifier_app**)

💻 To start the application, simply type the following command 

```bash
$ python app.py
```

The CLI will ask you to input some data in order to calculate:
* The monthly debt to income ratio 
* The loan to value ratio
* Qualifying loans

<img style="padding:20px;" src="img/capture_2_input.png" alt="iQualify: Loan Qualifier">

The app will make the calculations based on the data given in the csv file. Once the calculations are ready, you will be prompted to save the results in a CSV file. 

<img style="padding:20px;" src="img/cp_3_output.png" alt="iQualify: Loan Qualifier">



---

