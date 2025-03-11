
Two main elements

- Meal tracking component including all the concepts from the MEALS app
- Weight lifting component 
- Open sourced

### Tech Stack

##### Front End
- HTML & CSS 
- TypeScript

##### Back End
- Node.js + Express.js (REST API)

##### Database
- PostgreSQL

### Example File Structure

workout-tracker/
│── backend/                  # Node.js backend (Express API)
│   ├── src/
│   │   ├── controllers/       # Business logic for handling requests
│   │   │   ├── workoutController.ts
│   │   ├── models/            # Database models (PostgreSQL tables)
│   │   │   ├── workoutModel.ts
│   │   ├── routes/            # API routes
│   │   │   ├── workoutRoutes.ts
│   │   ├── db.ts              # PostgreSQL connection setup
│   │   ├── server.ts          # Express.js main server file
│   ├── .env                   # Environment variables (DB credentials)
│   ├── package.json           # Node.js dependencies
│   ├── tsconfig.json          # TypeScript config
│   ├── README.md
│
│── frontend/                  # Frontend (HTML, TypeScript, CSS)
│   ├── public/                # Static assets (CSS, images, icons)
│   │   ├── styles.css
│   ├── src/                   # TypeScript logic
│   │   ├── index.ts           # Main frontend logic
│   │   ├── api.ts             # API calls to the backend
│   ├── index.html             # Main HTML page
│   ├── package.json           # Dependencies (if using TypeScript bundler)
│   ├── tsconfig.json          # TypeScript config for frontend
│   ├── README.md
│
│── .gitignore                 # Ignore unnecessary files
│── README.md                  # Project documentation
│── docker-compose.yml         # Optional: for local dev using Docker

