# Mart

This is Swift code that demonstrates object-oriented programming concepts, including inheritance and polymorphism.

The code defines several classes that represent different types of products that a store might sell, such as Perissable, NonPerissable, Legumes, Fruit, Vetement, and ElectroMenager. Each class inherits from the Article class, which defines a few properties and methods that all products share, such as nom (name), prixAchat (purchase price), and prixVente (selling price).

The code also defines a Product struct, which has a name and a category (an enum value that represents whether the product is perishable or non-perishable). Products can be added to an Article instance, which organizes them into categories.

There is also an example of a convenience initializer in the Fruit class, which allows you to create a new Fruit object with a specified name, purchase price, and margin, and it calculates the selling price automatically based on the purchase price and the margin.

The code also has some commented-out code that creates instances of different products and adds them to an array. However, this code is incomplete and contains errors, and would not run correctly as is.
