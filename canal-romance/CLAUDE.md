# CLAUDE.md — Sweet Tea & Old Letters (canal do YouTube)

> Este arquivo é a memória do canal. O Claude Code lê este arquivo automaticamente ao abrir o terminal nesta pasta.
> Esta pasta e esta conversa são **exclusivas deste canal**. Não misturar com outros canais do dono.

---

## 0. Instruções para o Claude (ler primeiro)

**Quem é o usuário:** criador de vários canais faceless no YouTube, brasileiro. Conversa em **português**. Usa uma pasta e uma conversa por canal.

**Como trabalhar neste canal:**
1. **Idioma das entregas:** todo conteúdo do canal (títulos, roteiros, descrições, thumbnails, instruções de voz) vem **primeiro em português** (para leitura com calma) e **depois em inglês** (versão final). Roteiros longos: por partes/capítulos, cada parte em PT e logo abaixo em EN.
   - **Exceção:** prompts de imagem vêm **direto em inglês**, sem versão em português.
2. **Linguagem dos roteiros:** simples, humana, conversando com o ouvinte, como avó/avô falando. Ver seção 2.
3. **Canal 100% IA + ficção:** nunca dizer ou insinuar que a história é real, nem que imagens são fotos reais (ver seção 2). **Não lembrar o usuário do aviso de "conteúdo alterado" no upload** — ele já faz isso sozinho.
4. **Protagonistas únicos:** cada história tem personagens novos. Antes de criar uma história, consultar `nomes-usados.md` (ou a lista na seção 4) e, depois, **atualizar a lista**.
5. **Custos:** antes de gerar imagens/vídeos que gastam créditos (Higgsfield etc.), informar o custo e pedir confirmação. Rascunhos baratos primeiro; versão final em alta qualidade só depois da escolha.
6. **Salvar tudo em arquivos** nesta pasta (roteiros, títulos, decisões). Ao tomar uma decisão nova sobre o canal, **atualizar este CLAUDE.md**.
7. Respostas objetivas, sem enrolação; dar recomendação clara em vez de listar opções infinitas.

**Estrutura de pastas sugerida:**
```
SweetTeaAndOldLetters/
├── CLAUDE.md            ← este arquivo
├── nomes-usados.md      ← protagonistas/pares já usados
├── identidade/          ← ícone, banner, marca d'água, modelos de thumbnail
├── roteiros/            ← um arquivo por vídeo (ex.: 001-cowboy-train-station.md)
├── thumbnails/
└── descricoes/
```

**Ferramentas usadas na criação (se conectadas):** Higgsfield (imagens — GPT Image 2.6), vidIQ e NexLev (pesquisa de nicho, palavras-chave, outliers). A conta Gravyx está sem saldo.

---

## 0.1 Status atual (atualizado em 10/11/2026)

✅ Pesquisa de nicho concluída · ✅ Conceito e regras · ✅ Nome e @ · ✅ Ícone · ✅ Banner (arte) · ✅ Kit de montagem (seção 9)

**Próximos passos:**
1. **Montagem do canal** (seguir o checklist da seção 9):
   - baixar ícone e banner (links na seção 7) para `identidade/`;
   - ícone → 800×800; marca d'água → 150×150;
   - banner → 2560×1440 com "Sweet Tea & Old Letters" + slogan aplicados na área segura central (1546×423) — pode ser feito por código (Python/Pillow + fontes Playfair Display e Dancing Script do Google Fonts) ou no Canva;
   - o usuário faz no YouTube Studio a parte que exige login (criar canal, @, enviar imagens, colar textos, criar playlists).
2. **Modelo de thumbnail** (gerar exemplo na Higgsfield).
3. **Modelo de roteiro reutilizável** + resumo das 3–4 primeiras histórias.
4. **Primeiro vídeo:** escolher um dos 21 títulos da seção 6.

---

## 0.2 Resumo da pesquisa de nicho (nov/2026)

