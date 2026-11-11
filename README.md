<div align="center">

# Cjobfit

**Measured by What Matters.**

Cjobfit brings screening, assessments, interviews, and team evaluation into one hiring platform — available on web for employers and on iOS and Android for candidates.

[![Website](https://img.shields.io/badge/Website-www.cjobfit.com-0066cc?style=flat-square)](https://www.cjobfit.com)
[![App Store](https://img.shields.io/badge/App_Store-iOS-black?style=flat-square&logo=apple)](https://apps.apple.com/ae/app/cjobfit/id6807575102)
[![Google Play](https://img.shields.io/badge/Google_Play-Android-3ddc84?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.cjobfit.cjobfit_mobile)

</div>

---

## Why Cjobfit

Hiring today is fragmented. Employers juggle separate tools for job posting, resume review, assessments, interviews, and team feedback — with no shared context between them. Candidates submit applications and rarely hear back, with no way to demonstrate their actual skills beyond a resume.

Cjobfit addresses three specific problems:

- **Manual screening is slow and inconsistent.** Reviewing resumes one by one, without structure, leads to missed candidates and wasted time.
- **Hiring tools don't talk to each other.** Assessments, interviews, and team notes live in different places, making it hard to evaluate candidates fairly.
- **Candidates have limited ways to show what they can do.** A resume alone doesn't capture communication skills, problem-solving ability, or cultural fit.

---

## How It Works

Employers post a job and choose which evaluation stages to use. Candidates apply through the mobile app and move through each stage. The employer team reviews results together and makes a final decision.

```
Post a job
    → Review applicants and AI-generated resume scores
    → Run skills assessments (optional)
    → Conduct AI voice interviews (optional)
    → Conduct live video interviews (optional)
    → Team evaluates, votes, and decides
```

Each stage is optional. Employers configure the pipeline to match their process.

---

## Employer Platform

The employer platform runs on the web. Key capabilities:

**Applicant Review**
- Resume scoring against job requirements, generated automatically when a candidate applies
- Applicant list with filters, status tracking, and side-by-side comparison

**Skills Assessments**
- Custom question sets per role, with multiple question types
- Server-side timer enforcement and automatic scoring
- Results visible per candidate with answer breakdowns

**AI Voice Interviews**
- Candidates complete an async voice interview from the mobile app
- Responses are transcribed using AWS Transcribe and scored by AI
- Employers review transcripts and scores without scheduling calls

**Live Video Interviews**
- Scheduled video calls between employer and candidate, conducted inside the platform
- Interview notes and ratings captured during the session

**Team Collaboration**
- Invite team members and assign them to specific roles or job postings
- Share applicants with teammates for independent review
- Each reviewer submits a structured evaluation with scores and comments
- Team lead sees aggregated scores, individual recommendations, and a validation workflow before a final decision is recorded

**Communication**
- End-to-end encrypted messaging between employers and candidates
- Message history preserved per applicant

**Dashboard**
- Pipeline metrics: applications received, assessments completed, interviews scheduled, offers made
- Activity feed and status overview per job posting

---

## Candidate Experience

Candidates use the Cjobfit mobile app on iOS or Android.

- Browse and search job listings without creating an account
- Apply to jobs and track application status in real time
- Complete skills assessments directly in the app, with a countdown timer
- Record AI voice interview responses on their own schedule
- Join live video interviews from the app
- Message employers through encrypted in-app chat
- Receive push notifications for status updates and interview invitations

The app is available in the UAE App Store and Google Play. Regional availability may vary.

---

## Technology

| Layer | Stack |
|---|---|
| Web frontend | Next.js, TypeScript, Tailwind CSS |
| Backend API | Node.js, Express, Prisma ORM |
| Mobile app | Flutter (iOS and Android) |
| Database | PostgreSQL on AWS RDS |
| AI scoring | OpenAI API |
| Voice transcription | AWS Transcribe |
| File storage | AWS S3 |
| Email | AWS SES |
| Background jobs | AWS SQS |
| Infrastructure | AWS ECS Fargate, CloudFront |
| Payments | Stripe |

---

## Security and Privacy

- Candidate and employer messages are end-to-end encrypted
- Authentication uses JWT with short-lived access tokens and refresh token rotation
- Rate limiting is applied across all API endpoints
- Candidate data collection is scoped to what is required for the hiring process
- Candidates can request data deletion through the app
- Assessment submissions are validated server-side to prevent tampering

[Privacy Policy](https://www.cjobfit.com/privacy) · [Terms of Service](https://www.cjobfit.com/terms)

---

## About

Cjobfit is designed, built, and shipped by **Farhan Muhammed** — a solo founder who built the full product across web, iOS, and Android.

The application source code is proprietary and private. This repository serves as a public product overview.

---

## Contact

Email: [info@cjobfit.com](mailto:info@cjobfit.com)
Website: [www.cjobfit.com](https://www.cjobfit.com)

---

<div align="center">
<sub>
<a href="https://www.cjobfit.com">Website</a> ·
<a href="https://apps.apple.com/ae/app/cjobfit/id6807575102">App Store</a> ·
<a href="https://play.google.com/store/apps/details?id=com.cjobfit.cjobfit_mobile">Google Play</a> ·
<a href="https://www.cjobfit.com/privacy">Privacy Policy</a> ·
<a href="https://www.cjobfit.com/terms">Terms</a> ·
<a href="mailto:info@cjobfit.com">Contact</a>
</sub>
</div>
