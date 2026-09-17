# 01-ts-basics

GoIT TypeScript homework. The project covers TypeScript basics: primitive types, interfaces, typed arrays, function typing, union types, generics, `Promise` typing, and a typed HTTP request with Axios.

The tasks run in the browser and print their results to the developer console.

## Live demo

[https://groteskzp.github.io/01-ts-basics/](https://groteskzp.github.io/01-ts-basics/)

Open the page and check the browser console to see the task output.

## Features

- Explicit types for primitive values: `string`, `number`, and `boolean`
- `Product` interface with a readonly `id` and an optional `description`
- Typed arrays: `string[]`, `number[]`, and `Product[]`
- Typed `printUserInfo` function with an optional `email` parameter and a `void` return type
- Union type that allows only `"loading"`, `"success"`, or `"error"`
- Generic `getFirstElement<T>` helper that returns the first item of an array
- Typed `Promise<string>` that resolves with a delayed message
- Typed Axios `GET` request to [JSONPlaceholder](https://jsonplaceholder.typicode.com/posts) that returns a list of posts

## Tech stack

- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vite.dev/)
- [Axios](https://axios-http.com/)

## Getting started

1. Clone the repository:

   ```bash
   git clone https://github.com/groteskzp/01-ts-basics.git
   cd 01-ts-basics
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open the local URL shown in the terminal and inspect the browser console.

## Scripts

| Script | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Type-check with `tsc` and build the production bundle |
| `npm run preview` | Preview the production build locally |