Fontes: NexLev (≈140 canais analisados) e vidIQ (palavras-chave, outliers, crescimento). Valores de receita/RPM são estimativas.

**Por que romance hétero (decisão final):**
- RPM US$ 7–16 (público feminino 40+, EUA) contra US$ 2–6 do romance LGBT (BL/MM), cujas buscas vêm majoritariamente de Vietnã, Nigéria e Paquistão (vidIQ: "gay love story" 53 mil buscas/mês, 47% Vietnã).
- Vários canais criados em 2026 chegaram a US$ 5–30 mil/mês estimados em poucos meses: Timeless Love (2,4 mi views/mês, RPM ~US$ 11, vídeos ~1h30), Boots & Roses (cowboy, RPM ~US$ 12), Heartelle Drama (~US$ 29 mil/mês), Epic Drama, PoPo Sweet Drama.
- Canais de **narrador idoso** pagam o maior RPM e aceitam vídeos de 2h+: Old Lion Stories (RPM ~US$ 13, 143 min), Dad Prevails (RPM ~US$ 16, 142 min), Hidden Family Stories (RPM ~US$ 14).
- **Tendência em alta:** "segunda chance com protagonista idoso" — vídeos de canais pequenos com 20x–900x a média (Hidden Fortune Stories 190 mil views/924x; Velvet Legacy Tales 38x; Fatebound Stories 22x; Second Chance Tales 86 mil).
- vidIQ: "historical romance" 18,6 mil buscas/mês, concorrência 21, +52%; "love at first sight" +68%; "slow burn romance" 21,9 mil, concorrência 28. "lost love story" só 4,3 mil buscas — o crescimento vem de recomendações, ou seja, **título + thumbnail** são o que importa.

**Riscos identificados:** concentração em poucos vídeos virais (média ≫ mediana); ~2/3 dos canais novos de audiobook romance não monetizaram ou pararam de postar; voz de IA robótica e conteúdo repetitivo arriscam desmonetização; nunca reutilizar clipes de microdramas (copyright).

**Canais de referência para estudar:**
- Timeless Love — https://www.youtube.com/channel/UCeUXyk5craQKAa9jrvdUD_A
- Boots & Roses — https://www.youtube.com/channel/UCnkylnG5o91q0BTcmc9MW0A
- Noble Heart Romance — https://www.youtube.com/channel/UCrMYcIbH3YEUh4vAuqZqpbw
- Heartelle Drama — https://www.youtube.com/channel/UC7yGCnlEOnXQOHXMn8ofVyQ
- Old Lion Stories — https://www.youtube.com/channel/UCBQP2z9Gw2eqfLhe1w1PeuA
- Fatebound Stories — https://www.youtube.com/channel/UC454-HsUlsViDRdkZlWNqSw
- Velvet Legacy Tales — https://www.youtube.com/channel/UCBxG6uvINXiQj1ePOIrDYMg
- Hidden Fortune Stories — https://www.youtube.com/channel/UC9k0Fq_uWKrHxMN_WFzUXNg
- Second Chance Tales — https://www.youtube.com/channel/UCeYB6HlHLHJlBE00mP4Epiw
- Vintage Mic-tales — https://www.youtube.com/channel/UCbLVE2HVlKyWOEBiaHXOZ4w

**Fórmula de título que viraliza:** idade ou ano específico ("At 81", "In 1959") + conflito/separação + salto no tempo ("55 Years Later") + gancho aberto (carta, testamento, foto, neto batendo na porta).

---
## 1. Conceito

**PT:** Um idoso (70–85 anos) conta, em primeira pessoa, o grande amor da juventude — o amor que a época, a família, a guerra ou a diferença social separou. Dentro desse formato fixo, cada vídeo traz um enredo diferente (cowboy, empregada e herdeiro, guerra, amor de verão etc.).

**EN:** An elderly narrator (70–85) tells, in first person, the great love of their youth — the love that time, family, war or social class kept apart. Inside this fixed format, every video brings a different storyline (cowboy, maid & heir, wartime, summer love, etc.).

