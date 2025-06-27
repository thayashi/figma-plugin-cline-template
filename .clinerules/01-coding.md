## 01-coding.md (Coding Standards)

### Use Create Figma Plugin
Use Create Figma Plugin fundatinal laibrary.
This repository is set up with the create-figma-plugin Node modules already. You don't need to set them up.
@create-figma-plugin/ui
@create-figma-plugin/utilities
create-figma-plugin has a lot of utility functions and UI components already.
- [Utilities — Create Figma Plugin](https://yuanqing.github.io/create-figma-plugin/utilities/)
- [@storybook/core - Storybook](https://yuanqing.github.io/create-figma-plugin/storybook/?path=/story/index--index)

Please utilize them as much as possible.

Refer tihs code. There are many good references how to use Create Figma Plugin Framework.
https://github.com/yuanqing/figma-plugins/tree/main/packages

### TypeScript/JavaScript Standards
- **TypeScript First**: Write all files in TypeScript when possible
- **Strict Type Definitions**: Enable `strict: true`, avoid `any` type usage
- **Naming Conventions**:
  - File names: kebab-case (`color-inspector.ts`)
  - Variables/Functions: camelCase (`getRgbColors`)
  - Constants: UPPER_SNAKE_CASE (`RGB_COLOR_REGEX`)
  - Interfaces: PascalCase (`ColorData`)

### Code Quality
- **ESLint + Prettier**: Code formatting and quality checks
- **Single Responsibility**: Each function should have one responsibility
- **Pure Functions Preferred**: Minimize side effects
- **Error Handling**: Proper exception handling with try-catch blocks

