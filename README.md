
```
# InventoryManagementSystem

A simple inventory management system built in Java to efficiently manage and organize warehouse products. The system allows you to add, update, delete, and retrieve product details using a HashMap for fast data operations.

## Repository Link

[https://github.com/sgindeed/InventoryManagementSystem](https://github.com/sgindeed/InventoryManagementSystem)

## Features

- Add new products to the inventory
- Update existing product details
- Delete products from the inventory
- Retrieve product details
- Display all products in the inventory

## Project Structure

```
InventoryManagementSystem/
│
├── src/
│   └── inventory/
│       └── management/
│           ├── Product.java
│           ├── InventoryManagementSystem.java
│           └── Main.java
│
└── README.md
```

### Classes

- `Product`: Represents a product with attributes `productId`, `productName`, `quantity`, and `price`.
- `InventoryManagementSystem`: Manages the inventory using a `HashMap<String, Product>`.
- `Main`: Contains the `main` method to demonstrate the functionality of the inventory management system.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- An IDE or text editor of your choice

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/sgindeed/InventoryManagementSystem.git
    ```

2. Open the project in your IDE.

3. Navigate to the `Main` class and run the `main` method to see the inventory management system in action.

### Usage

Here are the primary methods available in the `InventoryManagementSystem` class:

- `addProduct(Product product)`: Adds a new product to the inventory.
- `updateProduct(Product product)`: Updates an existing product's details.
- `deleteProduct(String productId)`: Deletes a product from the inventory using its product ID.
- `getProduct(String productId)`: Retrieves a product's details using its product ID.
- `displayInventory()`: Displays all products in the inventory.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.
```
