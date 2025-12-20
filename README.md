# MEAN-Stack-Assignment

## Q1. What is Web Development?

Web Development is the process of designing, building, and maintaining websites and web-based applications that run on the internet. It involves creating web pages that are visually attractive, functional, secure, and easy to use. Web development ensures that users can access information, submit data, and interact with applications through a web browser.

**Web development generally consists of three major components:**

### **1. Frontend Development:**
This part focuses on the user interface and user experience. It includes everything that users see and interact with on their screen, such as layouts, buttons, forms, and navigation menus. Technologies like HTML, CSS, and JavaScript are commonly used.

### **2. Backend Development:**
Backend development handles the server-side logic of a website. It processes user requests, performs calculations, applies business rules, and communicates with the database. Technologies such as Node.js, PHP, and Python are used for backend development.

### **3. Database Management:**
The database is responsible for storing and managing application data such as user details, login credentials, and records. Databases ensure data can be stored securely and retrieved efficiently.

### **Example:**
- Login page and buttons → Frontend
- Login verification logic → Backend
- Saving user details → Database

<img width="1024" height="572" alt="image" src="https://github.com/user-attachments/assets/917a9c2b-1f13-472a-90a7-6f4c6b6aaaf0" />

---


## Q2. Difference between Frontend and Backend

| Frontend | Backend |
|----------|---------|
| Visible to the user | Works behind the scenes |
| Runs in the browser | Runs on the server |
| HTML, CSS, JavaScript | Node.js, PHP, Python |
| Focuses on UI/UX design | Focuses on data processing |

**Example:**
- Designing the login form → Frontend  
- Checking username and password → Backend

<img width="1024" height="572" alt="image" src="https://github.com/user-attachments/assets/499b1048-0c28-421f-9a9e-43527ee54949" />


---

## Q3. Client–Server Communication

| Client | Server |
|--------|--------|
| Sends request to the server | Receives and processes the request |
| Runs in the browser | Runs on a remote machine |
| Sends URL or form data | Applies application logic |
| Waits for response | Sends response back |

**Steps:**
- Client sends a request (HTTP).
- Server processes the request.
- Server sends a response (HTML / JSON / Data).
- Client displays the result to the user.

**Neat Diagram:**
[ Client / Browser ] 
        |
        |  HTTP Request
        v
[ Server ]
        |
        |  HTTP Response
        v
[ Client / Browser ]

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/42614ac6-fb00-404c-b87d-e3cec063957d" />



---

## Q4. What is MEAN Stack?

MEAN Stack is a full-stack JavaScript technology used to develop modern web applications. It allows developers to use JavaScript for both frontend and backend development, which makes the development process simple and efficient.

| Letter | Technology | Description |
|--------|------------|-------------|
| M | MongoDB | NoSQL database used to store application data |
| E | Express.js | Backend framework for handling requests and routes |
| A | Angular | Frontend framework for building user interfaces |
| N | Node.js | Server-side runtime environment |

**Key Point:**
Using a single programming language (JavaScript) across the entire stack makes development faster, scalable, and easier to manage.

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/48b9b8b4-09e6-48d2-8515-9e223e67b92b" />


---

## Q5. Install Angular CLI using npm

Angular CLI is a command-line tool that helps developers create, build, and manage Angular applications efficiently.

To install Angular CLI, use the following command in the terminal or command prompt:

npm install -g @angular/cli

| Command Part | Description |
|-------------|-------------|
| npm | Node Package Manager |
| -g | Installs the package globally |
| @angular/cli | Angular Command Line Interface |

To verify the installation, use the following command:

ng version


<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/d0870a57-42e4-4e4c-8cef-65e9a5f45a2f" />

---

## Q6. MEAN Architecture Workflow

The MEAN architecture defines how data flows between the client, server, and database in a MEAN Stack web application.

**Workflow Explanation:**
- Angular (Client) takes input from the user and sends a request.
- Express.js with Node.js (Server) receives and processes the request.
- MongoDB (Database) stores and retrieves application data.
- The processed response is sent back to the client.

**Architecture Diagram:**
[ Client (Angular) ]
          |
          v
[ Server (Express + Node.js) ]
          |
          v
[ Database (MongoDB) ]

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/39851e83-6179-45a5-89eb-ed56979b672b" />





