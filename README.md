# TypeScript Express Starter

## Overview

This repository provides a boilerplate for building TypeScript-based Express applications. It follows a modular structure to keep code organized and maintainable.

## Structure

The project structure is as follows:

src/
├── common/
│ ├── interfaces/
│ │ ├── logger.interface.ts # Interface definitions
│ │ └── repository.interface.ts # Interface definitions
│ ├── logger/
│ │ ├── console-logger.ts # Console logger implementation
│ │ └── file-logger.ts # File logger implementation
│ └── exceptions/
│ └── http-exception.ts # HTTP exception handling
├── config/
│ ├── db.config.ts # Database configuration
│ ├── server.config.ts # Server configuration
│ └── index.ts # Configuration entry point
├── controllers/
│ ├── articles.controller.ts # Controller for articles
│ └── users.controller.ts # Controller for users
├── middlewares/
│ ├── error.middleware.ts # Error handling middleware
│ ├── http-logger.middleware.ts # HTTP request logging middleware
│ ├── not-found.middleware.ts # Not found handling middleware
│ └── index.ts # Middleware entry point
├── models/
│ ├── article.model.ts # Article data model
│ └── user.model.ts # User data model
├── repositories/
│ ├── article.repository.ts # Repository for articles
│ └── user.repository.ts # Repository for users
├── routers/
│ ├── articles.router.ts # Router for articles
│ ├── users.router.ts # Router for users
│ └── index.ts # Router entry point
├── services/
│ ├── article.service.ts # Service for articles
│ └── user.service.ts # Service for users
├── types/
│ ├── articles.d.ts # TypeScript declarations for articles
│ ├── users.d.ts # TypeScript declarations for users
│ └── service-response.d.ts # TypeScript declarations for service responses
├── utils/
│ └── some-utility.ts # Utility functions
├── tests/
│ ├── articles.test.ts # Tests for articles
│ └── users.test.ts # Tests for users
├── prisma/
│ ├── schema.prisma # Prisma schema
│ └── client.ts # Prisma client initialization
├── app.ts # Express application entry point
└── index.ts # Server entry point
.editorconfig # Editor configuration
.eslintignore # ESLint ignore configuration
.eslintrc.json # ESLint configuration
.gitignore # Git ignore configuration
Dockerfile # Dockerfile for containerization
jest.config.ts # Jest configuration
package.json # Project dependencies and scripts
README.md # This file, project overview and setup instructions
tsconfig.json # TypeScript configuration
