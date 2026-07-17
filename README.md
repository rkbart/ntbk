# ntbk

A monorepo containing the ntbk platform.

## Structure

- `ntbk-api/` - Rails API backend
- `ntbk-client/` - Next.js frontend client

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
