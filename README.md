# Marvel em Pauta

Blog responsivo de cultura pop dedicado ao universo Marvel. O projeto apresenta notícias sobre filmes, séries e bastidores em uma experiência editorial inspirada em revistas digitais.

## Recursos

- Página inicial com matéria principal e notícias complementares.
- Categorias, datas e tempo estimado de leitura.
- Páginas individuais para cada matéria.
- Navegação responsiva para desktop e dispositivos móveis.
- Tipografia editorial e layout com foco na leitura.

## Tecnologias

- [Angular](https://angular.io/) 14
- TypeScript
- HTML e CSS

## Como executar

Pré-requisito: Node.js e npm instalados.

```bash
npm install
npm start
```

Abra [http://localhost:4200](http://localhost:4200) no navegador. A aplicação será atualizada automaticamente ao salvar alterações nos arquivos.

## Scripts disponíveis

| Comando | Descrição |
| --- | --- |
| `npm start` | Inicia o servidor de desenvolvimento. |
| `npm run build` | Gera a versão de produção em `dist/`. |
| `npm test` | Executa os testes unitários com Karma. |

## Estrutura do projeto

```text
src/app/
├── components/    # Cabeçalho e cartões de matérias
├── data/          # Conteúdo das notícias
└── pages/         # Página inicial e páginas de artigo
```

## Conteúdo

As matérias estão centralizadas em `src/app/data/dataFake.ts`. Para adicionar uma notícia, inclua um novo objeto com `id`, categoria, data, tempo de leitura, título, descrição e URL da imagem.
