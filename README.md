# ntbk

A self-hosted note-taking platform for developers.

> Markdown-native editing | Fast search | Full data ownership | AI-powered features

## Structure

- `ntbk-api/` - Ruby on Rails API backend
- `ntbk-client/` - React/Vite/TypeScript frontend client

## Features

- **Authentication**: Email/password and Google OAuth login
- **Workspaces**: Create and manage multiple workspaces
- **Documents**: Create, edit, upload files (PDF, DOCX, MD, etc.)
- **Tags**: Organize and filter documents by tags
- **Search**: Full-text search across all documents
- **AI Chat**: RAG-powered chat with semantic search
- **AI Summaries**: Generate document summaries
- **User Settings**: Profile management, password change, theme selector

## Development

### ntbk-api

```bash
cd ntbk-api
bundle install
rails db:setup
rails server
```

### ntbk-client

```bash
cd ntbk-client
npm install
npm run dev
```

## Git Submodules

This repo uses git submodules. To clone with submodules:

```bash
git clone --recurse-submodules git@github.com:rkbart/ntbk.git
```

Or after cloning:

```bash
git submodule init
git submodule update
```

## Documentation

- **Frontend Wiki**: `/home/rkbart/Documents/Obsidian Vault/NTBK/frontend/`
- **Backend Wiki**: `/home/rkbart/Documents/Obsidian Vault/NTBK/backend/`
- **Frontend Development Guide**: `ntbk-client/DEVELOPMENT.md`
- **Backend Development Guide**: `ntbk-api/DEVELOPMENT.md`
