# Prices_Computers
PC brands and their prices
 
computers = ["Hp","Acer","Lenovo","Asus"]
   prices = [250,320,450,350]

num_computers = len(computers)
print("  We have  " +str(num_computers) + "in our repository")

total_computers = list(zip(prices,computers))
print(total_computers)

total_computers.sort()
print(total_computers)

cheapest = total_computers[0]
print(cheapest)
priciest = total_computers[2]
print(priciest)

four_computers = total_computers[0:3]

num_dollar_slices = prices.count(250)
print(num_dollar_slices)

