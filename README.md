# Car Dealership Full Stack Application

A full-stack web application for browsing car dealerships, viewing reviews, and posting new reviews — built with **Django (backend)**, **React (frontend)**, and **MongoDB/SQLite** for data storage.  
It also integrates a **sentiment analysis microservice** to analyze user-submitted reviews.

---

## Features

- **User Authentication**
  - Registration, login, and logout using Django's authentication system.
- **Car Inventory**
  - Car makes and models managed through Django admin.
  - Populated with sample data via `populate.py`.
- **Dealership Management**
  - Fetch dealership list (all or by state).
  - View detailed dealership information.
- **Reviews**
  - View dealer reviews.
  - Post a new review (runs through sentiment analysis service).
- **Frontend**
  - Built with React, uses React Router for page navigation.
  - Fully separated frontend and backend (served together in production).

---

## Tech Stack

### Backend
- **Django** (REST API)
- **Django ORM** (SQLite by default)
- **MongoDB** (via `pymongo` / API integration)
- **External Sentiment Analysis Service**

### Frontend
- **React**
- **React Router**
- **CSS / JSX Components**


