# Figure 3.1

```
// pseudo code for a pizza delivery chatbot
print(“Hello, thanks for calling PizzaBot! How may I help you?”)

user_input = “some user response”

if user_input == “I would like to place an order” or “I would like a pizza for delivery”:
 print(‘Sure, I can help with you that. Press 1 for pizza, 2 for other menu items or 3 for condiments. Please note that you can talk to a real human being by pressing 0 at any time’)

user_input = 1 // this comes from the user

if user_input == 1:
 print(“The available pizza sizes are small, medium and large. Please say 1 for small, 2 for medium and 3  for large”)

user_input = “some response from the user”

if user_input:
 print(“Would you like toppings on your pizza? Select 1 for yes or 2 for no.”)

if user_input === 1:
 // continue with the toppings selection flow
if user_input == 2:
 // try to upsell other items

if user_input == 2:
 // kick off the other menu items flow

if user_input == 3:
 // kick off the condiments flow

if user_input == 0:
 // forward user to a real human
else:
 print(‘Sorry, I did not understand your input’)
```
