# CampusSetu

Frontend-first hackathon prototype for Polytechnic students.

## Stack
- React + TypeScript + Vite
- Tailwind CSS
- React Router
- Lucide React
- Mock/local React state only

## Run
```bash
npm install
npm run dev
```

Open the localhost URL shown by Vite.

## Build
```bash
npm run build
```

## Demo flow
Home → Discover → connect with 92% match → Mentor → request guidance → Study Pods → start timer/check goals/send chat → Resources → open 2025 DSA PYQ → Discuss in Pod → Campus Pulse → Roadmap.

## Optimizations made
- Shared mock-data layer instead of repeated JSX data.
- Shared AppContext for demo state.
- Reusable UI components.
- No Redux or unnecessary libraries.
- Responsive desktop/mobile navigation.
- No backend/API/video dependencies.
- All opportunity content is fictional/demo content.
