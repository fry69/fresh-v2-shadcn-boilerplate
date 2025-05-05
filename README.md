[fresh repository](https://github.com/denoland/fresh)

# fresh v2 shadcn boilerplate

A simple boilerplate for Fresh v2 that ships with an aliased, up-to-date version of [shadcn](https://github.com/shadcn-ui/ui).

We take advantage of [esm.sh](https://esm.sh/) to alias React dependencies to [preact/compat](https://www.npmjs.com/package/@preact/compat), and mark `preact` as an external dependency to ensure the best compatibility with current `preact` version Fresh is using.

## Documentation

Please refer to the proper documentation for each dependency this project uses:
- [Fresh](https://fresh.deno.dev/docs/introduction)
- [shadcn](https://ui.shadcn.com/docs)
- [lucide-preact](https://lucide.dev/)

## Getting started

The scaffolding process to create a Fresh project has already been performed. You can use the normal commands to run Fresh:

```
deno task start
```

## Contributing

Please feel free to create pull requests and open issues for any problems you run into!