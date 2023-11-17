# Soroban RPC API Specification

## JSON-RPC

This is a specification of the API presented by Soroban RPC.

### Building

The specification is split into multiple files to improve readability. The
complete spec can be compiled into a single document as follows.

```bash
npm install
npm run build
# Build successful.
```

This will output the file to `openrpc.json` in this directory. This file will
have all schema `$ref`s resolved.
