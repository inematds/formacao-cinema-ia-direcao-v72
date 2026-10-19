# PLANO — Curso 0 · Direção: pensar como diretor antes de gerar

Formação Cinema com IA (curso 0 de 6), INEMA Learning v7.2, PT/EN/ES. Público: criadores, professores e quem faz vídeo para empresa; **sem terminal**. Escrito em 19/10/2026, antes do conteúdo.

**Como se prova a prática (cursos 0–2):** toda prática gera um arquivo de texto (cartão, escada, lista de movimentos, cartão de look, quadros, ficha, decupagem, storyboard) e quem confere é a **própria página**: seção `conferidor` (motor 7.9.12, `assets/v72-conferidor.js`, regras no JSON). O "pronto quando" cita a resposta literal da página (`OK: …`). Ensaio sem custo = botão "Exemplo que passa" (e "Exemplo com erro" para ver o que a página recusa). Opção para quem tem terminal: `python3 conferir.py <aula> arquivo.txt` (mesmas regras). Nenhuma prática gera vídeo nem gasta crédito: o curso 0 entrega o plano; gerar é do curso 1.

**Exemplo que atravessa o curso:** "A primeira fornada" — Dona Lia (personagem fictícia, 58 anos) abre a padaria do bairro às 4h50; primeira fornada; o primeiro cliente bate na porta de ferro. Cena de 30 s.

## As 8 aulas

| # | slug | título | objetivo (≤160) | diagrama | prática → "pronto quando" |
|---|---|---|---|---|---|
| 1 | diretor | O diretor e a máquina: o que a IA faz e o que continua sendo seu | separar o que você decide do que a IA executa e preencher o cartão do diretor de uma cena antes de gerar qualquer coisa. | fluxo de 2026: intenção → imagem-chave → vídeo com áudio → montagem → rótulo (quem decide em cada etapa) | cartao.txt → página: `OK: cartão com 8 campos preenchidos`; pasta do projeto fora da plataforma |
| 2 | plano | Plano, ângulo e distância: a gramática que todo gerador entende | escolher tamanho de plano e ângulo pela emoção do público e escrever a escada de planos da cena nos termos do gerador. | escada de 6 tamanhos (geral → detalhe) | escada.txt → `OK: 6 planos com tamanho e ângulo variados` |
| 3 | camera | A câmera como verbo: cada movimento conta uma coisa | escolher um movimento por plano pela intenção e escrever, para cada plano, o efeito que ele causa em quem assiste. | 6 intenções → movimento (aproximar, afastar, acompanhar, revelar, girar, tremer) | movimentos.txt → `OK: 6 planos, um movimento cada, com o efeito escrito` |
| 4 | luz | Luz, cor e atmosfera: o look decidido antes do prompt | decidir fonte, direção, qualidade, temperatura e atmosfera da luz da sua cena e escrever o cartão de look que vai em todo prompt. | fonte → direção → qualidade → temperatura e contraste → atmosfera | look.txt → `OK: cartão de look com 7 campos` |
| 5 | composicao | Composição e profundidade no quadro | compor cada quadro com um assunto que se entende em um segundo e três camadas de profundidade separadas por foco, luz ou cor. | assunto → terços/centro → linhas e diagonal → espaço negativo → três camadas | quadros.txt → `OK: 4 quadros com composição e três camadas` |
| 6 | ficha | Personagem, figurino e ambiente: a ficha que segura a consistência | escrever a ficha do personagem e do ambiente que você vai reaproveitar como referência em todos os planos, sem imitar pessoa real. | identidade → figurino → objeto → ambiente → trava → referências | ficha.txt → `OK: ficha com 10 campos preenchidos` |
| 7 | decupagem | Do roteiro à decupagem: lista de planos com som e fala | transformar uma cena escrita numa decupagem numerada com tamanho, ângulo, movimento, som e duração de cada plano. | roteiro → arco → planos → câmera → som → tempo | decupagem.txt → `OK: 6 planos com tamanho, ângulo, movimento e som · 20 s` |
| 8 | storyboard | Seu storyboard: uma cena de 30 s decupada e conferida | juntar cartão, ficha, look e decupagem num storyboard de 30 s conferido pela página, pronto para virar prompt. | mapa da formação (4 degraus) + gerador de plano com datas | storyboard.txt → `OK: storyboard com 8 planos conferidos · 30 s`; pasta com os 4 arquivos |

Cada aula: diagrama primeiro, passos curtos, bloco com copiar (modelo do arquivo), conferidor, prática, teste de 3–5 perguntas comentadas, resumo, links. A aula 8 fecha com `mapa` (4 degraus: cartão, movimento, ficha, decupagem) + `gerador` (as 8 aulas) e aponta, em `links`, para o curso seguinte: `https://inematds.github.io/formacao-cinema-ia-geracao-v72/` (curso 1, ainda não publicado em 19/10/2026).

