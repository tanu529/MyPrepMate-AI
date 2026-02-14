# MyPrepMate AI – Design Document

## System Overview
MyPrepMate AI is an AI-powered placement companion designed for Tier-2 and Tier-3 college students. The system analyzes a student’s current preparation level, compares it with their target career goal, and generates a personalized roadmap with daily actionable tasks for placement success.

## User Flow
1. User signs up and selects their goal (e.g., 8+ LPA job, product-based company, government exam, etc.)
2. User enters current skill level (DSA, aptitude, core subjects, projects)
3. AI performs a reality gap analysis (current vs required level)
4. System generates a personalized long-term roadmap
5. AI creates daily study and practice tasks
6. User practices recommended questions
7. AI tracks performance and updates weak areas
8. Dashboard shows progress, consistency score, and next best action

## Core Modules
- User Profile & Goal Selection Module
- Reality Gap Analyzer
- AI Roadmap Generator
- Daily Action Planner
- Smart Question Recommendation Engine
- Performance Tracking Dashboard
- Low-Resource Mode for limited connectivity users

## High-Level Architecture

### Frontend
- Web-based student dashboard
- Goal selection interface
- Progress visualization
- Daily task manager

### Backend
- User data management
- Performance analysis engine
- Roadmap generation logic

### AI Engine
- Skill gap analysis
- Personalized roadmap generation
- Intelligent recommendation system
- Natural language doubt explanation

### Database
- Stores:
  - User profile
  - Skill assessment data
  - Daily progress
  - Performance history

## Technology Stack (Proposed)

### Frontend
- HTML, CSS, JavaScript (React – scalable version)

### Backend
- Python (FastAPI / Flask) or Node.js

### Database
- MongoDB (for flexible student progress data)

### AI Integration
- LLM API for:
  - Roadmap generation
  - Weak area detection
  - Personalized recommendations
  - Doubt solving

### Cloud (Deployment)
- AWS cloud infrastructure for scalable deployment

## Low-Resource Optimization (AI for Bharat Focus)
- Lightweight UI for low-end devices
- Offline daily task sync
- Minimal data usage mode
- Text-first interface for slow internet regions

## Scalability
The system can be extended to:
- Mobile application
- Multi-language support (Hindi + regional languages)
- Company-specific placement preparation tracks
- Integration with college training platforms

## Future Enhancements
- AI mock interview simulator
- Resume analyzer
- Peer learning community
- Voice-based AI mentor for vernacular users
