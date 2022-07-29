# Design system for the Hive

This repo contains a storybook project for a Design system for [the Hive]().

It consist of purely presentational components, according to the "Atomic Design" methodology.

## Scope

The intention is to keep this project confined to what can be packed away into an isolated component library.

| This project                        | Apps using this project     |
| ----------------------------------- | --------------------------- |
| Atoms, Molecules, Organisms         | Templates & Pages           |
| Export npm package of UI components | Import UI component library |
| Presentational components           | Mocks/API data              |

It should not have to deal with components that make API requests or get data otherwise.

## Milestones

At least for validating the idea of creating and contributing this design system I'll need:

- [ ] Boilerplate w/ Vite and new Storybook project
- [ ] Choose Design Tokens and add stories
- [ ] Add a couple example components (atoms, molecules) with stories
- [ ] Setup addons (test, docs, actions...)
- [ ] Export and ask for feedback

## Particulars

I want to use a headless UI library so I won't have to build everything from scratch.

I'm still not sure how to handle CSS.
