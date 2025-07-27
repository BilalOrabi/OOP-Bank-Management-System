# 🏦 OOP Bank Management System

A console-based bank management system developed in C++ by mixing **Object-Oriented Programming (OOP)** and **procedural paradigms**. This application enables users to manage clients, users, currencies, and financial transactions through a layered and modular design, including secure login and user activity tracking.

---

## 📁 Project Structure

The project is organized into logical layers and menus for better readability and scalability:

├── 🧠 Business Logic Layer
│ ├── 🏦 clsBankClient.h
│ ├── 💱 clsCurrency.h
│ ├── 👤 clsPerson.h
│ ├── 🔐 clsUser.h
│ ├── 🌐 Global.h
│ └── 🧬 InterfaceCommunication.h


├── 🏠 Main Menu Screens Layer
│ ├── 📜 clsMainScreen.h
│ ├── 👥 clsClientListScreen.h
│ ├── ➕ clsAddNewClientScreen.h
│ ├── ❌ clsDeleteClientScreen.h
│ ├── 🔍 clsFindClientScreen.h
│ └── 📝 clsUpdateClientScreen.h


├── 💲 Currencies Menu
│ ├── 📋 clsCurrenciesListScreen.h
│ ├── 🧮 clsCurrencyCalculatorScreen.h
│ ├── 🔁 clsCurrencyExchangeMainScreen.h
│ ├── 🔎 clsFindCurrencyScreen.h
│ └── 🧾 clsUpdateCurrencyRateScreen.h


├── 💳 Transactions Menu Screens
│ ├── 💰 clsDepositScreen.h
│ ├── 🧾 clsTotalBalancesScreen.h
│ ├── 📜 clsTransferLogScreen.h
│ ├── 🔁 clsTransferScreen.h
│ └── 💸 clsWithdrawScreen.h


├── 👤 Users Menu Screens
│ ├── ➕ clsAddNewUserScreen.h
│ ├── ❌ clsDeleteUserScreen.h
│ ├── 🔍 clsFindUserScreen.h
│ ├── 👥 clsListUsersScreen.h
│ ├── 🔑 clsLoginRegisterScreen.h
│ ├── ⚙️ clsManageUsersScreen.h
│ └── 📝 clsUpdateUserScreen.h


├── 🧰 Utility Tools
│ ├── 📅 clsDate.h
│ ├── 🛡️ clsInputValidate.h
│ ├── 📆 clsPeriod.h
│ ├── 🔤 clsString.h
│ └── 🧠 clsUtil.h

---

## 🎯 Features

- 🔐 **User Login and Register system** with logging of login history.
- ➕ Add, ❌ delete, 🔍 find, and 📝 update clients and users.
- 💰 Deposit, 💸 withdraw, and 🔁 transfer funds.
- 💱 Currency exchange calculator and rate updater.
- 📊 Transaction summaries and balance sheets.
- 🧼 Clean, modular code using classes and **mixing OOP and procedural paradigms**.

---

## 🧱 Technologies Used

- **Language:** C++
- **Programming Style:** Mixing **Object-Oriented Programming (OOP)** and **Procedural Paradigms**
- **IDE:** Visual Studio 2022
- **Design Pattern:** Layered Architecture (Separation of UI & Logic)
  
---
