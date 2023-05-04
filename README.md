# yarnberry-workspace

```bash
# @wanted/web 구동
$ yarn workspace @wanted/web dev
```

```
# 모든 프로젝트를 typecheck 하기
$ yarn g:typecheck
```

<!-- - root가서 상태 갱신하기

```
cd ..
yarn
```

- 실행 확인

```bash
yarn workspace @wanted/web run dev
# cd apps/cd wated/yarn dev로 실행하지 않아도 된다.
```

- typescript 의존성 추가

```
yarn add -D typescript
yarn dlx @yarnpkg/sdks vscode // > 허용
```


#### 8. apps/wanted에서 pacakges/lib 의존해 보기

- root로 이동

```bash
cd ../../
yarn # pnp.cjs에 갱신
```

- root 실행

```
yarn workspace @wanted/web add @wanted/lib

# apps/wanted/package.json에 의존성이 추가된 것을 확인
``` -->

<!-- #### tsconfig 설정 공유

- root에 tsconfig.base.json 생성

```
{
  "compilerOptions": {
    "strict": true,
    "useUnknownInCatchVariables": true,
    "allowJs": true,
    "skipLibCheck": true,
    "forceConsistentCasingInFileNames": true,
    "noEmit": true,
    "esModuleInterop": true,
    "moduleResolution": "node",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "incremental": true,
    "newLine": "lf"
  },
  "exclude": ["**/node_modules", "**/.*/"]
}
```

#### prettier, eslint 설정 공통화

- root 에서 prettier, eslint 설치

```
yarn add prettier eslint eslint-config-prettier eslint-plugin-import eslint-plugin-react eslint-plugin-react-hooks eslint-import-resolver-typescript @typescript-eslint/eslint-plugin @typescript-eslint/parser -D


yarn dlx @yarnpkg/sdks
``` -->
