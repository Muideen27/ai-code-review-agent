# AI Code Review Agent

An intelligent code review agent powered by Google's Gemini 2.5 Flash model that provides automated code review feedback using AI.

## Features

- 🤖 **AI-Powered Reviews**: Uses Google's Gemini 2.5 Flash for intelligent code analysis
- 📁 **Git Integration**: Automatically detects file changes using simple-git
- 🔍 **Comprehensive Analysis**: Reviews code for correctness, clarity, maintainability, performance, and security
- ⚡ **Fast Runtime**: Built with Bun for optimal performance
- 🛠️ **TypeScript Support**: Fully typed with modern TypeScript configuration

## Installation

```bash
bun install
```

## Usage

```bash
bun run index.ts
```

## Project Structure

- `index.ts` - Main entry point with AI agent setup
- `prompts.ts` - System prompt for code review behavior
- `tools.ts` - Git integration tool for file change detection
- `package.json` - Dependencies and project configuration
- `tsconfig.json` - TypeScript configuration

## Dependencies

- `@ai-sdk/google` - Google AI SDK integration
- `ai` - Vercel AI SDK for streaming
- `simple-git` - Git operations
- `zod` - Schema validation

## Requirements

- Bun runtime
- TypeScript 5+
- Git repository with changes to review

This project was created using `bun init` in bun v1.2.22. [Bun](https://bun.com) is a fast all-in-one JavaScript runtime.
