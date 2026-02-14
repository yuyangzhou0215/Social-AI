# Social-AI

A full-stack social network application built with Go (Golang) and React.

## Overview

Social-AI is a scalable web application that allows users to:

- Register and log in using JWT-based authentication
- Create and browse posts
- Generate images with text prompts
- Search posts using Elasticsearch

## Tech Stack

### Frontend
- React
- React Router
- JWT Authentication

### Backend
- Go (Golang)
- Gorilla Mux
- Elasticsearch
- Google Cloud Platform (GCP)

## Architecture

Client → Go Backend → Elasticsearch  
Client → Go Backend → Google Cloud Storage

## Deployment

Deployed on Google Cloud Platform with firewall configuration and external IP access.
