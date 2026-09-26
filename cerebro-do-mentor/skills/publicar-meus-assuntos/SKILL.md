---
name: publicar-meus-assuntos
description: Use quando o mentor quiser publicar sobre um assunto e o Estúdio não oferecer — "quero publicar sobre X", "meu tema não aparece", "por que X não virou tópico?", "o que falta para eu publicar sobre isso?" — ou quando ainda não declarou sobre o que quer publicar. Move a trilha dos assuntos declarados, no topo da Início do Console, assunto por assunto.
user-invocable: true
---

# Publicar sobre os seus assuntos

Este é o indicador que dá sentido aos outros: **quantos dos assuntos que o mentor
declarou o Estúdio oferece como tópico**. Sem declaração não há régua nenhuma.

⚠️ **Antes de tudo, a porta que não espera.** Qualquer assunto que ele domine já pode
virar publicação hoje: no Console, toda resposta do chat vira peça, com a prosa da própria
resposta. Aqui na conversa, `virar_conversa_em_peca` faz o mesmo numa chamada — custa a
consulta e o render, então a recusa traz o preço; pergunte com ele na mão. Diga isso na
mesma frase em que falar do que falta ao Estúdio. O resto desta skill leva semanas; isto
leva minutos.

## 1. Declarar

Chame `funil_do_estudio`. Se não houver assunto declarado, pergunte **sobre o que ele quer
publicar** — assuntos, com as palavras dele, não rótulos do acervo.

`marcar_assunto_alvo` **substitui a lista inteira**. Para somar um assunto, mande a lista
completa. Chame primeiro sem confirmar, mostre a prévia (o campo "Saem" mostra o que
cairia), e só grave depois do sim.

Declarar já faz uma coisa por ele: o assunto declarado fica **fixado** no Estúdio e passa
por cima dos termos que ele ocultou. Mas fixar **não cria massa** — um assunto sem
material suficiente continua fora.

## 2. Onde cada assunto parou

A resposta do funil diz a etapa de cada assunto declarado, de 1 a 5 — a mesma trilha que
o mentor vê no topo da Início do Console (Início › A trilha dos seus assuntos). Depois de
um gesto, é lá que ele confere onde o assunto está agora. Na linha de cada assunto há uma
gaveta com o detalhe: recorte a recorte, se ele já está no Estúdio; a distância até o piso,
se falta vizinho. É o mesmo número que o funil te devolve — mande-o abrir ali. Trate **um por vez**, e cada etapa
pede um gesto diferente:

| Etapa | O que quer dizer | O gesto |
|---|---|---|
| **1 · ausente do acervo** | Nenhum documento dele fala do assunto. Não é régua: é fonte que não existe. | Material **dele** sobre o assunto, carregado no Console. |
| **2 · falta vizinho** | Existe, mas aparece sozinho: não se cruza com outros assuntos nos mesmos trechos. | `o_que_falta_para` com o assunto — com o que já se cruza e que tipo de fonte fecha a lacuna. |
| **3 · rende peça** | Tem material de sobra e mesmo assim não chegou. Quem barra é a régua. | [[destravar-a-regua]] — **não** carregar mais. |
| **4 · virou tópico** | Chegou ao Estúdio, mas nenhum recorte se apoia em mais de um trecho. | [[firmar-recortes]] |
| **5 · recortes com lastro** | Chegou, e se sustenta. | Nada. Diga que chegou. |

⚠️ Se a etapa 4 vier como **"não medido"**, é incógnita, não reprovação: diga que não deu
para olhar os recortes dele agora.

## ⚠️ Que material fecha a lacuna — e qual não fecha

- **Serve:** conhecimento do próprio mentor em mais um documento — aula, artigo,
  transcrição, caso carregado no Console, **ou** texto que ele redigiu com você e enviou
  por `enviar_ao_acervo` (prepare-o antes com a skill `preparar-para-o-cerebro`). Os dois criam fatos **e** contam como segunda fonte. Ser escrito
  com IA não desconta nada: o que conta é o conhecimento ser dele (#1368).
- **Não serve:** reenviar uma resposta do próprio Cérebro. É **eco**: o servidor mede o
  conteúdo contra o que o Cérebro já produziu e deixa o eco fora do lastro — o assunto pode
  até aparecer, mas continua barrado pelo piso de documentos. Diga isso antes, ou ele manda
  o texto e acha que falhou.
- **Não serve:** `trazer_fonte`. A fonte entra como referência para conferir afirmações;
  ela **não gera fatos** e não move nada no Estúdio.

## O que não fazer

- **Não prometa que o material fecha a lacuna.** "Tende a fechar" é o mais forte que a
  leitura autoriza; depende do texto real e da extração.
- **Não declare por ele.** A lista é a intenção dele — sugerir assuntos a partir do
  acervo inverte a pergunta.
- **Não comemore 3 de 3** sem olhar a etapa: tópico sem recorte firme chega, mas chega
  fraco.

Explicação dos quatro números em [[qualidade]]; a ordem geral em [[cuidar-do-cerebro]].
