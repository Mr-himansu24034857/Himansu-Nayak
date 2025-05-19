# Himansu-Nayak
This Fiel Include All The i did or i am doing especially Python Language .
#Define The Menu Of Resturant
menu={
    'Pizza':40,
    'Burger':80,
    'Pasta':60,
    'Sandwich':50,
    'Salad':30,
    'Soup':20, 

}
#Greet
print("Welcome to the Rajbhog")
print("Pizza:Rs 40\n Burger:Rs 80\n  Pasta:Rs 60\n  Sandwich:Rs 50\n  Salad:Rs 30\n  Soup:Rs 20")

order_total=0
#80+70=150
item_1= input("Enter the names of the item you want to order= ")
if item_1 in menu:
    order_total += menu({item_1})
    print(f"Your item  {item_1} has been added to your ordered")

else :
    print(f"Ordered item {item_1} is not available yet")

Another_order = input("Do you want to order another item? (yes/no) ")
if Another_order== "yes":
    item_2= input("Enter the name of the second item you want to order= ")
    if item_2 in menu:
        order_total += menu({item_2})
        print(f"Your order total is {item_2}")
    else:
        print(f"Ordered item {item_2}is not available yet")
        print(f"Your total order amount of item to pay  is {order_total}")