- **Público-alvo:** mulheres 40–75+, EUA (principal), Reino Unido, Canadá, Austrália.
- **Nicho:** romance hétero. (Decisão tomada após análise NexLev + vidIQ: maior RPM, US$ 7–16, e retorno mais rápido.)
- **Tendência que sustenta a ideia:** "segunda chance com protagonista idoso" — vários canais novos com vídeos 20x–900x acima da média (out/nov 2026).

---

## 2. Regras de narrativa (obrigatórias em todo roteiro)

1. **Conversa com o ouvinte** — o narrador fala direto com quem ouve ("You know that feeling, dear…", "Let me tell you something I've never told anyone"). Perguntas leves de vez em quando. No final, convite para comentar.
2. **Linguagem simples e humana** — frases curtas, palavras do dia a dia, jeito de avó/avô falando, não de livro. Inglês fácil de entender.
3. **Detalhes sensoriais** — cheiro de café, rádio tocando Elvis, vestido azul de domingo, chuva no telhado do celeiro.
4. **Emoção verdadeira, sem melodrama** — mostrar sentimentos com gestos e silêncios.
5. **Ritmo** — pequeno gancho a cada 8–10 minutos ("But that night, everything changed…"). Pausas marcadas no roteiro para a voz de IA.
6. **Conteúdo limpo** — romance e emoção, nada explícito (protege a monetização).
7. **Ficção** — nunca usar pessoas reais como se fosse história verdadeira.

### Regras de IA e ficção (atenção constante)
O canal é 100% feito com IA (imagens e áudio) e as histórias são pura ficção.
- **Nunca** dizer ou insinuar que a história é real: nada de "true story", "real story", "based on true events", "this really happened" em títulos, thumbnails, descrições ou roteiros.
- **Nunca** apresentar imagens de IA como fotos reais (nada de "real photo", "actual picture", "found photo").
- O narrador fala em primeira pessoa como personagem, o que é normal na ficção; só não se afirma que ela existe ou que os fatos aconteceram.
- Não é preciso escrever "ficção" em todo lugar do canal (decisão do dono do canal), mas evitar qualquer frase que engane.
- O aviso de conteúdo de IA no upload o dono do canal já faz por conta própria. **Não é preciso lembrar disso nas entregas.**

### Prompts de imagem
Prompts para gerar imagens (logo, banner, thumbnails, cenas) vêm **direto em inglês**, sem a versão em português.

### Estrutura padrão do roteiro
1. **Gancho no presente (0–2 min):** evento atual que dispara a memória (funeral, carta, neto, reencontro).
2. **Flashback da juventude (~60%):** a história de amor com o enredo do episódio.
3. **O que separou os dois (~15%):** família, classe, guerra, orgulho, mal-entendido.
4. **A vida que seguiu (~10%):** décadas de saudade.
5. **Volta ao presente + desfecho (~15%):** reencontro, carta respondida ou final agridoce (variar).

---

## 3. Duração (sempre variar entre 1h e 2h)

Narrador idoso ≈ 140–150 palavras/minuto.

| Duração | Palavras | Combina com |
|---|---|---|
| ~1h | 8.500–9.000 | Summer Love, Hidden Millionaire |
| ~1h20 | 11.500–12.000 | Maid & Heir, Forbidden by Family |
| ~1h40 | 14.000–15.000 | Cowboy, Second Chance |
| ~2h | 17.000–18.000 | Love in Wartime, sagas de décadas |

Rodízio sugerido: 1h05 → 1h40 → 1h20 → 2h → 1h10 → 1h50 → 1h30… (nunca dois seguidos iguais).
Marcar no roteiro os pontos de anúncio (pausas entre capítulos) e entregar capítulos com timestamps na descrição.

---

## 4. Protagonistas e vozes — ✅ DEFINIDO

**Sem narradores fixos com nome.** Cada história tem o seu próprio protagonista idoso, com nome, idade, passado e personagens únicos (ex.: Evelyn, a ex-empregada da mansão; Henry, o ex-peão do rancho; Dorothy, que esperou o soldado). Nada de repetir o mesmo personagem em várias histórias.

