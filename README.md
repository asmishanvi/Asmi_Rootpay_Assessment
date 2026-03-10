# RootPay Assessment - Multi-Step Onboarding Flow

A pixel-accurate implementation of the RootPay multi-step onboarding flow built with React and TypeScript.

## Live Demo

https://rootpay-assessment.netlify.app/

## GitHub Repo

<ADD_GITHUB_REPO_URL>

## Local Setup (VS Code)

1. Open the folder: `/Users/asmishanvi/Downloads/Asmi_Rootpay_Assignment`
2. Open a VS Code terminal in that folder.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the dev server:
   ```bash
   npm run dev
   ```
5. Open the URL shown in the terminal (usually `http://localhost:5173`).

## Architecture & Decisions

- React + TypeScript with Vite for fast builds and typed components.
- Component-driven UI: reusable atoms (Button, Input, OTP, Dropdown, Radio card) composed in the Onboarding screen.
- State and validation handled at the screen level per step to keep flow logic centralized and predictable.
- LESS with design tokens for consistent spacing, typography, and colors; BEM-style class naming.
- React Router used for onboarding and success/dashboard routes.

## Enhancements

- Full interaction states (hover, focus, active, loading, disabled).
- OTP auto-focus and numeric-only input handling.
- Country code dropdown with click-outside close.
- Success modal with account summary.
- Subtle transitions for step and button feedback.
