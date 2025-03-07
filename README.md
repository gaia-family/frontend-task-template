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

At Gaia we offer our prospects payment plans to help pay for their treatment. We would like you to create a simple application for a prospect to apply for our payment plans. Consider [this Figma](https://www.figma.com/design/ocQBX5nkoP32ErHSYBoFCN/Frontent-Engineer-Interview-Task?node-id=0-42&t=y1jSwhDWWQhUhc5l-1) as the requirement.

### Requirements

1. Create a sign up page with a form that collects the following information from the prospect:
   - Full name (text)
   - Phone number (text)
   - Email (text)
   - Date of birth (date)
   - Which treatment are you considering? (choice)
   - When are you planning to start your treatment? (date)

2. The form should include basic validation:
   - All fields are required
   - Email and phone number must be in a valid format. Assume US phone number.

3. When the form is submitted:
   - Send a POST request to `/api/ivf-sign-up`
    * You do not need to implement any calculation, you can mock the endpoint
   - Redirect to the pricing page

4. Create the Pricing Page that:
   - Thanks shows a success message to the user and proposes a Gaia plan and the next steps as indicated in the Figma design
   - The numerical values (like $ price per month from) can be randomly generated

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

- Adherence to the design in the Figma file
- Clean, maintainable code
- Proper TypeScript usage
- Good component structure
- Error handling
- User experience considerations
- Form validation implementation

### Time Expectation

This task should take approximately 2-3 hours to complete. Focus on implementing the core requirements first before adding any extra features.
