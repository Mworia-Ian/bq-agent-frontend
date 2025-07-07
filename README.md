# BQ Agent Frontend

A modern chat interface for an agricultural sales assistant, built with Next.js and React.

## Features

- Real-time chat interface
- Responsive design for all devices
- Markdown support for rich text formatting
- Clean and intuitive user interface

## Tech Stack

- [Next.js](https://nextjs.org/) - The React Framework for the Web
- [TypeScript](https://www.typescriptlang.org/) - Type-safe JavaScript
- [React Markdown](https://github.com/remarkjs/react-markdown) - Markdown component for React
- [CSS Modules](https://github.com/css-modules/css-modules) - For scoped CSS styling

## Getting Started

### Prerequisites

- Node.js 18.0 or later
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Mworia-Ian/bq-agent-frontend.git
   cd bq-agent-frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Project Structure

- `/app` - Main application directory
  - `page.tsx` - Main page component
  - `layout.tsx` - Root layout component
  - `page.module.css` - Styles for the main page
  - `globals.css` - Global styles
- `/public` - Static files
- `/node_modules` - Dependencies (automatically created)

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

## Environment Variables

Create a `.env.local` file in the root directory to set up environment variables:

```env
NEXT_PUBLIC_API_URL=your_api_url_here
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
