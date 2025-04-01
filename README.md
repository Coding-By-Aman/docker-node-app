# Dockerized Node.js App 🚀

This is a simple **Node.js (Express) API** containerized with **Docker**.

## 📌 Features
- Basic Express.js API
- Dockerized for easy deployment

## 🔧 Setup & Run

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/docker-node-app.git
cd docker-node-app
```

### 2️⃣ Build the Docker Image
```sh
docker build -t my-node-app .
```

### 3️⃣ Run the Container
```sh
docker run -p 3000:3000 my-node-app
```

### 4️⃣ Access the API  
Open: **[http://localhost:3000](http://localhost:3000)**  

## 🔕 Stop the Container  
Press `Ctrl + C` in the terminal.  
Or stop it manually:  
```sh
docker ps
docker stop <container_id>
```

