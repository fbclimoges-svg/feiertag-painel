# Gramacruz — Portfólio Federal (JFES) + Execução Ativa TJES

**Data do levantamento:** 30/07/2026
**Fontes:** relatório de acompanhamento (código de cliente 34028387) cruzado com a API pública DataJud/CNJ (índices `api_publica_trf2` e `api_publica_tjes`).
**Nota:** este portfólio é distinto dos 4 autos estaduais da estratégia Cedros/Magnitos (0005645, 0021588, 0012200, 0015696) — manter pastas e controles separados.

## Resumo executivo

| # | Processo | Tipo | Exequente/Autor | Situação (DataJud) | Prioridade |
|---|---|---|---|---|---|
| 1 | 0000089-43.2012.4.02.5001 | Cumprimento de sentença | União (AGU) / MPF | **ENCERRADO** — baixa definitiva 25/04/2025 | Baixa |
| 2 | 0001179-91.2009.4.02.5001 | Execução fiscal | ANM | **PARADO** desde 21/03/2022 — avaliar prescrição intercorrente | Média |
| 3 | 0023238-29.2016.4.02.5001 | Execução fiscal | Fazenda Nacional | **ENCERRADO** — prescrição decretada 12/11/2024; baixa 14/02/2025 (favorável) | Média |
| 4 | 0032660-91.2017.4.02.5001 | Execução fiscal (multas IBAMA) | IBAMA | **ATIVA** — decisão judicial 11/03/2025 | **Alta** |
| 5 | 5001084-70.2023.4.02.5005 | ACP — Flora | MP-ES, MPF, ANM, IEMA, União | **ENCERRADA** — sentença 31/03/2025 (art. 485, VI, CPC); **sem apelação**; trânsito em julgado 30/05/2025 | Baixa |
| 6 | 5004271-23.2022.4.02.5005 | ACP — Dano ambiental | União, MPF, IEMA | **ENCERRADA** — baixa definitiva 02/04/2025 | Média |
| 7 | 5006055-10.2024.8.08.0011 | Execução de título extrajudicial — **Gramacruz exequente** | GRAMACRUZ | **ATIVA** — petições 20–21/05/2026 | **Alta** |

**Quadro geral:** dos 6 federais, 4 já foram baixados definitivamente. Restam ativos apenas a ExFis do IBAMA (0032660) e, no estadual, a execução em que a Gramacruz é credora (5006055).

## Verificação da ACP 5001084-70.2023.4.02.5005 — sentença íntegra obtida

Sentença obtida na consulta pública do eproc/JFES em 30/07/2026 (evento 66, SENT1) — íntegra em `docs/Sentenca-ACP-5001084-Colatina.txt`, resumo em `docs/Resumo-ACP-5001084-Colatina.md`.

- **1ª Vara Federal de Colatina** (juiz da sentença: Rafael de Azevedo Pinto). Ação originária de **20/07/2005**, Comarca de Água Doce do Norte, remetida à JF por dano ambiental de exploração indevida de granito.
- **Sentença de 31/03/2025**: extinção **sem resolução de mérito por ausência superveniente de interesse processual (art. 485, VI, CPC)** — laudos IEMA/IDAF de 2024 atestaram área em regeneração natural há ~20 anos, fauna e flora restabelecidas e **PRAD cumprido**. Sem custas nem honorários; **sem remessa necessária**.
- **Contexto favorável à Gramacruz**: a Safra Mármores reconheceu **culpa exclusiva** pela degradação e a Gramacruz já havia requerido sua **exclusão do polo passivo** (evento 16.1).
- **Apelação: NÃO houve.** Ciência com renúncia ao prazo por Ricardo de Cerqueira Cruz (07/04/2025); decurso de prazo das demais partes (13 e 29/05/2025); **trânsito em julgado e baixa definitiva em 30/05/2025**. Nenhum registro no TRF2.
- **Risco de repropositura: baixo** — a extinção se fundou em dano já reparado; nova ACP exigiria fato novo de degradação.

## Prioridades marcadas

1. **P1 — 5006055-10.2024 (TJES/Cachoeiro, 5ª Vara Cível):** única frente ofensiva; levantar valor do título, objeto e teor das petições de mai/2026 no PJe (advogado).
2. **P1 — 0032660-91.2017 (ExFis IBAMA):** única fiscal federal ativa; obter teor da decisão de 11/03/2025 e prazos em aberto.
3. ~~P2 — 5001084-70.2023: inteiro teor da sentença~~ — **concluído em 30/07/2026** (sentença arquivada; sem apelação; risco de repropositura baixo).
4. **P2 — 0001179-91.2009 (ExFis ANM):** parada há 4+ anos — avaliar arguição de prescrição intercorrente (precedente favorável na própria carteira: 0023238-29.2016).
5. **P2 — 0023238-29.2016:** cruzar a CDA extinta por prescrição com a base de 683 CDAs do track PGFN/REGULARIZE antes de fechar a Transação Individual.
6. **P3 — 5004271-23.2022 e 0000089-43.2012:** confirmar com o advogado a forma de encerramento no eproc.

## Limitações de verificação

- A consulta pública do eproc/JFES voltou a funcionar via navegador em nuvem (captcha Cloudflare resolvível) — atualizar a rotina de monitoramento, que a tratava como geo-bloqueada.
- O DataJud/CNJ fornece movimentos oficiais, mas não o texto das decisões nem valores de causa/CDA.
- O processo 5006055 tramita no PJe/TJES — peças exigem acesso de advogado.
