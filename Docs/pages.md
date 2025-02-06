# BookTrackr - Project Pages Documentation

## 1. Home Page (Landing Page)
### **Purpose:**
- Serves as the introduction to BookTrackr.
- Provides an overview of the app’s features and functionality.

### **Features:**
- Welcome message with a brief introduction.
- Call-to-action (CTA) buttons for **Sign Up** and **Login**.
- Basic UI elements for branding (logo, tagline, etc.).

---

## 2. Signup Page
### **Purpose:**
- Allows new users to create an account.

### **Features:**
- Form with fields for:
  - Username
  - Email
  - Password (hashed using bcrypt)
- Validation for required fields.
- Link to the **Login Page** if the user already has an account.

---

## 3. Login Page
### **Purpose:**
- Allows existing users to log into their accounts.

### **Features:**
- Form with fields for:
  - Email
  - Password
- Login validation and authentication.
- Link to **Signup Page** if the user doesn’t have an account.

---

## 4. Dashboard/Profile Page
### **Purpose:**
- Displays an overview of the user's reading progress and account details.

### **Features:**
- **Reading Stats:**
  - Total books added.
  - Number of books in "Want to Read," "Reading," and "Finished" categories.
- List of recently added books with their status.
- View and edit profile information (username, email, password).
- Display reading achievements (e.g., books completed, total reading time if tracked).
- Logout option.

---

## 5. Add New Book Page
### **Purpose:**
- Allows users to add books to their reading list.

### **Features:**
- Form with fields for:
  - Book Title
  - Author
  - Genre
  - Reading Status (Want to Read, Reading, Finished)
- Submit button to save book details in the database.

---

## 6. Book List Page
### **Purpose:**
- Displays all books added by the user.

### **Features:**
- Table or card layout showing book details.
- Sorting and filtering options based on:
  - Reading Status
  - Genre
  - Author
- Clickable book entries for more details.

---

## 7. Book Details Page
### **Purpose:**
- Shows detailed information about a specific book.

### **Features:**
- Display of:
  - Book Title, Author, Genre
  - Current Reading Status
  - Notes or Reviews (if added by the user)
- Options to:
  - Edit book details
  - Delete the book
  - Update reading progress

---

## 8. Logout Functionality
### **Purpose:**
- Logs the user out of their session.

### **Features:**
- Logout button redirects to the **Login Page** after clearing session data.

---