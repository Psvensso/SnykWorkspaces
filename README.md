# SnykWorkspaces
This project shows how to run Snyk on a very basic 'hello world' [yark workspaces](https://classic.yarnpkg.com/en/docs/workspaces) project

- Authenticate with snyk `snyk auth`
- Install with yarn `yarn install`, the post install script will run the snyk test after installation is complete

Alternatively run the snyk test again with `snyk test --yarn-workspaces -d`
