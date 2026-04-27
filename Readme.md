# 🍲 Recipe Manager Desktop App

A robust and intuitive **WPF desktop application** built with **C# and .NET**, designed to help users create, manage, filter, and explore detailed recipe structures with ease.

---

## ✨ Features

### 🧾 Create Recipes

* Add recipes with:

  * Name
  * Food group
  * Ingredients (name, quantity, measurement, calories)
  * Step-by-step instructions

### 🔍 Dynamic Filtering

Instantly filter recipes by:

* Ingredient name
* Food group category
* Maximum total calorie count

### 📖 Detailed View

* Expand recipes to view:

  * Structured ingredient breakdown
  * Quantities and measurements
  * Calorie information
  * Preparation steps

### 🔄 Data Management

* Refresh recipe list
* Reset filters
* Load latest updates seamlessly

---

## 🛠️ Tech Stack

* **Language:** C#
* **Framework:** .NET (WPF)
* **UI Markup:** XAML
* **Architecture:** MVVM (Model-View-ViewModel)
* **Data Storage:** Local storage

---

## 🚀 Getting Started

### ✅ Prerequisites

* Visual Studio 2022 or newer
* ".NET desktop development" workload installed

---

### ⚙️ Installation & Running

```bash
git clone https://github.com/Kingh66/Recipe-App-final-version.git
```

1. Open the project

   * Navigate to the folder
   * Double-click the `.sln` file

2. Restore dependencies

   * Right-click solution → **Restore NuGet Packages**

3. Run the application

   * Press **F5** or click **Start**

---

## 📖 How to Use

### ➕ Adding a Recipe

1. Enter recipe name and select a food group
2. Click **Add Ingredient**

   * Fill in details
   * Click **Save Ingredient**
3. Enter preparation steps

   * Press **Enter** to add new steps
4. Click **Save Recipe**

---

### 🔎 Filtering Recipes

* Use filter panel:

  * Ingredient name
  * Food group
  * Max calories
* Click **Apply Filters**

---

### 👀 Viewing Recipe Details

* Click any recipe in the list
* Expand to view full details

---

### 🔄 Refreshing Data

* Click **Refresh Recipes**

  * Clears filters
  * Reloads full dataset

---

## 👨‍💻 Developer Notes

### 🎨 UI & UX Enhancements

* Used `ImageBrush` in XAML for custom background styling
* Clean and modern layout for better usability

### 🔗 Data Binding

* Fully dynamic binding for:

  * Ingredients list
  * Steps list
* UI updates automatically without manual refresh

### 📜 Input Handling

* `Enter` key creates new steps
* Smooth multi-step entry experience

### 📜 Scroll Management

* Integrated `ScrollViewer` for handling long content

### ❌ User Control

* Added **Cancel button** during ingredient creation
* Allows quick input discard without breaking flow

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 💡 Future Improvements (Optional Ideas)

* Cloud sync (Firebase / Azure)
* User authentication
* Recipe image uploads
* Export to PDF
* Nutrition analytics dashboard

---

## 👤 Author

**Sizwe Mthembu**
Software Developer | Focused on clean UI, real-world usability, and scalable systems

---
