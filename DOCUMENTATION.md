# CareerCraft - Next.js Starter Template

A professional Next.js starter template with authentication, dashboard, and modern design.

## Features

- ✅ **Next.js 15** with TypeScript and App Router
- ✅ **Professional Project Structure** with organized folders (components, lib, utils, hooks, types)
- ✅ **Authentication System** with NextAuth.js and credentials provider
- ✅ **Global Theme Provider** with dark/light mode support using next-themes
- ✅ **Responsive Design** with Tailwind CSS
- ✅ **Modern Landing Page** with hero section, features, and call-to-action
- ✅ **Sign In/Sign Up Pages** with form validation
- ✅ **Protected Dashboard** with middleware-based route protection
- ✅ **Professional UI Components** (Button, Input, Card) with consistent styling
- ✅ **Dark Mode Support** with system preference detection

## Pages

1. **Landing Page** (`/`) - Modern homepage with features and CTA
2. **Sign In Page** (`/auth/signin`) - User authentication
3. **Sign Up Page** (`/auth/signup`) - User registration 
4. **Dashboard** (`/dashboard`) - Protected main dashboard with sidebar navigation

## Tech Stack

- **Framework**: Next.js 15 with TypeScript
- **Styling**: Tailwind CSS with custom design system
- **Authentication**: NextAuth.js with credentials provider
- **Theme**: next-themes for dark/light mode
- **Icons**: Heroicons (SVG)
- **Utilities**: clsx, tailwind-merge for class management

## Getting Started

1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Set up Environment Variables**
   ```bash
   cp .env.example .env
   # Update NEXTAUTH_SECRET with a secure random string
   ```

3. **Run Development Server**
   ```bash
   npm run dev
   ```

4. **Build for Production**
   ```bash
   npm run build
   npm start
   ```

## Demo Credentials

For testing the authentication system:
- **Email**: demo@example.com
- **Password**: password123

## Project Structure

```
src/
├── app/                    # Next.js app router pages
│   ├── api/auth/          # NextAuth API routes
│   ├── auth/              # Authentication pages
│   ├── dashboard/         # Protected dashboard
│   └── globals.css        # Global styles
├── components/            # Reusable components
│   ├── layout/           # Layout components (Header, etc.)
│   └── ui/               # UI components (Button, Input, Card)
├── lib/                  # Utility libraries
├── types/                # TypeScript type definitions
└── middleware.ts         # Route protection middleware
```

## Key Features

### Authentication System
- NextAuth.js integration with credentials provider
- JWT-based sessions
- Route protection with middleware
- Automatic redirects for protected routes

### Theme System
- Light/dark mode toggle
- System preference detection
- Consistent color palette
- Smooth transitions between themes

### Professional UI
- Modern, clean design
- Responsive layout
- Consistent component styling
- Professional color scheme

### Dashboard Features
- Sidebar navigation
- Stats cards with metrics
- Quick action buttons
- Recent activity section
- Responsive layout

## Customization

This template is designed to be easily customizable:

1. **Styling**: Modify `tailwind.config.ts` and `globals.css`
2. **Components**: Extend or modify components in `src/components/`
3. **Authentication**: Configure providers in `src/lib/auth.ts`
4. **Database**: Add Prisma integration for persistent data storage
5. **Features**: Add new pages and functionality as needed

## Next Steps

This template provides a solid foundation for building professional web applications. Consider adding:

- Database integration (Prisma + PostgreSQL/MongoDB)
- Email verification system
- OAuth providers (Google, GitHub)
- File upload functionality
- Advanced dashboard features
- API endpoints for CRUD operations
- Testing setup (Jest, Cypress)
- Deployment configuration (Vercel, Docker)

## License

MIT License - feel free to use this template for personal or commercial projects.