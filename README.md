# 🤖 UiPath RPA Project – Automation Challenges
This repository contains two RPA workflows built with **UiPath** to automate requests of public swagger API book . 

---

🎯 Objective:
-Sending HTTP requests (GET, POST, PUT, DELETE) to a Book API
-Automating the full lifecycle of a book record (Create → Read → Update → Delete)

---
## 📌 Prerequisites
- UiPath Studio 
- Installed dependencies:
  - `UiPath.Form.Activities`
  - `UiPath.System.Activities`
  - `UiPath.Testing.Activities`
  - `UiPath.WebAPI.Activities`
-Internet connection

---
## 📁 Project Structure

RPAchallenges-UIPATH/
├── Dependencies(windows)/
│ ├── UiPath.Form.Activities=25.2.0
│ ├── UiPath.System.Activities=24.10.7
│ ├── UiPath.Testing.Activities=24.1.3
│ ├── UiPath.WebAPI.Activities=1.21.1
│
├── RequestTest /
│ ├──  AddBook.xaml
│ ├──  Delete book.xaml
│ ├──  Get Book by id.xaml
│ ├──  GetBooks.xaml
│ ├──  PutBook.xaml
│── Workflow.xaml
└── README.md

---

### 📂 Workflow Descriptions

-'AddBook.xaml' => Sends a POST request to add a new book
  exemple of data :
  {
    "id": 10,
    "title": "APIs BASES",
    "description": "Book about APIs",
    "pageCount": 50,
    "excerpt": "new book",
    "publishDate": "2025-05-09T15:50:12.611Z"
  }

-'Delete book.xaml' => Sends a DELETE request to remove a book

-'Get Book by id.xaml' => Sends a GET request to retrieve a book details

-'GetBooks.xaml' =>  Sends a GET request to retrieve a list of books

-'PutBook.xaml' =>  Sends a PUT request to update book details

---


## 🧪 How to Run a Request
1. Open the project.
2. Select the workflow of the request needed 
3. Click **Run** to test the request.




