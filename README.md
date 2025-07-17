

##  <a name="table">Table of Contents</a>

1.  [Introduction](#introduction)
2.  [Tech Stack](#tech-stack)
3.  [Features](#features)




## <a name="introduction">🤖 Introduction</a>

Create an  app from scratch featuring user authentication, subscriptions, and payments using Next.js, Supabase, and Stripe! a real-time teaching platform with Vapi, integrate an AI vocal agent, and deliver seamless, interactive learning sessions.




## <a name="tech-stack">⚙️ Tech Stack</a>

- **[Clerk]** 

* **[Next.js]**

* **[Sentry]** is an error tracking and performance monitoring tool 

* **[shadcn/ui]**

- **[Supabase]** 
* **[Tailwind CSS]**
* **[TypeScript])** 

- **[Vapi]** is a developer-centric voice AI platform that enables the creation of conversational voice agents.



## <a name="features">🔋 Features</a>

 **AI Voice Agents**: Take tutoring sessions with voiced AIs specializing in the topics you want to get better at.

 **Authentication**: Secure user sign-up and sign-in with Clerk; Google authentication and many more.

 **Billing & Subscriptions**: Easily manage plans, upgrades, and payment details.

 **Bookmarks and Session History**: Let users organise their learning by bookmarking tutors and accessing previous sessions.

 **Code Reusability**: Leverage reusable components and a modular codebase for efficient development.

 **Create a Tutor**: Create your own AI tutors, choosing a subject, topic, and style of conversation.

 **Cross-Device Compatibility**: Fully responsive design that works seamlessly across all devices.

**Database Integration**: Uses Supabase for real-time data handling and storage needs.

 **Modern UI/UX**: Clean, responsive design built with Tailwind CSS and shadcn/ui for a sleek user experience.

 **Scalable Tech Stack**: Built with Next.js for a fast, production-ready web application that scales seamlessly.

 **Search Functionality**: Find tutors quickly with robust filters and search bar.



## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/adrianhajdin/saas-app.git
cd saas-app
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
# Sentry
SENTRY_AUTH_TOKEN=

# Vapi
NEXT_PUBLIC_VAPI_WEB_TOKEN=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```

Replace the placeholder values with your actual ImageKit, NeonDB, Upstash, and Resend credentials. You can obtain these credentials by signing up on: [Supabase](https://supabase.com/dashboard), [Clerk](https://jsm.dev/converso-clerk), [Sentry](https://jsm.dev/converso-sentry), [Vapi](https://jsm.dev/converso-vapi).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.



