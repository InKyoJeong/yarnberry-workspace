# yarnberry-workspace

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
