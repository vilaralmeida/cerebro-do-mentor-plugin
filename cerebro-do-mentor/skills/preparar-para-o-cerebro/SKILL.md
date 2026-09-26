---
name: preparar-para-o-cerebro
description: Use ANTES de `enviar_ao_acervo`, sempre que o mentor pedir para salvar, enviar ou carregar um texto no Cérebro — um artigo dele, uma anotação, o resumo de uma conversa. Reescreve o texto no formato que o Cérebro lê melhor (o assunto nomeado em cada parágrafo que trata dele, a ligação na mesma frase, as citações no fim), sem mudar o que o texto afirma nem apagar as ressalvas.
user-invocable: true
---

# Preparar um texto para o Cérebro

O Cérebro liga dois nomes quando eles aparecem **no mesmo trecho** do documento (um trecho
tem cerca de 1.200 caracteres). Ele não entende "ele", "o sistema", "essa percepção": se o
parágrafo não escreve o nome do assunto, para o Cérebro o assunto não está ali. Foi medido
num artigo real que citava o assunto em 1 de 8 trechos: a versão original ligou 1 das 22
coisas que o texto afirma; reescrita com estas regras, ligou 7 — as instituições que o
texto cita passaram de nenhuma para 4 de 7.

Esta versão é **a do acervo**, não a que o mentor publica. O Estúdio escreve as peças a partir
do que o Cérebro entendeu; o texto daqui é para ser bem entendido, não para ser bonito.

## As regras

1. **Descubra o assunto antes.** Pergunte ao mentor, se não estiver claro, qual é o assunto
   (ou os assuntos) do texto — de preferência um que ele já declarou (`temas_declarados`).
   Use o nome EXATO com que ele o declarou.
2. **O nome do assunto em cada parágrafo que trata dele.** Troque "ele", "o sistema", "essa
   percepção", "o fenômeno" pelo nome. Sinônimo que o texto usa para o assunto vira o nome,
   uma vez, junto do sinônimo: "a senciência de IA — a consciência de IA —".
3. ⚠️ **Parágrafo que NÃO trata do assunto não ganha o nome.** Um parágrafo sobre uma lei, uma
   fonte ou outro tema fica como está. Pôr o nome ali inventa uma ligação que o autor não fez
   — é o erro mais grave desta skill.
4. **A ligação na mesma frase.** Quando o texto relaciona o assunto a outra coisa, escreva os
   dois nomes na mesma frase: "A consciência de IA reduz a supervisão humana", e não "Isso
   reduz a supervisão".
5. **Nome completo e sigla** na primeira vez em cada parágrafo: "Organização Mundial da Saúde
   (OMS)". Depois, pode usar a sigla.
6. **Lista fica lista, numa frase que nomeia o assunto**: "O relatório coloca a consciência
   de IA ao lado de consentimento, transparência e privacidade." Não quebre a lista em
   frases repetidas — foi medido: o resultado é o mesmo, e as frases repetidas fizeram o
   Cérebro deixar de reconhecer alguns dos itens.
7. **A ressalva fica.** "Pode", "a hipótese é que", "segundo X", "é provável" continuam
   exatamente como estão. Nunca transforme hipótese em fato: o mentor publica a partir daqui.
8. **Citações no fim.** Autores, revista, ano, página e título de artigo vão para uma seção
   final "Fontes". No corpo, cite a instituição ou o documento pelo nome ("o artigo de 2025
   na npj Digital Medicine"), sem a lista de autores.
9. **Título na primeira linha**, com o nome do assunto, sem marcador (`#`). Sem títulos de
   seção soltos no meio: vire-os frase ("O efeito ELIZA é…").
10. **Um parágrafo por ideia**, até uns 800 caracteres.
11. **Nada novo, nada a menos.** Não acrescente conhecimento que o texto não tem, não resuma
    afirmações fora, não corrija o autor. Na dúvida sobre o que o autor quis dizer, pergunte.

## Antes de enviar

Mostre ao mentor a versão preparada e diga em uma frase o que mudou ("pus o nome do assunto
em 5 parágrafos e passei os autores para as fontes"). Só envie depois do sim dele, com
`enviar_ao_acervo(..., preparado=true)` — o Cérebro então sabe que o assunto já vem nomeado
onde é discutido, e não o espalha pelos parágrafos que não tratam dele.

Se ele disser "manda como está", envie o texto dele sem preparar, com `preparado=false`.

⚠️ O que esta skill NÃO resolve: um conceito que o Cérebro reconhece com pouca confiança
(ex.: "pareidolia") continua abaixo da régua mesmo no trecho certo. Preparar põe o nome no
lugar; não muda como o Cérebro o lê.
