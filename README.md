# Supermarket Billing System

This is a simple **Supermarket Billing System** implemented in **C++**. It allows users to manage the inventory of the supermarket, generate bills for customers, and update stock levels accordingly.

## Features

- **Display Current Stock**: View the details of products currently in stock.
- **Add a New Product to the Stock**: Add a new product to the inventory with details such as name, ID, price, and quantity.
- **Update Product Details**: Modify the details of an existing product, including its name, price, and quantity.
- **Generate Bill for a Customer**: Create a bill for a customer by adding products to the bill and calculating the total amount.
- **Update Stock Based on Products Sold**: Automatically update the stock levels based on the products sold in the bill.
- **Store Stock to a File**: Save the current stock details to a file for future references.

## Usage

- **Display Current Stock**: Choose option `1` to view the details of products currently in stock.
- **Add a New Product to the Stock**: Choose option `2` to add a new product to the inventory. Enter the details of the product when prompted.
- **Update Product Details**: Choose option `3` to update the details of an existing product. Enter the ID of the product to update and provide the new details.
- **Generate Bill for a Customer**: Choose option `4` to generate a bill for a customer. Enter the details of each product to add to the bill. Once all products are added, the bill will be displayed, and the stock will be updated accordingly.
- **Exit**: Choose option `5` to exit the program.

## File Structure

- `main.cpp`: Contains the main function and user interface.
- `Stock.h` and `Stock.cpp`: Define the `Stock` class and its functions for managing the inventory.
- `Bill.h` and `Bill.cpp`: Define the `Bill` class and its functions for generating bills.
- `stock.txt`: Text file to store the stock details.

## Setup

### 1. Download the Source Code
Download the source code of the project.

### 2. Extract the Files
Extract the downloaded files to a directory on your local machine.

### 3. Compile the Source Code
Open a terminal or command prompt and navigate to the directory where you extracted the files. Then, compile the source code using a C++ compiler:

```bash
g++ main.cpp Stock.cpp Bill.cpp -o SupermarketBilling
```

###4. Run the Executable
Once the compilation is successful, run the executable from the terminal or command prompt:

```bash
./SupermarketBilling
```

## Notes

- **C++ Compiler Required**: Ensure that you have a working C++ compiler (like `g++`) installed on your system.
- **File Organization**: Make sure all necessary files (`main.cpp`, `Stock.h`, `Stock.cpp`, `Bill.h`, `Bill.cpp`, and `stock.txt`) are located in the same directory.
- **Custom File Structure**: If your project uses a different file structure or file names, update the compilation command accordingly.
- **No External Libraries Needed**: This project uses standard C++ libraries. No additional dependencies are required.
- **Data Persistence**: The stock data is saved to a file (`stock.txt`). Ensure you have the necessary permissions to read/write this file in your working directory.
- **Cross-Platform**: The system should work on any OS (Windows, macOS, Linux) with minor adjustments to file paths or compilation commands.

