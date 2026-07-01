# Entrega do Seminário — Vibrações e Oscilações

**Aluno:** Pedro Vinicius Marçal Naves Queiroz
**Tema:** Oscilador harmônico e oscilador amortecido — Capítulo 22 de HIBBELER, R. C., *Dinâmica*.

Este pacote contém a apresentação de slides, o relatório escrito (em dois formatos), o roteiro de fala e
este guia. Tudo em **português do Brasil** e **sem dependências externas** (abre offline, com duplo clique).

---

## 1. Arquivos gerados

| Arquivo | O que é | Como usar |
|---|---|---|
| `seminario_vibracoes_oscilacoes.html` | **Apresentação de slides** (22 slides), com diagramas SVG, fórmulas e revelação progressiva de equações. | Abrir no navegador e apresentar. |
| `relatorio_escrito_vibracoes_oscilacoes.md` | **Relatório escrito** em Markdown (para ler/editar em qualquer editor). | Abrir em editor de texto ou visualizador de Markdown. |
| `relatorio_escrito_vibracoes_oscilacoes.html` | **Relatório escrito imprimível** (mesma versão, formatada para impressão A4 / PDF). | Abrir no navegador e exportar em PDF. |
| `roteiro_apresentacao_vibracoes_oscilacoes.md` | **Roteiro de fala** slide a slide (o que falar, fórmulas, erros a evitar, transições). | Ler antes e durante o ensaio. |
| `README_ENTREGA_SEMINARIO.md` | Este guia, com instruções e checklist de requisitos. | Você está lendo. |

> **Dica:** os dois arquivos-fonte do livro (`cap22_part1.pdf` e `cap22_part2.pdf`) foram usados apenas como
> referência; não precisam ser entregues. A versão anterior dos arquivos foi preservada na pasta
> `backup_antes_melhorias_ux/`.

---

## 2. Como abrir a apresentação

1. Dê um **duplo clique** em `seminario_vibracoes_oscilacoes.html` (ou clique com o botão direito → "Abrir com"
   → seu navegador: Chrome, Edge, Firefox…).
2. A apresentação abre direto no primeiro slide. Para **tela cheia**, pressione **F11**.
3. Não é preciso internet nem instalar nada.

### Navegação por teclado

| Tecla | Ação |
|---|---|
| **→** , **Espaço** (ou Page Down) | Próximo slide |
| **←** (ou Page Up) | Slide anterior |
| **Home** | Primeiro slide |
| **End** | Último slide |

Também há **botões ‹ ›** no canto inferior direito, uma **barra de progresso** no topo, o **número do slide**
(ex.: `7 / 22`) e suporte a **arrastar o dedo** (swipe) em telas de toque.

Nos slides de dedução (**6** e **12**), cada <kbd>→</kbd> **revela uma equação por vez**. No topo de cada slide
há um **roteiro de seções** que destaca a etapa atual (Conceito → Sem amortecimento → Com amortecimento →
Comparação → Aplicação → Conclusão).

A fala sugerida de cada slide está no arquivo **`roteiro_apresentacao_vibracoes_oscilacoes.md`** (roteiro de apresentação).

---

## 3. Como exportar o relatório (ou os slides) em PDF

Pelo próprio navegador, sem programas extras:

1. Abra o `relatorio_escrito_vibracoes_oscilacoes.html` (há um botão **"🖨️ Imprimir / Salvar em PDF"** no
   topo) **ou** pressione **Ctrl + P** (no Mac, **⌘ + P**).
2. Em "Destino", escolha **"Salvar como PDF"**.
3. Confira o tamanho **A4** e clique em **Salvar**. O relatório já tem layout de impressão pronto (~6–7 páginas).

**Para exportar os slides em PDF** (caso o professor peça): abra `seminario_vibracoes_oscilacoes.html`, dê
**Ctrl + P**, escolha "Salvar como PDF" e, em layout, selecione **Paisagem (Landscape)**. O modo de impressão
mostra todos os slides em sequência.

---

## 4. Checklist dos requisitos do professor

