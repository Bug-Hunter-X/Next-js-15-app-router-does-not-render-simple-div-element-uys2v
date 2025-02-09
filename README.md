# Next.js 15 app router rendering issue

This repository demonstrates a bug in Next.js 15's app router where a simple `div` element fails to render correctly. This issue did not exist in Next.js 13. 

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe that the page does not render the `div` element containing the text "Hello, world!".

## Expected Behavior

The page should render a `div` element containing the text "Hello, world!".

## Actual Behavior

The page renders nothing.