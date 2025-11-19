## 👋 Hi, I’m Fırat Koçoğlu

I’m a software developer who enjoys building clean, functional, and real-world applications.
Currently focused on backend development with Laravel and JavaScript (TypeScript, Node.js | Next.js), while exploring modern web technologies and best practices.

# 🚀 Projects

### IncidentIQ — AI-powered Incident & SLO Platform

I’m building a developer-first platform that ingests logs & metrics, detects anomalies, tracks SLO / error budgets, and routes alerts & on-call. On top, a RAG-based AI assistant suggests root causes using past incidents and runbooks.
#### Tech:
#### Focus: clean architecture, event-driven design, reliability, and explainable AI for faster MTTR.

### 🛒 Laravel E-Commerce

A complete e-commerce application with product, cart, order, and payment management, including an admin panel for category, inventory, and image management. Also includes a standalone microservice to automate product image ingestion built by Fastify + TypeScript. 
#### Tech: Laravel 12, PHP 8.4, PostgreSQL, Redis, Horizon, React, TailwindCSS, Stripe, Node.js (Fastify).
#### Focus: Designed with clean architecture, transaction safety, async queues, and caching for real-world reliability and scalability.

### 🧩 Image Ingestion Microservice

This repository includes a standalone microservice responsible for generating realistic product images using Unsplash and uploading them to Cloudinary.
It is implemented in TypeScript with Fastify, built as a production-grade ingestion pipeline.

🔌 Responsibilities
	•	Fetch category-relevant images from Unsplash
	•	Download & process raw image buffers
	•	Upload images to Cloudinary using streaming
	•	Register uploaded image URLs in the Laravel backend
	•	Auto-retry with exponential backoff for network/API failures
	•	Track failed products and support targeted reruns

⚙ Technology Stack
	•	Node.js (Fastify, TypeScript)
	•	Cloudinary SDK + Streaming uploads
	•	Axios + Retry wrapper
	•	Pino structured logging
	•	Laravel API integration (internal token)
