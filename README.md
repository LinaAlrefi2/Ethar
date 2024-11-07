# 🌟 Ethar Application

**Ethar** is a donation platform designed to connect **donors** and **donees**, making it easy for donors to give and donees to receive items they need. With a few simple steps, **donors** can upload items to donate, while **donees** can browse available items and request what they need, with a limit of five items per month. Built using **JavaFX**, **SQL database**, and following the **MVC (Model-View-Controller)** architectural pattern, Ethar provides a streamlined, user-friendly experience for both parties.

---

## 🌐 Key Features

- **Simple Donation Process for Donors**: Donors can donate items easily by selecting a category and uploading a photo of the item they wish to give.
- **Easy Access for Donees**: Donees can browse available items and select up to five items per month that meet their needs.
- **Efficient Matching System**: Ethar helps ensure donated items reach those who need them most by organizing and limiting requests.
- **Secure Database Management**: All information, including user details and item listings, is managed securely in a SQL database.
- **User-Friendly Interface**: Built with JavaFX, the Ethar application provides a clean, intuitive interface for users on both the donor and donee sides.

---

## 🛠️ Technologies Used

- **JavaFX**: For creating the graphical user interface (GUI) with interactive and visually appealing elements.
- **SQL Database**: Used to store all user and item information securely and efficiently.
- **MVC Architecture**: Organizes the code into Model, View, and Controller components to promote clean code and maintainability.

---

## 📂 Project Structure

Ethar is built using the **MVC (Model-View-Controller)** architecture to separate the application logic, UI, and data handling:

- **Model**: Contains classes that represent the data  manage item and user details, and interact with the SQL database.
- **View**: The user interface built with JavaFX that displays forms, item lists, and the donation/request process for donors and donees.
- **Controller**: The control layer that processes user input, interacts with the Model to handle data updates, and updates the View based on Model changes.

---

## 🎨 How Ethar Works

### For Donors
1. **Select Category**: Donors can select the category for the item they wish to donate .
2. **Upload Photo**: Upload a photo of the item to give donees a clear view of what’s available.
3. **Submit**: The item becomes available for donees to browse and request.

### For Donees
1. **Browse Items**: Donees can browse items available for donation by category.
2. **Select Up to 5 Items**: Each donee can select up to five items per month. This limit ensures fair distribution and helps reach a wider community of donees.
3. **Request Items**: Once requested, the item is marked as reserved and cannot be requested by another donee.

---

## 🚀 Getting Started

### Prerequisites

1. **Java Development Kit (JDK)**: Ensure that JDK 8 or above is installed.
2. **JavaFX SDK**: JavaFX libraries should be set up if not included in your JDK.
3. **SQL Database**: Configure your SQL database and update the database connection settings in the Model layer.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/LinaAlrefi2/Ethar.git
   cd Ethar
   ```

2. **Set Up the Database**:
   - Create a new SQL database and run the provided SQL script (`ethar_schema.sql`) to set up the tables.
   - Update the database connection settings in the **Model** layer files (e.g., `DatabaseConnection.java`) to match your SQL server details.

3. **Run the Application**:
   - Open the project in your preferred IDE.
   - Ensure JavaFX is configured correctly, and run the main application file (e.g., `EtharApp.java`).

---


---

## 🔧 Customization

You can modify or extend Ethar by customizing any of the MVC components:

- **Model**: Adjust the database models or add new tables for additional features.
- **View**: Update the JavaFX layout files to change the UI design, themes, or add new screens.
- **Controller**: Add new functionality by updating controllers to handle more user interactions and process additional data.

---

## 📋 Future Enhancements

Planned or potential features for Ethar include:

- **Notifications**: Alerts to notify donees when their requested items are ready for pickup.
- **User Feedback**: Allow users to leave feedback or rate the donation process.
- **Donation History**: Keep a history of each donor’s and donee’s past donations and requests for easier tracking.
- **Admin Dashboard**: An admin interface to monitor and manage activity, including overseeing donations, user accounts, and inventory.

---

## 🛡 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## 🙏 Acknowledgements

Special thanks to the open-source community for their invaluable resources, and to the JavaFX and SQL developer communities for tools that make Ethar possible.

---

With Ethar, donating and receiving items becomes simple, fair, and impactful. Thank you for using and supporting Ethar! 🎁
