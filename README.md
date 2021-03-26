# System Analysis and Design Course Project.
# JiDong⚽🏀🏈🏐

## ——Online Sports Community of Tongji University

Members of the project（sort by last name strokes）：杨梓浩，李航宇，郑柯凡，胡启云，曹峰源

- [1.Project Objectives](#1project-objectives)
- [2.Main Functions and Project Features](#2main-functions-and-project-features)
- [3.Expected Users and Key Goals](#3expected-users-and-key-goals)
- [4.Similar Products](#4similar-products)
  - [4.1Function Comparison between Similar Products and Our Product](#41function-comparison-between-similar-products-and-our-product)
  - [4.2Specific Analysis and Innovation](#42specific-analysis-and-innovation)
- [5.Future Development](#5future-development)
- [6.Potential Difficulties in Development](#6potential-difficulties-in-development)
- [7.Related Technology](#7related-technology)
  - [7.1Construction](#71construction)
  - [7.2Data Processing](#72data-processing)
  - [7.3Design](#73design)
- [8.Harvest](#8harvest)
  - [8.1Technology Growth](#81technology-growth)
  - [8.2Teamwork](#82teamwork)
   

## 1. Project Objectives

We hope that by building an online sports community on campus, we can stimulate everyone's enthusiasm for sports through online appointments, personalized sports goal customization, and online interaction.

## 2. Main Functions and Project Features

1. Contact friends and reserve courts. Users who are certified as teachers and students of Tongji University can initiate ball appointment information (including specific details such as sports venues, expected sports time, etc.) to other users on the platform, and users who receive the information can choose whether to accept it. In addition, users can directly reserve the school venue after the appointment is successful.
2. Personalized customization. Users can set specific exercise goals for themselves on the platform, and the platform will also provide personalized exercise customization based on the exercise goals set by the user and user information.
3. Sports club management. All sports clubs can apply for the function of online club management on the platform. After applying, the relevant person in charge of the club can post activity notices and recruit new members on the platform.
4. Content publishing and communication. Users can post sports-related articles, videos and other content on the platform, and can also share their own sports experience, and other users can also leave messages and comments.
5. Other functions: Ranking function, users with the highest rankings can get certain rewards. Provide paid training channels to allow certified users to post information on sports skills training (such as tennis coaches, etc.).

## 3. Expected Users and Key Goals

JiDong is currently mainly for students, faculty and staff of Tongji University. Users can upload all-in-one cards and other materials for authentication. It is hoped that by building an online sports community, it will provide a more convenient way for teachers and students to exercise, promote users' sports communication, stimulate users' sports enthusiasm, and promote the sports atmosphere on campus.

## 4. Similar Products

### 4.1 Function Comparison between Similar Products and Our Product

| Platforms          | Personalized Customization | Community Communication | Stadium Reservation | Ranking | For Campus |
| :----------------- | -------------------------- | ----------------------- | ------------------- | ------- | ---------- |
| Keep               | ✔                          | ✔                       | ✖                   | ✔       | ✖          |
| Nike Training Club | ✔                          | ✔                       | ✖                   | ✖       | ✖          |
| 去动               | ✔                          | ✔                       | ✖                   | ✔       | ✖          |
| 悦动圈             | ✔                          | ✔                       | ✖                   | ✔       | ✖          |
| JiDong             | ✔                          | ✔                       | ✔                   | ✔       | ✔          |

### 4.2 Specific Analysis and Innovation

- The private sports goal customization function provided by JiDong is similar to that of major software, and the platform can tailor training plans for personal sports preferences. In addition, compared to other platforms, JiDong can arrange targeted activities according to the physical education courses taken by student users.
- JiDong is similar to other communities, allowing users to share sports-related content in the community communication module. But the content of JiDong platform will be more closely related to campus life.
- JiDong is able to provide corresponding campus services. Compared with other platforms, JiDong can provide scheduled functions of sports venues on campus. In addition, the management of school sports clubs allows the clubs to be closer to the student population and allow more people to fall in love with sports.
- JiDong's sports ranking function is a revised version of the ranking functions of major platforms. We can calculate the user's ability value and ranking in a certain sport to make the users more motivated.
- JiDong is an online sports community customized for campus. In the campus environment, games such as ball appointments and running appointments can enrich the daily lives of teachers and students. In addition, JiDong also allows certified teachers to guide the training (can be paid).

## 5. Future Development

We plan to increase the investment in the platform and the iteration of the project after the trial operation of Tongji University is mature and the ecosystem of the platform is stable, so that the entire project will be gradually radiated to all universities in Shanghai, and then further expanded to universities across the country.

Our ultimate goal is to build JiDong into the largest online sports community in China with the most stable ecosystem and the most complete functions. Connect different colleges and universities, break the barriers of sports exchanges between multiple schools, launch multi-school sports competitions, set up college sports rankings, so that colleges and universities form healthy competition, and promote the development of college sports in China.

## 6. Potential Difficulties in Development

1. Reservations for venues in the school, community management mode need to be supported by the school. However, there will be certain conceptual differences between our developers and those in the school responsible for sports, and it will take some time to negotiate.
2. Subsequent research and development of the project may require financial support.
3. The management and security of the platform require certain technical support and long-term maintenance by technical personnel.

## 7. Related Technology

### 7.1 Construction

Use `TypeScript` for server development on the `nest.js` framework based on `Node.js`. `Node.js` is a `JavaScript` runtime environment development platform based on Chrome V8 engine, on which excellent traditional frameworks such as `koa2` and `express` were born, and `nest.js` is based on `express`. The code standard has the advantages of good ecology and low maintenance cost.

### 7.2 Data Processing

All website related information will be maintained by DBMS based on `MySQL`. `MySQL` is a relational database management system that has the advantages of fast speed, small size, low cost, and open source. After the user accesses the community website through the uniform resource locator (URL) from the browser entrance, he can choose the unified authentication of Tongji University to log in and confirm his identity. The account information (student number and password) will be stored and maintained by the DBMS. Other website resources such as push articles, personal rankings and appointment information will be maintained by the DBMS for a long time.

### 7.3 Design

Mainly use `CSS` and `JavaScript` frameworks for front-end design of web pages. `CSS` is a computer language used to express HTML and other file styles. It can accurately typeset various elements in web pages and has the ability to edit web objects and models efficiently. In addition, `Vue.js` is an excellent progressive `JavaScript` framework for building user interfaces. It is easy to use, flexible, and has good performance. It is also easy to integrate with third-party libraries or existing projects. So as to enrich our community interface.

## 8. Harvest

The implementation of this project, in addition to building a brand new campus community and facilitating the daily life of students, is also self-evident for the overall growth of our team.

### 8.1 Technology Growth

In terms of technology, we are divided into server-side and web-side. The server-side uses the `nest.js` framework and uses `MySQL` to manage the database; the web-side uses `CSS` and `JavaScript` to design web pages. A lot of this knowledge is relatively unfamiliar to us now, but in the future, as the project is gradually deepened, we will inevitably gradually improve our coding capabilities during the implementation of the project and become more familiar with the server-side and web-side environments.

### 8.2 Teamwork

The progress of a project cannot be achieved by one member alone, but it is also not something that everyone can blindly write code to do well. In the process of the concrete implementation of the project, we need to unite and cooperate and divide the labor carefully. Reasonably arrange personnel and time in the process of the project to maximize efficiency. This is what we can learn from the implementation of the project.
