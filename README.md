# 🚗 Full Stack Uber Clone

This is a full-stack mobile application that replicates the core functionalities of Uber. It is built using React Native and Expo, with a backend powered by PostgreSQL and serverless functions.

## 🛠️ Tech Stack

* **Frontend**: React Native, Expo, Tailwind CSS
* **State Management**: Zustand
* **Backend**: PostgreSQL (NeonDB)
* **Authentication**: Clerk
* **Payments**: Stripe
* **Maps & Geolocation**: Google Maps API, Geoapify

## 🚀 Quick Start

Follow these steps to set up and run the project locally.

### Prerequisites

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/en)
* [npm](https://www.npmjs.com/) (or yarn)

### 1. Clone the Repository

```bash
git clone [https://github.com/ello-anish/Uber-Clone.git](https://github.com/ello-anish/Uber-Clone.git)
cd Uber-Clone
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the root of the project and add your API keys and database URL. Replace the placeholder values with your actual Clerk, Stripe, NeonDB, Google Maps, andgeoapify credentials. You can obtain these credentials by signing up on the Clerk, Stripe, NeonDB, Google Maps and geoapify websites respectively.

```env
# Clerk
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=

# Google Maps
EXPO_PUBLIC_PLACES_API_KEY=
EXPO_PUBLIC_DIRECTIONS_API_KEY=

# NeonDB
DATABASE_URL=

# Geoapify
EXPO_PUBLIC_GEOAPIFY_API_KEY=

# Stripe
EXPO_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
```

### 4. Run the Application

Start the development server using Expo.

```bash
npx expo start
```

Scan the QR code with the Expo Go app on your iOS or Android device to see the application in action.
