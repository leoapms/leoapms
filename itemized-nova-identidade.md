# ITEMIZED — Nova Identidade do Canal (decisões e pesquisa)

> **Para o Claude do terminal:** este arquivo resume tudo o que foi decidido numa conversa no app (21/11/2026) sobre remodelar o canal ITEMIZED. Leia inteiro, compare com o que já existe/funciona no projeto local e **adapte** — não substitua às cegas o que já está funcionando. Onde houver conflito, pergunte ao dono do canal.

---

## 1. Decisões tomadas

| Tema | Decisão |
|---|---|
| Canal | **ITEMIZED** — https://youtube.com/@billitemized (ID `UCzc622wjo0kUUHoK-w6wasQ`) |
| Idioma | **Continua em inglês** (público EUA, RPM maior) |
| Personagem humano "Bill" | **Removido.** Não usar mais o Bill. |
| Novo estilo | **Boneco palito de cabeça redonda branca** (estilo dos canais de explainer de negócios que mais crescem nos EUA) |
| Marca própria / diferencial | **O recibo ("itemized receipt")**: todo vídeo mostra o preço que o cliente paga aberto linha por linha, com o **TOTAL em vermelho**. É o momento-assinatura do canal. |
| Nicho | Como negócios do dia a dia realmente ganham dinheiro (business breakdowns) |
| Geração de imagens dos vídeos | Feita pelo dono em **outra plataforma (sem custo de créditos)**. Aqui só foi gerada a identidade. |
| Vídeos atuais (2) | Sugestão: deixar **não listados** (somavam ~3 views) para o canal começar coerente. Refazer o do cinema no estilo novo (ângulo da pipoca). |
| Pendência | Separar personagem por personagem (folha de estilo → personagens individuais) — será feito no computador. |

Vídeos antigos do canal (estilo antigo, com o Bill):
- `YUJ0en3ZZMs` — How Movie Theaters Really Make Money (It's Not Tickets) — 16:24
- `Sw2Mh0Q6Dxo` — Cruise Lines Don't Want You To Know How They Actually Make Money — 13:34

---

## 2. Identidade visual gerada (Higgsfield)

**Foto de perfil** (fundo mostarda, segura para recorte circular)
1. Boneco espiando por cima de um recibo: https://d8j0ntlcm91z4.cloudfront.net/user_3JQCUjzYuU2cipeDySVvAQsF7zz/hf_20261121_170440_7de47d7f-e77f-486e-bdea-b39a3c46bb7c.png
2. Variação da 1: https://d8j0ntlcm91z4.cloudfront.net/user_3JQCUjzYuU2cipeDySVvAQsF7zz/hf_20261121_170441_00e10d85-d001-4f24-a2bb-acb6ab9663c3.png
3. Ícone de recibo com "I": https://d8j0ntlcm91z4.cloudfront.net/user_3JQCUjzYuU2cipeDySVvAQsF7zz/hf_20261121_170443_fde625d0-de91-483c-b5a0-c8da3e309888.png

**Banner**
- A) Creme + grade azul, recibo "ITEMIZED", boneco com lupa (1K): https://d8j0ntlcm91z4.cloudfront.net/user_3JQCUjzYuU2cipeDySVvAQsF7zz/hf_20261121_170446_a9ca7689-ac55-4ca4-b41b-cf87c2fe3208.png
- B) Mostarda, recibo com "TOTAL: THE TRUTH" em vermelho, boneco apontando (2K): https://d8j0ntlcm91z4.cloudfront.net/user_3JQCUjzYuU2cipeDySVvAQsF7zz/hf_20261121_170526_0a5d7158-8905-4d78-ad5e-9519631ddbd3.png

**Folha de estilo (2K)** — boneco frente/lado/costas, 6 expressões, elenco de apoio, recibo, paleta:
https://d8j0ntlcm91z4.cloudfront.net/user_3JQCUjzYuU2cipeDySVvAQsF7zz/hf_20261121_170524_60beb9a0-34ad-416e-b2bd-fb67638c820f.png

