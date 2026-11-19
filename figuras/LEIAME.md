# figuras/

Todas as imagens do manuscrito ficam aqui.

O `preambulo.tex` já define `\graphicspath{{figuras/}}`, então **não** se escreve o
nome da pasta no `\includegraphics`:

```latex
\begin{figure}[h]
\centering
\includegraphics[width=0.9\textwidth]{bpn-prevalencia}% figuras/bpn-prevalencia.pdf
\caption{Prevalência de baixo peso ao nascer por segmento.}\label{fig:bpn-prevalencia}
\end{figure}
```

## Convenções

- Nome do arquivo: `<desfecho>-<descricao>`, em minúsculas e sem acentos —
  `bpn-prevalencia`, `pre-termo-lift-consultas`, `fluxograma-amostra`.
- Formato: PDF ou PNG (o `pdflatex` não lê EPS diretamente). Prefira vetorial;
  em imagens rasterizadas, no mínimo 300 dpi.
- Uma figura por arquivo, sem numeração no nome — a numeração é do LaTeX.
- A figura entra no arquivo da seção onde é citada, em `secoes/`.
