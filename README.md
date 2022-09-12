# sveltekit-6440

Reproduction of https://github.com/sveltejs/kit/issues/6440

### Reproduce error

1. `npm i`
2. `npm run build`
3. `node build`

Error: `Error: Dynamic require of "stream" is not supported`

**Note**: There is a [manual workaround](https://github.com/sveltejs/kit/issues/6440#issuecomment-1236823838), but it is not feasible to use in an automated way.