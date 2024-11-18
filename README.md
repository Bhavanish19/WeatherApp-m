# Weatherly - Your Ultimate Weather Companion

Weatherly is a comprehensive weather application that provides real-time updates, forecasts, and detailed weather metrics. Built with modern web technologies, Weatherly aims to provide a seamless and engaging user experience, no matter where you are or what device you're using.

## 🚀 Key Features

- 🌍 **Real-time weather updates and forecasts**
- 🌡️ **Detailed weather metrics** including temperature, humidity, and wind speed
- 🌆 **Air quality monitoring** and **UV index tracking**
- 🎨 **Light/Dark theme support** for user preference
- 🌐 **Multi-language support** for a diverse audience
- 📱 **Responsive design** for various devices
- ♿ **Accessibility-focused interface** ensuring everyone can use the app
- 🗺️ **Interactive weather maps** to visualize weather data intuitively

## 🛠️ Built With

- **Next.js**: React framework for production
- **React**: JavaScript library for building user interfaces
- **TypeScript**: Typed superset of JavaScript
- **Tailwind CSS**: Utility-first CSS framework for rapid styling
- **Radix UI**: Unstyled, accessible components for React
- **Lucide React**: Beautiful and consistent icon pack
- **Recharts**: Composable charting library for visualizing weather metrics
- **React Leaflet**: Maps integration to provide interactive weather maps
- **next-themes**: Theme management for light and dark modes
- **React Error Boundary**: Error handling to enhance app reliability

## 📈 Development Process

The development of Weatherly focused on providing a robust yet intuitive user experience. Throughout the project, special attention was paid to the following:

- 🌍 **Core Weather Tracking Features**: Integrated essential weather tracking capabilities, such as real-time updates, forecast accuracy, and detailed weather metrics.
- 🔍 **OpenWeather API Integration**: Integrated the OpenWeather API to ensure accurate and up-to-date weather information.
- 🎨 **Responsive UI**: Designed and implemented a user interface that adapts smoothly to different screen sizes and themes, enhancing the user experience.
- ♿ **Accessibility**: Implemented accessibility features to make Weatherly usable by everyone, regardless of their abilities.
- ⚡ **Performance Optimization**: Optimized the app's performance to provide a seamless experience on both desktop and mobile devices.

## 🌤️ Weather API Server

The backend of Weatherly is powered by a high-performance, TypeScript-based Express server that integrates with the OpenWeather API. It offers comprehensive weather data with reliability and efficiency.

### 🚀 Key Features

- **Comprehensive Weather Data**
  - 🌍 Real-time weather conditions and detailed forecasts
  - 🌆 Air pollution metrics for informed decision-making
  - 🏙️ City search functionality for finding weather in different locations

- **Robust Security**
  - 🛡️ Rate limiting to protect against excessive requests
  - 🔐 CORS configuration for controlled resource sharing
  - 🛑 Helmet for security headers
  - ✅ Environment variable validation to ensure proper configuration

- **Performance Optimized**
  - 🚄 In-memory caching for fast response times
  - 📦 Response compression for optimized network usage
  - ⚠️ Efficient error handling to ensure stability
  - 📋 Request logging to keep track of server activity

- **Type Safety**
  - 📘 Full TypeScript implementation for reliable development
  - ✅ Zod validation schemas for input validation
  - 💻 Type-safe request handling to reduce runtime errors

### 🛠️ Built With

- **Express.js**: Fast, unopinionated web framework for building backend services
- **TypeScript**: Type-safe JavaScript to enhance code quality
- **Helmet**: Middleware for enhancing security
- **CORS**: Cross-origin resource sharing configuration
- **Compression**: Response compression to improve performance
- **Zod**: Runtime type validation for type safety
- **Express Rate Limit**: Middleware for limiting repeated requests
- **Winston**: Logging library for monitoring server events
- **Axios**: HTTP client for making API requests

## 📜 How to Run the Project


Clone the Repository: Clone this repository to your local machine using git clone <repository-url>.

Configure Environment Variables: Create a .env file in the root directory with the following keys:

API_KEY: Your OpenWeather API key.

Other necessary keys for security and configuration.

Build Docker Image: Build the Docker image using the following command:

docker build -t weatherly-app .

Run the Docker Container: Run the container on port 3000 using the command:

docker run -p 3000:3000 --env-file .env weatherly-app

Access the Application: Once the container is running, you can access Weatherly in your browser at http://localhost:3000.

ScreenShots :

[Screenshot 2024-11-18 at 3 24 03 AM](https://github.com/user-attachments/assets/f4381d66-b93f-4929-8b60-dfba12d84724)

![Screenshot 2024-11-18 at 3 24 11 AM](https://github.com/user-attachments/assets/c825eb37-b632-4dbd-ac68-1b1a991b0513)

![Screenshot 2024-11-18 at 3 24 21 AM](https://github.com/user-attachments/assets/ecdf7e5f-ded4-4270-8491-99b01433d2a9)

![Screenshot 2024-11-18 at 3 24 39 AM](https://github.com/user-attachments/assets/69b39f07-1874-473f-aaae-c679ccc575c2)




