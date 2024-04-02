# IMC_trading_2024
This repo is for the algo trading code for IMC trading 2024 competition

# Temporary Code Commit Rule:
1. First please make sure git bash is available for your computer. If not, google git bash and download would be good.
2. For Windows, please run: git clone https://github.com/qunoujiejingti/IMC_trading_2024.git; For Linux SSH, please run: git clone git@github.com:qunoujiejingti/IMC_trading_2024.git (If any access issue happens here please let me know)
3. For any code change, please first create your own branch with following rule: IMC_trading_2024_Round_YourName, for example, IMC_trading_2024_Tutorial_Tongfei, and make all your code change on your branch.
4. You can either create the branch directly from main on remote, or on your local and then push. When push to remote branch, create a pull request and I will review the code together with the contributer to merge the code into main.
5. We will use algo merged into main branch for our competition.

# Kevin's Branch ReadMe:
1. get_data_trader is used for getting data in the sample test.
2. the website will come back with a log file, in playground.ipynb, I have shown how to read the log file and get the data as well as the states
3. logs are stored in the logs folder, so you dont have to do it again
4. in src, the csv is officially provided data, pkl is a list of state for simulating trading environment
5. tutorial_trader is the main file for trading, which is still under construction.
