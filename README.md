# LaundryBackEndV7
Nodejs Api serving static frontend
<h1 align="center" color="#0000FF">LaundryBackEndV7</h1>

[![KeshavSoft Logo](./KeshavSoft.jpg)](https://keshavsoft.com/)

## **Table of Contents** 📚
- [Overview](#Overview)
- [Key Locations](#keyLocations)
- [Installation](#installation)
- [advanced installation](#advancedinstallation)
- [BackEnd Only](#BackEnd)
- [Folder Structure](#folder-structure)
- [Purpose of the Project](#purpose-of-the-project)
- [Important Points](#important-points)
- [end points testing](#testendpoints)
- [visual studio code extensions](#vscodeextensions)
 
### <a name="overview"></a>## **Overview** 🔎
This project focuses on Laundry operations for JSON files, making it easy to manage and manipulate data. It offers a user-friendly interface for performing essential actions on JSON files, such as creating, reading, updating, and deleting records.
### <a name="keyLocations"></a>## **Key Locations** 🔎
- **Backend:** root:bin, root:binSecured ( for jwt protected end points same as bin ), root:SV7 for new branched End points
- **Database:** root:Data
- **Columns Schemas definition location :** root:Schemas
- **Table Schemas definition location :** root:Schema.json
- **Table Schema to be considered :** root:Data
- **Frontend :** root:public
  
### <a name="installation"></a>## **Installation** 🚀

1. https://git-scm.com/

2. Create a folder and navigate into it using the command prompt.

3. Clone the repository
   ```
   git clone https://github.com/keshavsoft/LaundryBEBranchV7
   ```
4. Change Directory to LaundryBackEndV1 or Open the cloned folder, navigate to LaundryBackEndV1, and open the command prompt.
   ```
    cd LaundryBEBranchV7
   ```
5. Install Node modules
   ```
   npm install
   ```
6. Hold Ctrl + Shift + p 
   ```
   GenDataFromPk OnlyBackEnd
   ```
7. Run .bat Files for Login
   ```
   .\BatchFiles\ForLaundry\V4\forLogin.bat
   ```
8. Run .bat Files for NewOrder
   ```
   .\BatchFiles\ForLaundry\V4\forNewOrders.bat
   ```
9. Run the Application
- ```node app```

### <a name="advancedinstallation"></a>## **advancedinstallation** 🚀

1. https://git-scm.com/

2. Create a folder and navigate into it using the command prompt.

3. Clone the repository
   ```
   git clone https://github.com/keshavsoft/LaundryBackEndV7
   ```
4. Change Directory to LaundryBackEndV1 or Open the cloned folder, navigate to LaundryBackEndV1, and open the command prompt.
   ```
   cd LaundryBackEndV7
   ```
5. Create .env in the root location, and paste the below line to that file
   ```
   PORT=7019
   DataPk=required from root:.env
   ```
6. Run the below command to get frontend login generated
   ```
   node .\BatchFiles\ForLaundry\V4\forLogin.bat
   ```
7. Run the below command to get frontend for NewOrder generated
   ```
   node .\BatchFiles\ForLaundry\V4\forNewOrders.bat
   ```
8. Run the below command to get Backend generated

   Hold Ctrl + Shift + p 
   ```
   GenDataFromPk OnlyBackEnd
   ```
9. For Executing:
   ```
   npm run start
   ```
 
#### **Key Features** 
- **Dynamic Schema Handling:** Define table schemas using JSON files and dynamically generate LaundryBackEndV7 operations.
- **Cross-Platform Compatibility:** Compatible with Windows, Mac, and Linux operating systems.
- **Effortless Setup:** Use provided batch files for Windows or simple commands for other OS to set up the project quickly.
- **Automatic Frontend Setup:** Automatically creates a frontend codebase in the public Versin directory.
#### **Technologies Used** 
- **Node.js:** Leveraging the power of JavaScript on the server-side.
- **Express.js:** A minimal and flexible Node.js web application framework for building robust APIs.
- **SQLite:** A lightweight, file-based database for efficient data storage.
- **npm:** The package manager for Node.js used for installing project dependencies.


### <a name="folder-structure"></a>## **Folder Structure**

```plaintext
├── BatchFiles/
│   └── ForLaundry
├── public/
│   └── JsoncrudBD/
│       └── bin/
│           └── (frontend code)
├── Data/
│   └── JSON/
│       └── 901/
│           └── data.db
├── Project/
│   └── KWSServer
├── Token/
│   
├── Secret/
│   └── Generate
|   └── Lagout
├── app.js
├── Schema.json
├── package.json
├── .env
└── README.md
```

Database location :

Data

### <a name="purpose-of-the-project"></a>## **Purpose of the Project** 🎯
The primary objective is to simplify the process of managing and interacting with JSON files. By automating LaundryBackEndV7 operations, this project aims to enhance efficiency and reduce the complexity of handling JSON data.
### <a name="important-points"></a>## **Important Points** 


for mock testing the end points:

### <a name="vscodeextensions"></a>## **visual studio code extensions** 🚀

for est client or http calling

https://marketplace.visualstudio.com/items?itemName=humao.rest-client

code runner for executing batch files and js files

https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner


finished ui with nice admin

https://github.com/hacktheme/Nice-Admin

now trying to integrate mazer

https://github.com/zuramai/mazer

limitations

1. never use - for any names

for developers

backend : SV7

database : Data

frontend : public/V8
