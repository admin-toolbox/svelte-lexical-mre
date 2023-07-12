# Bug / Issue reproduction

```
pnpm create svelte@latest

pnpm i svelte-lexical

```

From the official repo, copy the `static` and `src` directories into the project.

```
pnpm run dev
```

Visit localhost:5173. The page will load, but the console will show the following error:

```

`Yjs was already imported. This breaks constructor checks and will lead to issues! - https://github.com/yjs/yjs/issues/438`

