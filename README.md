# Google Sheets Automated Portfolio Tracker

This project is an interface for managing a portfolio tracker using Google Sheets. Built with Next.js, it offers a modern and efficient approach to track, visualize, and manage portfolio data through Google Sheets, leveraging the strengths of server-side rendering, TypeScript safety, and customizable UI components.

## Tech Stack

- **Next.js 14**: Frontend framework for server-side rendering and improved page load speed.
- **TypeScript**: Provides type safety and helps minimize errors during development.
- **ShadCN UI Library**: Provides pre-built UI components that speed up development.
- **Tailwind CSS**: For utility-first styling, allowing rapid and consistent design.
- **React Query**: To manage data fetching and server-state synchronization with caching.
- **Zustand**: For managing local UI state in a lightweight and straightforward way.
- **Google Sheets API**: Integration with Google Sheets to read and write portfolio data.
- **Clerk Auth**: Secure authentication for user login and access management.

## Key Features

- **Real-time Portfolio Data**: Automatically fetches data from Google Sheets and displays it in an organized way.
- **Secure Authentication**: Leveraging Clerk Auth for managing user sessions.
- **Scalable Data Integration**: Next.js API routes are used to securely communicate with Google Sheets, making it easy to expand and manage large datasets.
- **Modern UI**: Built with ShadCN and Tailwind CSS, providing a responsive and user-friendly experience.

## Running the Project Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/joshfarhi/finance-dashboard.git
   ```
2. **Install Dependencies**:
   ```bash
   cd finance-dashboard
   npm install
   ```
3. **Environment Variables**:
   Set up the environment variables required for Google Sheets API and Clerk Auth in a `.env` file:
   ```
   GOOGLE_SHEETS_API_KEY=<Your Google Sheets API Key>
   CLERK_API_KEY=<Your Clerk Auth API Key>
   ```
4. **Run the Development Server**:
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) to see your application in the browser.

## Deployment

The project is designed for deployment on **Vercel**. Vercel’s edge caching and serverless functions allow for efficient data fetching and optimized performance.

- Connect your GitHub repository to Vercel.
- Set up necessary environment variables in the Vercel dashboard.
- Deploy with one click.

## Future Enhancements

- **Database Integration**: Adding Prisma with PostgreSQL for storing additional data like user preferences or analytics.
- **Caching Improvements**: Implementing Redis to reduce Google Sheets API calls and enhance performance.
- **Advanced Reporting**: Building custom visual reports directly on the interface using data visualization tools.

## Contributing

Contributions are welcome! Please open a pull request or an issue for any suggestions or fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

For questions or suggestions, please reach out to [Joshua Farhi](https://github.com/joshfarhi) or [JR Concepcion](https://github.com/JRCon1/).

---

**Repository Link**: [finance-dashboard](https://github.com/joshfarhi/finance-dashboard)
