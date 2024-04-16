pnpm i
pnpm husky

scripts:
"dev": "vite",
"start": "vite",
"build": "tsc && vite build",
"preview": "vite preview",
"test": "vitest run",
"format": "prettier --write .",
"lint": "eslint .",
"lint:fix": "eslint --fix .",
"type-check": "tsc --noEmit",
"prepare": "husky",
"lint:css": "stylelint '\*_/_.{css,scss,sass}'",
"lint:css:fix": "npm run lint:css -- --fix"