- Não repetir nomes de protagonistas nem de pares românticos entre vídeos (manter uma lista dos nomes já usados).
- Quem narra é o protagonista daquela história, em primeira pessoa.

**O que dá identidade ao canal:**
- **Vozes fixas:** 1 voz feminina idosa e 1 voz masculina idosa, sempre as mesmas (alta qualidade, sem som robótico). A voz segue o ponto de vista da história (ela conta → voz feminina; ele conta → voz masculina). Outras vozes só depois de ver os dados de retenção.
- Mesma abertura, mesmo encerramento, mesma trilha e mesmo estilo de thumbnail.
- A thumbnail de cada vídeo mostra o protagonista daquela história (não existe um rosto fixo do canal).

### Nomes já usados
_(atualizar a cada vídeo produzido)_
- —

---

## 5. Playlists

| # | Playlist | Enredo |
|---|---|---|
| 1 | Cowboy Love Stories 🤠 | Peões, rancheiros, velho oeste anos 50–70 |
| 2 | The Maid & The Heir 🏛️ | Empregada e herdeiro, diferença de classe |
| 3 | Love in Wartime 🎖️ | Soldado e enfermeira, cartas da guerra |
| 4 | Forbidden by Family 💔 | Casamento arranjado, pais que proibiram |
| 5 | The Hidden Millionaire 💰 | "Ele era só o rapaz simples…" + revelação |
| 6 | Second Chance at Love 🌅 | Reencontros na velhice |
| 7 | Summer Love, Lost Forever 🌻 | Amor de verão em cidade pequena |

Especiais: ⭐ Start Here: Most Loved Stories · 🌙 Stories to Fall Asleep To · 📖 Full Stories 2+ Hours.
Nos primeiros 20–30 vídeos: rotação equilibrada (3–4 por tema). Depois, priorizar os 2–3 temas que performarem melhor.

### Adaptação dos enredos à época
| Moderno | Versão "amor do passado" |
|---|---|
| Empregada e bilionário | Empregada e filho do dono da mansão (anos 50/60) |
| CEO e moça pobre | Herdeiro do petróleo/fábrica e a garçonete |
| Casamento por contrato | Casamento arranjado pelas famílias |
| Ex arrependido | "Escolhi o noivo rico e me arrependi por 50 anos" |
| Herdeiro escondido | "Ele era só o rapaz que consertava carros…" |

---

## 6. Banco de títulos (guardados para depois)

### 🤠 Cowboy Love Stories
1. **Voz feminina** — 🇧🇷 Aos 81 anos, ainda sonho com o cowboy que me esperou na estação de trem em 1959
   🇺🇸 At 81, I Still Dream of the Cowboy Who Waited for Me at the Train Station in 1959
2. **Voz feminina** — 🇧🇷 Meu pai me fez casar com o filho do banqueiro. O cowboy que eu amava esperou na estação por 3 dias
   🇺🇸 My Father Made Me Marry the Banker's Son. The Cowboy I Loved Waited at the Station for 3 Days
3. **Voz masculina** — 🇧🇷 Eu era só um peão. Ela era a filha do rancheiro. 60 anos depois, ela voltou ao nosso celeiro
   🇺🇸 I Was Just a Ranch Hand. She Was the Rancher's Daughter. 60 Years Later, She Came Back to Our Barn

### 🏛️ The Maid & The Heir
4. **Voz feminina** — 🇧🇷 Eu era a empregada da mansão. Ele era o herdeiro. 55 anos depois, o neto dele bateu na minha porta
   🇺🇸 I Was the Maid in Their Mansion. He Was the Heir. 55 Years Later, His Grandson Knocked on My Door
5. **Voz feminina** — 🇧🇷 A mãe dele me demitiu por amar o filho dela. Aos 77, recebi um envelope com o nome dele
   🇺🇸 His Mother Fired Me for Loving Her Son. At 77, I Received an Envelope With His Name on It
