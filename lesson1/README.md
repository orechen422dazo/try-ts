# TypeScript with anyenv environment
set up

1. nodenv install lts
```shell
nodenv install 20.15.0
node -v
nodenv rehash
node -v
env -v
```

2. Specify the project version
```shell
nodenv local 20.15.0
```

3. install typescript
```shell
npm init -y
npm install typescript --save-dev
npx tsc --init
```

3. create new file
```shell
touch index.ts
```

4. run tsc command
```shell
tsc
```