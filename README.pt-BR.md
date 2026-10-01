# jQuery selectors and cards

[English](README.md)

## Ideia e processo

Código educacional revisado em 01/10/2026. Não foram encontrados plano datado, wireframes ou diário pessoal nos arquivos revisados. Este README registra o exercício implementado, sem inventar histórico. A estrutura revisada não tem backend ou banco.

## Arquitetura e design

cards-jquery.html carrega jQuery 3.2.1, style.css e script.js. Controles de stream destacam cards correspondentes. statements.js é roteiro separado de console para seletores, CSS, substituição de HTML/texto e append; não é carregado pela página. CSS usa cards flex e breakpoint de 700px. HTML usa caminhos img/, mas a raiz contém images/; revise referências de imagens.

## Preview local

```bash
python3 -m http.server 8000
```

Abra `http://localhost:8000/cards-jquery.html`. Arquivos estáticos revisados não exigem instalação de pacotes; fontes/bibliotecas externas precisam de rede. Comando não executado nesta atualização.

## Testes e limites

Nenhuma suíte automatizada encontrada na listagem revisada da raiz. Comportamento no navegador não testado e nenhum deploy público confirmado aqui. Teste streams, caminhos de imagens, telas estreitas e teclado. Comandos de console são exemplos independentes: substituir body.html remove a página de exemplo. O seletor final my_footer não tem # do ID. Não copie inserção de HTML para conteúdo não confiável.

## Capturas

Nenhuma captura de aplicação verificada ou adicionada. Capturas futuras devem usar arquivos datados em `docs/assets/`, mostrar estados inicial/alterado em desktop/mobile e identificar o exercício de aula. Só adicione links após as imagens existirem.

## Créditos e licença

A página usa texto e marca de aula do Code Institute. Direitos de código, imagens e bibliotecas de terceiros preservados, sem nova licença. README original mantido no [apêndice em inglês](README.md#original-readme), como referência histórica.
