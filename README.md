# Hassan Fayyaz

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=240&color=0:0D1117,50:161B22,100:00BFFF&text=HASSAN%20FAYYAZ&fontColor=FFFFFF&fontSize=52&fontAlignY=38&desc=FULL-STACK%20DEVELOPER&descSize=19&descAlignY=60&animation=fadeIn" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2600&pause=800&color=58A6FF&center=true&vCenter=true&width=820&lines=Full-Stack+Developer;Next.js+%7C+React+Engineer;Node.js+%7C+Express.js+Developer;REST+API+%7C+Authentication;Building+Modern+Web+Applications" alt="Typing Animation" />
</p>

<p align="center">
  <a href="https://github.com/Hassan2033">
    <img src="https://img.shields.io/badge/GitHub-181B22?style=for-the-badge&logo=github&logoColor=FFFFFF" />
  </a>
  <a href="https://github.com/Hassan2033?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-0D1117?style=for-the-badge&logo=github&logoColor=58A6FF" />
  </a>
</p>

---

## About Me

<table>
<tr>
<td width="58%">

### Full-Stack Developer

I build modern web applications across the complete application stack, from responsive interfaces to backend APIs and databases.

My current focus includes:

* React and Next.js application development
* TypeScript
* Node.js and Express.js
* RESTful API architecture
* JWT authentication
* Access and refresh token architecture
* MySQL and MongoDB
* Backend architecture and database design

My goal is to build software that is **structured, secure, maintainable and scalable**.

</td>

<td width="42%">

```js
const developer = {
  name: "Hassan",
  role: "Full-Stack Developer",

  frontend: [
    "React",
    "Next.js",
    "TypeScript"
  ],

  backend: [
    "Node.js",
    "Express.js"
  ],

  database: [
    "MySQL",
    "MongoDB"
  ],

  architecture: [
    "REST APIs",
    "JWT",
    "MVC"
  ]
};
```

</td>
</tr>
</table>

---

## Technology Stack

### Languages

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,php" />
</p>

### Frontend

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,bootstrap" />
</p>

### Backend

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,express,laravel" />
</p>

### Database

<p align="center">
  <img src="https://skillicons.dev/icons?i=mysql,mongodb" />
</p>

### Authentication & APIs

<p align="center">
  <img src="https://img.shields.io/badge/REST_API-0D1117?style=for-the-badge&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/JWT-0D1117?style=for-the-badge&logo=jsonwebtokens&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/bcrypt-0D1117?style=for-the-badge&logoColor=58A6FF" />
</p>

### Development Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman,npm" />
</p>

---

## Engineering Areas

<table>
<tr>

<td align="center" width="25%">

<img src="https://skillicons.dev/icons?i=react" width="52"/>

### Frontend

React
Next.js
TypeScript
Tailwind CSS

</td>

<td align="center" width="25%">

<img src="https://skillicons.dev/icons?i=nodejs" width="52"/>

### Backend

Node.js
Express.js
REST APIs
Middleware

</td>

<td align="center" width="25%">

<img src="https://skillicons.dev/icons?i=mysql" width="52"/>

### Data

MySQL
MongoDB
Queries
Relationships

</td>

<td align="center" width="25%">

<img src="https://skillicons.dev/icons?i=git" width="52"/>

### Engineering

Git
GitHub
Postman
API Design

</td>

</tr>
</table>

---

## Application Architecture

```text
                         CLIENT
                            │
                            ▼
                 ┌─────────────────────┐
                 │   React / Next.js   │
                 │     Frontend        │
                 └──────────┬──────────┘
                            │
                       HTTP / REST
                            │
                            ▼
                 ┌─────────────────────┐
                 │   Express.js API   │
                 ├─────────────────────┤
                 │ Routes              │
                 │ Middleware          │
                 │ Authentication      │
                 │ Controllers         │
                 │ Error Handling      │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │   Business Logic   │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │      Database       │
                 │ MySQL / MongoDB     │
                 └─────────────────────┘
```

---

## Authentication Flow

<table>
<tr>
<td width="50%">

### Registration

```text
Client
  │
  ▼
POST /register
  │
  ▼
Input Validation
  │
  ▼
bcrypt.hash()
  │
  ▼
Database
  │
  ▼
Account Created
```

</td>

<td width="50%">

### Login

```text
Client
  │
  ▼
POST /login
  │
  ▼
Find User
  │
  ▼
bcrypt.compare()
  │
  ▼
Access Token
  │
  ▼
Refresh Token
```

</td>
</tr>
</table>

---

## Protected API Flow

