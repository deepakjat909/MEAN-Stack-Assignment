# MEAN-Stack-Assignment

Q1. What is Web Development?

Web Development ka matlab hota hai websites aur web applications banana aur maintain karna.
Isme website ka design, functionality, aur database sab kuch aata hai.

Web development mainly 3 parts me hota hai:

Frontend – jo user screen pe dekhta hai

Backend – jo server side pe kaam karta hai

Database – jaha data store hota hai

Example:

Login page, buttons → Frontend

Login verification → Backend

User details save hona → Database

Q2. Difference between Frontend and Backend (with examples)
Frontend	Backend
User ko jo dikhta hai	User ke peeche ka logic
Browser me run hota hai	Server pe run hota hai
HTML, CSS, JavaScript	Node.js, PHP, Python
UI/UX design	Data processing

Example:

Login form design → Frontend

Username/password check karna → Backend

Q3. Explain Client–Server Communication with a neat diagram

Client–Server communication me client (browser) request bhejta hai aur server response deta hai.

Steps:

Client request bhejta hai (URL / form data)

Server request process karta hai

Server response bhejta hai (HTML / JSON / data)

Client result display karta hai

Diagram:
[ Client / Browser ]
        |
        |  Request (HTTP)
        v
[ Server ]
        |
        |  Response (HTML / Data)
        v
[ Client / Browser ]

Q4. What is MEAN Stack?

MEAN Stack ek full-stack JavaScript technology hai jo web applications banane ke liye use hoti hai.

MEAN ka matlab:

M – MongoDB (Database)

E – Express.js (Backend Framework)

A – Angular (Frontend Framework)

N – Node.js (Server Environment)

Isme JavaScript ek hi language hoti hai frontend aur backend dono ke liye.

Q5. Install Angular CLI using npm

Angular CLI install karne ke liye terminal / command prompt me ye command use hoti hai:

npm install -g @angular/cli


Explanation:

npm → Node Package Manager

-g → globally install

@angular/cli → Angular Command Line Interface

Install hone ke baad check kar sakte hain:

ng version

Q6. Draw the MEAN Architecture Workflow
Workflow Explanation:

Angular (Client) user se input leta hai

Express + Node.js (Server) request handle karta hai

MongoDB (Database) data store / retrieve karta hai

Response wapas client ko milta hai

Diagram:
[ Client (Angular) ]
          |
          v
[ Server (Express + Node.js) ]
          |
          v
[ Database (MongoDB) ]
