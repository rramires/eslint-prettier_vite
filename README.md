# eslint-prettier-for-vite

#### Eslint + Prettier + Vite setup without headaches and conflicts

### Instalação e configuração do Vite

1 - Instale o Vite:

[Vite Guide](https://vite.dev/guide/g)

-   Obs: Caso antes já tenha um arquivo README, a instalação vai sobrescrever. Então faça backup antes ou volte a versão dele com usando o git.

```sh
npm create vite@latest .
```

Siga o passo a passo, no meu caso, já tem arquivos no projeto então vou mandar ignorar. E vou usar React + TypeScript.
(Use as setas para mudar de opção)

1. ✔ Ignore files and continue
2. ✔ React
3. ✔ TypeScript

2 - Instale as dependências e rode o projeto:

```sh
npm install
npm run dev
```

3 - Caso queira trocar a porta, adicione no **vite.config.ts**:

```js
export default defineConfig({
	// adicione
	server: {
		port: 3001,
	},
	//
	plugins: [react()],
})
```