6. **Voz masculina** — 🇧🇷 Eu era o rapaz rico que amava a empregada. Minha família a mandou embora — passei 50 anos procurando por ela
   🇺🇸 I Was the Rich Boy Who Loved the Maid. My Family Sent Her Away — I Spent 50 Years Looking for Her

### 🎖️ Love in Wartime
7. **Voz feminina** — 🇧🇷 Ele prometeu voltar da Coreia e se casar comigo. 60 anos depois, encontrei a última carta dele
   🇺🇸 He Promised to Come Home From Korea and Marry Me. 60 Years Later, I Found His Last Letter
8. **Voz feminina** — 🇧🇷 Eu era uma jovem enfermeira em 1951. Ele era o soldado que me fez prometer não esquecê-lo
   🇺🇸 I Was a Young Nurse in 1951. He Was the Soldier Who Made Me Promise Not to Forget Him
9. **Voz masculina** — 🇧🇷 Voltei da guerra para casar com ela — ela já usava o anel de outro homem
   🇺🇸 I Came Home From the War to Marry Her — She Was Already Wearing Another Man's Ring

### 💔 Forbidden by Family
10. **Voz feminina** — 🇧🇷 Meu pai me fez casar com o filho do banqueiro. O rapaz que eu amava nunca se casou
    🇺🇸 My Father Made Me Marry the Banker's Son. The Boy I Loved Never Married Anyone
11. **Voz feminina** — 🇧🇷 Nossas famílias se odiavam havia 30 anos. Nos apaixonamos mesmo assim — e pagamos o preço
    🇺🇸 Our Families Hated Each Other for 30 Years. We Fell in Love Anyway — and Paid the Price
12. **Voz masculina** — 🇧🇷 O pai dela disse que eu não era bom o bastante. 50 anos depois, comprei a casa onde ela cresceu
    🇺🇸 Her Father Said I Wasn't Good Enough. 50 Years Later, I Bought the House She Grew Up In

### 💰 The Hidden Millionaire
13. **Voz feminina** — 🇧🇷 Ele era só o rapaz que consertava o caminhão do meu pai. Ninguém sabia que ele era dono de metade do condado
    🇺🇸 He Was Just the Boy Who Fixed My Father's Truck. Nobody Knew He Owned Half the County
14. **Voz feminina** — 🇧🇷 Todos riram quando me casei com o fazendeiro pobre. No funeral dele, o advogado leu o testamento
    🇺🇸 Everyone Laughed When I Married the Poor Farmer. At His Funeral, the Lawyer Read the Will
15. **Voz masculina** — 🇧🇷 Ela me trocou por um homem rico em 1963. Nunca soube que eu era herdeiro de uma fortuna do petróleo
    🇺🇸 She Left Me for a Rich Man in 1963. She Never Knew I Was the Heir to an Oil Fortune

### 🌅 Second Chance at Love
16. **Voz feminina** — 🇧🇷 Aos 74, vi meu primeiro amor no funeral do meu marido — ele nunca parou de esperar
    🇺🇸 At 74, I Saw My First Love at My Husband's Funeral — He Had Never Stopped Waiting
17. **Voz feminina** — 🇧🇷 Aos 82, finalmente abri a carta que ele me escreveu em 1958 — eu devia ter ido com ele
    🇺🇸 At 82, I Finally Opened the Letter He Wrote Me in 1958 — I Should Have Gone With Him
18. **Voz masculina** — 🇧🇷 Aos 79, minha neta achou uma foto na minha carteira: "Vovô… quem é essa mulher?"
    🇺🇸 At 79, My Granddaughter Found a Photo in My Wallet. "Grandpa… Who Is This Woman?"

### 🌻 Summer Love, Lost Forever
19. **Voz feminina** — 🇧🇷 Um verão em 1962 mudou minha vida. Nunca mais o vi — até a semana passada
    🇺🇸 One Summer in 1962 Changed My Life. I Never Saw Him Again — Until Last Week
