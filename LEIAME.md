# Manuscrito — template SBC

Compile sempre **`main.tex`** (pdflatex → bibtex → pdflatex → pdflatex).

## Estrutura

```
main.tex             estrutura do documento
sbc-template.sty     estilo oficial SBC (não editar)
sbc.bst              estilo de referências SBC (não editar)
preambulo.tex        pacotes e macros (\fontetabela, \tabcompacta, L{})
secoes/00-frontmatter.tex   título, autores, endereço, e-mails
secoes/00b-resumo.tex       abstract (inglês) e resumo (português)
secoes/01..05-*.tex         corpo do artigo (sem mudanças de texto)
secoes/06-backmatter.tex    agradecimentos (opcional)
referencias/referencias.bib
figuras/
```
