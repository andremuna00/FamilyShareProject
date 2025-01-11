# FamilyShareProject - Software Engineering Course

![1642956405214](https://github.com/user-attachments/assets/e487232b-74b2-487d-83bf-25c65b584700)
![1642957214341](https://github.com/user-attachments/assets/fe7e3ef5-77dd-4204-a2c5-fbeb2a5e5b83)


## 📁 Project Overview

The FamilyShareProject is a digital platform designed to enable users to share physical items, such as toys, books, and food, or trade them with others. Additionally, it provides features such as a bulletin board for sharing content, Covid-19 tracking, and a dedicated chat system. This project aims to foster both digital and physical sharing while addressing contemporary needs like health safety during a pandemic.

---

## 👥 Team Members
- **Andrea Munarin** - 879607
- **Matteo Minardi** - 880895
- **Giovanni Costa** - 880892
- **Filippo Di Gennaro** - 882795
- **Massimo Cailotto** - 880763

---

## 🎯 Main Objectives

- **Digital Marketplace**:  
  Users can share or trade items (toys, books, food, etc.), and search for them using categories or a search bar.
  
- **Public Bulletin Board**:  
  A board for sharing materials like poems, notes, photos, and videos within the group.

- **Covid-19 Emergency Management**:  
  - Green Pass integration into user profiles.
  - Contagion tracing: Notify users if someone in their family has tested positive, with priority notifications for related activities.

---

## 🔧 Features

### 6.1 Splash Screen
A screen that appears for a short time when the app starts. It informs the user that the application has been launched and shows the logo and development team.

---

### 6.2 Registration Phase

#### 6.2.1 Sign Up - Part 1
The screen appears when a new user chooses to create an account. Personal information is requested to complete the user profile, and the user selects a password, which can be hidden or revealed using an eye icon.

#### 6.2.2 Sign Up - Part 2
This screen appears after the user clicks the “next” button. It asks if the user wants to include information about their child during registration. If yes, personal details and an image of the child can be added. The process ends when the “confirm” button is pressed.

---

### 6.3 Login
The login screen appears after the Splash Screen if the user has created an account. The user must enter their email and password to access the app's functionalities.

---

### 6.4 Homepage
After successful login, the homepage displays the list of groups the user is part of and upcoming activities, providing relevant information. Users can click on items for more details. At the bottom of the page, there is a legend explaining the exclamation point icon.

---

### 6.5 Groups

#### 6.5.1 Create Group
When creating a new group, the user enters a name, a brief description (optional), and adds participants. The group visibility can be set to public or private. After completing the form, pressing [CREATE] creates the group and displays the management screen.

#### 6.5.2 Group Activities
Displays the activities related to a group. Users can manage each activity by clicking on it and can also create new activities using the [ADD ACTIVITY] button.

#### 6.5.3 Group Members
Displays and manages the group’s participants. New members can be added via the [ADD MEMBER(S)] button.

#### 6.5.4 Group Info
Displays and allows editing of the group’s description and visibility settings.

---

### 6.6 Activities

#### 6.6.1 Create Activity - Part 1
Users can create a new activity by providing a title, optional description, optional location, and optional color. After entering the details, users proceed to the next screen.

#### 6.6.2 Create Activity - Part 2
Users set the days and times for the new activity. After filling in the details, the activity can be created by pressing [CREATE].

#### 6.6.3 Activity Info
Displays the details of an activity, such as the description, days and times, volunteers, and children involved.

---

### 6.7 User Info
This screen displays the user's profile details, such as name, email, and the option to upload and view the GreenPass image. It also allows adding or modifying children’s information.

---

### 6.8 Menu and Management
Access the navigation menu by clicking the icon at the top left, displaying all sections of the app. The current section is highlighted with a black arrow, and accessible sections are written in bold.

---

### 6.9 Bulletin Board
In this screen, users can post, download, and if they are the creator, modify or delete media posts. Shared files can be of various formats and include a name, description, author, and upload date. Media can be searched using an icon at the top right.

---

### 6.10 Marketplace
The "Marketplace" section facilitates the exchange or sharing of items between families in the same group. Each item has a description and an image. Users can search for items using keywords or manually browse the list. They can contact the item owner, initiate a trade, cancel a trade/loan, and view the status of an item.


---

## 📖 Table of Contents
- [How to Start](#how-to-start)
- [Configuration](#configuration)
- [Initialization](#initialization)
- [Main Project References](#main-project-references)

---

## 🚀 How to Start

### 📝 Requirements
- Android Studio
- NodeJs

### ⚙️ Configuration
Clone the repository

#### Server Setup
Navigate to the `/server` folder and run:  
```bash
npm install
```

#### Client Setup
Open the `/client` folder in Android Studio. Wait for the indexing and package downloads.  
In Android Studio, navigate to:  
`app > java > com.backbuffalos.familiesshareextended > Retrofit > RetrofitClient`  
Modify the IP and port parameters to link the Android app with the server.

For local testing, use the local machine's IP by running:  
```bash
ipconfig  # (Windows)
```

### 🚀 Initialization

1. Start the server:  
   Navigate to `/server` and run:  
   ```bash
   npm run start
   ```
   The terminal should display:
   ```
   Server started at http://localhost:4000.
   Connected to database
   ```

2. Start the client:  
   In Android Studio, click the "Run" button to launch the app.

---

## 🌐 Main Project References
- [Families Share](https://families-share.eu/)
- [Families Share Toolkit](https://www.families-share-toolkit.eu/)
- [GitHub - Families Share Platform](https://github.com/vilabs/Families_Share-platform)

---

## 👩‍💻 Authors and Copyright

**Black Buffalos Group**  
University of Venice Ca' Foscari
