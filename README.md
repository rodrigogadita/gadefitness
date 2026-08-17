# GadeFitness

Diário pessoal de dieta, treino e peso — app de página única (HTML/CSS/JS puro, sem build e sem backend).

## Uso

Abra `index.html` no navegador (ou acesse via GitHub Pages). Todos os dados (registros do dia, medições de peso e metas) ficam salvos apenas no armazenamento local do próprio navegador (`localStorage`) — nada é enviado a nenhum servidor.

Use a aba **Dados** para exportar um backup (`.json`) ou planilhas (`.csv`), e para importar um backup depois.

## Metas

A aba **Corpo** tem um cadastro de metas: cadastre, edite ou apague metas (data + peso alvo + nome) livremente. O ritmo semanal de cada meta é calculado automaticamente a partir da data e do peso da meta anterior.
