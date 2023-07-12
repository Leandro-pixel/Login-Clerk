#install nextjs with app-router and typescript
#install @clerk/nextjs

-Tailwind is being use on this code for styles

- create a .env.local file to use your keys from clerk to work:
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=(YOUR_KEY)
CLERK_SECRET_KEY=(YOUR_KEY)
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/