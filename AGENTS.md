> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

{/* Add product-specific terms and preferred usage */}
{/* Example: Use "workspace" not "project", "member" not "user" */}

## Localization

- The site is published in the same four languages as the app: Simplified Chinese (default, root directory, `zh-Hans`), Traditional Chinese (`zh-Hant/`), English (`en/`) and Korean (`ko/`).
- Every page exists in all four languages at the same relative path. When you add, change or remove a page, update all four versions and the matching `navigation.languages` entry in `docs.json`.
- Internal links in a translated page must keep its language prefix, for example `/en/features/analysis`.
- UI labels must match the app's own translations in `app/i18n/messages.ts` of [japanese-analyzer](https://github.com/cokice/japanese-analyzer). Use Taiwan terminology for `zh-Hant`.

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