Donos de assunto (CURRICULO): este curso é dono de plano, ângulo, movimento, luz, composição, ficha (o que é) e decupagem/storyboard. Não ensina gerador, versão nem anatomia de prompt (curso 1), nem som/trilha/montagem/ética a fundo (curso 2): aponta por link.

## Novo / atualizado em relação aos cursos antigos (idallai, aifilmmaking, ai-filmaking-p1, fpfilm1)

Conferido contra AUDITORIA-LOCAL.md e PESQUISA-ESTADO-DA-ARTE.md (19/10/2026).

- **Aula 1 — atualizado:** o "conjunto de ferramentas" fixo dos antigos (Freepik/Magnific Spaces, Seedance, Kling, Luma, Runway, Midjourney com função fixa) sai; entra o **pipeline de 2026** (imagem-chave → vídeo com áudio nativo → montagem → rótulo, §2 e §9). Áudio nativo como padrão de 2026 com exemplo datado (Veo 3.1, Kling 3.0, Seedance 2.x, Runway Gen-4.5, out/2026, §2). **Novo:** portabilidade com o caso Sora como estudo de caso (app fechado em 26/04/2026, API em 24/09/2026, §1) → guardar roteiro, referências e prompts fora da plataforma. Mantido dos antigos: "IA executa, não cria intenção", âncora (filme/anúncio/clipe), as 4 perguntas.
- **Aula 2 — atualizado:** vocabulário de plano, ângulo e lente alinhado ao **guia oficial de prompt de vídeo do Google (Veo e Gemini Omni Flash, página atualizada em 15/10/2026)**, incluindo o aviso oficial de que alguns ângulos avançados não são suportados oficialmente (§2, §7). Mantido: escada do estabelecimento ao detalhe e regra de decisão (aifilmmaking 4.4).
- **Aula 3 — reescrito:** "um movimento por plano", dolly × zoom × dolly zoom, estilo (steadicam/handheld/câmera lenta), não repetir movimento vizinho (skill mdd, biblioteca de tomadas). **Novo:** o conferidor reprova plano com dois movimentos (o "não empilhe" vira regra verificável). Termos alinhados aos movimentos do guia oficial (static, pan, tilt, dolly, truck, pedestal, zoom, crane, aerial, handheld).
- **Aula 4 — reescrito:** luz motivada, tirar luz (negative fill), recorte, quente × frio, névoa e camadas (aifilmmaking 4.2, fpfilm1 1.4). **Novo:** cartão de look fixo que entra em todo prompt; termos de luz do guia oficial (high-key, low-key, rembrandt, contraluz, luz volumétrica).
- **Aula 5 — reescrito:** teste de um segundo, terços × centro × diagonal, espaço negativo, três camadas, profundidade de campo, grande-angular × tele (aifilmmaking 1.3, 4.1, 4.3).
- **Aula 6 — novo:** ficha pensada para **referência por várias imagens** (§2): Veo 3.1 "Ingredients" com até 3 imagens de referência e Seedance 2.5 com até 30 imagens, 10 vídeos e 10 áudios (exemplos datados, out/2026); "elements" do Kling citado como relatado, não confirmado ([incerto]). Princípio sem plataforma: aparência de um lado, composição do outro (os antigos ensinavam como mecânica do Freepik, "@sketch/@character"). Personagem fictício; avatar só da própria pessoa, com consentimento (ética a fundo no curso 2).
- **Aula 7 — novo:** **coluna de som por plano** (ambiente, efeito, fala), porque o áudio agora sai junto com o vídeo (§2); o guia oficial recomenda descrever o áudio em frases separadas no prompt. Mantido: arco em três atos e último quadro forte (fpfilm1 1.3), subtexto e silêncio na fala (aifilmmaking 3.1).
- **Aula 8 — atualizado:** o storyboard deixa de ser "grade 2×3 gerada no Freepik" e vira arquivo de texto conferido pela página, portátil para qualquer gerador; mapa + gerador de plano; ponte para o curso 1 (prompts a partir da decupagem).

## Deixado de fora (desatualizado, sem fonte ou [incerto])
- Seedance 2.0 e "controle por YAML no Seedance 2" (aifilmmaking): superado pelo 2.5 (§1); controle por plano é assunto do curso 1.
- Kling "controle de câmera" de 2025, Luma/Runway sem versão (ai-filmaking-p1): versões são do curso 1.
- "Recursos do Freepik abril/2026", Spaces, nós e @referências como passo fixo (fpfilm1, aifilmmaking 2.x).
- "Regra de Murch: o som é 50%" e "o impacto cai 70–80% sem som" (fpfilm1 1.5): sem fonte primária na pesquisa; não entra.
- "Regra 80/20 da luz" (aifilmmaking 4.2): número sem fonte; entra só o princípio (tirar luz cria profundidade).
- Kling com 30 s, multishot de 6 cortes, Hailuo H3, Veo 4: [incerto] ou inexistente; não entram.
- Sora como ferramenta: só estudo de caso (aula 1).
- Exemplos com marca ou de terceiros (samurai, muscle car pós-apocalíptico dos antigos): trocados pelo exemplo próprio "A primeira fornada".
