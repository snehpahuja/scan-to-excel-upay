# Scan-to-Excel: Document Intelligence Platform

Web application converting scanned documents (PDF, PNG, JPG) into structured Excel files using OCR. Built for UPAY, an NGO managing educational centers.

## Overview

Automates document processing workflow: upload → OCR extraction → user review → Excel export. Includes analytics dashboard for attendance, grades, budget, and enrollment tracking.

## Features

- Document upload with automatic categorization
- Azure Document Intelligence OCR with custom model training
- Split-screen review interface with in-table editing
- Category-specific Excel generation and download
- Dashboard analytics (attendance, grades, financial, enrollment)
- Role-based access control (admin/employee)

## Tech Stack

**Frontend:** React, Vite, React Router  
**Backend:** Django REST Framework, SQLite / PostgreSQL  
**OCR:** Microsoft Azure Document Intelligence (custom-trained)  
**Auth:** JWT Authentication  

## Architecture

- **Presentation Layer:** React SPA with client-side routing
- **Application Layer:** Django REST API with role-based access
- **Intelligence Layer:** Azure Document Intelligence with transfer learning
- **Data Layer:** Relational database with ORM

## Team & Roles

**Sneh Pahuja** — Backend development, analytics dashboard, Scrum Master  
**Piya Shah** — Frontend UI/UX, OCR model training  
**Varsha Gunturu** — OCR integration, Excel export, Product Owner  

**Course:** Software Architecture & Design (CSIT306)  
**Institution:** FLAME University, Pune  
**Date:** October 2025

---

*Note: Repository is private. Full technical report available in this repository.*
