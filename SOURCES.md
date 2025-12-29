# KanbanFlow - Source Code Documentation

This document describes the source code structure and files of the KanbanFlow project.

## Project Origin

KanbanFlow was created using **Lovable** (https://lovable.dev) - a platform that helps build web applications 20x faster with AI assistance.

### Original Lovable Project
- **Project ID**: b2d7c938-2194-41b6-881c-01caa8203608
- **Project URL**: https://lovable.dev/projects/b2d7c938-2194-41b6-881c-01caa8203608
- **Live Demo**: https://id-preview--b2d7c938-2194-41b6-881c-01caa8203608.lovable.app

## Complete Source File List

The following source files are part of this project:

### Components
- **src/components/LoginPage.tsx** - Login page with role selection
- **src/components/dashboard/DashboardHeader.tsx** - Dashboard header component
- **src/components/dashboard/Sidebar.tsx** - Navigation sidebar
- **src/components/dashboard/StatCard.tsx** - Statistics card component
- **src/components/kanban/KanbanBoard.tsx** - Main kanban board component
- **src/components/kanban/KanbanColumn.tsx** - Individual kanban column
- **src/components/kanban/ProjectCard.tsx** - Project card in kanban
- **src/components/kanban/CreateProjectDialog.tsx** - Create project modal
- **src/components/ui/badge.tsx** - Badge component
- **src/components/ui/button.tsx** - Button component
- **src/components/ui/card.tsx** - Card component
- **src/components/ui/dialog.tsx** - Dialog component
- **src/components/ui/input.tsx** - Input component
- **src/components/ui/label.tsx** - Label component
- **src/components/ui/progress.tsx** - Progress bar component
- **src/components/ui/select.tsx** - Select/dropdown component
- **src/components/ui/textarea.tsx** - Textarea component
- **src/components/ui/toaster.tsx** - Toast notifications
- **src/components/ui/sonner.tsx** - Sonner integration
- **src/components/ui/tooltip.tsx** - Tooltip component

### Contexts (State Management)
- **src/contexts/AuthContext.tsx** - Authentication context with user management
- **src/contexts/ProjectContext.tsx** - Project management context

### Pages
- **src/pages/Index.tsx** - Home/Login page
- **src/pages/Dashboard.tsx** - Main dashboard page
- **src/pages/Kanban.tsx** - Kanban board page
- **src/pages/NotFound.tsx** - 404 page

### Types
- **src/types/kanban.ts** - TypeScript type definitions

### Configuration
- **src/App.tsx** - Main application component with routing
- **src/main.tsx** - Application entry point
- **src/index.css** - Global styles with Tailwind
- **tailwind.config.ts** - Tailwind CSS configuration
- **vite.config.ts** - Vite build configuration
- **tsconfig.json** - TypeScript configuration

### Root Files
- **README.md** - Project documentation
- **package.json** - Dependencies and scripts

## Key Features Implemented

### 1. Authentication System
- Role-based access control (RBAC)
- Support for 4 user roles: Admin, Manager, Employee, Client
- Mock authentication with email and password

### 2. Kanban Board
- Drag-and-drop functionality
- 4 columns: Outgoing, Ongoing, Review, Completed
- Real-time project status updates

### 3. Dashboard
- Statistics overview
- Recent projects list
- Activity feed
- Team performance metrics

### 4. Design System
- Dark theme with blue-to-purple gradients
- Responsive design
- Glass-morphism effects
- Status-coded badges and colors

## Technology Stack

- **Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS with custom configuration
- **Routing**: React Router DOM v6
- **UI Components**: Radix UI
- **Icons**: Lucide React
- **Build Tool**: Vite
- **State Management**: React Context API
- **Notifications**: Sonner
- **Utilities**: Class Variance Authority, clsx, tailwind-merge

## Development Setup

### Installation
```bash
npm install
```

### Development Server
```bash
npm run dev
```

### Build for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

## Getting Started with the Code

1. Clone the repository
2. Run `npm install` to install dependencies
3. Run `npm run dev` to start the development server
4. Open http://localhost:5173 in your browser
5. Log in with any email and a password of at least 4 characters

## File Structure Overview

```
kanbanflow/
├── src/
│   ├── components/
│   │   ├── kanban/
│   │   ├── dashboard/
│   │   ├── ui/
│   │   └── LoginPage.tsx
│   ├── contexts/
│   │   ├── AuthContext.tsx
│   │   └── ProjectContext.tsx
│   ├── pages/
│   │   ├── Dashboard.tsx
│   │   ├── Kanban.tsx
│   │   ├── Index.tsx
│   │   └── NotFound.tsx
│   ├── types/
│   │   └── kanban.ts
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.css
│   └── lib/
│       └── utils.ts
├── public/
├── tailwind.config.ts
├── vite.config.ts
├── tsconfig.json
├── package.json
├── README.md
└── SOURCES.md (this file)
```

## Next Steps

To view and download all source files:

1. Visit the Lovable editor: https://lovable.dev/projects/b2d7c938-2194-41b6-881c-01caa8203608
2. All files are available in the code editor
3. Files can be exported or integrated into your own project

## Credits

Built with **Lovable** - AI-powered web development platform.
