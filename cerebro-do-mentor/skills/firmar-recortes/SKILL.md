---
name: firmar-recortes
description: Use quando o mentor perguntar por recortes fracos ou estranhos no Estúdio — "os recortes não fazem sentido", "por que esse recorte aparece?", "meu tópico não tem recorte firme", "como melhoro os recortes com lastro?" — ou quando os indicadores "Recortes com lastro" ou "Tópicos com recorte firme" da página Qualidade estiverem ruins. Trabalha tópico a tópico, começando pelos assuntos que ele declarou.
user-invocable: true
---

# Firmar os recortes

Dois indicadores da Qualidade, uma alavanca só:

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
| Nenhum recorte | O tópico não aparece junto de mais nada | Não é defeito: o tópico gera a peça inteiro. Diga isso antes de propor qualquer gesto. |

4. Um tópico por vez, uma confirmação por gesto.

## ⚠️ O que sobe o número sem melhorar nada

- **Esconder recortes fracos** (`ajustar_recorte` com `esconder`) tira da conta os que têm
  um trecho só, e a porcentagem sobe. O tópico continua tão fino quanto antes. Esconda um
  recorte porque ele **não faz sentido** para o mentor — nunca por causa do placar.
- **Destilados por `enviar_ao_acervo`** criam trechos novos e podem firmar um recorte na
  conta. Mas são texto escrito com IA a partir do que ele já tem: não são segunda fonte.
  Se ele quiser usar, diga que o recorte vai parecer firme sem que haja mais de uma fonte
  por trás.
- **`trazer_fonte` não serve aqui.** A fonte entra só como referência para conferir
  afirmações e não gera fatos: nenhum recorte muda.

E um limite da própria régua, para quando ele perguntar: "dois trechos" podem ser dois
parágrafos do **mesmo** documento. Recorte firme quer dizer "não é coincidência de um
parágrafo" — não quer dizer "tem duas fontes".

## Quando parar

Se forem muitos tópicos, a conversa é o lugar errado: a seção **Recortes** da página
Qualidade mostra todos, do mais frágil ao mais firme, e o mentor escolhe ali quais valem o
esforço. A conversa é para decidir o que fazer com um tópico; a tela é para ver todos.

A explicação dos quatro números está em [[qualidade]].
