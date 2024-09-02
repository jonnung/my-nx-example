# My NX x NestJS Example

<a alt="Nx logo" href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

✨ Your new, shiny [Nx workspace](https://nx.dev) is ready ✨.

## Setup
새로운 NX Monorepo 환경 구성
```sh
npx create-nx-workspace
```

NestJS NX Plugin 추가
```sh
npx nx add @nx/nest
```

두 번째 NestJS 애플리케이션 추가
```sh
npx nx g @nx/nest:app second-example
```


## Run tasks
First Example 애플리케이션 의존성 그래프 확인

```sh
npx nx serve my-nx-example --graph
```

Monorepo에 포함된 모든 NestJS 애플리케이션 개발 서버 실행
```sh
npx nx run-many -t serve
```