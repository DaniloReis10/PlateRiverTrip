# Guia de contribuição

Obrigado por considerar contribuir com o PlateRiverTrip! Este guia explica como sugerir melhorias de forma simples e organizada.

## Como contribuir

1. Crie uma issue descrevendo a melhoria, correção ou dúvida.
2. Faça um fork do repositório.
3. Crie uma branch com nome descritivo, por exemplo `docs/atualiza-readme` ou `fix/links-rapidos`.
4. Faça alterações pequenas e focadas.
5. Teste a página localmente antes de abrir o pull request.
6. Abra um pull request explicando o que foi alterado e por quê.

## Padrões do projeto

- Mantenha o projeto sem dependências quando possível.
- Prefira HTML semântico e CSS simples.
- Use nomes de classes claros e descritivos.
- Otimize imagens antes de adicioná-las ao repositório.
- Atualize a documentação quando alterar estrutura, conteúdo ou fluxo de execução.

## Como testar localmente

Execute um servidor estático na raiz do projeto:

```bash
python3 -m http.server 8000
```

Acesse `http://localhost:8000` e confira:

- Se a página abre sem erros visuais.
- Se as imagens carregam.
- Se os links internos funcionam.
- Se o layout continua legível em telas menores.

## Pull requests

Ao abrir um pull request, inclua:

- Resumo das mudanças.
- Como você testou.
- Capturas de tela quando houver mudança visual relevante.
- Issues relacionadas, se existirem.
