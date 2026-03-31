# Apex Bath Remodeling & Pros - Landing Page PRD

## Original Problem Statement
Build a basic landing page with multi-step quiz then redirect to book an appointment.
- Brand colors: Blue #003A75, Orange #FF6C00
- 4 quiz questions leading to appointment booking
- Phone: +18175069696

## User Personas
1. **Homeowners** - Looking for bathroom remodeling services
2. **Commercial Property Managers** - Seeking professional remodeling contractors

## Core Requirements (Static)
- Split-screen landing page layout
- Multi-step quiz (4 questions)
- Appointment booking (5 days out, 10am/2pm/6pm slots)
- Webhook integration for form submissions
- Mobile responsive design

## What's Been Implemented (December 2025)
- [x] Landing page with split-screen layout (hero image + quiz)
- [x] Company logo integration
- [x] Step 1: Home type selection (4 options with icons)
- [x] Step 2: Timeline selection (ASAP, This Month, Next Month, Unsure)
- [x] Step 3: Address form (Home Address, City, Zipcode)
- [x] Step 4: Contact form (Full Name, Phone, Email)
- [x] Form validation on all steps
- [x] Backend API: POST /api/quiz/submit
- [x] Step 5: Appointment calendar (5 days ahead restriction)
- [x] Time slot selection (10:00 AM, 2:00 PM, 6:00 PM)
- [x] Backend API: POST /api/appointment/book
- [x] Confirmation screen
- [x] Progress bar and step indicators
- [x] MongoDB storage for submissions
- [x] Webhook placeholders ready (QUIZ_WEBHOOK_URL, APPOINTMENT_WEBHOOK_URL)

## Prioritized Backlog
### P0 (Waiting for User)
- [ ] Configure actual webhook URLs for quiz and appointment submissions

### P1 (Future Enhancements)
- [ ] Email confirmation after booking
- [ ] Admin dashboard for viewing submissions
- [ ] SMS reminders for appointments

### P2 (Nice to Have)
- [ ] Before/after gallery section
- [ ] Customer testimonials
- [ ] Service pricing calculator

## Next Tasks
1. User provides webhook URLs for form/appointment data
2. Configure environment variables with actual webhook endpoints
3. Test webhook integrations
