# Eduardo Alves

**Toda coisa aqui começou como pergunta.**

No ar em [educofseal.github.io](https://educofseal.github.io/)

Desenvolvedor. Python, web e dados. Cinco projetos, cinco perguntas que vieram antes do código. Nenhuma delas nasceu de tutorial.

## Os projetos

| Projeto | A pergunta | Stack |
|---|---|---|
| [Lease Lens](https://lease-lens.streamlit.app) | Dá pra transformar uma pasta de contratos em PDF em respostas operacionais? | Python, pdfplumber, SQLite, Streamlit |
| [Player2](https://github.com/Educofseal/Player2) | E se uma recomendação não fosse caixa-preta? | Python, Flet, grafos escritos à mão |
| [Pokédex](https://educofseal.github.io/Pokedex/) | Como carregar 151 Pokémon de uma API sem a página congelar? | JavaScript, PokéAPI |
| Qualidade de Testes | Que etapas existem entre o dado cru e o número que alguém usa pra decidir? | Python, pandas, SQL, Power BI |
| People Analytics | Consigo traduzir pergunta de gente em métrica que se sustenta? | Python, pandas, SQL, Power BI |

Os dois últimos estão em repositórios privados enquanto eu limpo dado de exemplo. Peça acesso e eu abro.

## Como este site é feito

Um `index.html` e uma pasta `assets`. HTML, CSS e JavaScript puro. Sem framework, sem build, sem npm.

O topo é um vídeo que roda para frente conforme você desce a página e para trás quando você sobe. Ele é buscado inteiro como Blob, para funcionar em hospedagem sem suporte a download parcial, e o tempo mostrado é suavizado num laço que descansa quando converge. Celular, tablet em pé e quem prefere menos movimento recebem um herói de imagem parada e nunca baixam o vídeo.

Números medidos, não estimados:

- Primeira tela: cerca de 164 KB
- Vídeo: 3,2 MB, entra depois, atrás de um anel de progresso
- Contraste do texto sobre a filmagem, no pior quadro de cada faixa: 6,4 · 6,2 · 11,9 · 14,1 (o piso é 3,5)
- Zero erro de console, nada vazando para a lateral entre 320px e 1440px

## Rodando localmente

Abrir o `index.html` com dois cliques mostra o topo como imagem parada, porque o navegador bloqueia `fetch` em arquivo local. Para ver a rolagem completa, sirva a pasta:

```
npx http-server
```

## Contato

- E-mail: contatoedu07@gmail.com
- LinkedIn: [contatoedu](https://www.linkedin.com/in/contatoedu/)
- GitHub: [@Educofseal](https://github.com/Educofseal)

---

Sem template. Construído à mão.

MIT © 2026 Eduardo Alves
