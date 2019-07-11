# The Crunchy Mouthful
**`Quest giver: Chef Sven`**
>I want to open up a new food cart.  Expand the business, reach new customers, you know the 
typical moves.  I have the location already picked out...  I mean its a cart so there is not a 
set location. Picking out the location was not really difficult.  What I really need help with
 is making the system for purchases.  I am scaling down my menu so I need some different requirements.  Help me and you can have free meals for a month.

##### Objectives
- Create issues on GitHub
- Create pseudocode for your algorithm
- Create a class call `CrunchyMouthful`
    - class should be made in the following location (-> denotes going to a sub-folder)
        - `src` -> `main` -> `java`
- Create a main method in this class
- Check to see if there is somebody waiting to order some food
  - Your program should continue to loop around and ask this question until the answer is no
- As long as there is a person willing to place an order you will need to do the following
- Display to them the menu choices and prices
  - 1. Chipotle Seitan Breakfast Burrito ($11.00)
  - 2. Creole Grilled Tofu ($12.00)
  - 3. Beastmode Burger Deluxe ($12.50)
  - 4. Water ($2.00)
  - 5. Root Beer ($3.00)
  - 6. Display Menu
  - 7. Checkout
- Ask the customer what item(s) they would like to order
  - Customers are allowed to make a maximum of 2 selections to order
  - You must store customer item orders independently, no collections allowed
- Once the customer decides to or has made 2 selections they should checkout
- Upon checkout you should display the items the customer ordered along with individual and total prices for the order
- Ask the customer how much they are paying for their order
- Create a public static method `calculateChange` that takes a two `double` variables as parameters
  - first the user payment
  - second the cart total
- This method should calculate and return how much change the customer is to receive
- If the number returned indicates that the customer still owes money ask them for more money
  - display a new updated amount they owe if they underpay
    - this should not impact the overall cart total
- Continue this process until they have either paid an exact amount or overpaid and need change
- Display to the customer the breakdown of their change in fewest coins and bills as possible

##### Helper
- Make yourself a list of issues on GitHub that you can go through and track and complete
- Your method names and class name must match what is in the directions, variable names can be whatever you wish.  However, remember naming conventions when coming up with variable names
- Think about what the return value would be if the customer underpays (you need to ask them for more money), paid exact amount, or overpaid (you owe them change)
  - You will need a loop and possibly some conditional checks to determine if you need to ask for more money or give change
  - There are a number of solutions for this with multiple correct implementations it comes down to your logic
- When trying to calculate out fewest coins or bills to return you will need to get a remainder at some point and use plan division at other times
  - This is where having pseudocode for your algorithm can play an important role
  - Break this process down with pencil and paper to see how this can be calculated out
- When you push your code back to GitHub the badge on your repo page will indicate if your algorithm is correct
  - if you have failed the build come see me so we can see what test cases failed
- If you wish to run the test cases from within IntelliJ come see me and I can show you what you will need to do
