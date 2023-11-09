# OnlineShoppingGame

# Objective: 

To create a Java program that simulates an online shopping game where players can shop for virtual items, earn points, and make strategic decisions.

# Guidelines
1.Create a base class called VirtualItem with the following attributes and methods:
Attributes:
int itemID (unique identifier for each virtual item).
String name (the name of the item).
double price (the virtual price of the item).
int points (the points that can be earned by purchasing the item).

Methods:
Constructor to initialize the attributes.
Getters and setters for each attribute.
Override the toString() method to provide a formatted string representation of the virtual item.

2.Create two subclasses: PowerUp and Decoration. Each subclass should inherit from the VirtualItem class and have additional attributes and methods:

PowerUp should have attributes like effect (e.g., "double points" or "extra life") and appropriate methods.
Decoration should have attributes like theme (e.g., "space" or "fantasy") and appropriate methods.

3.In the main class (let's call it ShoppingGame), create a list (ArrayList) to store virtual items, including power-ups and decorations. Populate the list with various items, each with different points and effects.

4.Implement a game-like system where the player can:
Start with a set number of points (e.g., 100 points).
Shop for virtual items by choosing from a menu.
Display the details of items in the shopping cart.
Calculate and display the total points earned through purchased items.
Make strategic decisions to maximize their points (e.g., buying power-ups to increase points).
Apply a discount to the total price for purchasing multiple items.
Track and display the remaining points.
End the game when the player decides to quit or runs out of points.






