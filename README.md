# Car_Rental_Dashboard
📘Car Rental Dashboard (React + Tailwind)
 🎨 Design Reference: (Car Rent Dashboard UI) https://www.figma.com/design/ohC3iZIhRQeY0PxSPOFY1D/Car-Rental-Company-Dashboard-UI--Community-?node-id=0-1&p=f&t=kKxKBtrcJcEtdCyK-0

🎯 Objective
Convert the provided Car Rental Dashboard design into a React app using:

React (Vite recommended)


TailwindCSS


Reusable components


Static mock data


🧩 Features & Sections
🟦 1. Sidebar
Logo section with "Car Rent" text


Navigation links:


Dashboard (active)


Drivers


Bookings


Notifications


Settings


Subsection: Report (Payment Details, Transactions, Car Report)


Logout button at the bottom


🟨 2. Top Bar
Search bar on the top right


Notification icon


🟩 3. Stats Section (Left side cards)
Income card


Expenses card


Hire vs Cancel card (with percentages & colored status)


Use static numbers from the screenshot. Data can be an object/array.

🟧 4. Car Availability Box
Input field for car number


Date picker (static input)


Time selector (static input)


"Check" button


These inputs don’t need to be functional; just focus on UI.

🟪 5. Live Car Status Table
Columns: No., Car no., Driver, Status, Earning, Details button


Show 3 rows with static mock data:


Alex Noman (Completed)


Razib Rahman (Pending)


Luke Norton (In route)


Status indicators:

Green dot = Completed


Yellow dot = Pending


Red dot = In route


🧠 What You Should Practice
Splitting UI into reusable components:


Sidebar


StatCard


CarAvailabilityBox


CarStatusTable


TableRow


Passing props to components for dynamic rendering


Styling with Tailwind utility classes


Using flex/grid for layouts


Making it responsive


📂 Suggested Structure
css

CopyEdit

src/

├── components/

│   ├── Sidebar.jsx

│   ├── TopBar.jsx

│   ├── StatCard.jsx

│   ├── CarAvailability.jsx

│   ├── CarStatusTable.jsx

│   ├── TableRow.jsx

│

├── data/

│   ├── stats.js

│   └── cars.js

│

├── pages/

│   └── Dashboard.jsx

│

├── App.jsx

└── index.jsx



📜 Requirements
Recreate layout to closely match the design


Use TailwindCSS for all styling


Use static mock data


Create reusable components


Maintain responsive behavior for tablet & desktop (mobile optional but a plus)


✅ Evaluation Checklist
Feature

Status

Layout matches screenshot

✅

Reusable components used

✅

Static data rendered dynamically

✅

Tailwind styling

✅

Responsive layout

✅

Clean file structure

✅

📬 Submission
Push to GitHub and share the repo link


Include README.md with:


How to run the project


Components created


Any extra features (if added)
