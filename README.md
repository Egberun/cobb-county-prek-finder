# Cobb County Pre-K Finder

A comprehensive tool for parents to find, compare, and evaluate Pre-K facilities in Cobb County, Georgia.

## Project Setup

This project uses Next.js 14 with TypeScript and Tailwind CSS. To set up the project:

1. Create a new Next.js project:
```bash
npx create-next-app@latest cobb-county-prek-finder --typescript --tailwind --eslint
```

2. Install additional dependencies:
```bash
npm install @radix-ui/react-icons @radix-ui/react-slot lucide-react recharts
npm install class-variance-authority clsx tailwind-merge tailwindcss-animate
```

3. Configure Tailwind CSS:
```bash
npx tailwindcss init -p
```

4. Set up project structure:
```
src/
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   ├── compare/
│   │   └── page.tsx
│   └── facility/
│       └── [id]/
│           └── page.tsx
├── components/
│   ├── PreKSearch.tsx
│   ├── PreKResults.tsx
│   ├── FacilityComparison.tsx
│   └── FacilityProfile.tsx
├── data/
│   └── facilities.ts
└── lib/
    └── utils.ts
```

## Development

Run the development server:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Features

- Search and filter Pre-K facilities
- Compare multiple facilities
- View detailed facility profiles
- Check quality ratings and compliance
- Explore neighborhood information
- Read parent reviews

## Data Sources

- Georgia DECAL database
- Quality Rated system
- Cobb County School District
- Parent reviews and ratings
- Neighborhood demographics
- Housing market information