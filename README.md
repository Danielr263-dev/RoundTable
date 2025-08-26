# RoundTable
A webapp for UCF users to interact with other users and create/edit posts for academic and extracurricular purposes

Will be using the following technologies followed by what they'll be used for: 

Backend: 
Technology / Purpose


Node.js	/ JavaScript runtime for building the backend. Fast, non-blocking, great for real-time features.
TypeScript	/ Strongly-typed superset of JS. Prevents runtime errors, improves maintainability, looks professional to Twitch.
Express.js	/ Minimalist web framework for Node. Handles routing, middleware, request/response.
NestJS (optional alternative)	/ More structured, enterprise-style framework with modules/controllers/providers. Helps scale if project grows.
Apollo Server / GraphQL	Allows flexible APIs, perfect for feeds & multiple queries in one request. Supports subscriptions (real-time).
Prisma ORM	/ Maps your database tables to TypeScript objects. Makes queries safe & easier, handles migrations.
PostgreSQL	/ Relational database for structured data (users, posts, likes, events). Supports joins, transactions, and indexing for feeds.
JWT (JSON Web Tokens)	/ Authentication tokens for secure login sessions.
SendGrid/Postmark	/ Email service for email verification or notifications. Free tier works for student projects.
Socket.IO / GraphQL Subscriptions	Real-time features: instant feed updates, likes, RSVPs.
Cloudinary / AWS S3	File storage for profile pictures or post media.
