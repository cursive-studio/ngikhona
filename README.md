# Ngikhona

Website for Ngikhona, a psychotherapy practice based in Camberwell, South London.

Ngikhona provides psychotherapy services for the local community and offers calm, confidential rooms available to rent by qualified clinicians.

## Website Overview

The site currently includes:

- A homepage introducing Ngikhona and its work in South London
- Service sections for 1:1 therapy, group therapy, child psychotherapy, and body work
- A team section for practitioner profiles
- A contact section for enquiries
- A dedicated spaces page for therapy rooms available to rent

## Tech Stack

- [Astro](https://astro.build/)
- Tailwind CSS
- Variable fonts via `@fontsource-variable`

## Project Structure

```text
/
├── public/
│   └── images/
├── src/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   └── styles/
├── astro.config.mjs
└── package.json
```

Astro pages live in `src/pages/`. Shared sections and UI elements live in `src/components/`, with global styles in `src/styles/global.css`.

## Development

Install dependencies:

```sh
npm install
```

Start the local development server:

```sh
npm run dev
```

Build for production:

```sh
npm run build
```

Preview the production build locally:

```sh
npm run preview
```

## Content Notes

Some content is still placeholder copy, especially practitioner biographies, room rental details, professional registration information, and footer/legal links. These should be replaced with confirmed practice information before launch.
