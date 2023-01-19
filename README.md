# Storybook + Nx + MDX issue

`yarn` to install deps

## Reproduce issue

```
nx storybook ui
```

to see the failure.

## Works on pure CRA+Storybook setups

Go to `pure-cra` and run `yarn storybook` to see that it works.

```
cd pure-cra
yarn storybook
```

`pure-cra` was generated with `npx create-react-app pure-cra --template typescript` and then I ran `npx sb init` to install Storybook.
