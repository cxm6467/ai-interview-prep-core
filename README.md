# Minimal TypeScript package template

### A minimal TypeScript package template.

## Installation

```bash
npm install ai-interview-prep-core
```

## Usage

```typescript
import { VERSION } from 'ai-interview-prep-core';

console.log(`Package version: ${VERSION}`);
```

## API

### Constants

#### `VERSION`
- `string` - Current package version

## Development

```bash
# Install dependencies
npm install

# Build the package
npm run build

# Development mode (watch)
npm run dev

# Clean build artifacts
npm run clean
```

### 📦 NPM Package Badge

This template includes an npm version badge. To customize it:

1. **For scoped packages** (`@yourscope/package-name`):
   - Replace `@cxm6467` with your npm scope
   - Replace `ai-interview-prep-core` with your package name
   - Keep `%2F` (URL-encoded `/`) between them

2. **For unscoped packages** (`package-name`):
   - Remove the scope entirely
   - Use just your package name

Example: 
- Current: `@cxm6467%2Fai-interview-prep-core`
- Your scoped: `@myorg%2Fmy-package`
- Your unscoped: `my-awesome-package`

## License

MIT
