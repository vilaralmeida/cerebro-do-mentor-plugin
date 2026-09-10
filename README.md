# Cérebro do Mentor — plugin para o Claude

Converse com o seu **Cérebro do Mentor** e cuide dele dentro do Claude: veja o que mudou
no acervo, entenda a nota de organização, reúna nomes espalhados, pode o vocabulário e
responda aos conselhos da nossa equipe. **Nada é escrito sem você confirmar.**

## Instalar

```
/plugin marketplace add vilaralmeida/cerebro-do-mentor-plugin
/plugin install cerebro-do-mentor@cerebro-do-mentor
```

Depois de instalar, conecte o servidor quando o Claude pedir — a autorização é de um
clique (OAuth) e não pede que você copie token nenhum.

## Como atualizar

⚠️ **As ferramentas do Cérebro se atualizam sozinhas.** Elas vivem no servidor, não no
plugin: quando melhoramos uma delas, você recebe na próxima conversa, sem fazer nada.

O que **não** vem sozinho é o plugin em si (as habilidades e os atalhos), quando sai uma
versão nova dele. Para pegá-la:

```
/plugin
```

Vá em **Installed**, escolha o *Cérebro do Mentor* e clique em **Update**. Pelo terminal,
o equivalente é `claude plugin update cerebro-do-mentor@cerebro-do-mentor`; para ver qual
versão você tem, `claude plugin list`.

## O que ele traz

- **Habilidades** — o método de cuidar do Cérebro: a ordem dos gestos, os três tempos em
  que cada um vale, e quando é melhor usar o Console em vez da conversa.
- **`/roteiro`, `/o-que-mudou`, `/higienizar`** — atalhos para os começos de conversa mais
  comuns.
- **Conector** — as ferramentas do Cérebro (consultar, enviar ao acervo, diagnosticar a
  nota, reunir, podar, e as demais).

## ⚠️ O primeiro gesto de escrita pode pedir um token novo

As ferramentas que **escrevem** na ontologia exigem o escopo `ontologia:write`, que não é
retroativo. Se você já tinha um token antigo, gere um novo em **Configuração › Tokens de
acesso** no Console, ou reconecte pelo celular.

## Confiança

Este plugin instala um conector que fala com o servidor do Cérebro do Mentor. Ele lê e
escreve **no seu acervo**, sempre com a sua confirmação. O código é mantido em repositório
privado e este repositório é um espelho publicado a cada versão.
