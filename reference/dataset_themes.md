# Temas das histórias do experimento

Esta descrição deriva dos textos preparados no manifesto e dos 15 baselines
recuperados no arquivo `experimento-icse.zip`. Os rótulos dos datasets seguem o
manifesto existente; o tema de uma história não comprova sua origem externa.

| Dataset no manifesto | Histórias-pai | Temas presentes nos textos |
| --- | --- | --- |
| Zooniverse | 25: US_001–US_015 e US_036–US_045 | Recomendação musical e de conteúdo; descoberta audiovisual por localização; qualidade, edição e direitos de conteúdo; detecção de pessoas, produtos e logos; segmentação de vídeos; engajamento, confiabilidade e assistência a voluntários; revisão de anotações e processamento de imagens de fauna. |
| PlanningPoker | 10: US_016–US_025 | Criação de sessões de estimativa ágil, convite de estimadores, rodadas, gestão de itens, registro de estimativas, importação de histórias e exportação de resultados. |
| BADCamp | 10: US_026–US_035 | Participação em conferências, patrocinadores e perfis, mapas e locais, inscrições e listas de espera em treinamentos, inscrições em encontros, programação e comunicação do evento. |

Cada história-pai participa das quatro condições. Esses números descrevem as
45 histórias-pai, não a distribuição das 100 perguntas selecionadas.

A seleção intencional de 25 perguntas por condição considerou temas e datasets
diferentes. Não há registro de cotas por tema/dataset ou regra reproduzível por item. Os agrupamentos descritivos acima foram
documentados a partir dos textos disponíveis e não devem ser apresentados como
categorias ou cotas predefinidas na seleção original.

## Histórico recuperado para as 15 histórias anteriores

Os arquivos `inputs/1_baseline/US_001.md` a `US_015.md` do experimento anterior
foram preservados em `legacy_baselines/`. Todos correspondem ao texto das entradas
baseline atuais após desconsiderar BOM UTF-8 e espaços externos. Os snapshots Git
do ZIP também contêm os 15 textos; `legacy_history.csv` registra os commits e blobs
correspondentes, sem importar contas, emails ou o diretório `.git` original.
`legacy_archive_record.json` registra o hash SHA-256 do ZIP recebido.

Essa recuperação estabelece a origem imediata no experimento anterior. As fontes
públicas foram fornecidas posteriormente; a comparação textual e a confirmação
humana são registradas abaixo. A seleção inicial e a sequência detalhada das
adaptações não estão documentadas.

## Comparação com as fontes e confirmação posterior

As três cópias fornecidas estão em `reference/source_datasets/`, com hashes em
`source_manifest.json`. A comparação confirmou texto e linha das 30 adições.
Para US_001, a linha 4 de `g28-zooniverse-uploaded.txt` coincide com o baseline
após retirar a cláusula de benefício.

Para as outras 14 histórias antigas, os vínculos com os datasets fornecidos
foram confirmados pela pesquisadora.
`reference/legacy_source_comparison.csv` preserva as correspondências e diferenças
de redação. Os campos `source_file`, `source_line` e `source_full_text` registram
os vínculos confirmados; `source_verification` distingue confirmação humana de
coincidência textual. Os campos `candidate_source_*` preservam a investigação anterior.

A sequência detalhada das adaptações anteriores ao experimento não está documentada.