| # | Requisito | Onde foi atendido |
|---|---|---|
| 1 | Tema **Vibrações/Oscilações** (cap. 22 do Hibbeler) | Capa (Slide 1); Relatório §1–2; título de todos os arquivos. |
| 2 | **2ª Lei de Newton** no sistema massa-mola simples | Slide 6; Relatório §3.2 (`ΣF_x = m·ẍ` → `−kx = m·ẍ`). |
| 3 | Escrever a **equação diferencial de 2ª ordem** | Slide 6; Relatório §3.2 (`m·ẍ + k·x = 0`). |
| 4 | **Equação do oscilador harmônico e solução geral** | Slides 6–8; Relatório §3.3–3.4 (`ẍ + ωₙ²x = 0`; soluções). |
| 5 | **Não derivar** a solução completa, só mostrar a forma e interpretar | Slide 2 (Sumário) e Relatório §1; soluções apresentadas e interpretadas, sem dedução. |
| 6 | Soluções com **exponenciais imaginárias** ou seno/cosseno | Slide 8; Relatório §3.4 (três formas + fórmula de Euler). |
| 7 | **2ª Lei de Newton** no oscilador amortecido (viscoso) | Slides 11–12; Relatório §4.1–4.2 (`−kx − cẋ = m·ẍ`). |
| 8 | **Equação diferencial do oscilador amortecido** | Slide 12; Relatório §4.2 (`m·ẍ + c·ẋ + k·x = 0`). |
| 9 | Os **três casos**: subamortecido, criticamente amortecido, superamortecido | Slides 15–19; Relatório §4.5–4.8. |
| 10 | **Quando cada caso ocorre** (matemática e fisicamente) | Slides 13–17 (condições em `ζ`); Relatório §4.4–4.7. |
| 11 | **Amortecimento desejado** em amortecedores de carro/moto | Slide 20; Relatório §5 (próximo do crítico). |
| 12 | **Parte escrita** com tema, os dois casos, soluções e interpretações | `relatorio_escrito_vibracoes_oscilacoes.md` e `.html` (completo). |

### Recursos técnicos da apresentação (também solicitados)

- ✅ Arquivo **HTML único e autossuficiente**, abre direto no navegador, **sem framework** e **sem
  dependências externas** (só HTML, CSS e JavaScript puro).
- ✅ **Navegação por teclado** (→/Espaço, ←, Home, End), **barra de progresso** e **número do slide**.
- ✅ **Revelação progressiva** das equações nos slides de dedução (6 e 12) e **roteiro de seções** no topo dos slides.
- ✅ **Notação de ponto legível** para velocidade (`ẋ`) e aceleração (`ẍ`) — sem risco de confundir `m ẍ` com `m x`.
- ✅ **Modo de impressão** via CSS `@media print` (slides em paisagem; equações totalmente reveladas).
- ✅ **Diagramas em SVG embutido** (massa-mola, diagrama de corpo livre, massa-mola-amortecedor, cosseno de
  "puxar e soltar") e **gráfico** comparando os quatro regimes.
- ✅ **Caixas de fórmula** e **tabela de símbolos**. (A fala de cada slide está no arquivo `roteiro_apresentacao_vibracoes_oscilacoes.md`.)

---

## 5. Dados de identificação (já preenchidos)

Estes dados já constam na capa da apresentação e no cabeçalho do relatório:

- **Aluno:** Pedro Vinicius Marçal Naves Queiroz
- **Disciplina:** Mecânica Geral (39A)
- **Professor:** José Romão Franca
- **Data de apresentação:** 1 de julho de 2026

Caso precise ajustar, edite os dois arquivos HTML e o `.md` do relatório.

---

## 6. Sobre as fontes e a originalidade

Todo o material foi **redigido com palavras próprias**, usando o Capítulo 22 do Hibbeler apenas como base para
a estrutura, a notação e as fórmulas — **sem cópia de trechos longos** do texto original. As citações trazem
seção e página:

- Seção 22.1 — *Vibração livre não amortecida* (pp. 575–580).
- Seção 22.4 — *Vibração livre amortecida viscosa* (pp. 595–597).
- *Revisão do Capítulo* (pp. 607–608).

Arquivos de referência: `cap22_part1.pdf` e `cap22_part2.pdf`.
