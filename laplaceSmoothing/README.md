# N-Gram Models

This code trains an n-gram language model with laplace smoothing and evaluates its performance for a given n value ("largest_value" in the code as  a variable)

## How to run the codes for the project
- First of all, the programming language used in the code is Python and the version used is Python 3.7
- Moreover, the program uses nucleotide sequences of human genes datasets. Therefore, all four of the datasets ought to be downloaded from [nucleotide sequences of human genes datasets](https://drive.google.com/drive/folders/1w_8mYzMnfGZk0WxHKGXAzvSxWC12-YNO?usp=share_link) and put into the folder called "src".  
- Furthermore, the program uses some external libraries which are listed in "requirements.txt" file inside "src" folder. They ought to be installed. Doing it is actually simple. Start a terminal from "src" folder. Then run "pip install -r requirements.txt" to install them.  
- Lastly, you can run the code by using "python main.py" command after setting the desired n value in the code by using "largest_value" variable.

**Note:** The execution time for the code is in terms of hours and it requires serious amount of memory usage. In my case, however, 16GB of RAM was sufficient  

Musa Nuri İhtiyar