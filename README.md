# Gitlawb Opengateway — Auto Setup

One-click configuration tool for the OpenClaude CLI gateway.

## Usage

### Windows
Double-click `fix-opengateway-auth.exe` or run from terminal:
```
fix-opengateway-auth.exe
```

### macOS
```bash
chmod +x fix-opengateway-auth-macos
./fix-opengateway-auth-macos
```

## What it does
1. Creates a profile with your API key
2. Registers a provider in OpenClaude config
3. Patches the CLI auth header for gateway compatibility

## Requirements
- [OpenClaude](https://www.npmjs.com/package/@gitlawb/openclaude) installed globally