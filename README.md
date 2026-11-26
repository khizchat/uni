# CampusFlow — University Management Dashboard

A premium, responsive university-management frontend built with React + Vite.

## Included
- Responsive admin dashboard with KPI cards, enrollment chart and department distribution
- Student directory with search, status filters, table layout and pagination styling
- Add-student modal with working local state
- Dashboard navigation for analytics, faculty, courses, departments, timetable, attendance, exams, library, events, finance, admissions and reports
- Notification and profile dropdowns, toast feedback, dark theme toggle
- Responsive sidebar and mobile layout

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite.

## Build for production
```bash
npm run build
```
The production output is generated in `dist/`.

## Deploy to Vercel
1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.
4. Deploy.

## Important
This is a frontend prototype with sample data and client-side interactions. It does not yet include a live backend, authentication, database persistence, payment gateway, or role-based access control. Connect your university's API/Firebase/Supabase backend before using it with real student records.
