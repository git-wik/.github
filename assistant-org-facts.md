`dist/` is the build output (tsup) and is committed; a change there without a matching change in `src/` is a stale build.
The MCP tools under `src/mcp/tools/` are the public surface that Claude Code sees, so changing one changes the product.
There is no merge gate and no generated code beyond `dist/` and the lockfile.
