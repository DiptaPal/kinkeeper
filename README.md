# 👥 KeenKeeper — Keep Your Friendships Alive

**KeenKeeper** is a friendship management web application designed to help you maintain meaningful relationships by keeping track of your friends, monitoring contact goals, and recording everyday interactions. It helps you stay connected with the people who matter most through a simple, organized, and responsive dashboard.

## 🌐 Live Demo

- **Live Website:** https://kinkeeper-lemon.vercel.app/
- **GitHub Repository:** https://github.com/DiptaPal/kinkeeper

---

## 📖 About the Project

In our busy lives, it is easy to lose touch with friends, even when those relationships matter to us. KeenKeeper helps solve this problem by providing a central place to manage friend profiles, track when you last contacted someone, set relationship goals, and maintain a timeline of interactions.

The application features a dashboard for viewing friends, individual friend detail pages, an interaction timeline, and a friendship analytics page. Its responsive interface is designed to work smoothly across mobile, tablet, and desktop devices.

## ✨ Key Features

### 🏠 1. Home Dashboard

- Display all friends in an organized card layout.
- Show profile pictures, names, days since the last contact, and relationship tags.
- Display color-coded relationship statuses:
  - 🔴 **Overdue** — The contact goal has passed.
  - 🟡 **Almost Due** — The next contact is approaching.
  - 🟢 **On Track** — The friendship is within its contact goal.
- Show summary cards for a quick overview of friendship activity.
- Navigate to an individual friend's detail page by clicking their card.
- Display a loading animation while friend data is being fetched.

### 👤 2. Friend Details Page

Each friend has a dedicated detail page containing their personal and relationship information.

- View the friend's profile picture, full name, email, biography, tags, and current status.
- Track the number of days since the last interaction.
- View the relationship contact goal and next due date.
- Access relationship management actions, including Snooze 2 Weeks, Archive, and Delete.
- Edit the relationship goal.
- Record new interactions using the Quick Check-In feature.

### ⚡ 3. Quick Check-In

Quick Check-In makes recording an interaction simple and convenient.

Users can select one of three interaction types:

- 📞 **Call**
- 💬 **Text**
- 📹 **Video**

When an interaction button is clicked:

- A new timeline entry is created for the selected interaction.
- The entry includes the interaction type, friend's name, and current date.
- A toast notification confirms that the interaction has been recorded.
- The Timeline and Friendship Analytics pages reflect the recorded interactions.

### 📜 4. Timeline

The Timeline page provides a chronological history of recorded friendship interactions.

- Display the interaction date and title.
- Show an appropriate icon for calls, texts, and video calls.
- Filter timeline entries by interaction type.
- View all interactions or focus on a particular type.
- Display a helpful message when no interactions match the selected filter.

### 📊 5. Friendship Analytics

The Stats page provides a visual overview of friendship interactions.

- Display a **Friendship Analytics** heading.
- Visualize the distribution of calls, texts, and video interactions using a Recharts donut/pie chart.
- Compare interaction counts using different chart segments.
- Use tooltips and a legend to make the chart easier to understand.

### 🧭 6. Navigation and Responsive Layout

- Navigate between Home, Timeline, and Stats pages.
- Display icons alongside navigation links.
- Highlight the active navigation item.
- Provide responsive layouts for mobile, tablet, and desktop screens.
- Include a consistent footer and a custom 404 page for unknown routes.

### 🔔 7. Notifications and User Feedback

- Display toast notifications when a user records a call, text, or video interaction.
- Provide visual feedback for important user actions.
- Show a clear empty state when filtered timeline results are unavailable.

### 🚀 8. Deployment Ready

- Designed for deployment on platforms such as Vercel.
- Support direct navigation to application pages after deployment.
- Include loading and fallback states for a smoother user experience.
- Provide a structured project layout for easier maintenance.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Next.js** | React framework for building the application and handling page routing. |
| **React.js** | Building reusable components and interactive user interfaces. |
| **JavaScript (ES6+)** | Application logic, event handling, filtering, and data manipulation. |
| **Tailwind CSS** | Utility-first styling and responsive layouts. |
| **DaisyUI** | Prebuilt UI components and styling utilities. |
| **Recharts** | Creating the friendship interaction pie/donut chart. |
| **React Hooks** | Managing component state and application behavior with hooks such as `useState`. |
| **React Toastify / Toast Library** | Displaying toast notifications for user interactions. |
| **JSON** | Storing structured friend profile data. |
| **Git & GitHub** | Version control and source code management. |
| **Vercel** | Hosting and deploying the Next.js application. |

> **Note:** Keep only the technologies and libraries that are actually installed and used in your project. For example, list React Toastify only if that is your notification library.

---

## 📂 Main Application Sections

| Page | Route | Description |
|---|---|---|
| Home | `/` | Dashboard displaying friend cards and summary statistics. |
| Friend Details | `/friends/[friendId]` | Individual friend information, relationship goals, and Quick Check-In actions. |
| Timeline | `/timeline` | History of friendship interactions with type-based filtering. |
| Stats | `/stats` | Visual analytics of call, text, and video interactions. |
| Not Found | Custom 404 | Displays a fallback page for invalid routes. |

*The friend details route should match the actual route structure used in your project.*

---

## 📈 Example Interaction Workflow

1. Open the Home dashboard.
2. Select a friend to view their details.
3. Review their contact history and relationship goal.
4. Choose Call, Text, or Video in the Quick Check-In section.
5. Receive a toast notification confirming the interaction.
6. Open the Timeline page to view the newly recorded interaction.
7. Filter the timeline by interaction type.
8. Visit the Stats page to see the interaction counts visualized in a chart.

---

## 📱 Responsive Design

KeenKeeper is designed to provide a consistent experience across different screen sizes.

- **Mobile:** Compact layouts and vertically stacked content.
- **Tablet:** Flexible card grids and comfortable spacing.
- **Desktop:** Multi-column layouts, a four-column friend grid, and a wider analytics dashboard.

---

## ⚙️ Getting Started

Follow these steps to run KeenKeeper locally.

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- npm or another compatible package manager
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git
```

### 2. Navigate to the Project

```bash
cd your-repository
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm run dev
```

### 5. Open the Application

Visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🔮 Future Improvements

Potential enhancements for future versions include:

- Add, edit, and delete friend profiles with persistent storage.
- Implement search by friend name or interaction type.
- Add sorting options for newest and oldest timeline entries.
- Persist interaction history across page reloads.
- Add user authentication and personalized dashboards.
- Implement reminders for upcoming relationship goals.
- Connect the application to a database for permanent data storage.
- Improve analytics with additional charts and relationship trends.

---

## 🎯 Project Goals

KeenKeeper demonstrates practical frontend development skills, including component-based architecture, Next.js routing, responsive UI design, React state management, JSON data handling, event-driven interactions, filtering, notifications, and data visualization.

The goal is to create a useful, accessible, and user-friendly application that encourages people to stay connected with their friends.

---

## 👨‍💻 Author

**Dipta Pal**

MSc Computer Science

---

⭐ If you find KeenKeeper interesting, feel free to explore the repository and share your feedback.

**KeenKeeper — Because every friendship deserves attention.**