1. Make sure to compile biome via `cargo build --bin biome`
2. Update `.zed/settings.json` and point the binary to the correct folder
3. Restart Zed
4. Open Activity Monitor or Task Manager
5. Filter processes by `biome`
6. Open `src/index.ts`
7. Notice that there are three `biome` processes (lsp-proxy, daemon and scanner)
8. One process keeps groing in memory usage


Probably we should check the logs and see what folders the scanner is scanning.
