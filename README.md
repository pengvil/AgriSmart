# AgriSmart

### A Simple Mobile App to Support Farmers

AgriSmart is a mobile-based agricultural support system designed to help farmers
and farm-related users access important farming information, organize agricultural
activities, and make better farming decisions.

---

## 📖 About AgriSmart

Agriculture plays an important role in food production, rural livelihood, and the
economy. However, many small and medium-scale farmers face difficulties in
accessing reliable and timely information regarding crop selection, fertilizer
usage, irrigation, pest control, diseases, weather conditions, and market prices.

Farmers may also face problems maintaining farming schedules and remembering
important activities such as:

- Watering
- Fertilizing
- Pesticide application
- Harvesting

AgriSmart aims to bring these essential farming services together into one
simple mobile application.

The application allows users to access crop-related information, manage farming
activities, receive weather information, view crop market prices, and obtain
basic agricultural guidance.

---

# 🎯 Project Objectives

The main objectives of AgriSmart are to:

- Provide easily accessible agricultural information.
- Help farmers organize farming activities.
- Provide crop care and farming guidance.
- Help users monitor weather-related information.
- Provide updated crop market price information.
- Assist farmers with common crop-related problems.
- Maintain organized farm and production information.
- Provide controlled access based on different user roles.

---

# 👥 User Roles

AgriSmart consists of four major system users.

## 👨‍🌾 Farmer

Farmers are the primary users of AgriSmart.

A Farmer can:

- Register an account
- Log in
- Create and update a farming profile
- Search crop information
- View crop details
- Create farming reminders
- View weather notices
- View crop market prices
- Select crop problems
- View agricultural suggestions

---

## 🚜 Farm Owner

Farm Owners can use AgriSmart to organize and manage farm-related information.

A Farm Owner can:

- Register an account
- Log in
- Create and manage a farm profile
- Maintain crop production records
- Manage farming schedules
- View crop market prices
- View weather notices

---

## 🧑‍🌾 Agricultural Field Worker

Agricultural Field Workers provide agricultural support and information through
the system.

A Field Worker can:

- Register an account
- Log in
- Search and view crop information
- View common crop-problem categories
- Provide farming suggestions
- Update suggestions when permission is granted
- View market information
- View weather information

---

## 🛡️ System Admin

The System Admin manages and controls the information available through
AgriSmart.

An Admin can:

- Log in using authorized Admin credentials
- Manage user accounts
- Manage crop information
- Manage crop market prices
- Manage weather notices
- Manage crop-problem categories
- Manage farming suggestions
- Control role-based system access

> The System Admin does **not** register through the normal public registration
> system.

---

# ✨ Major Features

## 🔐 Authentication & Role-Based Access

AgriSmart provides separate access privileges for:

- Farmers
- Farm Owners
- Agricultural Field Workers
- System Admins

The system ensures that users can only access features permitted for their role.

---

## 🌾 Farmer & Farm Management

Users can maintain agricultural information such as:

- Location
- Land size
- Crop type
- Farming category
- Farm name
- Number of workers
- Crop production records
- Planting dates
- Expected harvesting dates

---

## 🌱 Crop Information & Farming Guidance

Users can search for crops and access information including:

- Crop name
- Suitable season
- Soil type
- Crop care instructions
- Basic farming methods

---

## ⏰ Farming Reminders & Schedules

Farmers and Farm Owners can organize agricultural activities such as:

- Watering
- Fertilizing
- Pesticide application
- Harvesting
- Other scheduled farm tasks

---

## 🌦️ Weather Information

AgriSmart provides location-based weather information to help users plan
agricultural activities.

Weather information may include:

- Weather conditions
- Temperature
- Weather warnings
- Location-based notices

---

## 💰 Crop Market Information

Farmers and Farm Owners can view crop market information including:

- Crop name
- Market price
- Market location
- Last update date

---

## 🐛 Crop Problem & Agricultural Support

Farmers can access information about common agricultural problems such as:

- Pest attacks
- Crop diseases
- Irrigation problems
- Fertilizer-related problems

The system can provide:

- Possible causes
- Problem descriptions
- Suggested solutions
- Approved Field Worker/Admin suggestions

---

# 📁 Repository Structure

The current repository contains documentation and simulated user-related files.

```text
AgriSmart/
│
├── README.md
├── CHANGELOG.md
├── PROJECT_FEATURES.md
│
├── farmer.txt
├── farm_owner.txt
├── agricultural_field_worker.txt
└── system_admin.txt

---

# 🚀 Setup

Follow these steps to clone the AgriSmart repository and start working on the project.

## 📥 1. Clone the Repository

Open **Git Bash** in the location where you want to store the project and run:

```bash
git clone https://github.com/pengvi1/AgriSmart.git
```

Move into the project directory:

```bash
cd AgriSmart
```

---

## 👤 2. Configure Your Git Identity

Each team member should configure Git using their own name and email address:

```bash
git config user.name "Your Name"
git config user.email "your-email@example.com"
```
---

## 🌿 3. Check Available Branches

Fetch the latest branch information:

```bash
git fetch --all
```

Then check all local and remote branches:

```bash
git branch -a
```

You should see branches similar to:

```text
main
remotes/origin/feature
remotes/origin/main
remotes/origin/stage
```

---

## 💻 4. Switch to the Feature Branch

All normal development work should be done on the `feature` branch.

```bash
git checkout feature
```

Then download the latest changes:

```bash
git pull origin feature
```

You can confirm your current branch using:

```bash
git branch
```

The `*` should appear beside `feature`:

```text
* feature
  main
  stage
```

---

# 👥 Working as a Team

Before starting any work, always make sure you have the latest version of the `feature` branch:

```bash
git checkout feature
git pull origin feature
```

After making your changes, check which files were modified:

```bash
git status
```

Add your changes:

```bash
git add .
```

Commit your changes with a meaningful message:

```bash
git commit -m "describe your changes"
```

For example:

```bash
git commit -m "feat: update farmer information"
```

Push your work to the shared `feature` branch:

```bash
git push origin feature
```

---

## ✅ Quick Command Reference

Whenever you start working:

```bash
git checkout feature
git pull origin feature
```

After finishing your work:

```bash
git status
git add .
git commit -m "describe your changes"
git push origin feature
```

Always **pull before you start working** so that you have the latest changes made by other team members.