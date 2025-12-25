````md

# 🎌 AnimeApp — Full-Stack Node.js CRUD Application



![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)

![Express](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white)

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)

![EJS](https://img.shields.io/badge/EJS-8B0000)

![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white)

![License](https://img.shields.io/badge/License-Educational-blue)



---



## 📌 Overview



**AnimeApp** is a full-stack CRUD web application built using **Node.js**, **Express.js**, **MongoDB**, and **EJS**.  

It demonstrates core backend concepts such as **MVC architecture**, **database integration with Mongoose**, **server-side rendering**, and **RESTful routing**, combined with a clean and responsive UI powered by **Bootstrap**.



This project is well-suited for:

- 🎓 Students learning backend development  

- 💻 Developers practicing CRUD workflows  

- 📄 Portfolio and resume demonstrations  



---



## ✨ Features



- ✅ Create, Read, Update, Delete (CRUD) anime records  

- 📦 MongoDB integration using Mongoose  

- 🧠 MVC-inspired project structure  

- 🖥 Server-side rendering with EJS templates  

- 🎨 Responsive UI using Bootstrap + custom CSS  

- 📁 Clean, scalable, beginner-friendly codebase  



---



## 🛠 Technologies Used



### Backend

- **Node.js**

- **Express.js**



### Database

- **MongoDB**

- **Mongoose ODM**



### Frontend

- **EJS (Embedded JavaScript Templates)**

- **Bootstrap**

- **Custom CSS**



---



## 📁 Project Structure



```bash

ANIMEAPP/

│

├── config/

│   └── db.config.js          # MongoDB connection setup

│

├── model/

│   └── anime.model.js        # Mongoose schema & model

│

├── public/

│   ├── images/               # Static images & screenshots

│   ├── css/

│   │   ├── bootstrap.min.css

│   │   └── style.css

│   └── js/

│       └── bootstrap.bundle.min.js

│

├── views/

│   ├── home.ejs              # Anime listing page

│   ├── form.ejs              # Add anime page

│   └── edit.ejs              # Edit anime page

│

├── node_modules/

├── package.json

├── package-lock.json

└── server.js                 # Application entry point

````



---



## 🔄 Application Workflow



1. User interacts with the UI in the browser

2. Express server handles HTTP requests

3. Mongoose communicates with MongoDB

4. Controllers process business logic

5. EJS renders dynamic HTML views

6. Bootstrap styles the final UI



---



## 🗄 Database Configuration



Database connection logic is located in:



```bash

config/db.config.js

```



This file initializes the MongoDB connection using Mongoose and ensures the database is connected before handling requests.



---



## ⚙ Installation



### Prerequisites



* Node.js

* npm

* MongoDB (running locally)



### Steps



```bash

git clone https://github.com/JanhviAgrawal/Node.JS.git

cd Node.JS/AnimeApp

npm install

```



---



## ▶ How to Run the Project



```bash

node server.js

```



Open your browser and visit:



```text

http://localhost:3000

```



---



## 🚀 Usage & Routes



| Method | Route         | Description            |

| -----: | ------------- | ---------------------- |

|    GET | `/`           | Display all anime      |

|    GET | `/add`        | Show add anime form    |

|   POST | `/add`        | Save anime to database |

|    GET | `/edit/:id`   | Show edit anime form   |

|   POST | `/update/:id` | Update anime details   |

|    GET | `/delete/:id` | Delete anime record    |



---



## 🖼 Output / Screenshots



> Add screenshots of your application UI inside the `public/images` folder

> and reference them below.



### 🏠 Home Page (Anime List)



![Home Page Output](public/images/home.png)



### ➕ Add Anime Page



![Add Anime Output](public/images/add.png)



### ✏ Edit Anime Page



![Edit Anime Output](public/images/edit.png)



---



## 📌 Sample Output Description



* Home page displays all anime records in a structured list

* Add page allows users to insert new anime details

* Edit page pre-fills existing data for easy updates

* Delete action removes anime records from the database



---



## 🧪 Development Notes



* MVC-inspired architecture

* Server-side rendering (no frontend framework)

* Beginner-friendly yet scalable

* Easy to extend with new features



---



## 🚀 Future Improvements



* Input validation

* Authentication & authorization

* Search and filtering

* Pagination

* REST API version

* Cloud deployment (Render / Railway / AWS)



---



## 🔗 Connect on LinkedIn



Feel free to connect for collaboration, feedback, or opportunities:



**LinkedIn:**

👉 [https://www.linkedin.com/in/your-linkedin-username/](https://www.linkedin.com/in/janhvi-agrawal-j2004)



---



## 👩‍💻 Author



**Janhvi Agrawal**

GitHub: [https://github.com/JanhviAgrawal](https://github.com/JanhviAgrawal)



---



⭐ If you found this project useful, don’t forget to **star the repository** on GitHub!



```

```