20. **Voz feminina** — 🇧🇷 Todo verão ele me esperava no lago. No ano em que não fui, ele me deixou um bilhete
    🇺🇸 Every Summer He Waited at the Lake for Me. The Year I Didn't Come, He Left Me a Note
21. **Voz masculina** — 🇧🇷 Eu tinha 17, ela era a moça da cidade grande. 60 verões depois, ela voltou à nossa cidadezinha
    🇺🇸 I Was 17, She Was the Girl From the City. 60 Summers Later, She Returned to Our Little Town

---

## 7. Identidade do canal

### Nome — ✅ DEFINIDO
**Sweet Tea & Old Letters**
- Handle: **@SweetTeaAndOldLetters** (reserva: @SweetTeaOldLetters). Ambos apareciam livres em 09/11/2026; confirmar com o ✓ verde na criação.
- Criar e-mail e redes (Instagram, TikTok, Facebook) com o mesmo nome.
- Nomes descartados por já existirem: Porchlight Love Stories, Faded Letters, Love Left Behind, Hope Chest Love Stories, Rocking Chair Tales, Letters From the Porch, The Heart Remembers, Once Upon Us.

### Slogan
- 🇧🇷 Histórias de amor que o tempo não apagou.
- 🇺🇸 Love stories time couldn't erase.

### Paleta de cores (nostálgica, quente, "foto antiga")
| Cor | Hex | Uso |
|---|---|---|
| Creme papel antigo | `#F3E9DC` | Fundo, banner |
| Sépia café | `#6B4F3A` | Textos, logo |
| Rosa antigo | `#C9878A` | Destaques, coração |
| Dourado desbotado | `#C8A15A` | Detalhes, selos de ano |
| Azul noite | `#2E3A4F` | Contraste nas thumbnails |

### Tipografia
- Títulos: **Playfair Display** ou **Libre Baskerville** (serifada, clássica).
- Detalhe "escrito à mão": **Dancing Script** ou **Homemade Apple**.
- Texto da thumbnail: serifada bold, 3–5 palavras, alto contraste.

### Logo
Envelope antigo com selo de cera em formato de coração + raminho de rosa, em sépia e dourado. Versão simplificada (só o selo) para o ícone do canal.

**Ícone final — ✅ VERSÃO VERMELHA A (09/11/2026):** rosas e selo em vermelho carmesim forte.
- Job: `38db1572-39e4-46ba-b944-c630c4d2c6ff` (1024×1024 — suficiente para o ícone de 800×800 do YouTube)
- Arquivo: https://d8j0ntlcm91z4.cloudfront.net/user_3JQCUjzYuU2cipeDySVvAQsF7zz/hf_20261109_104954_38db1572-39e4-46ba-b944-c630c4d2c6ff.png
- Pendente (opcional): versão 2048×2048 — a Higgsfield bloqueou por limite diário do período de carência da conta.

**Versão anterior (rosa antigo), substituída:** gerado na Higgsfield (GPT Image 2.6, 2048×2048), a partir da versão 2 do rascunho.
- Job: `c1d98cab-8ad9-4575-b538-dcbb42243510`
- Arquivo: https://d8j0ntlcm91z4.cloudfront.net/user_3JQCUjzYuU2cipeDySVvAQsF7zz/hf_20261109_104629_c1d98cab-8ad9-4575-b538-dcbb42243510.png
- Prompt base (rascunho aprovado): *Elegant circular channel icon emblem: a vintage cream envelope sealed with a heart-shaped dusty-rose red wax seal, a small sprig of dusty pink roses and a faded gold ribbon tucked behind it, warm sepia and faded gold tones on an aged cream paper background, soft nostalgic golden-hour lighting, minimalist, centered composition with generous margin so it reads well when cropped to a circle, painterly vintage illustration style, high detail, no text, no letters*

