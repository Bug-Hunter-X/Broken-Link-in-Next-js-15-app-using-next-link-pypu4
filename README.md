# Broken Link in Next.js 15 app using next/link

This repository demonstrates a common issue encountered in Next.js 15 applications involving broken links when using the `next/link` component. The `/about` page link in the example app does not navigate correctly.  The solution shows how to fix it.

## Steps to Reproduce

1. Clone the repository.
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Observe that clicking the link does not navigate to the '/about' page.

## Solution

The solution involves ensuring the proper structure and configuration of your Next.js application, as demonstrated in the `brokenLinkSolution.js` file.  This includes verifying the file exists and the correct path to the page.