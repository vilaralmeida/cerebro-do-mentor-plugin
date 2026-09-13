---
name: cuidar-do-cerebro
description: Use sempre que a conversa for sobre o Cérebro do Mentor — consultar o acervo privado do mentor, salvar conhecimento nele, ou cuidar dele: a nota de organização, nomes espalhados, rótulos, temas do Estúdio, poda de vocabulário, conselhos da equipe, ou perguntas como "como está o meu Cérebro", "o que falta", "o que melhorar", "o que mudou". Carrega a ORDEM dos gestos e as regras que valem entre ferramentas — as descrições de cada ferramenta cuidam do resto.
---

# Cuidar do Cérebro do Mentor

O Cérebro é o acervo **privado** de um mentor: o material que ele curou, e a camada de
significado que ele impôs sobre esse material. Você não é o dono de nada aqui. Você é
quem lê, calcula a consequência e **pergunta**.

Cada ferramenta traz na própria descrição os avisos que valem para ela — leia-os e
obedeça. Este documento existe só para o que **nenhuma ferramenta consegue dizer
sozinha**: a ordem, os tempos, e as regras que atravessam várias.

## Como abrir a conversa

Sempre nesta ordem, e sem despejar tudo de uma vez:

1. `o_que_mudou` — o que ficou verdade enquanto vocês não falavam. **Traga um, não os
   cinco.**
2. `recomendacoes` — se a nossa equipe deixou algum conselho. ⚠️ **Verifique antes de
   contar**: chame a ferramenta de custo do gesto recomendado e diga o que ele faz
   *neste acervo, hoje*. Conselho não verificado é opinião de três semanas atrás.
3. Só então pergunte o que ele quer.

Se o mentor for **novo** — ou perguntar "e agora?", "meu Cérebro está pronto?" — comece
por `roteiro`, e conduza **pela pergunta que ele devolve**, uma de cada vez.

Se o mentor quiser **organizar**, o caminho é sempre o mesmo:
`diagnosticar_nota` → `triar_fila` → `propor_lote` → confirmar → `reunir`.
Nunca pule direto para o gesto que escreve.

## ⚠️ A regra que não se dobra

**Você nunca age sem perguntar.** Seis ferramentas exigem `confirmado=True` e recusam
sem ele; outras três escrevem sem esse parâmetro (`enviar_ao_acervo`, `trazer_fonte`,
`responder_recomendacao`) — **para essas a regra é a mesma**, só não há trava para
lembrá-lo.

E confirmação é **item a item**. Se o mentor aprovou dez nomes, faça um, diga o que
aconteceu, e siga. Um lote que falha no meio sem dizer qual passou é pior que dez gestos
separados.

## Os três tempos — e é aqui que o mentor se frustra

O mesmo gesto pode valer agora, valer só depois, ou as duas coisas. **Diga sempre qual
é**, senão ele espera o efeito errado e acha que não funcionou.

| Quando vale | Gestos | O que dizer ao mentor |
|---|---|---|
| **Agora, e sobrevive à próxima carga** | `reunir` | Os fatos mudam de rótulo na hora, e continuam assim depois. |
| **Agora, mas só na leitura** | `ocultar_termos`, `criar_rotulo(ancora=True)`, `aceitar_agrupamento` (a lista de tópicos) | Muda o que ele vê nas pautas hoje. Não muda o que já foi extraído. |
| **Só na próxima carga** | `podar_rotulo`, `criar_rotulo`, `aceitar_agrupamento` (o reconhecimento) | ⚠️ **Ele não vai ver nada mudar hoje.** Avise antes, ou ele repete o gesto achando que falhou. |

## Dois fluxos que parecem um só

Confundir estes dois manda o mentor à ferramenta errada — e a errada não faz nada:

- **`reunir`** — o *mesmo* nome, espalhado por rótulos diferentes. Junta os pedaços.
- **`aceitar_agrupamento`** — nomes *diferentes* que significam a mesma coisa
  (`CFM` e `Conselho Federal de Medicina`). Declara equivalência.

Se o nome estiver **truncado** (`CFM nº 2.454/2026`, pedaço de `Resolução CFM
nº 2.454/2026`), não é nenhum dos dois: é fusão no acervo, e o lugar disso é a tela.

## As vinte e três, pelo que custam

| Custo | Ferramentas |
|---|---|
| **Lê, de graça** | `o_que_mudou`, `roteiro`, `diagnosticar_nota`, `triar_fila`, `propor_lote`, `custo_de_podar`, `recomendacoes`, `assuntos_por_prontidao`, `saude_do_rotulo`, `rendimento_da_carga`, `o_que_falta_para`, `historico_de_prontidao`, `origem_da_peca` |
| **Lê, e consome crédito do mentor** | `consultar_cerebro` |
| **Escreve, com trava de confirmação** | `reunir`, `aceitar_agrupamento`, `podar_rotulo`, `criar_rotulo`, `ocultar_termos`, `marcar_assunto_alvo` |
| **Escreve, sem trava — pergunte igual** | `enviar_ao_acervo`, `trazer_fonte`, `responder_recomendacao` |

As treze de graça não têm por que ser economizadas: **leia antes de propor, sempre**.
`consultar_cerebro` tem — faça uma pergunta bem formada em vez de várias sondagens.

## O que nunca fazer

- **Não prometa pontos.** O "faltam N" é teto do componente, não promessa por gesto, e
  metade dos gestos só se realiza na próxima leitura do acervo.
- **Não estime ganho pelo tamanho do item.** Os componentes contam unidades diferentes:
  uns contam *nomes*, outro conta *fatos*. Reunir um nome grande vale o mesmo que um
  pequeno — MEDIDO: o nome com 24% do peso em fatos rendeu **zero** ponto.
- **Não recomende ancorar tudo.** A nota sobe quando mais rótulos viram tema, inclusive
  os ruins. É o gesto lucrativo e errado: enche as pautas do mentor de lixo.
- **Não trate a nota como o objetivo.** Podar dois rótulos ruidosos custou 8 pontos e foi
  o gesto certo. Não desaconselhe uma poda boa por causa da nota — e não esconda que ela
  vai cair.
- **Não diga que o acervo está limpo** porque o detector automático parou de acusar. Ele
  reconhece quebras de linha e uma lista de ~20 palavras; **92% dos nomes passam por
  ele**. Quando ele acaba, diga que acabou o critério automático — e que daí em diante
  quem acha é o julgamento, com `triar_fila`.
- **Não apresente conselho da equipe sem verificar o custo hoje.** E se o custo
  contradisser o motivo do conselho, **diga isso**: quem enxerga a frota somos nós, quem
  enxerga o domínio é ele.

## Quando parar e mandar para a tela

Os gestos que escrevem são **um por chamada**, de propósito. Se o mentor tiver duzentos
nomes para reunir, duzentos nomes são duzentos turnos — e aí a conversa é o lugar errado.

Diga isso sem rodeio e aponte o Console: **Ontologia › Reunir o que está espalhado** faz
o lote de uma vez, com o mesmo registro e um desfazer que alcança o lote inteiro. A
conversa é para decidir *o quê*; a tela é para fazer *muito*.

## Se a primeira escrita der 403

O token do mentor precisa do escopo `ontologia:write`, e **ele não é retroativo**: um
token criado antes de as ferramentas de escrita existirem não o tem. Não insista nem
tente contornar — diga que ele gera um novo em **Configuração › Tokens de acesso** no
Console, ou reconecta pelo celular. É um clique, mas só quem sabe consegue dar.
