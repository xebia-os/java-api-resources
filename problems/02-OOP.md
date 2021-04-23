### Awesome Bakery

Build a modern bakery shop where items are served from automated vending machines. 

You have two customers Ram and Shaam. Ram has Rs. 5000 and Shaam has Rs. 2500 in their respective e-wallets.

There are two vending machines — first for food items and second for beverages.

Food vending machine has following snacks:

1. 100 Candies each at Rs. 1
2. 50 Muffins each Rs. 50
3. 30 Chocolate cakes each at Rs. 100

Drink vending machine has following beverages

1. 10 Soft drinks each at Rs. 15
2. 20 Apple beers each at Rs. 75

Your job is to write a program that prints cash on hand of each customer and quantity of each item after executing following transactions.

1. Ram buys 30 candies
2. Shaam buys 10 Muffins
3. Shaam buys 5 chocolates 
4. Ram bus 3 chocolate cakes
5. Ram buys 2 Apple beer
6. Shaam buys 3 soft drinks
7. Ram buys 2 soft drinks
8. Shaam father gave Rs. 1000 more to him
9. Shaam buys 5 Chocolate cakes

------

### Student schedule application

- A schedule is a list of lectures, each one defined by subject, day-of-week, start & end times

- Make it possible to create a schedule as described above

- Make it possible to generate 'schedule in time' for a given period of time, defined by start and end dates. For instance, if lectures are defined like this: 

  Math Mondays 8:00-8:45, Tuesdays 10:00-10:45 

  Physics Mondays 9:00-9:45 

  Then a schedule generated for 2016.03.01 (Tue) would contain a single entry, Math

- Make it possible to answer a question 'What lecture is the student at' for any given point in time. That might be a specific lecture, non-working day, a break between lectures, or a time before or after the lectures. To make it more interesting, account for public holidays, for instance 2016.03.11 would result 'non-working day' even though there might be lectures defined for Friday.

- Make it impossible to define invalid schedule -- one with lectures overlapping, starting before 8:00 or ending after 18:00

------

### Elevator

Assuming that we have an elevator that goes from floor to 0 to floor 9 and elevator is available on the 0th floor think about all the classes and interactions between them

Use case 1: Requesting an elevator car

Use case 2: Making a request to 4th floor