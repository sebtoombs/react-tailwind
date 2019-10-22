# React - Tailwindcss

An example app showcasing how to use React with Styled Components & Tailwindcss

## Things To Note

- When installing tailwind.macro, currently need to run `yarn add tailwind.macro@next` to get the version compatible with tailwind@1
- To generate tailwind config (not required), run `npx tailwind init`
- Postcss & associated config is only required if you want to use @import "tailwind/..." (for global reset etc)

## Limitiations

The following limitations of the tailwind.macro@alpha have been discovered;

- The macro plugin will complain about this error: `"There was an error trying to load the config "tailwind" for the macro imported from "tailwind.macro. Please see the error thrown for more information."`. It doesn't appear to mean anything.
- flex-grow doesn't seem to work
