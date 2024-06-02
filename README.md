# EthDapp Starter

A project starter for developing web3 DApps with [React](https://react.dev/), [Wagmi](https://wagmi.sh/) and [Hardhat (Viem)](https://hardhat.org/).

## Running the project

```bash
npm install
```

To install the necessary dependencies.

### React Commands

The following commands are available for the react project.

```bash
npm run react:dev
```

Will start the vite dev server.

```bash
npm run react:build
```

Runs the typescript compiler and builds the react app.

### Hardhat Commands

```bash
npm run hardhat:compile
```

Compiles the contracts inside the hardhat project.

```bash
npm run hardhat:test
```

Runs the tests inside the test directory in the hardhat project.

```bash
npm run hardhat:test -- path-to-file
```

Run the test on the specific file.

```bash
npm run hardhat:node
```

Starts a JSON-RPC server on top of the Hardhat Network.
