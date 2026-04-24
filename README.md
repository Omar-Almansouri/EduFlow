# EduFlow — AI-Powered Student Time Management

> An intelligent study planning system that connects to your LMS and calendar, extracts tasks and deadlines automatically, and generates personalized study schedules — so students never miss a deadline again.

Built at the **KSU Transformation Hackathon** · Track: Educational Experience

---

## The Problem

78% of students have missed an exam or assignment deadline. 80% report anxiety specifically caused by poor time management — juggling multiple courses, deadlines, and priorities with no unified system.

| Pain Point | Impact |
|---|---|
| Scattered deadlines across platforms | Missed submissions |
| No awareness of upcoming workload | Last-minute cramming |
| Manual scheduling is time-consuming | Students don't do it |
| No early warning system | Stress peaks at deadline |

---

## What It Does

EduFlow is a smart time management platform that pulls academic data from your LMS and Outlook, extracts all deadlines and tasks automatically, and proposes study schedules that fit around your existing commitments.

### Core Features

- **Automatic ingestion** — connects to LMS and Outlook to collect course data, deadlines, and assignments without any manual input
- **AI extraction** — LLM parses unstructured course content to identify tasks, deadlines, and priorities
- **Smart scheduling** — generates personalized study plans based on the student's available time slots and deadline urgency
- **Calendar integration** — study sessions appear directly in the calendar view with course color-coding
- **Smart notifications** — proactive alerts for upcoming deadlines before pressure builds

---

## System Flow

```
1. Student logs in
        ↓
2. App connects to LMS + Outlook (database sync)
        ↓
3. AI extracts tasks, deadlines, and course info
        ↓
4. LLM model generates prioritized schedule
        ↓
5. Schedules and deadlines surface in dashboard + calendar
        ↓
6. Student receives smart reminders and views their plan
```

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React (Next.js) |
| UI Design | Figma |
| Backend / DB | Supabase |
| AI Model | LLM (v0 / Claude) |
| Rapid Prototyping | v0 by Vercel |
| LMS Integration | REST API (planned) |
| Calendar | Outlook API |

---

## MVP Demo

The MVP was built during the hackathon using v0 (Vercel) and demonstrates the core scheduling loop:

- Dashboard with active courses and upcoming deadlines
- Task creation linked to specific courses with due dates and priority levels
- Calendar view with auto-generated study sessions scheduled before each deadline
- Color-coded courses across all views

**Demo walkthrough:** A student inputs three tasks across different courses and deadlines. EduFlow automatically schedules study sessions before each due date, ensures nothing overlaps, and populates the calendar — all without manual planning.

---

## Expected Impact

- Reduced missed deadlines and submission anxiety
- Improved academic performance through structured preparation
- Less psychological stress from proactive scheduling vs reactive cramming
- Potential to improve university graduation and course completion rates — which directly affects QS/THE/U.S. News rankings

---

## Roadmap

| Phase | Feature | Status |
|---|---|---|
| MVP | Dashboard, task input, calendar | Complete |
| v1 | LMS + Outlook integration | In development |
| v2 | Improved AI scheduling algorithm | Planned |
| v3 | Faculty tools (assignment load visibility) | Planned |
| v3 | Continuous student feedback loop | Planned |

---

## License

This project is for academic and portfolio purposes.
