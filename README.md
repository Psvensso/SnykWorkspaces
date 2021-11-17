# SnykWorkspaces
This project shows how to run Snyk on a very basic 'hello world' [yark workspaces](https://classic.yarnpkg.com/en/docs/workspaces) project

- Authenticate with snyk `snyk auth`
- Install with yarn `yarn install`, the post install script will run the snyk test after installation is complete

Alternatively run the snyk test again with `snyk test --yarn-workspaces -d`


## Other repo's with Workspace setup
- https://github.com/facebook/react
- https://github.com/vercel/next.js (with lerna support on top)
- https://github.com/storybookjs/storybook (with lerna support on top)
- https://github.com/alibaba/ice (with lerna support on top)
- https://github.com/mobxjs/mobx (with lerna support on top)
- https://github.com/mui-org/material-ui (with lerna support on top)
- https://github.com/chakra-ui/chakra-ui
