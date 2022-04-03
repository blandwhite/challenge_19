# Blockchain Wallets
UNCC Online FinTech Bootcamp Module 19 Challenge due by 11:59pm 4/17/2022

<img src="Images/19-4-challenge-image.png"/>

Image from [bootcampspot.com](https://courses.bootcampspot.com/courses/980/files/1033423/download)

---

## Background

We work at a startup that is building a new and disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developers, we have been tasked with integrating the Ethereum blockchain network into the application in order to enable our customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

---

## What's Being Created

To complete this Challenge, we will use two Python files, both of which are contained in the starter folder.

 - The first file that we will use is called fintech_finder.py. It contains the code associated with the web interface of our application. The code included in this file is compatible with the Streamlit library. We will write all of our code for this Challenge in this file.

 - The second file that we will use is called crypto_wallet.py. This file contains the Ethereum transaction functions that we have created throughout this module’s lessons. By using import statements, we will integrate the crypto_wallet.py Python script into the Fintech Finder interface program that is found in the fintech_finder.py file.

Integrating these two files will allow us to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.

Specifically, we will assume the perspective of a Fintech Finder customer in order to do the following:

 1. Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

 2. Fetch and display the account balance associated with our Ethereum account address.

 3. Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

 4. Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

 5. Review the transaction hash code associated with the validated blockchain transaction.

---

## Technologies

This application is written in Python 3.7 using Visual Studio Code and Jupyter Lab

 - [Pandas](https://pandas.pydata.org/pandas-docs/stable/) - *an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.*
 - [Streamlit](https://streamlit.io/) - *an open source library that turns data scripts into shareable web apps in minutes.*
 - [Web3.py](https://web3py.readthedocs.io/en/stable/) - *a Python library for interacting with Ethereum.*

### Installation Guide

prior to running these libraries, install them from the command line:
  - pandas: `conda install pandas` or `pip install pandas`  
  - streamlit: `pip install streamlit`
  - web3: `pip install web3`
  
---

## Usage

---

## Contributors
Geoff Tarleton - jobeycat@protonmail.com

adapted from Starter Code supplied by UNCC FinTech Online Bootcamp by Trilogy Educational Services, a 2U, Inc. brand.

---

## License

[MIT](LICENSE)