### Banner — ✅ APROVADO (10/11/2026)
Varanda ao entardecer, cadeira de balanço, chá gelado, cartas com fita vermelha e rosas vermelhas; faixa central livre para nome e slogan.
- Versão final 4K (Higgsfield, GPT Image 2.6): job `e102f8ae-0482-456a-ba7d-7f5df59e6140`
- Arquivo: https://d8j0ntlcm91z4.cloudfront.net/user_3JQCUjzYuU2cipeDySVvAQsF7zz/hf_20261110_125908_e102f8ae-0482-456a-ba7d-7f5df59e6140.png
- Rascunho escolhido (B): job `4cda11a6-430a-41b9-996c-35df45005820`
- Prompt base: *Wide YouTube channel banner artwork: a warm Southern front porch at golden-hour sunset, an empty wooden rocking chair, a glass of iced sweet tea with lemon on a small side table, a bundle of old love letters tied with a faded red ribbon, a few vivid crimson roses in a mason jar, soft warm sepia and faded gold tones with cream highlights, nostalgic painterly vintage illustration style matching a cream envelope and red wax seal logo. Keep the central horizontal band calm and uncluttered (soft blurred background there) so a channel name can be added later; place the detailed objects toward the left and right sides. No text, no letters, no people.*
- Montagem no Canva: tamanho 2560×1440; "Sweet Tea & Old Letters" em Playfair Display (sépia `#6B4F3A` ou creme com sombra suave) e o slogan "Love stories time couldn't erase." em Dancing Script, ambos dentro da área segura central de 1546×423.

### Thumbnail padrão
- Esquerda: rosto do narrador idoso em close (emoção: saudade/lágrima contida).
- Direita: casal jovem da época em tom sépia (o "passado").
- Selo dourado com o ano ("1959").
- Texto curto em serifada: "HE WAITED 60 YEARS".
- Mesma paleta e mesmo layout em todos os vídeos.

### Vinheta de abertura (sempre igual)
- 🇧🇷 "Puxe uma cadeira, querido(a)… esta é uma história que eu nunca contei a ninguém."
- 🇺🇸 "Pull up a chair, dear… this is a story I've never told anyone."

### Encerramento (sempre igual)
- 🇧🇷 "Se essa história tocou seu coração, me conta nos comentários: você já amou alguém que a vida levou embora? Até a próxima história."
- 🇺🇸 "If this story touched your heart, tell me in the comments… did you ever love someone life carried away? Until our next story, dear."

### Trilha
Piano suave ou violão acústico, volume baixo, sem letra. Mesma trilha de abertura em todos os vídeos.

---

## 8. Entregáveis por vídeo (padrão)
1. Título final + opções para testar (PT → EN)
2. Narrador + instruções de voz (tom, ritmo, emoção, pausas)
3. Roteiro completo por capítulos (cada parte em PT e depois EN)
4. Ideia de thumbnail (texto + descrição da imagem)
5. Descrição do vídeo com capítulos/timestamps + tags
6. Playlist do vídeo

---

## 9. Kit de montagem do canal (textos prontos para colar)

### Nome, handle e textos principais
- **Nome:** Sweet Tea & Old Letters
- **Handle:** @SweetTeaAndOldLetters (reserva: @SweetTeaOldLetters)
- **Slogan (banner):** Love stories time couldn't erase.

**Descrição do canal**
🇧🇷 Puxe uma cadeira, sirva um chá e fique um pouco. Aqui, avôs e avós contam o grande amor da juventude: o cowboy que esperou na estação, a empregada que amou o herdeiro, o soldado que prometeu voltar. Amores que a vida separou, mas o coração nunca esqueceu. Novas histórias toda semana, para ouvir com calma ou para adormecer.

🇺🇸 (colar no YouTube)
Pull up a chair, pour yourself some sweet tea, and stay a while.

Here, grandmothers and grandfathers share the great love of their youth: the cowboy who waited at the train station, the maid who loved the heir, the soldier who promised to come home. Loves that life kept apart, but the heart never forgot.

🌹 Long, heartfelt love stories from another time
☕ Perfect to listen slowly, while you relax, or to fall asleep to
💌 New stories every week

