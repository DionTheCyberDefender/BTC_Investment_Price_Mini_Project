# BTC_Investment_Price_Mini_Project.py
#Bitcoin Investment Value in USD (Calculator)

#1 Ask user for current BTC investment and current BTC price in USD

investment_in_bitcoin = float(input("How much BTC do you own? "))
bitcoin_to_usd = float(input("How much is BTC currently worth in USD? "))

#2) Write a function to calculate BTC Investment Value in usd

def bitcoinToUSD(investment_in_bitcoin, bitcoin_to_usd):
    
    total = investment_in_bitcoin * bitcoin_to_usd
    return total

#3) Use function to calculate the total price of investment in USD

ValuedTotal = bitcoinToUSD(investment_in_bitcoin, bitcoin_to_usd)
print("Your current Bitcoin Investment is worth ", ValuedTotal)
    
import datetime
current_time = datetime.datetime.now()
print(current_time)
