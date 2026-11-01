# cyclecursos-dados

Dados abertos usados pelo app **CycleCursos**: cursos de graduação **gratuitos** reconhecidos pelo MEC,
calendários do SISU, ProUni e FIES, e editais de ingresso dos Institutos Federais.

Atualizado todo dia por um robô. Endereço dos arquivos:
`https://gilmaralberto.github.io/cyclecursos-dados/<arquivo>.json`

| Arquivo | Conteúdo | Fonte |
|---|---|---|
| `catalogo.json` | Cursos de graduação com `IN_GRATUITO = 1` | Inep — Microdados do Censo da Educação Superior |
| `sisu.json` | Cronogramas do SISU, ProUni e FIES | Portal Único de Acesso ao Ensino Superior (MEC) |
| `editais.json` | Editais de ingresso (graduação e pós) | Feeds RSS dos Institutos Federais |
| `status.json` | Última execução de cada fonte | Robô |

Os dados públicos de origem são do Governo Federal; confira sempre o edital oficial de cada instituição.
