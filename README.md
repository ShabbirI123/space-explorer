# Space Explorer Web Application

The "Space Explorer" web application is an interactive portal that allows users to explore exciting data and images from space. With access to a wealth of information about space missions, astronauts, planets, and much more, this application provides a unique platform for space enthusiasts.

## Features

1. **Daily Space Images:** Discover stunning daily images from space.
2. **Missions Explorer:** Get detailed information about various space missions.
3. **Planets Guide:** Explore the different planets of our solar system with detailed data and images.
4. **Asteroids Tracker:** Track asteroids and get information about their positions and orbital data.
5. **Favorites:** Users can save their favorite data and images to easily find them later.

## Technologies

- **Frontend:** HTML5, CSS3, TypeScript
- **Build Tools:** npm, Webpack (or another tool of your choice)
- **Testing:** Jest (or another testing framework of your choice)
- **CI/CD:** GitHub Actions
- **Hosting:** GitHub Pages (or another hosting provider of your choice)

## Setup

### Prerequisites

- Node.js (v14.x or newer)
- npm (v7.x or newer)

### Installation

1. Clone the repository to your local computer:

   ```sh
   git clone https://github.com/your-username/space-explorer.git
   ```

2. Navigate to the project directory:
   
   ```sh
   cd space-explorer
   ```

3. Install the necessary dependencies:

   ```sh
   npm install
   ```
   
### Development

To start the application in development mode, run the following command:
   
   ```sh
   npm run dev
   ```

The application will start by default at http://localhost:3000 (or another port specified in the configuration file).
Production Build

To create a production build, run the following command:

   ```sh
   npm run build
   ```

The built files will be stored in the dist/ folder.

### Testing

To run the tests for the project, use the following command:

   ```sh
   npm run test
   ```

## Deployment

The project is automatically deployed via GitHub Actions to GitHub Pages (or another hosting provider of your choice) when changes are pushed to the main branch.

## License

This project is under the MIT License - see the LICENSE.md file for details.