# Urban Sprawl Detection Dashboard

A web application for detecting and analyzing urban sprawl patterns using satellite imagery and machine learning.

## Project Structure

- **frontend/**: React-based UI for the dashboard
- **backend/**: Express.js server for API and data processing
- **ml/**: Machine learning models for land cover classification
- **data/**: Training and test datasets

## Setup

### Backend
```bash
cd backend
npm install
npm start
```

### Frontend
```bash
cd frontend
npm install
npm start
```

## Environment Variables

Create a `.env` file in the backend directory:
```
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

## Features

- Satellite image analysis
- Urban sprawl detection
- Land cover classification
- Interactive dashboard with visualizations
- Population trends analysis
- Environmental metrics (flood risk, rainfall, air quality, temperature)

## Technologies

- **Frontend**: React, Chart.js, Leaflet
- **Backend**: Node.js, Express, MongoDB
- **ML**: Python, TensorFlow/PyTorch
