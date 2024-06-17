**🚀 IMAGINAI**
We are thrilled to introduce our comprehensive guide on building a **state-of-the-art IMAGINAI** Platform with five AI tools: **Chatbot**, **Image Generation**, **Music Generation**, **Video Generation**, and **Code Generation**. 

**🔧 Next.js 14 App Router: A Game-Changer**
Built using Next.js 14, it integrates Stripe for seamless billing, leverages OpenAI and ReplicateAI for AI functionalities, and uses Crisp for customer engagement, Aiven for data infrastructure, and Prisma for database management. 

**🛠️ Building with Advanced Technologies**
Beyond the core functionalities, we’ll embark on an instructive journey of building our SaaS application using a rich palette of web development technologies:

**React**
**Tailwind**
**Prisma**
**MySQL**
**Clerk**

# Features

- **Tailwind Design**: Sleek, modern design using Tailwind CSS
- **Tailwind Animations and Effects**: Smooth animations and effects with Tailwind CSS
- **Full Responsiveness**: Optimized for all devices
- **Clerk Authentication**: Supports email, Google, and 9+ social logins
- **Client-Side Form Validation and Handling**: Implemented with react-hook-form
- **Server-Side Error Handling**: Managed with react-toast
- **Image Generation Tool**: Powered by OpenAI
- **Video Generation Tool**: Powered by Replicate AI
- **Conversation Generation Tool**: Powered by OpenAI
- **Music Generation Tool**: Powered by Replicate AI
- **Page Loading State**: Visual indicators for page loading
- **Stripe Monthly Subscription**: Integrated for seamless payments
- **Free Tier with API Limiting**: Limited access for free users
- **Route Handlers for API Requests**: Writing POST, DELETE, and GET routes in app/api
- **Direct Database Access in Server Components**: Fetch data without using APIs
- **Handling Parent-Child Component Relations**: Efficiently manage component relationships
- **Next.js 13 App Router Structure**: Organized folder structure
- **Reusable Layouts**: Consistent, reusable layouts across the application

# Getting Started

1. **Ensure Requirements**: Verify that Git and NodeJS (18.x.x) are installed on your system.
2. **Clone the Repository**: Clone this repository to your local machine.
   ```sh
   git clone https://github.com/aftabrehan/jarvis-ai.git
   ```
3. **Set Up Environment Variables**: Create a `.env` file in the root directory and add the following contents:

   ```env
   # Disable Next.js telemetry
   NEXT_TELEMETRY_DISABLED=1

   # Clerk API keys
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
   CLERK_SECRET_KEY=sk_test_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

   # Clerk redirect URIs
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/dashboard
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/dashboard

   # OpenAI API key
   OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

   # Replicate API token
   REPLICATE_API_TOKEN=r8_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

   # Database URL (PlanetScale/Aiven)
   DATABASE_URL="mysql://<username>:<password>@<host>:<port>/<database_name>?ssl-mode=REQUIRED"

   # Stripe API and webhook secret keys
   STRIPE_API_SECRET_KEY=sk_test_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
   STRIPE_WEBHOOK_SECRET=whsec_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

   # App base URL
   NEXT_PUBLIC_APP_URL=http://localhost:3000

   # Crisp website ID
   NEXT_PUBLIC_CRISP_WEBSITE_ID=xxxxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxx
   ```
   Open terminal in root directory. Run npm install --legacy-peer-deps or yarn install --legacy-peer-deps.
Setup Prisma by adding MySQL Database (PlanetScale/Aiven). Run npx prisma db push or yarn prisma db push to push the queries in the database.
Now, the app is fully configured 👍, and you can start using this app with either npm run dev or yarn dev.

