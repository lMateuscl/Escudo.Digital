# Escudo Digital

Plataforma educativa de segurança digital desenvolvida para um projeto extensionista. O objetivo é ajudar as pessoas a reconhecer golpes online e adotar hábitos de proteção.

## Estrutura

```text
escudo-digital/
├── index.html
├── src/
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── app.js
├── .gitignore
├── .nojekyll
└── README.md
```

- **index.html:** conteúdo e estrutura das sete áreas do site.
- **src/css/styles.css:** cores, tipografia, componentes e layout responsivo.
- **src/js/app.js:** navegação e atividades interativas.
- **.nojekyll:** permite servir o projeto como arquivos estáticos no GitHub Pages.

## Abrir o site

Baixe ou clone o projeto e abra o arquivo **index.html** no navegador. Mantenha a pasta **src** ao lado dele. Não é necessário instalar dependências, executar um build ou configurar banco de dados.

## Funcionalidades

- Página inicial com acesso às atividades.
- Biblioteca com seis exemplos de golpes e busca por texto.
- Simulador com cinco mensagens fictícias e explicações.
- Analisador educativo baseado em regras locais.
- Quiz com cinco perguntas, pontuação e explicações.
- Checklist com oito medidas de proteção e progresso local.
- Orientações sobre como agir após um golpe, com fontes oficiais.

## Colocar no GitHub e publicar

Envie o **conteúdo desta pasta** ao repositório: index.html, src, README.md e os arquivos de configuração. O index.html deve ficar na raiz do repositório, ao lado de src.

Para disponibilizar o site online, configure o GitHub Pages para publicar a raiz da branch que contém esses arquivos. Este projeto usa caminhos relativos e pode ser servido no endereço de um repositório, sem alterações de código.

## Privacidade e limites

O analisador não usa inteligência artificial, não abre links e não confirma se uma mensagem é segura. Ele apenas identifica padrões de texto, como urgência e pedidos de credenciais. O texto analisado não é enviado nem salvo.

O checklist utiliza localStorage, quando disponível. O progresso fica no navegador e pode ser perdido ao limpar os dados, mover o arquivo ou trocar de navegador. Quiz e simulador mantêm resultados apenas enquanto a página está aberta.

As atividades funcionam sem internet. Links externos para fontes oficiais precisam de conexão.

## Tecnologias e estágio do projeto

HTML, CSS e JavaScript, sem bibliotecas externas. Esta versão é estática: Flask, SQLite, cadastro de participantes e coleta de resultados da comunidade não estão implementados.

## Fontes educativas

- [Cartilha de Segurança para Internet — CERT.br](https://cartilha.cert.br/)
- [Segurança no Pix — Banco Central](https://www.bcb.gov.br/estabilidadefinanceira/pix-seguranca)

Revise periodicamente os conteúdos e as orientações antes da aplicação com a comunidade.
