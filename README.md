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

O que **não** vem sozinho é o plugin em si — as habilidades e os atalhos. E como você
recebe uma versão nova dele **depende de como ele chegou até você**. São duas formas, e o
mesmo comando não serve para as duas.

Para descobrir qual é a sua:

```
claude plugin list
```

A linha do *Cérebro do Mentor* mostra a origem.

### Se você mesmo adicionou o marketplace

O Claude guarda uma **cópia do catálogo** na sua máquina, e `update` consulta essa cópia —
não o repositório. Então são dois passos, nesta ordem:

```
claude plugin marketplace update cerebro-do-mentor
claude plugin update cerebro-do-mentor@cerebro-do-mentor
```

⚠️ **Pular o primeiro é o engano mais comum.** O segundo sozinho compara a sua versão com
um catálogo velho, conclui que não há nada novo, e não avisa que só olhou a cópia.

Na interface é o mesmo caminho: atualize o **marketplace** e depois o plugin, em
`/plugin`.

### Se ele chegou pelas configurações da sua conta

Aqui você **não atualiza à mão**: o plugin é empacotado e entregue pela sincronização da
conta, e a versão nova chega quando ela roda. `update` não força isso.

Para saber o que você tem hoje, o `claude plugin list` mostra a versão instalada; a data
da última sincronização fica no `manifest.json` da pasta sincronizada.

⚠️ **Se a versão instalada estiver atrás desta e não avançar**, a sincronização é o lugar
a olhar — não o plugin. Enquanto isso, dá para receber as versões novas adicionando o
marketplace por conta própria (a seção acima), desde que você **desinstale antes a cópia
sincronizada**: com as duas ao mesmo tempo, as habilidades aparecem duplicadas e não há
como saber qual está valendo.

## O que ele traz

- **Habilidades** — o método de cuidar do Cérebro: a ordem dos gestos, os três tempos em
  que cada um vale, e quando é melhor usar o Console em vez da conversa.
- **`/roteiro`, `/o-que-mudou`, `/higienizar`** — atalhos para os começos de conversa mais
  comuns.
- **Conector** — as ferramentas do Cérebro (consultar, enviar ao acervo, diagnosticar a
  nota, reunir, podar, e as demais).
- **Medida de publicabilidade** — quais assuntos do seu acervo já rendem uma peça
  inteira, quanto falta para os que não rendem, o que cada carga de material rendeu de
  fato, e de onde saiu cada peça que você gerou.

## ⚠️ O primeiro gesto de escrita pode pedir um token novo

As ferramentas que **escrevem** na ontologia exigem o escopo `ontologia:write`, que não é
retroativo. Se você já tinha um token antigo, gere um novo em **Configuração › Tokens de
acesso** no Console, ou reconecte pelo celular.

## Confiança

Este plugin instala um conector que fala com o servidor do Cérebro do Mentor. Ele lê e
escreve **no seu acervo**, sempre com a sua confirmação. O código é mantido em repositório
privado e este repositório é um espelho publicado a cada versão.
