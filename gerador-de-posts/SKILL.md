---
name: gerador-de-posts
description: Transforma uma ideia, anotação, link, experiência ou texto bruto em posts prontos para LinkedIn, Instagram, X/Twitter e Threads, em português e no estilo pessoal do usuário (definido em perfil.md). Entrega 3 variações com ângulos diferentes por rede. Use sempre que o usuário quiser escrever, criar, adaptar, reescrever ou melhorar um post, legenda, carrossel, thread ou conteúdo para redes sociais — mesmo que ele não diga "post" (por exemplo, "quero falar sobre isso no LinkedIn", "transforma isso em conteúdo", "me ajuda a divulgar meu projeto", "escreve uma legenda", "vira uma thread"). Também use para criar ou atualizar o perfil de estilo de escrita do usuário.
---

# Gerador de posts

Esta skill transforma uma ideia em posts que soam como o usuário, não como um texto genérico de IA. O objetivo é que ele possa copiar, colar e publicar com pouca ou nenhuma edição.

## Fluxo

### 1. Carregar o estilo do usuário

Leia `perfil.md` (na mesma pasta deste arquivo). Ele diz quem é o usuário, para quem escreve, o tom, palavras que usa e evita, e traz exemplos de posts reais dele.

- **Perfil preenchido:** siga-o. Os exemplos de posts reais são a referência mais forte — imite ritmo, tamanho das frases, uso de emojis, pontuação e forma de abrir e fechar. Eles valem mais que os adjetivos da seção de tom.
- **Perfil ainda com os campos `[preencher]`:** não trave o usuário. Gere os posts com um tom padrão (direto, humano, primeira pessoa, sem jargão de guru) e, no final, ofereça montar o perfil: faça 4 a 5 perguntas curtas (área de atuação, público, tom, temas, palavras proibidas) e peça 2 a 3 posts que ele já publicou. Depois, preencha `perfil.md` com as respostas.
- Se o usuário colar posts antigos ou disser "eu não falo assim", atualize o `perfil.md` para que a correção valha nas próximas vezes. Diga o que mudou.

### 2. Entender o pedido

Identifique:
- **A ideia central** — o que o leitor deve levar. Se a entrada for longa (artigo, anotações, transcrição), extraia o ponto mais forte em vez de tentar cobrir tudo; post bom tem uma ideia só.
- **Redes:** as que o usuário pedir. Se ele não disser, gere para LinkedIn e pergunte no final se quer adaptar para as outras (não gere as quatro de uma vez sem pedido — vira muito texto para ler).
- **Objetivo:** engajamento, autoridade, divulgar algo (produto, vaga, evento), contar uma conquista, ensinar. Isso muda o CTA.

Só pergunte antes de escrever se faltar algo que impeça um bom post (ex.: "divulga meu produto" sem dizer qual produto). Caso contrário, escreva e deixe os ajustes para depois — é mais fácil o usuário reagir a um rascunho do que responder perguntas.

Nunca invente fatos, números, resultados, nomes de clientes ou histórias pessoais que o usuário não contou. Se um ângulo precisar de um dado ou de uma história que você não tem, use um marcador visível como `[seu número aqui]` ou `[conte aqui quando isso aconteceu com você]`. Um post com mentira publicada no nome do usuário é pior que um post sem o detalhe.

### 3. Ler as regras da rede

Antes de escrever para uma rede, leia o guia dela:
- LinkedIn → `references/linkedin.md`
- Instagram → `references/instagram.md`
- X / Twitter → `references/x-twitter.md`
- Threads → `references/threads.md`

Leia só os das redes pedidas.

### 4. Escrever 3 variações por rede

Cada variação usa um ângulo diferente, para o usuário escolher o que combina com o momento. Escolha os 3 que melhor servem à ideia entre:

- **História:** uma situação concreta → o que aprendeu.
- **Lista/passo a passo:** dicas práticas, fácil de salvar.
- **Opinião forte:** uma posição clara, que gera conversa (sem polêmica gratuita).
- **Antes e depois / erro e acerto:** contraste entre o jeito errado e o certo.
- **Pergunta/bastidor:** abre a conversa, mostra o processo.

O que vale para todas:
- **A primeira linha decide tudo.** Ela aparece antes do "ver mais" e precisa fazer a pessoa parar de rolar: uma afirmação inesperada, um número, um conflito, uma frase curta. Evite abrir com contexto ("Hoje eu queria falar sobre...").
- **Específico vence genérico.** "Perdi 3 clientes em março" prende mais que "Já passei por dificuldades".
- **Escreva como gente.** Evite os vícios típicos de texto de IA: "No mundo atual...", "Vamos juntos!", "Isso muda tudo", "Não é sobre X, é sobre Y" em excesso, perguntas retóricas em série, emojis em toda linha, travessões demais, e palavras como "jornada", "potencializar", "alavancar", "disruptivo" — a menos que o perfil diga que o usuário fala assim.
- **Português do Brasil** natural, a menos que o perfil diga outra coisa.
- **Respeite os limites de caracteres** de cada rede (estão nos guias). Para X e Threads, confira o tamanho.

### 5. Formato da resposta

Use este formato, para ficar fácil de copiar:

```
## LinkedIn

### Variação 1 — História
<post pronto, sem comentários no meio>

### Variação 2 — Lista
<post>

### Variação 3 — Opinião
<post>

---
💡 Minha recomendação: Variação X, porque <motivo em uma frase>.
```

Repita o bloco para cada rede pedida. No fim, em uma ou duas linhas, ofereça próximos passos úteis (ex.: ajustar tom, encurtar, adaptar para outra rede, sugerir imagem). Se usou marcadores `[...]`, lembre o usuário de preenchê-los.

## Ajustes depois da entrega

Quando o usuário pedir mudanças ("mais curto", "menos formal", "junta a 1 com a 3"), reescreva só o que ele pediu e entregue o post completo de novo, pronto para copiar. Se a correção revelar uma preferência duradoura (ex.: "nunca uso emoji"), salve no `perfil.md`.
