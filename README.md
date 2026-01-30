# ai-regex

[![npm version](https://img.shields.io/npm/v/ai-regex.svg)](https://www.npmjs.com/package/ai-regex)
[![npm downloads](https://img.shields.io/npm/dm/ai-regex.svg)](https://www.npmjs.com/package/ai-regex)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-regex)](https://github.com/lxgic-studios/ai-regex/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate regex patterns from plain English. No more regex pain.

## Install

```bash
npm install -g ai-regex
```

## Usage

```bash
npx ai-regex "email addresses"
# → /[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}/g

npx ai-regex "US phone numbers" --json
# → Full JSON with pattern, flags, explanation, examples
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT
