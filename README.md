# RENVEXROI  App

A modern, responsive ROI application for managing withdrawals and transaction history with a clean, intuitive interface.

## Features

### 🔐 Authentication
- Secure user login and session management
- Credential-based authentication with cookie handling

### 💰 Withdrawal Management
- Request new withdrawals with bank details
- Real-time withdrawal status tracking (Approved/Pending/Rejected)
- Detailed transaction history with timestamps

### 📱 Responsive Design
- Mobile-first approach with adaptive layouts
- Dark/light mode toggle for user preference
- Touch-friendly interface optimized for all devices

### 📄 Receipt System
- Printable transaction receipts
- Bank-style receipt design with typewriter aesthetics
- Secure field masking for sensitive information
- Copy transaction IDs with one click

### 🎨 UI/UX Highlights
- Smooth animations with Framer Motion
- Modern gradient backgrounds and glass-morphism effects
- Intuitive navigation with bottom bar and top navbar
- Contextual status indicators with color coding

## Tech Stack

### Frontend
- **React** - Component-based UI library
- **React Router** - Client-side routing
- **Framer Motion** - Smooth animations and transitions
- **Tailwind CSS** - Utility-first CSS framework
- **Axios** - HTTP client for API requests

### Icons
- **React Icons (Tabler Icons)** - Consistent iconography

### State Management
- **React Context API** - Global state for dark mode and user data

### Build Tools
- **Vite** - Fast development server and build tool
- **ESLint** - Code linting and formatting

## Project Structure

```
src/
├── components/
│   ├── auth/           # Authentication components
│   ├── dashboard/      # Main dashboard views
│   ├── new/           # New UI components
│   ├── utils/         # Utility components
│   └── UserContext/   # Context providers
├── pages/              # Main application pages
├── utils/              # Helper functions
├── assets/             # Static assets
└── App.jsx             # Main application component
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/finwise-banking-app.git
cd finwise-banking-app
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Create environment file:
```bash
cp .env.example .env
```

4. Configure environment variables:
```env
VITE_API_BASE_URL=http://localhost:3000/api
```

### Development

Start the development server:
```bash
npm run dev
# or
yarn dev
```

### Building for Production

Create a production build:
```bash
npm run build
# or
yarn build
```

Preview the production build:
```bash
npm run preview
# or
yarn preview
```

## Environment Variables

| Variable | Description | Example |
|----------|-------------|---------|
| `VITE_API_BASE_URL` | Base URL for backend API | `http://localhost:3000/api` |

## Key Components

### Authentication
- **Login Page** - Secure user authentication
- **Session Management** - Persistent login sessions
- DEMO USER
- EMAIL: user@gmail.com
- PASSWORD user123

### Dashboard
- **Overview** - Account summary and quick actions
- **Withdrawal Form** - Request new withdrawals
- **Transaction History** - Complete transaction records

### UI Components
- **Navbar** - Top navigation bar
- **BottomBar** - Mobile-friendly bottom navigation
- **Loading** - Animated loading indicators
- **TransactionModal** - Detailed receipt viewer

## Responsive Design

The app is fully responsive and optimized for:
- **Mobile Devices** - Touch-friendly interface with proper spacing
- **Tablets** - Adaptive layouts for medium screens
- **Desktop** - Enhanced experience with additional screen real estate

### Mobile Features
- Bottom navigation bar for easy thumb access
- Scrollable modals for small screens
- Optimized touch targets
- Portrait and landscape orientations

## Dark Mode

The application supports both light and dark themes:
- Toggle between themes in the user interface
- System preference detection
- Persistent theme selection using localStorage

## Security Features

- Credential-based authentication
- Secure API communication with credentials
- Sensitive data masking (account numbers, names)
- Client-side data protection with localStorage encryption

## Performance Optimizations

- Code splitting for faster initial loads
- Lazy loading of non-critical components
- Optimized animations and transitions
- Efficient state management to prevent re-renders

## API Integration

The app communicates with a backend API for:
- User authentication
- Withdrawal requests
- Transaction history retrieval
- Account information management

## Customization

### Theming
Modify the Tailwind configuration in `tailwind.config.js` to customize:
- Color palette
- Spacing scales
- Typography
- Breakpoints

### Branding
Update the following files to customize branding:
- Logo components
- Color schemes
- Typography styles

## Browser Support

- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)

## Deployment

### Static Hosting
The app can be deployed to any static hosting service:
- Vercel
- Netlify
- GitHub Pages
- AWS S3

### Server Deployment
For server-based deployments:
1. Build the application
2. Serve the `dist` folder
3. Configure reverse proxy if needed

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

### Code Style
- Follow the existing code structure
- Use functional components with hooks
- Maintain consistent naming conventions
- Write descriptive commit messages

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, please open an issue on the GitHub repository or contact the development team.

## Acknowledgments

- [React](https://reactjs.org/) - For the amazing UI library
- [Tailwind CSS](https://tailwindcss.com/) - For the utility-first CSS framework
- [Framer Motion](https://www.framer.com/motion/) - For smooth animations
- [Tabler Icons](https://tabler-icons.io/) - For beautiful icons
- [Vite](https://vitejs.dev/) - For the blazing fast build tool

---

*Built with ❤️ for modern ROI experiences*
