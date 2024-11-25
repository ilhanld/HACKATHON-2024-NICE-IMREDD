# 🌍 - RiskyQuest 
## Educate yourself about climate disasters

ClimateAware is an interactive web application created during a hackathon on the theme of climate disasters. This project aims to raise users' awareness of extreme weather events while allowing them to learn via an educational quiz.

## 🚀 - Main features
Interactive map:

Click on a point on the map to display climate disasters specific to that area (hurricanes, fires, floods, etc.).
The data is provided in real time using a dedicated API.
Educational quiz:

For each climate disaster, a quiz is offered to help you better understand its causes, impacts and possible solutions.
Get a score to assess your level of awareness.
Modern interface:

Developed with React for a fast, fluid user experience.
Robust backend:

Managed with Express.js, it collects and transmits data on climate disasters from reliable sources.

## 🛠️ Technologies utilisées

### Front
![](https://i.imgur.com/DUAYEFv.png)

### Backend
![](https://i.imgur.com/gm8q2D4.png)

## 📥 Installation
### Requirements

 - Node.js (version 16+ recommended)
 - npm or yarn to manage dependencies

Clone the project repository :

    git clone [REPOS NAME]
    cd [REPOS NAME]

install the dependencies for the backend :

    cd backend
    npm install

Install the dependencies for the frontend :

    cd ../frontend
    npm install

# 🏗️ - Project Structure
```
project-root/
│
├── docker-compose.yml # Orchestration of Docker services
├── front/ # Frontend source code (React)
│ ├── Dockerfile # Dockerfile to build the frontend
│ ├── nginx.conf # Nginx configuration for the frontend
│ ├── package.json # Frontend dependencies
│ ├── ... other files
│
└── back/ # Backend source code (Node.js)
	├── Dockerfile # Dockerfile to build the backend
	├── package.json # Backend dependencies
	├── ... other files
```