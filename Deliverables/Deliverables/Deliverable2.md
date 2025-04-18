# Deliverable 2 – Functional & System Requirements

## Functional Requirements
### 1. Smart Bin Monitoring
- Sensor sends fill level to system every hour.
- Bin status: Empty, Half-Full, Full.
- Alert generated if bin is Full.

### 2. Mobile App – User Features
- View nearby bin locations and status.
- Set reminders for collection days.
- Report overflowing or damaged bins.
- View recycling tips based on waste type.

### 3. City Dashboard
- Monitor all bins in real-time on a map.
- Generate route for most efficient collection.
- Analyze collection trends (weekly/monthly).

### 4. Notifications & Feedback
- Push notifications to users for collection schedules.
- Submit feedback or complaints with photos.

## System Requirements
- Backend: Node.js or Django REST API
- Database: MongoDB for bin data + PostgreSQL for users/feedback
- Frontend: React Native (Mobile), React.js (Web)
- IoT Integration: Arduino sensors + Wi-Fi Module
- Hosting: AWS or Firebase
- Security: OAuth2.0, encrypted data transmission, user roles

## Non-Functional Requirements
- Scalability to accommodate 10,000+ users
- High availability (99.9%)
- Response time under 2 seconds for API
- Secure user authentication and role-based access
