# IQTPC, Índice de Qualidade do Transporte Público Coletivo

Proposta técnica da CGDI/DEREG/SEMOB/MCID, publicada como livro Quarto.

## Como ler

Comece por `index.qmd`, que traz a ordem de precedência entre os documentos. Os capítulos, na ordem de leitura, são:

1. `index.qmd`, índice geral
2. `IQTPC_parametros_qualidade_transporte_publico.qmd`, documento principal
3. `IQTPC_Manual_de_calculo.qmd`, Manual de cálculo
4. `IQTPC_Anexo_I_matriz_origem_dados.qmd`
5. `IQTPC_Anexo_II_pesquisa_nacional.qmd`
6. `IQTPC_Anexo_III_arquitetura_coleta_pemob.qmd`
7. `IQTPC_Anexo_IV_aproveitamento_politicas_MCID.qmd`

## Como gerar o livro

Requer [Quarto](https://quarto.org).

```
quarto render
```

Gera em `_book/`: um site HTML navegável, `IQTPC.pdf` e `IQTPC.docx`.

Para pré-visualizar com recarregamento automático durante a edição:

```
quarto preview
```
