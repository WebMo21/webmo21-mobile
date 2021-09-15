# 🏋️ Fitness Time - Workout Planner Mobile App

A modern mobile application enabling users scheduling and organization of fitness activities.

🌐 [VISIT LIVE WEBSITE](https://www.fitness-time.app)

🎨 [VISIT FRONTEND REPOSITORY](https://github.com/WebMo21/webmo21-frontend)

🖥️ [VISIT BACKEND REPOSITORY](https://github.com/WebMo21/webmo21-backend)

📱 [VISIT MOBILE APP REPOSITORY](https://github.com/WebMo21/webmo21-mobile)

![Preview Mobile App](preview-fitness-time-app.gif)

## ✨ Features

- CRUD for workouts
- CRUD for weekly workout plans
- Add, View, Update, Remove assigned workouts within their weekly workout plan
- Various filters and search functionalities
- Some CRUD for users based on authorization role
- Different functionality for role user and admin
- Language support for German and English

## 🤖 Tech

- Modern client-side based on [Swift](https://swift.org/) through [Xcode](https://developer.apple.com/documentation/Xcode-Release-Notes/xcode-12_5-release-notes)
- Lightweight and modular front-end framework [UIkit](https://getuikit.com/)
- CoreDataStack was implemented to persist structured data locally as an Array of JSON

## 🎨 UI

- Responsive contraints for iOS operated mobile devices (Iphone Xr, 11, 11 pro, 11 pro max, 12, 12pro, 12 pro max)
- Localization works in Apple way. So to change the language the language of the device has to be changed as it is derived of that.
- **Used Images**
  - All used images are either CC0 free to use or their license has been purchased at [Adobe Stock](https://stock.adobe.com) or [flaticon](https://www.flaticon.com)

## 🏗️ Architecture & Design decisions

### 📁 File Structure

- /Fitness_Time
  - Contains App directory with Views, Controllers and Models
- /Fitness_TimeTests
  - Contains tests for business logic
- /Fitness_TimeUITests
  - Contains tests for the User Interface
- /Products
  - Contains the output of the builds

### 📏 Convention & Guidelines

- Use of the regular [conventions of the Swift](https://swift.org/documentation/api-design-guidelines/#protocols-describing-what-is-should-read-as-nouns) programming language

### 📝 Authentication Decisions

For user authentication in the mobile app an email is used.

### 🐛 Downsides & Known Bugs

- Not all functionality could been fulfilled for the mobile app due to time constraints

## 🏠 Getting Started

### ⏹️ Prerequisites

The following applications should be installed before running this software.

```bash
Git
Xcode
```

### Run Mobile App locally

```bash
git clone <Frontend URL>
cd into project
Start Xcode
Use Xcode GUI to Start the App on a simulated target device
```

## 🧮 Organization

🔨 Tools

The Team (as visible below) worked together with a variety of different online tools to achieve the project outcome. Some of them are:

- [Xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12) as code editor of choice
- [Discord](https://discord.com) for communication & screen sharing useful for digital pair programming
- [Git](https://git-scm.com) for working together on the codebase

🌊 Git flow

We used Git Flow to merge code into the codebase with a structured order and keep feature of the software concise. Our design is the following:

- main branch (production environment)
- develop branch (develop environment)

## 👨 Team

| <img src="team-jakob-holz.png" width="200"> | <img src="team-onur-menekse.png" width="200"> | <img src="team-artur-kamrad.png" width="200"> | <img src="team-sascha-majewsky.png" width="200">   |
| ------------------------------------------- | --------------------------------------------- | --------------------------------------------- | -------------------------------------------------- |
| Jakob Holz                                  | Onur Menekse                                  | Artur Kamrad                                  | [Sascha Majewsky](https://github.com/SaschaWebDev) |

## 🔑 License

License under MIT License. See [LICENSE](https://github.com/WebMo21/webmo21-frontend/blob/main/LICENSE) for further information.
