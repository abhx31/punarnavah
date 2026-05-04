# Punarnavah - Turning Waste into Opportunity

A sustainable waste management platform connecting households, artisans, and municipalities to promote circular economy and efficient waste utilization.

## Features

### Household Waste Management Portal
- **Artisan Requirements:** Artisans can post their specific waste material needs
- **Community Contribution:** Users can provide waste materials that match artisan requirements
- **Monetization:** Contributors receive payment for their waste materials
- **Upcycled Marketplace:** Artisans can sell their created products through the integrated marketplace

### Municipal Waste Management Portal
- **Waste Collection:** Collaboration with municipalities for accessing unprocessed waste
- **Segregation System:** Efficient categorization of waste into plastics, textiles, and other materials
- **Industrial Integration:** Platform for industries to purchase sorted waste as raw materials

## 🛠️ Tech Stack

### Frontend
- ReactJS
- TailwindCSS
- TypeScript

### Backend
- NodeJS
- ExpressJS
- Prisma
- JWT Authentication

### Database
- PostgreSQL

### DevOps & Deployment
- Docker
- AWS
- CI/CD (Github Actions)
- Vercel

### Integrations
- Cloudinary for Media Storage

## 📦 NPM Package
We've published a common package for schema validation and type safety:
- Package Name: `@abhinav3105/punarnavah-common`
- Built with TypeScript and Zod
- Ensures consistency across frontend and backend

## ⚙️ Architecture

![image](https://github.com/user-attachments/assets/ab3f2117-db60-443d-b718-c9b16bb34cb0)

![image](https://github.com/user-attachments/assets/11082e58-0117-4e19-8e72-d167eb2afa6b)

## 🔗 Important Links

- **Website:** [https://punarnavah.abhinavdev.in.net/](https://punarnavah.abhinavdev.in.net/)
- **API Server:** [https://punarnavah-backend.abhinavdev.in.net/](https://punarnavah-backend.abhinavdev.in.net/)
- **NPM Package:** [https://www.npmjs.com/package/@abhinav3105/punarnavah-common](https://www.npmjs.com/package/@abhinav3105/punarnavah-common)
- **Docker Image:** [https://hub.docker.com/repository/docker/abhinav0531/punarnavah-server/general](https://hub.docker.com/repository/docker/abhinav0531/punarnavah-server/general)

## 🚀 Getting Started

- Clone the repository
```bash
git clone https://github.com/abhx31/Punarnavah.git
cd Punarnavah
```

### Setting up Client

1. Install dependencies in the client
```bash
cd client
npm install
```

2. Set up environment variables
- Create a .env file or use .env.example
```bash
VITE_BACKEND_URL = 
VITE_BACKEND_URL = 

VITE_CLOUDINARY_UPLOAD_PRESET = 
VITE_CLOUDINARY_CLOUD_NAME = 
VITE_CLOUDINARY_URL = 

```

3. Start running the client
```bash
npm run dev
```


### Setting up Server

1. Install dependencies in the client
```bash
cd server
npm install
```

2. Set up environment variables
- Create a .env file or use .env.example
```bash
DATABASE_URL=

PORT = 
CLIENT_URL = 
JWT_SECRET = 

SENDER_EMAIL = 
SENDER_PASS = 

```

3. Start running the server
```bash
npm run dev
```

## 🤝 Contributing

I welcome contributions to Punarnavah! Please feel free to submit issues and pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


