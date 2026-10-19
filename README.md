# 🎓 Muslim Model School Khaddi – Management System

A **fully functional**, modern, and responsive school management system built with **HTML, CSS, and JavaScript** — no backend required. All data is stored in the browser's `localStorage`.

---

## 📂 Project Structure

```
school/
├── index.html          ← Login Page
├── dashboard.html      ← Admin Dashboard
├── students.html       ← Student Management
├── teachers.html       ← Teacher Management
├── attendance.html     ← Attendance Management
├── fees.html           ← Fees Management
├── exams.html          ← Exams & Results
├── classes.html        ← Classes & Timetable
├── noticeboard.html    ← Notice Board
├── portal.html         ← Parent & Student Portal
├── logo.jpg            ← School Logo
├── css/
│   ├── login.css       ← Login page styles
│   └── style.css       ← Main app styles
└── js/
    ├── data.js         ← Database + Seed data
    ├── auth.js         ← Authentication module
    └── app.js          ← Core utilities & UI
```

---

## 🚀 How to Open / Run

### Option 1: Direct File Open (Simplest)
Just double-click **`index.html`** in your file manager. It will open in your default browser.

### Option 2: Live Server (Recommended for Development)
If you have VS Code installed:
1. Install the **Live Server** extension
2. Right-click `index.html` → "Open with Live Server"

### Option 3: Any Local HTTP Server
```bash
# Python 3
python -m http.server 8080

# Node.js (npx)
npx serve .
```
Then open `http://localhost:8080` in your browser.

---

## 🔐 Login Credentials

| Role    | Username  | Password   |
|---------|-----------|------------|
| Admin   | admin     | admin123   |
| Teacher | teacher1  | teacher123 |
| Student | S001      | student123 |
| Parent  | P001      | parent123  |

> Click the **demo credential cards** on the login page to auto-fill credentials.

---

## ✨ Features

### 1. 🏠 Admin Dashboard
- Real-time stats: students, teachers, classes, fees
- Monthly attendance bar chart
- Fee collection donut chart
- Recent activity feed
- Latest notices preview
- Class fill-rate progress bars
- Quick action buttons

### 2. 👨‍🎓 Student Management
- Add, edit, delete students
- Search & filter by name, roll, class, status
- Full student profile modal with attendance, fees, and results summary
- Role-based access (Admin/Teacher can edit)

### 3. 👩‍🏫 Teacher Management
- Add, edit, delete teacher profiles
- Table view + card grid view
- Subject, qualification, salary, and contact tracking

### 4. 📅 Attendance Management
- Mark attendance (Present / Absent / Leave) per student or teacher
- Class-wise attendance marking with bulk actions
- Monthly calendar overview
- Attendance history table
- Printable monthly report

### 5. 💰 Fees Management
- Add, edit fee records
- One-click mark-as-paid
- Filter by status (All / Paid / Unpaid)
- Printable fee receipt with receipt number
- Collection statistics and rate

### 6. 🎓 Exams & Results
- Create exams with subject, class, date, total marks
- Interactive mark entry table with live grade preview
- Automatic grade calculation (A+ to F)
- Printable student report card with school letterhead
- Results history with percentage bars

### 7. 🏫 Classes & Timetable
- Visual class cards with capacity bars
- Add/edit/delete classes and assign class teachers
- Subject-teacher assignment table
- Interactive weekly timetable viewer with printable output

### 8. 👨‍👩‍👧 Parent & Student Portal
- Personalized view: attendance rate, fees, results, notices
- Attendance donut chart
- Fee payment history and outstanding dues
- Exam results table with progress bars
- Admin can preview any student's portal

### 9. 📢 Notice Board
- Post general, event, urgent, and holiday notices
- Filter notices by type
- Upcoming events and holidays sidebar
- Full CRUD management

### 10. 🔒 Authentication & Security
- Role-based login (Admin, Teacher, Student, Parent)
- Session-based authentication using `sessionStorage`
- Role-based UI (menu items hidden based on role)
- Protected routes (redirects to login if not authenticated)

---

## 🎨 Design Features
- **Blue & White** professional color theme
- **Inter** font family from Google Fonts
- **Animated login page** with floating particles
- **Dark sidebar** with active state highlighting
- **Responsive** – works on mobile, tablet, and desktop
- **Toast notifications** for all actions
- **Smooth animations** and hover effects
- **Print-ready** report cards, receipts, and attendance reports

---

## 🔧 Customization

### To Reset Demo Data
- Log in as Admin
- Click the **"Reset Demo"** button in the Dashboard
- Or clear localStorage: `localStorage.removeItem('ssms_db')` in browser console

### To Add More Seed Data
Edit the `SEED` object in **`js/data.js`** to add more students, teachers, etc.

### To Change School Name/Logo
- Replace `logo.jpg` with your school logo
- Search for "Muslim Model School Khaddi" in HTML files and replace with your school name

---

## 📋 Browser Support
- Chrome (recommended)
- Firefox
- Edge
- Safari

> **Note:** All data is stored in `localStorage`. Clearing browser data will reset the system. For production use, a backend (Node.js, PHP, Python) with a real database should be implemented.

---

## 📞 Technical Details

| Technology | Usage |
|------------|-------|
| HTML5 | Structure & Semantic markup |
| CSS3 | Animations, Flexbox, Grid, Responsive |
| Vanilla JavaScript | Logic, DOM manipulation, localStorage |
| Font Awesome 6 | Icons |
| Google Fonts (Inter) | Typography |
| localStorage | Data persistence |
| sessionStorage | Authentication sessions |
| SVG | Donut charts |

---

*Muslim Model School Khaddi – Academic Year 2025–26*
