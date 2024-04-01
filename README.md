# SC3000 Assignment 1
 Balancing a Cartpole using Tabular Q Learning.

## ⭐ Authors
* [@isaacchunn](https://github.com/Neo-Zenith) (Isaac Chun)
* [@Jaysenso](https://github.com/Jaysenso) (J'sen Ong)
* [@Marcushjf](https://github.com/Marcushjf) (Marcus Ho)


## 📁 Folder Structure

```
├── video                   	# Videos recorded for Task 3
├── .gitignore			# -
├── LICENSE			# MIT License
├── README.md			# Readme file
├── cartpole_balancing.ipynb    # Notebook for Assignment 1
├── requirements.txt            # Dependencies for project

```

## 📌 Setting Up

> [!NOTE]
The version of Python used was 3.11.8 with pip installed dependencies. The anaconda version of Python was not used and all dependencies such as numpy, torch were installed using pip.

1. We used the Jupyter notebook extension with Visual Studio Code as our IDE. 
2. Open a terminal in the root directory in Visual Studio Code.
3. Installing dependencies using pip
	```console
	pip install -r requirements.txt
	```

> [!WARNING]
> Torch is listed as a dependency, but it was never used as the repository does not include our custom environment that allowed GPU acceleration. The current files in our repository does not depend on torch and uses the typical Classic Control environment for gym.



