# Workflow

## 1. Setup

- Install `pnpm` v10
- Setup Turborepo
  - [Use shadcn/ui template](https://ui.shadcn.com/docs/monorepo)
- [Learn to use monorepo](https://turborepo.com/docs/crafting-your-repository/creating-an-internal-package)
- Create 2nd(widget) app
- Create `math` shared package
- [Add new shadcn component](https://ui.shadcn.com/docs/monorepo#add-components-to-your-project)

### 1.1 Misc

- Fix ESLint package error

  - Use pnpm filter option to install package only
    on specific package.

    ```
    pnpm -F eslint-config add --save-dev @eslint/js
    ```
