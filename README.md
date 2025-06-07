#Iterating and Checking Keys
product_prices = {"apple": 1.50, "banana": 0.75, "orange": 1.20, "grape": 2.00}
for key in product_prices.keys():
  print (key)
for values in product_prices.values():
  print(values)
print("\n--- Key-Value Pairs ---")
for key, value in product_prices.items():
  print(f"{key}: {value}") 
print("\n--- Key Check: banana ---")
if "banana" in product_prices:
  print("True")
else:
  print("False")
print("\n--- Key Check: kiwi ---")
if "kiwi" in product_prices:
  print("True")
else:
  print("False")
