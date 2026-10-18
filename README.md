# CPU Scheduling Simulator

Interactive browser-based Operating Systems mini-project for visualizing and comparing CPU scheduling algorithms.

**Student in supplied report:** Abhishek Kumar · **Roll No.:** 25ET2041002  
**College:** Alard University · **Class:** 2nd Year · **Academic Year:** 2026–2027

## Features
- FCFS, non-preemptive SJF, non-preemptive Priority, and Round Robin
- Editable process ID, arrival time, burst time, and priority
- Gantt chart, including idle CPU intervals
- Completion, turnaround, waiting, and response time per process
- Average performance metrics and CPU utilization
- Algorithm comparison chart, sample data, validation, and learning section

## Run locally
Requires Node.js 18+ and npm.

```bash
npm install
npm run dev
```

To create a production build:

```bash
npm run build
npm run preview
```

## Formulas
- TAT = Completion Time − Arrival Time
- WT = Turnaround Time − Burst Time
- RT = First CPU Start Time − Arrival Time
- CPU utilization = Busy CPU Time ÷ Total Elapsed Time × 100%

## Project structure
```text
cpu-scheduling-simulator/
├── src/
│   ├── algorithms.ts
│   ├── App.tsx
│   ├── main.tsx
│   └── styles.css
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## GitHub deployment
This is a Vite app, so GitHub Pages needs a build workflow (deploy the generated `dist/` folder). Set Pages source to **GitHub Actions** and configure a Vite deployment workflow.

Before submitting, install dependencies, run the app, test every algorithm and add genuine screenshots to the report. Update student details if necessary and only mark tests complete after performing them.