> Os links são do CDN do Higgsfield; as imagens também estão na galeria da conta Higgsfield. Baixe e guarde localmente.

### Personagens a separar depois (da folha de estilo)
- **Protagonista** (o espectador): boneco palito, cabeça redonda branca, olhos de ponto, sem roupa por padrão
- **Expressões:** chocado, desconfiado, rindo, pensando, bravo, convencido (smug)
- **Elenco de apoio** (mesmo estilo + roupa de uma cor): dono de negócio de terno, chef com chapéu, caixa com viseira, ricaço de cartola
- **Prop principal:** o recibo (papel branco, bordas rasgadas em zigue-zague, linhas com preços, TOTAL em vermelho)

---

## 3. Textos da identidade

**Nome:** ITEMIZED
**Slogan:** *Every business, itemized.*

**Descrição do canal:**
> Ever wondered where your money actually goes? ITEMIZED breaks down how everyday businesses really make money: buffets, cruise lines, gyms, casinos, movie theaters, pawn shops and more. Every episode takes the price you pay and itemizes it, line by line, until the real total shows up. No jargon. No fluff. Just the receipt they never hand you.
>
> New breakdowns every week.

**Paleta oficial**

| Cor | Hex | Uso |
|---|---|---|
| Creme | `#F5EFE0` | fundo principal / papel |
| Azul grade | `#CFE3F0` | grade de fundo (blueprint) |
| Cinza | `#8A8A8A` | cenários neutros |
| Mostarda | `#E5B53A` | cor da marca (perfil, banner, destaques) |
| Verde dinheiro | `#3E9B57` | lucro, dinheiro |
| Vermelho alerta | `#D64541` | TOTAL do recibo, prejuízo, alertas |
| Preto | `#1A1A1A` | contornos e texto |

**Prompt base** (colar no início de cada cena na plataforma de geração):
```
Flat 2D vector explainer style, simple stick figure with a big round white head, black dot eyes, thin black stick limbs, thick clean black outlines, muted cream and light-blue background, color only on key props (money green, alert red, mustard yellow), minimal and readable.
```

---

## 4. Receita de produção (o que os canais de sucesso fazem)

Baseado em análise com vidIQ (4 vídeos assistidos inteiros) de canais em inglês:

- **Visual:** boneco de cabeça redonda branca, olhos de ponto, contorno preto grosso, roupa de cor chapada. Fundo em tons apagados; cor forte só nos números (verde = lucro, vermelho = prejuízo).
- **Números na tela:** etiquetas de preço, recibos de papel, pilhas de dinheiro, gráficos simples (barra/pizza/linha), caixas de texto em caixa alta.
- **Animação:** baixa — imagens paradas com zoom/pan, piscadas, pequenos loops. **Troca de imagem a cada 3–8 s.**
- **Duração ideal:** **22–27 min** (é onde estão os maiores sucessos).
- **Narração:** calma, analítica, levemente irônica/seca, ritmo ágil. Música leve (acústica/lo-fi/corporate). Poucos efeitos: caixa registradora, papel, moedas, carimbo.
- **Ritmo de postagem dos líderes:** ~3 vídeos/semana (Marcus Explains: 62 vídeos em 4,5 meses). Meta realista: 2/semana.

### Estrutura de roteiro
**Gancho (0–60 s), dois modelos que funcionam:**
1. **História real absurda e específica** — ex.: vídeo de buffet do Marcus abre com um homem de 160 kg protestando com placa na porta do buffet → leva à pergunta "como um buffet livre sobrevive?".
2. **Fantasia → virada** — ex.: "você sonha em ter uma academia… mas academia não é negócio de fitness, é negócio de assinatura com halteres."

**Corpo:** 4 a 6 blocos — o mecanismo → a conta real (custos x margem) → comparação surpreendente (ex.: buffets de Las Vegas bancados pelo cassino) → psicologia do cliente → **o recibo final (assinatura ITEMIZED)**.

