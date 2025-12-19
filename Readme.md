# VideoGram

A high-performance, distributed video streaming platform built to handle scalable content delivery. This project demonstrates a transition from a monolithic architecture to a **Microservices-based system** focused on low latency and efficient data handling.

## 🔗 Links

- **Live Demo:** https://video-tube-frontend-gamma.vercel.app/
- **Backend Tech:** Node.js, Express, gRPC, Cloudinary, Redis, Docker
- **Frontend Tech:** React, Redux, React Query, Vite, TailwindCSS, Zod, Formik
- **Database:** PostgreSQL, MongoDB

---

## 🚀 Key Features & Performance

- **Microservices Migration:** Re-architected from a monolith to independent services using **Docker** for containerization.
- **High-Speed Communication:** Implemented **gRPC** for internal service-to-service calls, reducing overhead compared to traditional REST.
- **Optimized Caching:** Integrated **Redis** for metadata caching, resulting in a **~30% improvement in API response times**.
- **Database Scalability:** Hybrid approach using **PostgreSQL** for structured data and **MongoDB** for flexible content metadata.
- **File Storage:** Implemented **Cloudinary** for efficient video storage and delivery.

---
