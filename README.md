# GridSense

GridSense is an intelligent smart energy monitoring and electricity waste analysis dashboard. It helps users analyze household electricity usage, estimate bills, detect inefficient appliances, and visualize energy consumption trends.

## Features

- **Dashboard Overview**: Track your total monthly energy usage (kWh), estimated electricity bill, CO₂ emissions, and efficiency score.
- **Appliance Input System**: Easily add multiple appliances to track their individual consumption based on wattage and hours used.
- **Smart Energy Insights**: Receive automated tips on reducing your power bill, highlighting your top power consumers, and detecting "vampire" appliances on standby.
- **Data Visualization**: View pie charts breaking down usage by category, bar graphs for monthly consumption, and line charts for weekly trend simulations.
- **Responsive & Modern UI**: Built with a sleek dark mode design, glassmorphism UI components, and subtle animations for a premium experience.
- **Local Storage Persistence**: Your data is saved securely in your browser, meaning you don't lose track of your appliances if you close the page.

## Tech Stack

- **Frontend Framework:** [React](https://reactjs.org/) + [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Charts:** [Recharts](https://recharts.org/)
- **Icons:** [Lucide React](https://lucide.dev/)

## Installation & Running Locally

1. **Install Dependencies:**
   ```bash
   npm install
   ```

2. **Start the Development Server:**
   ```bash
   npm run dev
   ```

3. **Build for Production:**
   ```bash
   npm run build
   ```

## Deployment

The project is fully configured for deployment on platforms like Vercel or Netlify. Simply import the repository and deploy using standard Vite settings (Build command: `npm run build`, Output directory: `dist`).

## Future Improvements

- Backend integration for multi-device sync.
- AI-based energy-saving predictions.
- Downloadable PDF usage reports.
- Advanced theme toggling (Light/Dark mode).
