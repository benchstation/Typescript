### Flags
- `-y`: Assumes "yes" as the default answer for all prompts.
- `-D`: Installs packages only as development dependencies.

#### Initiate Node project
```shell
npm init -y
```

#### Install Typescript locally
```shell
npm i typescript -D
```

#### Locally compile all Typescript files into Javascript manually
```shell
npx tsc [filename].ts
```

> You need to use `npx` when executing NodeJS locally.

#### Installs ts-node 
```shell
npm i ts-node -D
```

#### Executes files directly without the need to compile them to JavaScript manually 
```shell
npx ts-node [filename].ts
```

#### Install ESLint
```shell
npm i eslint -D
```