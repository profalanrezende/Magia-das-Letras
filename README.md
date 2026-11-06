# Magia das Letras — A.R.S. HTML APPS e GAMES

Variação alfabetizadora do **Magia Doce**: troque peças vizinhas para juntar 3 ou mais iguais (ou formar palavras) antes que o tempo (5 a 15 min) acabe.

## Modos (30 níveis cada + Modo Infinito ∞ gerado a partir do banco de dados)
1. **Vogal** – A E I O U, depois maiúsculas/minúsculas, pares, trios e acentos.
2. **Consoante** – P T M B D F V L N S R C G J Z X H Q, depois pares confusos (P/B, T/D, F/V…).
3. **Família Silábica**
   - **3.1 Sílabas iguais** – 30 famílias (P, T, M… CH, LH, NH, QU, GU, BR, PR…).
   - **3.2 Juntar sílabas** – sílabas lado a lado (→ ou ↓) formam palavras reconhecidas; o tabuleiro já traz as sílabas das palavras da fase.

Tempo por nível: 5 min no nível 1, crescendo até 15 min no 30. Estrelas pelo tempo que sobra.
O Modo Infinito libera ao vencer o nível 30 (ou pela opção “Liberar todos os níveis”, com senha).

## Studio do Professor
Botão **🎛 Studio do Professor** na tela inicial (senha padrão **prof123**, troque em *Backup e senha*). Ali você cria, testa (▶ Testar agora) e salva modos com as suas regras:
- **Vogal / Consoante:** letras da missão, o que atrapalha (vogais, consoantes ou ambas), estilo das letras.
- **Sílabas iguais:** uma ou mais famílias (V, V F, GU, BR…) ou lista de sílabas; sílabas de outras famílias entram para atrapalhar.
- **Juntar sílabas:** cole o texto do dia e toque em ✂️ *Separar sílabas*. Qualquer palavra do dicionário formada (→ ou ↓) conta para a meta; as palavras do dia dão bônus. Opção “só valem as da lista”.
- Em todos: tamanho do tabuleiro (4×4 a 7×7), nº de peças que atrapalham, tempo (5–15 min) e meta.

Os modos ficam no aparelho e aparecem na tela inicial. Para levar a outros aparelhos: exporte e coloque o `desafios.json` junto do jogo (aparece com a etiqueta “turma”). O arquivo incluído traz exemplos.

## Dicionário
`dict.js` (~120 mil palavras, o mesmo do Detetives do Saber) valida as palavras formadas no tabuleiro e as digitadas pelo professor.

## Publicar
Envie **todos** os arquivos desta pasta para o repositório e ative GitHub Pages (Settings → Pages → branch `main`, pasta `/root`). Funciona offline depois do primeiro acesso (PWA).
