# Budget Tracker

Finarium is a **full-stack personal finance web app** built with **Vanilla JS + Tailwind CSS** on the front end and **Firebase (Firestore, Auth, Cloud Functions)** on the back end.  
It lets users track income, expenses, and savings in real time with clean charts and a friendly animated mascot.

##  Features

- **Real-time data sync** using Firebase Firestore
- **Anonymous or custom-token authentication**
- Add, edit, and delete:
  -  **Income** sources
  -  **Outflows** (Bills, Expenses, Debt)
  -  **Savings** goals
- **Dynamic dashboard** with:
  - Net balance calculations
  - Doughnut chart of outflows (Chart.js)
- Responsive **Tailwind UI** with a collapsible sidebar
- Fun **mascot bubble** that offers motivational tips

## Tech Stack

| Layer       | Technology                                         |
|-------------|----------------------------------------------------|
| Front end   | HTML5, Vanilla JavaScript (ES modules), Tailwind   |
| Charts      | [Chart.js](https://www.chartjs.org/)               |
| Back end    | Firebase Firestore (database & real-time updates)  |
| Auth        | Firebase Auth (anonymous & custom token)           |
| Hosting     | Firebase Hosting or any static host (Netlify, Vercel, etc.) |

Although Firebase is “serverless,” this project qualifies as **full-stack** because it implements both:
* **Client logic/UI** and
* **Server-side data & auth rules / optional Cloud Functions**

##  Getting Started

### Clone the repo
```bash
git clone [https://github.com/Luvienna/budget-tracker.git]
cd finarium-budget-tracker
