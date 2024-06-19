# Customer Product Management System

A Java-based application for managing customers and products efficiently. This system allows users to add, update, delete, and view customer and product information.

## Table of Contents
- [Installation](#installation)
- [Changes](#changes)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Contributing](#contributing)
- [Project Report](#project-report)
- [Contact](#contact)



## Installation

#### Step 1 : Clone the Repo

```bash
git clone https://github.com/PurabKeshwani/CustomerProductManagementSystem.git
```
#### Step 2: Install IntelliJ IDEA for Running the Project
[Download Link](https://www.jetbrains.com/idea/download/?section=windows)

#### Step 3: Open the Project
1. Open IntelliJ IDEA.
2. Select Open or Import from the welcome screen.
3. Navigate to the cloned repository folder and select it.
4. Click Open as Project.

## Changes
Ensure the paths for readCustomerJsonFile, readProductJsonFile, and readPurchaseJsonFile are updated in manageCustomer, manageProduct, managePurchase, Controller, and all other relevant locations.

For Example: 
```java
 readCustomerJsonFile("ENTER YOUR CUSTOMERS.JSON FILE PATH");
```


## Usage
The application is designed with a user-friendly interface, making it incredibly straightforward to use. It offers an enjoyable user experience, with tasks easily executed through intuitive button clicks.

## Directory Structure
```css
 LAB 11 JAVA
├── javalab7
│   └── javalab7
│       └── src
│           ├── Controller
│           │   └── Controller.java
│           ├── Main.java
│           ├── Model
│           │   ├── Customers
│           │   │   ├── Customers.java
│           │   │   ├── Customers.json
│           │   │   ├── FileHandlingCustomers.java
│           │   │   ├── manageCustomers.java
│           │   │   └── Person.java
│           │   ├── Displayable.java
│           │   ├── Model.java
│           │   ├── Products
│           │   │   ├── FileHandlingProducts.java
│           │   │   ├── Items.java
│           │   │   ├── manageProducts.java
│           │   │   ├── Products.java
│           │   │   └── Products.json
│           │   └── Purchase
│           │       ├── FileHandlingPurchase.java
│           │       ├── managePurchase.java
│           │       ├── Purchase.java
│           │       └── Purchase.json
│           └── View
│               ├── Customer
│               │   ├── AddPanelCustomer.java
│               │   ├── CenterPanelCustomer.java
│               │   ├── DeleteCustomerPanel.java
│               │   ├── EditCustomerPanel.java
│               │   ├── FirstFrame.java
│               │   ├── InitialPanelCustomer.java
│               │   └── ManageCustomerFrame.java
│               ├── Product
│               │   ├── AddProductPanel.java
│               │   ├── DeleteProductPanel.java
│               │   ├── EditProductPanel.java
│               │   ├── InitialPanelProduct.java
│               │   ├── ManageProductFrame.java
│               │   └── ProductTablePanel.java
│               ├── Purchase
│               │   ├── AddPurchasePanel.java
│               │   ├── DeletePurchasePanel.java
│               │   ├── EditPurchasePanel.java
│               │   ├── InitialPanelPurchase.java
│               │   ├── ManagePurchaseFrame.java
│               │   └── PurchaseTablePanel.java
│               └── View.java
```
## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Project Report

[MINI PROJECT REPORT](https://docs.google.com/document/d/1WpVl4Ge6EuYPrN_FlxM95vSIKYiC1v2vvfbhUGLoz2Y/edit?usp=sharing)


## Contact
Purab Keshwani

Email: purabkeshwani1999@gmail.com






