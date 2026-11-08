# Calculadora de Títulos — UECE e UFC

Aplicação estática (HTML/CSS/JavaScript), compatível com GitHub Pages.

## Publicação

1. Crie um repositório público no GitHub (ex.: `calculadora-titulos`).
2. Envie `index.html`, `style.css`, `app.js`, `data.js` e a pasta `assets/` para a raiz.
3. Em **Settings → Pages → Build and deployment**, selecione **Deploy from a branch**, branch **main**, pasta **/(root)**.
4. Aguarde a publicação em `https://SEU-USUARIO.github.io/calculadora-titulos/`.

## Identidade visual

As logomarcas oficiais devem ser obtidas nos portais das instituições e salvas como `assets/uece.png` e `assets/ufc.png`. Até que sejam adicionadas, o site mostra a sigla em texto, sem criar brasões fictícios. Fontes:
- UECE: https://www.uece.br/institucional/assessoria-de-comunicacao/
- UFC: https://ufc2012.ufc.br/a-universidade/identidade-visual-da-ufc

## Fontes dos critérios

- UECE: Edital nº 03/2025–FUNECE, Anexo III, publicado no DOE de 12/02/2025.
- UFC: Tabela para Avaliação de Títulos, aprovada na 196ª reunião do Conselho do Campus de Quixadá, em 02/09/2026, vinculada à Resolução nº 24/CEPE/2025.

A aplicação não é oficial. Confirme critérios, atualizações e documentação com a banca. A classificação de itens tachados da UFC é orientativa para Computação/TI.

## Cálculo

`pontuação do critério = min(quantidade × peso, teto individual)`; `pontuação do quadro = min(soma dos critérios, teto do quadro)`. Progresso separado por instituição no `localStorage` do navegador. Na UECE, as alternativas de área específica/correlata de uma mesma modalidade são mutuamente exclusivas. Na UFC, mestrado não pontua quando há doutorado.

## Atenção

No Quadro IV da UECE, o item 4.7 tem teto operacional de 10 semestres (5 anos), enquanto outros itens por ano respeitam os 5 anos. A pontuação máxima global do quadro é 20. As atividades de pontuação zero da UFC continuam listadas.
