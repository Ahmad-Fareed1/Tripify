# 🌍 Tripify

**Tripify** is a modern, full-stack travel search and booking platform. It provides users with a seamless experience to search for flights, find hotel deals, and explore curated travel packages.

## ✨ Key Features

- 🛫 **Flight Search**: Real-time flight search with detailed filtering (airline, stops, class).
- 🏨 **Hotel Deals**: Find the best prices for hotels in your destination.
- 📦 **Travel Packages**: Combined flight and hotel deals for maximum savings.
- 🔐 **User Dashboard**: Manage bookings and view flight/hotel tickets.
- 🎨 **Responsive UI**: Built with a premium aesthetic using Tailwind CSS and shadcn/ui.

## 🛠️ Tech Stack

- **Frontend**: React, TypeScript, Vite
- **Styling**: Tailwind CSS, Lucide React (Icons)
- **UI Components**: shadcn/ui
- **Backend/Database**: [Supabase](https://supabase.com/)
- **API Management**: Supabase Edge Functions & Vercel Serverless Functions

## 🔌 API Integrations

Tripify leverages powerful external APIs to fetch real-time travel data:

- **SerpApi**: Used for fetching real-time Google Flights and Google Hotels data.

## 🚀 Getting Started

### Prerequisites

- Node.js (v18+)
- npm or bun


## 📁 Project Structure

```text
├── api/             # Vercel Serverless Functions
├── src/
│   ├── components/  # Reusable UI components
│   ├── hooks/       # Custom React hooks
│   ├── pages/       # Route-level components (Deals, Flights, Hotels)
│   └── services/    # API and Supabase service layers
├── supabase/        # Edge Functions and DB schema
└── public/          # Static assets
```