**Variante "Every Level":** escada de 6 níveis de preço (ex.: cruzeiro — cabine interna $300 → oceanview → varanda → mini-suíte → suíte → owner's suite $50.000+), ~3–4 min por nível.

### Fórmulas de título
- `How [X] Actually Make Money (It's Not [Y])`
- `The Economics of Owning a [X]` — "the economics of owning" ≈ 174 mil buscas/mês
- `How [X] Trap You at Every Level ($A to $B)`

---

## 5. Próximos temas (priorizados pelos dados)

| # | Tema | Evidência |
|---|---|---|
| 1 | All-You-Can-Eat Buffets | Marcus 590K · Dinheiro Descomplicado 479K · Barry 56K · "how buffets make money" ≈ 33K buscas/mês |
| 2 | All-Inclusive Resorts | Dinheiro Descomplicado 1,4M · Marcus 482K |
| 3 | Pawn Shops | Marcus 497K |
| 4 | Nightclubs | Marcus 433K · Zanroo 472K |
| 5 | Gyms | Mr. Finance 319K · "economics of owning a gym" ≈ 75K buscas/mês |
| 6 | Casinos | Tony Talks 75K · "economics of owning a casino" ≈ 35K buscas/mês |
| 7 | Dollar Stores | Marcus 162K |
| 8 | Used Car Dealerships | Marcus 188K |
| 9 | Cruise Lines (Every Level) | Barry 430K · Dinheiro Descomplicado 738K |
| 10 | Movie Theaters (refazer, ângulo pipoca) | "why is movie theater popcorn so expensive" ≈ 7,2K buscas/mês |

Outros com bom histórico: music labels (429K), money laundering (516K), cafés (232K), souvenir shops (109K), sports teams (130K), music festivals (91K).

**Regra aprendida:** temas de lazer/consumo (viagem, comida, diversão) performam muito melhor que bancos/seguros/hospitais (que ficaram em 200–500 views no Barry Explains).

---

## 6. Canais de referência (EUA/inglês)

| Canal | Criado | Inscritos | Destaques | Estilo |
|---|---|---|---|---|
| **Marcus Explains** `UC3PwuepPoJA-OlFbEFD2hHw` | jul/2026 | 32,4K | 4,9M views; vídeos de ~26 min | boneco cabeça redonda (tipo Cyanide & Happiness) |
| **Mr. Finance** `UC6AwWrRKNrwt83CMJqeTUzw` | jun/2026 | 83,2K | 4,2M views; "The Economics of Owning a…" | **boneco palito** |
| **Dinheiro Descomplicado** (PT-BR) `UCnD7qMT-ymczMl7DIAncZZw` | — | — | adapta temas que estouram em inglês | 2D vintage + boneco palito |
| Barry Explains `UCgPACy3zH-KSkCE1w_xfgPg` | jul/2026 | 2K | formato "Every Level" (430K) | anime — *não* é palito |
| Zanroo Finance, Ned Talks Business, Tony Talks Business | 2025–26 | 6–15K | "economics of owning" | variados |

Vídeo de referência enviado pelo dono: `hoX3psbaong` (Dinheiro Descomplicado, 259K views) — 2D chapado, paleta quente vintage, boneco branco de camiseta verde, gráficos em ciano tipo holograma, transição de papel rasgando, voz calma, lo-fi.

---

## 7. Próximos passos sugeridos
1. Escolher foto de perfil e banner (refazer a escolhida em alta qualidade se precisar).
2. Separar personagens da folha de estilo em arquivos individuais.
3. Atualizar banner, foto, descrição e deixar os 2 vídeos antigos não listados.
4. Roteiro do 1º vídeo novo: *How All-You-Can-Eat Buffets Actually Make Money* (22–27 min, gancho de história real, recibo no final).
5. Produzir 2 vídeos/semana + 3–4 Shorts por vídeo longo (o dado mais chocante de cada um).
