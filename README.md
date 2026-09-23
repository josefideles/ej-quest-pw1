# EJ Quest — AB1

Protótipo visual para Programação Web I. A proposta é organizar trilhas de conhecimento para facilitar a integração de membros de empresas juniores, tendo a RocketJR como contexto de aplicação proposto.

## Tecnologias e pré-requisitos

React, JavaScript, Vite, CSS puro e cinco imagens SVG locais. Use **Node.js 22.12 ou superior** e npm.

## Executar

Abra um terminal dentro de `ej-quest-ab1/`:

```bash
npm ci
npm run dev
```

Abra o endereço indicado pelo terminal, normalmente `http://localhost:5173`.

```bash
npm run build
npm run preview
```

O build gera `dist/`. O preview permite conferir essa versão localmente, normalmente em `http://localhost:4173`.

## Disponível nesta versão

- Jornada com quatro paradas visuais e imagens locais.
- Perfil de Fideles, Membro da RocketJR.
- Navegação entre Jornada e Perfil.
- Ranking e Desafios desativados com “Em breve”.

XP é ilustrativo e fixo em 200. Não há abertura de conteúdos, progressão, quizzes, login, APIs, banco de dados ou persistência. O material não é apresentado como processo oficial da RocketJR.

## Documentação

- [PLANEJAMENTO.md](./PLANEJAMENTO.md): especificação SDD, critérios e validação.
- [EXPLICACAO.md](./EXPLICACAO.md): questões do projeto, conceitos, personalização e roteiro de apresentação.

## Validação realizada

`npm install` e `npm run build` foram executados com sucesso. Não houve ferramenta de navegador disponível nesta sessão: a navegação interativa, imagens renderizadas, teclado e layout em celular/desktop precisam de conferência manual. Não foi instalado framework de testes.

## Pendências: GitHub e apresentação online

A publicação no GitHub e uma URL online são requisitos ainda pendentes. Nenhum repositório remoto ou site foi criado nesta tarefa.

Para publicar posteriormente:

1. Crie um repositório no GitHub e envie os arquivos desta pasta, incluindo `package-lock.json`, respeitando `.gitignore`. Não envie `node_modules/` ou `dist/`.
2. Se usar o repositório que contém os outros projetos, configure **`ej-quest-ab1` como diretório raiz** do serviço de hospedagem. Se publicar somente esta pasta em um repositório próprio, a raiz é a própria pasta do repositório.
3. Em uma hospedagem estática compatível com Vite, use Node.js 22.12+, instalação `npm ci`, comando de build `npm run build` e diretório de saída `dist`.
4. Para GitHub Pages, configure uma ação que instale, gere e publique o conteúdo de `dist`; não publique apenas o código JSX. O Vite já utiliza `base: './'`, compatível com assets relativos em subdiretórios.
5. Abra o endereço gerado, confira a navegação e registre as URLs reais de repositório e site antes da entrega acadêmica.

Evoluções futuras possíveis: conteúdo acessível nas paradas, progressão real, ranking, desafios e backend.
