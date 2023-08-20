[![Automated E2E Testing](https://github.com/ErlendE96/social-media-client/actions/workflows/e2e-test.yml/badge.svg)](https://github.com/ErlendE96/social-media-client/actions/workflows/e2e-test.yml)
[![Automated Unit Testing](https://github.com/ErlendE96/social-media-client/actions/workflows/unit-test.yml/badge.svg)](https://github.com/ErlendE96/social-media-client/actions/workflows/unit-test.yml)

# social-media-client-testing

Before starting the project, make sure you have Node.js and npm installed on your computer.

Install the Dependencies:

npm i

## Configuration

- SASS/CSS for styling.
- live-server used for live viewing of the website.
- ESLint for linting JavaScript files.
- Prettier for code formatting.
- Husky and lint-staged for ensuring code quality through pre-commit hooks.
- Unit testing with Jest.
- End-to-end testing with Cypress.

## Dependencies

- Styling: sass & bootstrap
- Development: live-server
- Testing: jest & cypress
- Linting & Formatting: eslint, prettier
- Others: husky, lint-staged

## Testing

Run both tests, jest and cypress:
- npm run test
  
run cypress in terminal:
- npm run test-e2e-cli
  
run cypress GUI:
- npm run test-e2e

run jest:
- npm run test-unit

## run lint:

npm run lint

## To format code:

npm run format
