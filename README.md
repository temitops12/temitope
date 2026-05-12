# temitope — React Native Calculator

A simple but well-structured calculator application developed with Expo as part of my Git coursework submission.

## Getting Started

Clone this repo and run the following in the project directory:

```bash
npm install
npm start
```

If you're on Android: press `a`. For web: press `w`.

## Implementation Notes

The calculator component lives in `components/calculator.tsx`. It manages two pieces of state — the current display value and the running equation — and handles operators, decimals, backspace (C), and full reset (AC).

Floating-point rounding is handled by multiplying the result by 1e8, rounding, then dividing back. This prevents issues like `0.1 + 0.2 = 0.30000000000000004`.

## Theme

Cyan accent colour applied throughout, with appropriate contrast adjustments for dark mode.
