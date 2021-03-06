# @yanc/cra-template-typescript

## Usage

- `<template-name>`
  - latest version: `@yanc/cra-template-typescript@github:aistyler/yanc-react-templates#workspace=@yanc/cra-template-typescript`
  - specific version: `@yanc/cra-template-typescript@github:aistyler/yanc-react-templates#workspace=@yanc/cra-template-typescript&tag=@yanc/cra-template-typescript/1.0.0`

```sh
# e.g. using @yanc/react-scripts
npx create-react-app app --scripts-version "@yanc/react-scripts@github:aistyler/yanc-react-scripts#semver:~4.0.0" --template `<template-name>`

# e.g. using default react-scripts
npx create-react-app app --template `<template-name>`
```

## Testing a template on local

```npx create-react-app {app-name} --template @yanc/cra-template-typescript@file:{absolute_path_to_template}```

```sh
# e.g.
npx create-react-app app --template @yanc/cra-template-typescript@file:$PWD/../packages/cra-template-typescript
```
