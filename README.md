<div align="center">
  <br />
    <a href="https://github.com/FernandoPiDi" target="_blank">
      <img src="https://i.ibb.co/Bf04Hpd/Readme-thumbnail-from-JS-Mastery.png" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="reactnative" />
    <img src="https://img.shields.io/badge/-Expo-black?style=for-the-badge&logoColor=white&logo=expo&color=000020" alt="expo" />
    <img src="https://img.shields.io/badge/-PostgreSQL-black?style=for-the-badge&logoColor=white&logo=postgresql&color=4169E1" alt="postgresql" />
    <img src="https://img.shields.io/badge/-Stripe-black?style=for-the-badge&logoColor=white&logo=stripe&color=008CDD" alt="stripe" />
  </div>


<h3 align="center">Full Stack Uber Clone</h3>

</div>

## <a name="introduction">🤖 Introduction</a>

This project is a full-stack mobile application that combines various technologies to deliver a functional and appealing solution that leaves a lasting impression. It uses React Native to handle the user interface, Google Maps to render maps and provide directions, Stripe to securely manage payments, and serverless Postgres as the database. Additionally, its design is styled with TailwindCSS, achieving a modern and professional look.

## <a name="tech-stack">⚙️ Tech Stack</a>

- React Native
- Expo
- Stripe
- PostgreSQL
- Google Maps
- zustand
- Clerk
- Tailwind CSS

## <a name="features">🔋 Features</a>

:white_check_mark: Onboarding Flow: Smooth user registration and setup experience.

:white_check_mark: Email and Password Authentication with Verification: Secure login system with email confirmation.

:white_check_mark: Google oAuth Integration: Quick and easy login using Google credentials.

:white_check_mark: Authorization: Robust access control for different user roles.

:white_check_mark: Home Screen with Live Location and Google Maps: Real-time location tracking displayed on an interactive map with markers.

:white_check_mark: Recent Rides: Easily view a summary of your recent trips.

:white_check_mark: Google Places Autocomplete: Effortlessly search for locations worldwide with autocomplete suggestions.

:white_check_mark: Find Rides: Locate rides by specifying departure and destination points.

:white_check_mark: Select Rides from Map: Pick nearby available vehicles directly from the map interface.

:white_check_mark: Confirm Ride with Complete Details: Access full ride information, including estimated time and fare.

:white_check_mark: Stripe Payment Integration: Make payments securely using multiple methods, including credit/debit cards.

:white_check_mark: Create Rides After Payment: Book a ride seamlessly after successful payment confirmation.

:white_check_mark: Profile Management: Update and manage your account details from the profile screen.

:white_check_mark: Ride History: Keep track of all previously booked rides.

:white_check_mark: Optimized for Android and iOS: Fully responsive design for a smooth experience on both platforms.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/FernandoPiDi/uber-clone.git
cd uber-clone
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=

EXPO_PUBLIC_PLACES_API_KEY=
EXPO_PUBLIC_DIRECTIONS_API_KEY=

DATABASE_URL=

EXPO_PUBLIC_SERVER_URL=https://uber.dev/

EXPO_PUBLIC_GEOAPIFY_API_KEY=

EXPO_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
```

Replace the placeholder values with your actual Clerk, Stripe, NeonDB, Google Maps, andgeoapify credentials. You can
obtain these credentials by signing up on
the [Clerk](https://clerk.com/), [Stripe](https://stripe.com/in), [NeonDB](https://neon.tech/), [Google Maps](https://console.cloud.google.com/)
and [geoapify](https://www.geoapify.com/) websites respectively.

**Running the Project**

```bash
npx expo start
```

Download the [Expo Go](https://expo.dev/go) app and Scan the QR code on your respective device to view the project.

## Contact

You can find me on:

- LinkedIn: [Luis Duvan Fernando Pinto Diaz](https://www.linkedin.com/in/duvanfernandopintodiaz/)
- Email: duvanpidi@hotmail.com
