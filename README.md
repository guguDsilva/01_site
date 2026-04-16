# 01_site
Criação de site em colaboração.

## Deploy no Vercel

Instruções rápidas para publicar este site estático no Vercel.

Opções:

1) Deploy via Git (recomendado)

	- Faça push do seu repositório para GitHub, GitLab ou Bitbucket.
	- No painel do Vercel (https://vercel.com), clique em "New Project" e conecte o repositório.
	- O Vercel detecta automaticamente que é um site estático e faz o deploy.

2) Deploy via Vercel CLI (rápido, direto da sua máquina)

	- Instale o Vercel CLI (Node.js necessário):

```powershell
npm i -g vercel
```

	- Faça login (uma vez):

```powershell
vercel login
```

	- No diretório do projeto (`01_site`), rode:

```powershell
vercel --prod
```

	- O comando guia você pelas opções e faz o deploy para uma URL temporária e, se confirmar, para a URL de produção.

Observações e configuração incluída:

- Adicionado `vercel.json` com configuração mínima para servir `index.html` como app estático e rotear todas as rotas para ele.
- Não é necessário build para este projeto (HTML/CSS estático).

Se quiser, eu posso:

- Ajudar a conectar este repositório ao GitHub (instruções passo-a-passo).
- Gerar um arquivo `.vercelignore` para excluir arquivos indesejados.
- Fazer o deploy inicial via CLI a partir da sua máquina (me diga se quer que eu gere os comandos específicos).

