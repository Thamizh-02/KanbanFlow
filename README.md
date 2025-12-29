# KanbanFlow

A professional Kanban project management system with role-based access control, built with React, TypeScript, and Tailwind CSS.

## Features

- **Role-Based Access Control**: Admin, Manager, Employee, and Client roles
- **Kanban Board**: Drag-and-drop project management with 4 columns (Outgoing, Ongoing, Review, Completed)
- **Project Creation**: Create and manage projects with priority, timeline, and budget
- **Real-time Updates**: Live dashboard with project statistics
- **Dark Theme**: Modern dark interface with blue-to-purple gradients

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- React Router DOM
- Radix UI Components
- Lucide Icons

## Getting Started

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

## Project Structure

```
src/
├── components/
│   ├── kanban/         # Kanban board components
│   ├── dashboard/      # Dashboard components
│   ├── ui/            # Reusable UI components
│   └── LoginPage.tsx  # Login component
├── contexts/
│   ├── AuthContext.tsx      # Authentication context
│   └── ProjectContext.tsx   # Project management context
├── pages/
│   ├── Dashboard.tsx   # Dashboard page
│   ├── Kanban.tsx     # Kanban page
│   └── Index.tsx      # Home/Login page
├── types/
│   └── kanban.ts      # TypeScript types
└── App.tsx
```

## Demo Credentials

For testing, enter any email and a password with at least 4 characters.

## Built with Lovable

This project was initially scaffolded and designed using Lovable (https://lovable.dev)
