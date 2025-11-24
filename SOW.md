# Statement of Work (SOW) - AI Skin-Care Application

---

## 1. Project Overview

The purpose of this project is to design, develop, and deploy an AI-powered skin-care analysis application capable of scanning a user's face, detecting skin conditions, recommending personalised routines, and enabling future scalability for cloud deployment. The app will analyse images using computer vision and provide secure user profiles, history tracking, and product recommendations.

---

## 2. Scope of Work

### 2.1 Features to be Developed

#### A. AI & Image Processing
- Facial skin analysis (acne, dark circles, wrinkles, pigmentation, oiliness, dryness)
- AI-powered quality enhancement (compress image to small size while keeping Ultra-HD quality)
- Real-time or uploaded photo scanning
- Skin-tone and texture detection
- Generate daily/weekly skin-care insights

#### B. User Management
- User registration/login (email, social sign-in)
- Store user profile: age, gender, skin type, and preferences
- History of uploaded images and previous analysis reports
- Privacy-focused system ensuring no image misuse

#### C. Skin-Care Recommendation Engine
- Personalised routine (AM / PM)
- Product suggestions (open-source datasets or user-provided database)
- Lifestyle recommendations (water intake, sleep, SPF reminders)

#### D. Dashboard & UI/UX
- Clean and modern UI for mobile and web
- Real-time results screen
- Save/Share report option
- Multi-language support (English initially)

#### E. Admin Panel
- Manage users
- Manage recommended products
- Review logs and AI reports

#### F. Integration
- Cloud hosting (free/low-cost options for testing: Vercel, Netlify, GitHub Pages + backend on Render/Railway)
- API integration for AI model (custom or open-source models like Mediapipe, DeepFace, YOLO, Skin-disease datasets)

---

## 3. Technical Approach

### 3.1 Architecture

| Component | Technology Options |
|-----------|-------------------|
| **Frontend** | React Native / Flutter (mobile) OR React.js (web) |
| **Backend** | Node.js / Python FastAPI |
| **AI Engine** | Pre-trained CNN models, Open-source datasets (HAM10000, DermNet, Kaggle skin datasets), Custom fine-tuned model |
| **Database** | Firebase or MongoDB Atlas (free tier) - Optional: No database required if only anonymous analysis is offered |

### 3.2 Cloud & DevOps
- GitHub repository for source control
- CI/CD pipeline (GitHub Actions)
- Deployment to Vercel / Netlify / Render

---

## 4. Deliverables

| # | Deliverable |
|---|-------------|
| 1 | UI/UX design wireframes |
| 2 | AI model setup + training/test results |
| 3 | Frontend application |
| 4 | Backend APIs |
| 5 | Admin dashboard |
| 6 | Database setup |
| 7 | Deployment & hosting |
| 8 | Testing & QA reports |
| 9 | User documentation |
| 10 | Final production build (APK / Web link) |

---

## 5. Project Timeline

| Phase | Duration | Deliverables |
|-------|----------|-------------|
| Requirements Gathering | 3-5 days | Finalised requirements |
| UI/UX Design | 1-2 weeks | Wireframes, prototypes |
| AI Model Development | 2-4 weeks | Trained model |
| Backend Development | 1-2 weeks | APIs ready |
| Frontend Development | 2-3 weeks | App screens |
| Testing & QA | 1 week | Bug-free build |
| Deployment | 2-3 days | Live app |

**Total Estimated Timeline:** 6-10 weeks (depending on complexity)

---

## 6. Responsibilities

### Client Responsibilities
- Provide product list (optional)
- Approve UI/UX designs
- Provide branding (logo, theme)
- Support testing and feedback cycle

### Developer Responsibilities
- End-to-end development
- AI training & model integration
- UI/UX development
- Testing + bug fixes
- Deployment setup
- Code documentation
- Post-launch support (30 days)

---

## 7. Acceptance Criteria

The project will be considered complete when:
- [ ] All listed features are implemented and verified
- [ ] AI skin analysis delivers acceptable accuracy
- [ ] All UI/UX designs match the approved mockups
- [ ] App is deployed and fully usable
- [ ] Documentation is provided
- [ ] Final demo session is completed

---

## 8. Pricing (Optional Template)

| Model | Rate |
|-------|------|
| Fixed Price | EUR XX,000 |
| Hourly Model | EUR XX/hour |

---

## 9. Assumptions

- The client agrees to provide approvals within 48 hours
- AI results are based on available datasets and not a medical diagnosis
- Additional features outside the scope will require a change request

---

## 10. Risks & Constraints

| Risk | Description |
|------|-------------|
| Image Quality | Accuracy depends on the quality of input images |
| Cloud Performance | Cloud hosting performance may vary in free-tier services |
| Legal/Medical | Medical/legal disclaimers are required (app is not a doctor) |

---

**Document Version:** 2.0  
**Last Updated:** November 24, 2025  
**Prepared by:** Skincare App Research Team
