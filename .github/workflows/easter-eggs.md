# Easter Eggs da Página

| # | Easter Egg | PC | Celular | Recompensa |
|---|------------|----|---------|------------|
| 1 | **Console do navegador** | F12 → Console | F12 → Console (se o browser permitir) | `flag{nekyl_was_here}` |
| 2 | **Terminal secreto** (crase) | Tecla `` ` `` | — | Terminal interativo |
| 3 | **Terminal secreto** (`:term`) | `:` → digitar `term` | — | Terminal interativo |
| 4 | **Terminal secreto** (triple-tap) | — | 3 toques rápidos no nome "NEKYL" | Terminal interativo |
| 5 | **Terminal secreto** (long press) | — | Segurar no nome "NEKYL" (800ms) | Terminal interativo |
| 6 | **Konami Code** | `↑↑↓↓←→←→BA` | — | Matrix mode |
| 7 | **Matrix mode** (terminal) | Comando `matrix` | Comando `matrix` | Liga/desliga efeito Matrix |
| 8 | **Matrix mode** (`:matrix`) | `:` → digitar `matrix` | — | Liga/desliga efeito Matrix |
| 9 | **Matrix mode** (screensaver) | 20s sem interação | 20s sem interação | Matrix aparece automaticamente |
| 10 | **SSH fake login** (Termux) | Duplo clique no logo Termux | 2 toques no logo Termux | Tela de brute-force |
| 11 | **SSH fake login** (terminal) | Comando `ssh` ou `:ssh` | — | Tela de brute-force |
| 12 | **SSH flag** | 5× senha errada | 5× senha errada | `flag{4cc355_gr4nt3d_2026}` |
| 13 | **Flag do terminal** | Comando `flag` | Comando `flag` | `flag{d3sm0nt4r_pr4_3nt3nd3r}` |
| 14 | **Footer duplo clique** | Duplo clique no rodapé | 2 toques no rodapé | Resumo de todos os segredos |

### Flags

| Flag | Como obter |
|------|-----------|
| `flag{nekyl_was_here}` | Console do navegador (F12) |
| `flag{d3sm0nt4r_pr4_3nt3nd3r}` | Terminal secreto → comando `flag` |
| `flag{4cc355_gr4nt3d_2026}` | SSH brute-force (5 tentativas de senha) |

### Screensaver

- Após **20 segundos sem interação** com a página, o **Matrix mode** ativa automaticamente como um descanso de tela
- Quando ativo, **permanece até recarregar a página** — novas interações não cancelam
