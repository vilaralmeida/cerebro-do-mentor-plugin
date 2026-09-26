---
name: firmar-recortes
description: Use quando o mentor perguntar por recortes fracos ou estranhos no Estúdio — "os recortes não fazem sentido", "por que esse recorte aparece?", "meu tópico não tem recorte firme", "como melhoro os recortes com lastro?" — ou quando os indicadores "Recortes com lastro" ou "Tópicos com recorte firme" estiverem ruins, ou acender na Início o alerta de recorte firme ou de pouco material. Trabalha tópico a tópico, começando pelos assuntos que ele declarou.
user-invocable: true
---

# Firmar os recortes

Dois indicadores do placar, uma alavanca só — e um alerta só na Início:

- **Recortes com lastro** — de todos os recortes que o Estúdio oferece, quantos aparecem
  junto do tópico em dois ou mais trechos diferentes.
- **Tópicos com recorte firme** — quantos tópicos têm pelo menos um desses.

O segundo é o que aponta o trabalho: a média do primeiro pode subir sem que nenhum tópico
fraco melhore. **Trabalhe pelos nomes, não pela porcentagem.**

## O caminho

1. `funil_do_estudio` — a resposta nomeia os tópicos **sem nenhum** recorte firme e marca
   os que são assunto declarado. **Comece por esses**: é a peça que ele mais quer, saindo
   apoiada num parágrafo só. Sem assunto declarado, pergunte se ele quer declarar antes
   ([[publicar-meus-assuntos]]) — senão você vai firmar tópicos que ele não pretende usar.
2. Escolha **um** tópico com ele e chame `recortes_do_topico`: quais recortes o Estúdio
   oferece e em quantos trechos cada um se apoia.
3. Leia a causa antes do gesto:

| O que você vê | O que quer dizer | O gesto |
|---|---|---|
| Recortes com 1 trecho cada, vindos do mesmo documento | O tema tem pouco material dele | Mais material **dele** sobre o tema, carregado no Console. `o_que_falta_para` com o tópico diz com o que ele já se cruza e de que documentos veio cada vizinho. |
| O mesmo tema sob grafias diferentes (`CFM` e `Conselho Federal de Medicina`) | Os trechos se dividem entre as grafias, e nenhuma alcança dois | `temas_declarados` para ver o que já existe → `aceitar_agrupamento`. Diga **quando** vale: ver os tempos em [[cuidar-do-cerebro]]. |
| Um recorte que o mentor reconhece como o ângulo certo, e que não aparece | Ele existe no acervo mas não está entre os mais frequentes | `ajustar_recorte` com `acrescentar` ou `fixar` — só aceita nome que existe no acervo e aparece junto do tópico. |
| **Recortes a confirmar** na resposta | Cruzam o tópico, mas em menos trechos que o piso | Os candidatos que a régua barrou. Veja a seção abaixo. |
| Nenhum recorte | O tópico não aparece junto de mais nada | Não é defeito: o tópico gera a peça inteiro. Diga isso antes de propor qualquer gesto. |

4. Um tópico por vez, uma confirmação por gesto.

## Os recortes a confirmar

Quando o tópico é tratado em documentos focados — um arquivo por ângulo —, os ângulos
cruzam o tópico pouco, e a régua os barra. Eles vêm na resposta de `recortes_do_topico`
como **Recortes a confirmar**, com o número de trechos de cada um. No Estúdio, a mesma
lista tem o mesmo nome e um botão **Confirmar** por candidato; o título do painel diz
quantos são, mesmo fechado. E quando o tópico é um assunto que ele declarou, a Início
acende um alerta "«tópico» tem N recortes a confirmar" que abre o Estúdio já com a lista
à vista — se ele chegar por esse alerta, é esta a conversa. Na trilha da Início, a gaveta
do assunto mostra os mesmos recortes, firmes e candidatos, com o número de trechos de cada.

Leia a lista com o mentor, um candidato por vez, com três perguntas:

1. **Dá uma peça?** Um post sobre «tópico» visto por este ângulo — ele escreveria?
2. **É o próprio assunto com outra grafia?** (`CFM` num tópico que já é o Conselho) — aí
   não é recorte, é grafia a reunir.
3. **É só uma citação?** Nome de lei, autor ou instituição mencionado de passagem não
   sustenta uma peça.

O que passa nas três vira recorte com `ajustar_recorte` e `acao="acrescentar"` — o mesmo
gesto do botão **Confirmar** — com `confirmado=True` depois de ele dizer sim àquele nome.

⚠️ **Nunca baixe o piso por causa desta lista.** A régua vale para todos os tópicos; o
problema é deste. Baixar o piso firmaria de uma vez os candidatos de todos os outros
tópicos, inclusive os que são coincidência.

⚠️ **Não chame isto de "quase lá".** No Console, "Quase lá" é outra coisa: assunto a um
vizinho de virar tópico. Use o nome que a tela usa: **recortes a confirmar**.

## ⚠️ O que sobe o número sem melhorar nada

- **Esconder recortes fracos** (`ajustar_recorte` com `esconder`) tira da conta os que têm
  um trecho só, e a porcentagem sobe. O tópico continua tão fino quanto antes. Esconda um
  recorte porque ele **não faz sentido** para o mentor — nunca por causa do placar.
- **Textos por `enviar_ao_acervo`** criam trechos novos e firmam um recorte **quando
  trazem conhecimento dele** — redigido com IA ou não. ⚠️ Mas se você montar o texto a
  partir de respostas do próprio Cérebro, é eco: o recorte parece firme sem fonte nova por
  trás. Não faça isso para mexer no placar.
- **`trazer_fonte` não serve aqui.** A fonte entra só como referência para conferir
  afirmações e não gera fatos: nenhum recorte muda.

## Duas réguas para "aparecer junto"

O Cérebro conta "aparecer junto no mesmo trecho" com duas réguas de confiança, de
propósito: **vizinhos** — e o zoom de `o_que_falta_para` — contam com **confiança ≥ 0,7**,
e com **≥ 0,5 nos assuntos que o mentor declarou** (alvos, fixados, temas de interesse);
**recortes** contam com **confiança ≥ 0,5**. Declarar um assunto, portanto, também afina a
régua dele — o zoom diz qual régua usou. O mesmo par pode sair "1 trecho" no zoom e
"2 trechos" nos recortes. Não é erro, e não é o acervo mudando entre uma leitura e outra:
as duas respostas dizem a régua que usaram. Se o mentor estranhar, explique isso antes
de qualquer gesto — e nunca some ou compare os dois números como se fossem a mesma conta.

E um limite da própria régua, para quando ele perguntar: "dois trechos" podem ser dois
parágrafos do **mesmo** documento. Recorte firme quer dizer "não é coincidência de um
parágrafo" — não quer dizer "tem duas fontes".

## Quando parar

Se forem muitos tópicos, a conversa é o lugar errado. Para os assuntos que ele declarou,
a gaveta de cada um, na trilha da Início, mostra recorte a recorte; o alerta "Ver recorte a
recorte" leva direto a ela. Para o acervo inteiro — inclusive o que ele não declarou —, a
lista do mais frágil ao mais firme continua no endereço `/qualidade` do Console, fora do
menu. A conversa é para decidir o que fazer com um tópico; a tela é para ver todos.

A explicação dos quatro números está em [[qualidade]].
