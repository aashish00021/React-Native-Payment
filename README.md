# React Native Stripe Subscription App

A modern React Native application demonstrating Stripe payment integration with a subscription-based model. 
The app features a beautiful UI with subscription plans, payment processing using Stripe's Payment Sheet, and a Node.js backend.

## Prerequisites

- Node.js >= 18
- React Native development environment set up
- Stripe account with API keys
- Android Studio (for Android development)
- Xcode (for iOS development)

## Project Structure

```
React-Native-Stripe/
├── Backend/                 # Express server
│   ├── index.js            # Server entry point
│   └── package.json        # Backend dependencies
│
└── subscriptionModel/      # React Native app
    ├── components/         # React components
    │   └── Home.tsx       # Main subscription page
    ├── App.tsx            # Root component
    └── package.json       # Frontend dependencies
```

## Installation

1. Clone the repository:
\`\`\`bash
git clone [repository-url]
\`\`\`

2. Install backend dependencies:
\`\`\`bash
cd Backend
npm install
\`\`\`

3. Install frontend dependencies:
\`\`\`bash
cd subscriptionModel
npm install
\`\`\`
## Running the Application

1. Start the backend server:
\`\`\`bash
cd Backend
npm start
\`\`\`

2. Start the React Native app:

For Android:
\`\`\`bash
cd subscriptionModel
npm run android
\`\`\`

For iOS:
\`\`\`bash
cd subscriptionModel
npm run ios
\`\`\`

## Testing Payments

Use Stripe's test card numbers for testing:
- Card number: 4242 4242 4242 4242
- Expiry: Any future date
- CVC: Any 3 digits
- ZIP: Any 5 digits

## Important Notes

- When testing on Android emulator, the backend URL uses `10.0.2.2` instead of `localhost`
- For physical devices, update the API_URL in `Home.tsx` to your local IP address
- Make sure your Stripe API keys are properly configured in both frontend and backend

## References

- [Stripe](https://stripe.com)

## Demo Video


https://github.com/user-attachments/assets/33058aea-32d8-4a36-8997-70872a92689f