Subscribe and pull up a chair. There's always one more letter to open.

**Palavras-chave do canal** (YouTube Studio → Personalização/Configurações → Canal → Palavras-chave)
love stories, romance stories, old love stories, second chance love, lost love story, first love, historical romance, romance audiobook, love story audiobook, cowboy romance, western romance, maid and heir, wartime love story, forbidden love, emotional stories, stories for seniors, bedtime stories for adults, sleep stories, nostalgic stories, sweet romance

### Configurações recomendadas
| Item | Valor |
|---|---|
| País de residência | o seu país real (impostos/AdSense) |
| Idioma do canal | Inglês (Estados Unidos) |
| Público | **Não é conteúdo para crianças** |
| Categoria padrão dos uploads | Pessoas e blogs (People & Blogs) ou Entretenimento |
| Idioma padrão dos vídeos/títulos | Inglês |
| Licença | Licença padrão do YouTube |
| Comentários | Ativados, com moderação de comentários potencialmente inadequados |
| Marca d'água | Ícone (150×150), "fim do vídeo" ou "posição personalizada" |
| Conteúdo alterado (IA) | já feito pelo dono do canal no upload |

### Playlists (nome + descrição em inglês para colar)
1. **Cowboy Love Stories | Old Western Romance** — Rancher's daughters, ranch hands and the loves that waited on dusty roads. Western romance stories from the 1950s to the 1970s, told by those who lived them.
2. **The Maid & The Heir | Love Across Social Class** — She cleaned the mansion. He was born to inherit it. Love stories that crossed every line their families drew.
3. **Love in Wartime | Soldiers, Nurses & Letters** — Promises made before the train left, letters that came too late, and hearts that waited for years. Romance stories from wartime.
4. **Forbidden by Family | Arranged Marriages & Lost Love** — Fathers who said no, families who forbade it, marriages chosen by others. The loves that were never allowed to be.
5. **The Hidden Millionaire | Love Before the Truth** — He was just the boy who fixed trucks. Nobody knew who he really was. Romance stories with a secret worth waiting for.
6. **Second Chance at Love | Reunited After Decades** — Funerals, old letters, a photo in a wallet. Late-in-life love stories about finding your first love again.
7. **Summer Love, Lost Forever | Small-Town Romance** — One summer, one lake, one love that never came back. Nostalgic small-town romance stories.

Especiais:
- **⭐ Start Here | Most Loved Stories** — The stories our listeners loved the most. The perfect place to begin.
- **🌙 Stories to Fall Asleep To | Calm Love Stories** — Long, gentle love stories to listen to in the dark and drift off to sleep.
- **📖 Full Stories 2+ Hours | Long Romance Audiobooks** — Our longest love stories, for a whole evening of listening.

### Checklist da montagem (ordem sugerida)
1. Criar a conta Google/e-mail do canal (ex.: sweetteaandoldletters@…).
2. Criar o canal no YouTube com o nome **Sweet Tea & Old Letters** e o handle **@SweetTeaAndOldLetters** (conferir o ✓ verde).
3. Enviar o **ícone** (versão vermelha A, ajustada para 800×800).
4. Enviar o **banner** (2560×1440, nome e slogan dentro da área segura central de 1546×423).
5. Colar a **descrição** e adicionar o e-mail de contato.
6. Adicionar as **palavras-chave** do canal.
7. Ajustar **país, idioma e público** (não é para crianças).
8. Definir os **padrões de upload** (categoria, idioma, licença, comentários).
9. Ativar os **recursos intermediários/avançados** (verificação por telefone): libera thumbnails personalizadas e vídeos com mais de 15 min.
10. Criar as **10 playlists** com nome e descrição (podem ficar vazias até o primeiro vídeo).
11. Enviar a **marca d'água** (opcional).
12. Reservar o mesmo nome no **Instagram, TikTok e Facebook**.
13. Depois do primeiro vídeo: montar a **página inicial** (vídeo em destaque + seções de playlists).
