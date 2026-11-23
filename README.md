## 📸 API Testing Screenshots

| Method | Endpoint | Purpose |
|--------|----------|---------|
| `POST` | `/api/register` | Create a new account |
| `POST` | `/api/login` | Log in and get a token |
| `POST` | `/api/komik` | Create a komik |
| `GET` | `/api/komik` | Read komik |
| `PUT` | `/api/komik/:id` | Update a komik |
| `DELETE` | `/api/komik/:id` | Delete a komik |

---

## 🔐 Authentication

### 📝 Register
<img width="800" alt="Register" src="https://github.com/user-attachments/assets/64a66a32-561e-4818-8fb8-0dbbcd2ca00c" />

Creates a new user account. Returns the created user data with `201 Created`.

### 🔑 Login
<img width="800" alt="Login" src="https://github.com/user-attachments/assets/f6f83fe0-cd7b-442d-98af-8d129c52a37f" />

Authenticates the user and returns a token for accessing protected endpoints.

---

## 📦 CRUD Operations

### ➕ POST: Create
<img width="800" alt="POST" src="https://github.com/user-attachments/assets/5403c723-76fd-419f-96dc-93c67a4089f1" />

Creates a new record from the JSON body and returns it with `201 Created`.

### 📄 GET: Read
<img width="800" alt="GET" src="https://github.com/user-attachments/assets/7b7108a7-72eb-489d-893a-651403a54c84" />

Fetches all records, or a single record by ID, with `200 OK`.

### ✏️ PUT: Update
<img width="800" alt="PUT" src="https://github.com/user-attachments/assets/685e5f5d-f05b-436a-8756-b0ba98dcf900" />

Updates an existing record by ID and returns the updated data.

### 🗑️ DELETE: Remove
<img width="800" alt="DELETE" src="https://github.com/user-attachments/assets/746c7f19-3b72-4c26-91ac-ceeeb4dd62d2" />

Deletes a record by ID and returns a confirmation message.
