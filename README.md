# Astro Component Template 🧑‍🚀

This is [an unofficial template](#how-is-this-different-from-the-official-component-template) meant to ease the development of components for [Astro](https://astro.build/) that are intended for distribution. It does so by providing you with:

## Folder Structure

```plaintext
├── .vscode/                    # VS Code settings folder
│   ├── settings.json           # Workspace settings
│   └── extensions.json         # Recommended extensions to install
├── src/                        # Your component source code
│   ├── Component.astro         # Example component file
│   └── main.ts                 # Example source code file
├── test/                       # Your component tests
│   └── example.test.js         # Example tests
└── index.ts                    # Should contain all the exports your component provide to users
```


## Theme Goals

two themes, one minimilaist and clean, the other more colourful and playful

Goals:

-   not to have an extensive design system
-   have a design system with "essential" bare minimum (plus a couple of nice to have) components for a developer to setup an astro ecommerce site with snipcart
-   some light weight interactivty where time allows

Requirements:

-   a single homepage/product store page layout per theme
    -   need a typography component
        -   need a title component
        -   need a paragraph component
    -   need a description component
-   a single product page layout
-   a button component per theme that can be used for anything, but primarly to add the wrapping product with
-   a "variant" component to allow a user to pick a variant (may just constrain this to colour for mvp) and the add button will do the correct thing
-   a component to render a table of snipcart custom fields or maybe with dd/dt/dl
-   a product card per theme
-   a product grid to abstract grids for developers
-   a flex box component to abstract flex for developers
-   a component to display product features
-   a product price component

Nice to have:

-   slot inside Snipcart setup component to allow some proof of concept customisation of snipcart checkout
-   some hero/feather icons?
-   subscriptions