```text
Client
  │
  │ Authorization: Bearer <access_token>
  ▼
Authentication Middleware
  │
  ▼
jwt.verify()
  │
  ├────────────── Invalid ──────────────► 401
  │
  ▼
Authenticated Request
  │
  ▼
Controller
  │
  ▼
Database
  │
  ▼
Response
```

---

## Featured Projects

<table>
<tr>

<td width="50%">

### TripNest

**Smart Travel Booking Platform**

A travel booking platform designed around a complete digital travel experience.

**Features**

* Authentication
* Wishlist
* Booking Preview
* Interactive Maps
* Digital Boarding Pass
* QR Code
* PDF Generation
* Responsive Interface

**Focus**

`Web Development` `UI/UX` `APIs` `Application Architecture`

</td>

<td width="50%">

### FixFinders

**Practical Web Application**

A real-world application project focused on solving a practical problem through a structured web experience.

**Focus**

`Frontend` `Responsive UI` `Application Structure`

**Repository**

<a href="https://github.com/Hassan2033/FixFinders">
  <img src="https://img.shields.io/badge/View_Repository-161B22?style=for-the-badge&logo=github&logoColor=58A6FF" />
</a>

</td>

</tr>

<tr>

<td width="50%">

### Vision Project

**Web Application**

A functional web development project focused on modern frontend implementation.

**Focus**

`Frontend` `Responsive UI` `Application Structure`

**Repository**

<a href="https://github.com/Hassan2033/vision-project">
  <img src="https://img.shields.io/badge/View_Repository-161B22?style=for-the-badge&logo=github&logoColor=58A6FF" />
</a>

</td>

<td width="50%">

### Next Projects

Currently expanding my portfolio around:

```text
Next.js
Express.js
MySQL
Authentication
REST APIs
Full-Stack Architecture
```

</td>

</tr>
</table>

---

## GitHub Activity

<p align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=Hassan2033&hide_border=true&area=true&bg_color=0D1117&color=58A6FF&line=1F6FEB&point=FFFFFF"
    width="100%"
    alt="GitHub Activity"
  />
</p>

---

## Development Journey

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2100&pause=650&color=58A6FF&center=true&vCenter=true&width=850&lines=HTML+%2B+CSS;JavaScript;React;Next.js;TypeScript;Node.js;Express.js;MySQL+%2B+MongoDB;REST+APIs;JWT+Authentication;Full-Stack+Development"
    alt="Development Journey"
  />
</p>

---

## Current Focus

<table>
<tr>

<td width="50%">

### Current

```text
Advanced Next.js
        ↓
TypeScript
        ↓
Backend Architecture
        ↓
REST API Design
        ↓
Authentication
```

</td>

<td width="50%">

### Next

```text
Database Optimization
        ↓
Testing
        ↓
Docker
        ↓
CI / CD
        ↓
System Design
```

</td>

</tr>
</table>

---

## Engineering Principles

<table>
<tr>

<td align="center" width="33%">

### Clean Code

Readable and maintainable implementation.

</td>

<td align="center" width="33%">

### Separation of Concerns

Each layer has a clear responsibility.

</td>

<td align="center" width="33%">

### Security

Authentication and API security matter.

</td>

</tr>

<tr>

<td align="center">

### Database Design

Structure data intentionally.

</td>

<td align="center">

### Reusability

Build reusable components and logic.

</td>

<td align="center">

### Continuous Improvement

Every project is an opportunity to improve.

</td>

</tr>
</table>

---

## Development Workflow

```text
Requirement
     │
     ▼
Architecture
     │
     ▼
Implementation
     │
     ▼
Testing
     │
     ▼
Debugging
     │
     ▼
Optimization
     │
     ▼
Deployment
```

---

## Learning Roadmap

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2300&pause=700&color=58A6FF&center=true&vCenter=true&width=850&lines=Advanced+Next.js;TypeScript;Backend+Architecture;API+Design;Authentication+%26+Authorization;Database+Optimization;Automated+Testing;Docker;CI%2FCD;System+Design"
    alt="Learning Roadmap"
  />
</p>

---

## Developer Mindset

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&width=850&lines=Understand+the+system%2C+not+just+the+syntax.;Build+real+projects.;Debug+what+you+build.;Learn+from+every+mistake.;Improve+every+version."
    alt="Developer Mindset"
  />
</p>

---

## Connect

<p align="center">

<a href="https://github.com/Hassan2033">
  <img src="https://img.shields.io/badge/GitHub-Hassan2033-0D1117?style=for-the-badge&logo=github&logoColor=FFFFFF" />
</a>

</p>

---

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&height=130&section=footer&color=0:00BFFF,50:161B22,100:0D1117"
    width="100%"
  />
</p>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=500&lines=Build.;Learn.;Improve.;Repeat."
    alt="Footer Animation"
  />
</p>
