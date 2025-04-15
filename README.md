# Airdropshub

A web application for discovering and participating in cryptocurrency airdrops.

## Features

- User authentication (Sign up, Login)
- Browse airdrop listings
- Add new airdrop projects
- Donate to support the platform
- Responsive design

## Tech Stack

- React
- TypeScript
- Chakra UI
- Supabase (Authentication & Database)
- React Router
- Vite

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory with your Supabase credentials:
   ```
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Build for production:
   ```bash
   npm run build
   ```

## Project Structure

```
src/
  ├── components/     # Reusable UI components
  ├── hooks/         # Custom React hooks
  ├── lib/          # Third-party library configurations
  ├── pages/        # Page components
  ├── theme.ts      # Chakra UI theme configuration
  ├── App.tsx       # Main application component
  └── main.tsx      # Application entry point
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

MIT 