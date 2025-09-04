# KhedmaNow 🛠️

KhedmaNow is a **local services booking platform** that connects customers with trusted service providers.  
Users can search, book, and manage services such as home repairs, cleaning, tutoring, beauty, and more — all in one place.  

---

## 🚀 Features

### 1- Location-based Services
- Detects user location to show only nearby providers.
- Remembers last used location for faster repeat bookings.
- **Why it matters:** faster response, relevant results, less no-shows.

---

### 2- User Roles (Customer & Service Provider)
- **Customers:** browse → search → book → pay cash → review.
- **Providers:** create profile, set services & prices, manage availability, accept/decline bookings.
- Role-aware navigation and dashboards for each type.
- **Why it matters:** clear flows and simpler UX for each user.

---

### 3- Service Provider Profiles
- Profile header: photo, name, rating, service category, city/coverage area.
- Details: years of experience, bio, services offered, **pricing** (hourly + minimum charge).
- **Availability preview** (next available slots).
- **Ratings & Reviews** with photos (optional) and verified badge after completed bookings.
- **Why it matters:** builds trust and helps users decide quickly.

---

### 4- Booking System with Calendar
- Opens from “Book Now” on a provider profile.
- Shows **provider-only available days & time slots** (not full calendar).
- Smart checks: prevents double booking, enforces lead time, shows travel window if needed.
- Price summary: base/min charge + hourly + estimated total before confirmation.
- Booking statuses: **Pending → In Progress → Completed** (+ Canceled when applicable).
- Confirmation screen + email/notification receipt.
- **Why it matters:** transparent pricing & availability, smoother coordination.

---

### 5- Payment Options (Cash First)
- **Cash on Delivery** as the default.
- Optional “Mark as Paid” step after completion (for records).
- Can add online payments later without changing the flow.
- **Why it matters:** higher trust in early stages and simple adoption.

---

### 6- Real-time Notifications
- Status updates for both sides:
  - Customer: request received, accepted/declined, on the way, completed.
  - Provider: new booking request, reminders, cancellation alerts.
- Channels: in-app notifications + email; push notifications (optional later).
- Notification Center with filters: **Pending / In Progress / Completed** and timestamps.
- **Why it matters:** reduces no-shows and keeps everyone aligned.

---

### 7- Ratings & Reviews
- Available only after **Completed** bookings (to prevent spam).
- 1–5 star rating + short comment; can add photo proof (optional).
- Aggregated rating on provider cards and profiles.
- Report-review flow for abuse.
- **Why it matters:** trust, quality control, and better matching.

---

### 8- Admin Dashboard
- KPIs: total bookings, active users, active providers, revenue proxy, disputes.
- User management: approve/suspend providers, verify identities, reset passwords.
- Service management: categories, price ranges, featured providers.
- Dispute center: view complaints, request evidence, resolve and record outcomes.
- Audit logs & basic analytics (popular categories, peak times, retention).
- **Why it matters:** platform health, safety, and scalable operations.

---

### 9- Booking History & Invoices
- Both users can see booking history with statuses and receipts.
- Export/print basic invoice (even for cash) for record-keeping.
- **Why it matters:** transparency and professionalism.


---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap, Javascript, React. 
- **Backend**: Node.js (Express.js)  
- **Database**: MongoDB / MySQL    
- **Version Control**: Git & GitHub

---

## 📌 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/alitobal-06/DEPI_Project.git
   cd DEPI_Project
