# create-notelink

CLI tool to quickly scaffold a new NoteLink API project.

## Usage

### Using bunx (recommended)

```bash
bunx create-notelink my-app
```

### Using bun create

```bash
bun create notelink my-app
```

### After installation

```bash
bun create notelink my-app
cd my-app
bun install
bun dev
```

Your API documentation will be available at http://localhost:8080/swagger

## What's Included

The generated project includes:

- ✅ Pre-configured NoteLink API setup
- ✅ Example authentication routes with JWT
- ✅ User management endpoints
- ✅ Health check endpoints
- ✅ CORS, rate limiting, and logging middleware
- ✅ TypeScript configuration
- ✅ OpenAPI/Swagger documentation
- ✅ Environment configuration

## Requirements

- Bun >= 1.0.0

## License

MIT
