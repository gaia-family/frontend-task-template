# Gaia Frontend Task

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## The Task

> First ensure that you can get the project running. You should see a simple page that says "Your code here" in your browser

At Gaia we can offer our members a loan to help pay for their treatment. We would like you to create a simple loan application flow with the following requirements:

### Requirements

1. Create a form page that collects the following information from the member:
   - Monthly income (number)
   - Housing status (dropdown: "Renting" or "Owner")
   - Monthly expenses (number)
   - Outstanding loans (dynamic array of amounts)
     - Allow users to add/remove multiple outstanding loan amounts
   - First name (text)
   - Last name (text)
   - Email (text)

2. The form should include basic validation:
   - All fields are required
   - Income and expenses must be positive numbers
   - Email must be in a valid format

3. When the form is submitted:
   - Send a POST request to `/api/loan-application`
    * You do not need to implement a loan application calculation, you can mock the endpoint
   - Redirect to a confirmation page

4. Create a confirmation page that:
   - Thanks the user for their application
   - Displays a friendly message that we'll be in touch shortly
   - Shows a reference number (can be randomly generated)

### Technical Requirements

- Use TypeScript
- Implement form validation (you can use any form library of your choice)
- Add basic styling (you can use any CSS solution)
- Implement proper error handling
- Add loading states during form submission
- Add error handling

### Bonus Points

- Responsive design
- Meaningful tests
- Accessibility considerations
- Clean, well-documented code
- Elegant UI/UX touches

### What We're Looking For

- Clean, maintainable code
- Proper TypeScript usage
- Good component structure
- Error handling
- User experience considerations
- Form validation implementation

### Time Expectation

This task should take approximately 2-3 hours to complete. Focus on implementing the core requirements first before adding any extra features.
