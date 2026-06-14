# PlateRiverTrip

Site estático de uma página para organizar um fim de semana de camping no **Platte River State Park**, com roteiro diário, lista de itens para levar, previsão esperada do clima e links rápidos de navegação.

## 📌 Visão geral

O projeto é composto por HTML e CSS puros, sem etapa de build e sem dependências JavaScript. Ele pode ser aberto diretamente no navegador ou publicado em qualquer serviço de hospedagem estática, como GitHub Pages, Netlify ou Vercel.

## ✨ Funcionalidades

- Hero visual com imagem de destaque do parque.
- Links rápidos para as seções principais da página.
- Cards de clima esperado para os dias da viagem.
- Lista de itens úteis para camping.
- Roteiro detalhado por dia, incluindo horários, deslocamentos e atividades.
- Layout responsivo para desktop e dispositivos móveis.

## 🗂️ Estrutura do projeto

```text
.
├── index.html              # Página principal com HTML, CSS embutido e conteúdo da viagem
├── images/                 # Imagens usadas pelos cards e hero
│   ├── camping.jpg
│   ├── forest.jpg
│   ├── hero.jpg
│   ├── tower.jpg
│   └── waterfall.jpg
├── README.md               # Documentação principal do projeto
├── CONTRIBUTING.md         # Guia para contribuir com o projeto
├── CODE_OF_CONDUCT.md      # Código de conduta da comunidade
└── SECURITY.md             # Política para reporte de vulnerabilidades
```

## 🚀 Como executar localmente

Como o projeto é estático, você pode escolher uma das opções abaixo.

### Opção 1: abrir diretamente

Abra o arquivo `index.html` no navegador.

### Opção 2: usar um servidor local

```bash
python3 -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## 🛠️ Como editar o conteúdo

Todo o conteúdo principal está em `index.html`:

- Edite a seção `.hero` para alterar título e chamada inicial.
- Edite o card `#weather` para atualizar a previsão esperada.
- Edite o card `#packing` para atualizar a lista de itens.
- Edite os cards `#saturday`, `#sunday` e `#monday` para alterar o roteiro.
- Substitua imagens dentro da pasta `images/`, mantendo os nomes atuais ou atualizando os caminhos no HTML.

## 🎨 Guia rápido de estilos

Os estilos ficam embutidos no bloco `<style>` em `index.html` para manter o projeto simples. As principais classes são:

- `.hero`: seção de abertura com imagem de fundo.
- `.container`: largura máxima e espaçamento geral da página.
- `.card`: cartões brancos com sombra e cantos arredondados.
- `.content`: espaçamento interno dos cartões.
- `.info-box`: blocos destacados com detalhes de roteiro.
- `.weather-grid` e `.weather-card`: grade e cartões de clima.
- `.quick-links`: botões de navegação interna.

## ✅ Checklist antes de publicar

- Verificar se todas as imagens carregam corretamente.
- Validar os horários e endereços do roteiro.
- Testar em tela pequena e tela grande.
- Conferir se os links rápidos levam para as seções corretas.
- Atualizar clima e datas quando a viagem mudar.

## 🌐 Publicação no GitHub Pages

1. Envie o projeto para um repositório no GitHub.
2. Acesse **Settings > Pages**.
3. Em **Build and deployment**, escolha a branch principal e a pasta raiz (`/`).
4. Salve as alterações.
5. Aguarde o GitHub gerar a URL pública do site.

## 🤝 Contribuição

Contribuições são bem-vindas. Leia o arquivo [CONTRIBUTING.md](CONTRIBUTING.md) antes de abrir uma issue ou pull request.

## 🔒 Segurança

Para reportar problemas de segurança, consulte [SECURITY.md](SECURITY.md).

## 📄 Licença

Nenhuma licença foi definida ainda. Antes de reutilizar, distribuir ou publicar versões derivadas, confirme com o proprietário do repositório qual licença deve ser aplicada.
