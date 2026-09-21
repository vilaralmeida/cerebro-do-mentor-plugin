---
name: destravar-a-regua
description: Use quando o mentor perguntar por assuntos que têm material e não aparecem no Estúdio — "por que X não aparece se eu falo tanto disso?", "o que são os barrados?", "rendem peça e não chegam à tela", "afrouxar a régua", "mostrar um termo que eu ocultei" — ou quando o indicador "Rendem peça e não chegam à tela" da página Qualidade estiver alto. Separa o que é régua do que é falta de material, e nunca manda carregar mais.
user-invocable: true
---

# Destravar a régua

Este indicador conta assuntos que **já têm material de sobra** e mesmo assim não estão
na lista de tópicos do Estúdio. Quem os barra é a régua, nunca o acervo.

⚠️ **A regra desta skill: não aconselhe carregar material.** É o conselho que "não
aparece" sugere, e aqui ele é o errado — o mentor compraria material para resolver
configuração, e o número não mexeria.

⚠️ **E a régua existe por um motivo.** Ela esconde o que é eco: um assunto citado em
muitos lugares, mas sempre de passagem. Número alto aqui não é problema por si. A pergunta
certa não é "como zero isso?", é **"algum destes é assunto que você queria ver?"**

## O caminho

1. `funil_do_estudio` — a resposta traz o número, exemplos pelo nome e, separados, os que
   estão na lista de termos que **o próprio mentor ocultou**.
2. Mostre os exemplos e pergunte quais ele quer no Estúdio. Os que ele não reconhecer
   como assunto dele ficam onde estão.
3. Para cada um que ele quiser, o gesto depende do motivo:

| Motivo | Como saber | O gesto |
|---|---|---|
| **Ele mesmo ocultou** | Aparece na lista de ocultados da resposta | Declarar como assunto (`marcar_assunto_alvo`) fixa o assunto e passa por cima da lista. Ou tirá-lo da lista no Console, em Ontologia. |
| **Um piso** (vizinhos, documentos, frequência) | Os demais — a leitura não diz qual | Declarar como assunto (`marcar_assunto_alvo`) passa pelos pisos de vizinhos e de documentos. Não passa pelo piso de frequência: esse só muda em Ontologia › **Quais assuntos viram tópico**. |

⚠️ `marcar_assunto_alvo` **substitui a lista inteira** de assuntos declarados. Para somar
um assunto, mande a lista atual mais o novo — mostre a prévia e confirme antes. Detalhes em
[[publicar-meus-assuntos]].

⚠️ Tirar da lista de ocultos é **condição, não garantia**: se um piso também barrar o
assunto, ele continua fora. Diga isso antes, ou ele desfaz a ocultação e acha que não
funcionou.

## Declarar ou afrouxar?

- **Declarar** age sobre **um** assunto, o que ele escolheu. É o gesto certo quase sempre.
- **Afrouxar um piso** (no Console) age sobre **todos**: traz o assunto que ele quer junto
  com todo o eco que a régua segurava. Se ele quiser afrouxar, diga isso com esse nome — e
  que a série da página Qualidade deixa de ser comparável no dia em que a régua muda.

Pelo plugin não há como afrouxar piso nem tirar termo da lista de ocultos: os dois só
existem no Console. Não tente contornar com outra ferramenta — `ocultar_termos` só
**acrescenta** à lista.

## O que dizer quando ele perguntar "por que está barrado?"

Se o assunto está entre os ocultados, diga isso pelo nome. Se não está, diga que é um dos
pisos e que a leitura não aponta qual — **não chute**. O que dá para afirmar é o que não é:
não é falta de material.

A explicação dos quatro números está em [[qualidade]]; a ordem geral em
[[cuidar-do-cerebro]].
