# REVISÃO independente — formacao-cinema-ia-direcao-v72 (19/10/2026)

Revisor: subagente que não escreveu o curso, com BRIEF-CURSO, CURRICULO, AUDITORIA-LOCAL e PESQUISA-ESTADO-DA-ARTE (longrun 2026-10-19-formacao-cinema-ia-v72). Só leitura; rodou `conferir.py --exemplo/--errado` nas 8 aulas e ~25 casos à mão; abriu o guia oficial de prompt do Google (atualizado em 15/10/2026) e confirmou o que o curso cita.

## Rodada 1 — 7,5/10
O que estava bom: nenhuma versão desatualizada (Sora só como estudo de caso); datas do Sora, Veo 3.1 (3 referências), Seedance 2.5 (30/10/10) e AI Act (02/08/2026) batem com a pesquisa; "elements" do Kling dito como relatado; exemplo próprio ("A primeira fornada"), sem marca de terceiros; links para os donos de assunto certos; quizzes coerentes.

Graves:
1. Aula 1: o conferidor só aceitava filme/anúncio/clipe; "videoaula", "reels", "institucional" (o próprio público) eram recusados.
2. Conferidores aceitavam coluna vazia (`efeito:`, `som:`), ao contrário do que o texto prometia.
3. Afirmações sem fonte ditas como fato nos leads das aulas 2, 3 e 6 e no passo 3 da aula 6.

Menores: rack focus como movimento; holandês como composição; "contraplongée"/"ângulo normal" não reconhecidos; "pedestal" na descrição contava como movimento; "2 s" na descrição entrava na soma; ficha recusava "Idade: 34"; arco atribuído a "cursos de cinema"; prática da ficha com produto estranha; vizinhos repetidos não conferidos; timecode "00:03" não lido.

## Correções
- Aula 1: formatos aula/videoaula/tutorial, institucional, reels/short/vídeo curto.
- Motor 7.11.14 (`conferir.py` e `v72-conferidor.js`): grupo-rótulo com `min` (som:, efeito:, frente:/meio:/fundo: vazios recusados); duração lida primeiro da coluna `N s`.
- Leads e passo da aula 6 suavizados ("pesa muito", "um dos erros mais visíveis", "pode levar").
- Rack focus fora dos movimentos e da tabela; holandês fora da composição; "contraplongée", "ângulo normal" e "pedestal up/down"; ficha e camadas com mínimo de 2 caracteres; "convenção dos três atos"; prática da ficha com produto reescrita.
- Depois da tradução: famílias de termos trilíngues e `termos` fora do tradutor (motor 7.11.15); "pan" solto removido (em espanhol "pan" é pão).

## Rodada 2 — 8,5/10
Os três graves conferidos como corrigidos; menores corrigidos. Pendentes (menores, aceitos): vizinhos com o mesmo movimento não são conferidos pela página (o exercício e2 da aula 3 cobre por leitura); timecode "00:03" não é lido como duração.

NOTA: 8,5/10
