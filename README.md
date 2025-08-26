# JavaFX Inventory Management System

A comprehensive desktop application for managing an inventory of parts and products, built using JavaFX. This application provides a full graphical user interface to handle core inventory operations and demonstrates a clean implementation of the Model-View-Controller (MVC) design pattern.

---

## Key Features

* **Dynamic Product & Part Management:** Easily **Add**, **Modify**, and **Delete** both parts and products.
* **Integrated Parts Association:** Associate multiple parts with a single product.
* **Robust Search:** Quickly find any part or product using the built-in search functionality.
* **Data Validation:** Ensures data integrity with checks for logical business rules (e.g., inventory levels, price constraints).
* **Persistent State:** Inventory data is maintained throughout the application's lifecycle.
* **User-Friendly Interface:** A clean and intuitive UI built with FXML and styled for ease of use.

---

## Screenshots

Here is a look at the application in action.

| Main Form                                                                                               | Add Part Form                                                                                                 | Add Product Form                                                                                                   |
| :------------------------------------------------------------------------------------------------------ | :-------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------- |
| <img src="https://github.com/exxxius/javafx-inventory-app/blob/master/mainform.png?raw=true" alt="Main Form" width="400"/> | <img src="https://github.com/exxxius/javafx-inventory-app/blob/master/addpartform.png?raw=true" alt="Add Part Form" width="400"/> | <img src="https://github.com/exxxius/javafx-inventory-app/blob/master/addproductform.png?raw=true" alt="Add Product Form" width="400"/> |

---

## Technologies & Tools

* **Language:** Java 11+
* **Framework:** JavaFX
* **UI Markup:** FXML
* **Design Tools:** SceneBuilder
* **IDE:** IntelliJ IDEA / NetBeans

---

## Project Structure

The application follows the **Model-View-Controller (MVC)** design pattern to separate concerns and improve maintainability:

* **`/model`**: Contains the data classes (`Part`, `Product`, `Inventory`) that represent the application's core data structures.
* **`/view`**: Contains the FXML files that define the structure and layout of the user interface.
* **`/controller`**: Contains the Java classes that handle user input, process data, and connect the Model and the View.

---

## How To Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/exxxius/javafx-inventory-app.git](https://github.com/exxxius/javafx-inventory-app.git)
    ```
2.  **Open the project** in your favorite Java IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans).
3.  **Configure the JavaFX SDK** for your project if it's not automatically detected.
4.  **Locate and run** the `Main.java` file (or the class that extends `Application`) to start the program.
