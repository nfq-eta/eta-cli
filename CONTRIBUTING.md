# nfq-cli contributing guide

## Issue Reporting Guidelines

- First identify where error is coming from. If it's occuring while running `nfq` command then issue is indeed on
`nfq-cli` so please report it here. If error appears when you run one of `npm run` scripts, problem originates
from a template you're using, [maybe one of the offical ones](https://github.com/nfq-cli). If so, please
open an issue on a template repository.

- Try to search for your issue, it may have already been answered or even fixed in the development branch.

## Development Setup

``` bash
yarn
npm run lint
```

## Releasing new version
1. Check for js errors `npm run lint`
1. Commit all changes
1. Tag new version `yarn version`
1. Push git changes to master branch
1. Wait for travis to publish
