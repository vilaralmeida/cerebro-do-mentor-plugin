---
name: publicar-meus-assuntos
description: Use quando o mentor quiser publicar sobre um assunto e o Estúdio não oferecer — "quero publicar sobre X", "meu tema não aparece", "por que X não virou tópico?", "o que falta para eu publicar sobre isso?" — ou quando ainda não declarou sobre o que quer publicar. Move o indicador "Assuntos que você declarou" da página Qualidade, assunto por assunto.
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

A resposta do funil diz a etapa de cada assunto declarado, de 1 a 5. Trate **um por vez**,
e cada etapa pede um gesto diferente:

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

- **Serve:** documento do próprio mentor (aula, artigo, transcrição, caso) carregado no
  Console. É o único que cria fatos **e** conta como segunda fonte.
- **Ajuda pouco:** texto destilado por `enviar_ao_acervo`. Ele cria fatos e pode fazer o
  assunto aparecer, mas **não conta como lastro** — o assunto pode passar a render e parar
  barrado pelo piso de documentos. Diga isso antes, ou ele manda o texto e acha que falhou.
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
