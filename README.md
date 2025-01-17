Cribl Cloud Diag Upload Service
---

## To Start
- Clone this repo
- With globally installed `npm` or accessed via `npx`
    + From the root of your cloned repo,
        - `cd` into `packages/diag-upload-api`
        - Do `npm install` to install the dependencies
        - Then `npm start` to start the api.
    + From the root of your cloned repo,
        - `cd` into `packages/diag-upload-ui`
        - Do `npm install` to install the dependencies
        - Then `npm start` to start the react app.

## API
Create a RESTful API to:
- [ ] Upload a file
- [ ] Get all files
- [ ] Download a file
- [ ] Delete a file
- [ ] Update a file

## UI
- [ ] Hook up your API to the provided UI under `/packages/diag-upload-ui`. Expectation here is that you only need to change minimal UI code to connect your developed api. You should mostly be working in the `/src/utils.ts` file.