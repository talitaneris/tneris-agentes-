# PRD de Design: Instagram @tijoleste

**Cliente:** Tijoleste, loja de materiais de construção no Tatuapé/SP, especialista em churrasqueiras de tijolinho, há 36 anos no mercado
**Responsável:** Talita Neris (TNERIS Digital)
**Versão:** 1.0, 20/10/2026
**Fontes analisadas:**
- Canva "TEMPLATES  Tijoleste " (DAGueP1YG1A, 58 páginas, todas 1080x1350)
- Canva "Tijoleste / Tamanho 1:1" (DAFlt6-Kcls, 58 páginas, **também 1080x1350 (4:5), apesar do nome**). É praticamente a mesma estrutura do arquivo de templates, com algumas fotos e textos trocados (ex.: pág. 6, 7, 10, 31, 42).
- Canva "Tijoleste" (DAGahgWLLoc, 1 página quadrada). **Não é o logo:** é um post/aviso "LEMBRETE – Estamos abertos até às 13h".
- Brand Kit kAGDKJHvPSA: o conector do Canva só devolve o ID. **Não consegui ler as cores, fontes e logos cadastrados no kit.**
- Posts recentes já publicados no perfil (29/09 a 19/10/2026) e foto de perfil, salvos em /workspace/tijoleste-ref/
- Pauta: /workspace/tijoleste-pauta.md (seções 0 e 1)

Legenda: **[observado]** = visto nos arquivos. **[sugestão]** = inferência ou recomendação minha, ainda não validada pela Talita/cliente.

---

## 1. Paleta de cores

| Papel | Hex | Origem |
|---|---|---|
| Vermelho tijolo (cor principal da marca) | **#962D18** | [observado] amostra do "quadrado" de cor da pág. 1 dos templates (guia de estilo) e dos títulos em vermelho (págs. 38, 42) |
| Preto/grafite (fundos escuros) | **#1C1A1A** | [observado] quadrado de cor da pág. 1 e fundo dos layouts escuros (págs. 35–58) |
| Cinza claro (apoio, pílulas de informação) | **#DBD8D8** | [observado] quadrado de cor da pág. 1 e pílulas de telefone/endereço (pág. 38) |
| Branco (fundos claros, texto sobre escuro) | **#FFFFFF** | [observado] fundos dos posts estilo "tweet" e textos sobre fundo preto |
| Vermelho tijolo escuro (fundo de post de avaliação) | #802E19 | [observado] post de 16/10 (print da avaliação do Google) |
| Textura do logo | tons #B94833 / #BA604E / #8B3D30 | [observado] amostra do preenchimento de tijolinho do logo (foto de perfil) |

Observações:
- [observado] O arquivo DAGahgWLLoc ("Lembrete") usa um vermelho vivo com gradiente que fica fora da paleta acima. Parece uma peça avulsa.
- [observado] Algumas páginas do arquivo de templates ainda são modelos genéricos de outra marca: pág. 2 "Borcelle / Imobiliária", pág. 4 "Testimonial" com texto em inglês, pág. 5 em magenta com "@grandesite". **Não usar como referência de marca.**
- [sugestão] Vermelho #962D18 sobre fundo de tijolinho ou de foto quente dá pouco contraste. Nesses fundos, usar texto branco e deixar o vermelho para contornos e detalhes.

## 2. Tipografia

A API do Canva não informa o nome das fontes. A identificação abaixo é **visual** [observado/sugestão: confirmar no Canva]:

| Uso | Fonte (identificação visual) | Onde aparece |
|---|---|---|
| Títulos de impacto | **Montserrat Black / ExtraBold, em CAIXA ALTA**, às vezes itálico (ex.: "HOJE.", "MATERIAL", "COMO CAMINHAR CORRETAMENTE SOBRE AS TELHAS") | págs. 1, 31, 32, 38, 42, 49 |
| Subtítulos e texto de apoio | **Montserrat Regular/Medium**, com o destaque em Montserrat Bold na cor vermelha | págs. 6–12, 33–58 |
| Microtexto / assinatura | Montserrat Bold em caixa alta com **espaçamento entre letras bem aberto** ("@ T I J O L E S T E", "A R R A S T A  P A R A  O  L A D O", "LEIA A LEGENDA", "MAIS INFOS NA LEGENDA") dentro de uma pílula com contorno vermelho | págs. 31, 38, 42, 46–58 |
| Posts estilo "tweet" | Sans neutra parecida com **Roboto/Inter** (nome em negrito + @tijoleste em cinza + selo azul de verificado) e microtexto itálico monoespaçado "– ARRASTA PARA O LADO" | págs. 13–30 |

[observado] A pág. 1 dos templates funciona como mini guia de estilo: os 3 quadrados de cor (preto, cinza, vermelho) e 3 pesos de "Inserir um subtítulo" (regular, black e bold).

## 3. Logo

- [observado] Logo = **palavra "TIJOLESTE" em caixa alta, com preenchimento de textura de tijolinho vermelho e o símbolo ®**, sobre fundo branco (é a foto de perfil do Instagram, /workspace/tijoleste-ref/profile_logo.jpg).
- [observado] Nos templates, o logo entra como **avatar redondo pequeno** (imagem MAFnPMbJXig, cerca de 44–55 px) ao lado de "Tijoleste" + "@tijoleste", imitando um cabeçalho de perfil (págs. 6–36).
- [observado] Também aparece um **ícone de linha em vermelho** (tijolos + colher de pedreiro) como marca secundária (págs. 1 e 38).
- [observado] Em vários layouts a assinatura é só o texto "@TIJOLESTE" espaçado, sem o logo.
- [não verificado] Não consegui abrir o arquivo do logo pela API (acesso negado ao asset) nem ver os logos do Brand Kit. Não sei se existe versão vetorial, versão negativa (branca) ou PNG transparente.
- [sugestão] Regras de uso:
  - sobre fundo escuro ou de tijolinho, usar o logo dentro de um círculo ou caixa branca, como no avatar dos templates;
  - não esticar, não recolorir e não aplicar a textura em outros textos;
  - manter respiro mínimo de cerca de 1/2 da altura da palavra ao redor;
  - largura mínima de ~120 px em 1080 px.

## 4. Padrões de layout por formato

### 4.1 Post de feed 4:5 (1080x1350): o formato real de todos os templates
[observado] Famílias de layout recorrentes:
1. **Diagonal preto + foto** (págs. 1, 42, 46–58): bloco preto #1C1A1A cortado na diagonal, com a foto do produto do outro lado. Título Montserrat Black em caixa alta (vermelho + branco alternando linhas), "@TIJOLESTE" espaçado e a pílula "ARRASTA PARA O LADO" com seta.
2. **Foto inteira + título grande** (pág. 31): foto clara ocupando o fundo todo, título Montserrat Black vermelho em caixa alta, cabeçalho de perfil (logo + Tijoleste + @tijoleste) e pílula "LEIA A LEGENDA".
3. **Estilo "tweet"** (págs. 13–30): fundo branco, cabeçalho de perfil com logo e selo de verificado, texto de 1 a 3 frases e uma foto com cantos arredondados.
4. **Editorial cobogó** (págs. 6–12): fundo branco com formas curvas cinza-claro bem sutis, faixa vertical vermelha, título com destaque em vermelho bold e foto com cantos arredondados.
5. **Informativo / contato** (pág. 38): foto de produto recortada, título MATERIAL em vermelho itálico black, pílulas cinza com telefone (11) 99795-4030 e endereço (Av. Salim Farah Maluf, 1000 – Tatuapé, São Paulo – SP).
- [observado] Margem lateral típica de ~108 px (10%) e textos alinhados à esquerda.

### 4.2 Post 1:1 (1080x1080)
- [observado] Nenhum template 1:1 de verdade foi encontrado. O arquivo "Tamanho 1:1" está em 4:5. O único quadrado é o "Lembrete" (DAGahgWLLoc).
- [sugestão] Para quadrado, adaptar o layout 4:5 mantendo as margens de 108 px e testar o redimensionamento no Canva.

### 4.3 Carrossel
- [observado] Capa com título grande + pílula "ARRASTA PARA O LADO". Slides internos no mesmo fundo e na mesma família (ex.: págs. 6–12 cobogó, 22–30 pisos e bloco ecológico, 42–45 telhas, 49–55 panelas de ferro). O último slide traz uma chamada de engajamento ("Esse post foi útil? Curta, comenta e compartilha", "Agora conta, qual desses benefícios…").
- [observado] Em alguns slides a diagonal ou a foto continua de um slide para o outro (panorâmica, págs. 46–49 e 53–55).

### 4.4 Capa de Reel 9:16 (1080x1920)
- [observado] Não há template 9:16 nos arquivos do Canva. Os Reels "TIJOLESTE responde" já publicados (01/10 e 19/10) usam como capa o próprio frame do vídeo, com a figurinha de pergunta do Instagram ("TIJOLESTE responde 👇" + pergunta) no topo.
- [sugestão] Zona segura: o grid do perfil corta a capa no centro.
  - **4:5 → y 285 a 1635**
  - **1:1 → y 420 a 1500**
  - Manter **todo o texto principal e o logo entre y ≈ 460 e 1460**, com margens laterais de ≥ 70 px.
  - Acima de y 250 e abaixo de y 1650 deixar só a textura (a interface do Reel cobre essas áreas).

### 4.5 Stories (1080x1920)
- [observado] Nenhum template de Stories nos arquivos. Pela pauta, avisos, horários e feriados vão **só** para os Stories.
- [observado] O "Lembrete" (DAGahgWLLoc) mostra a linguagem de aviso usada: card branco tipo janela, título em vermelho, botão "VEM PRA TIJOLESTE", telefone (11) 2694-9333 e endereço com CEP 03076-000.
- [sugestão] Para Stories, adaptar esse card ao fundo #1C1A1A ou de tijolinho, com o texto entre y 250 e 1650 e figurinha de link para o WhatsApp.

## 5. Estilo de foto
- [observado] Os posts recentes usam **fotos reais da loja e de obras**: churrasqueiras de tijolinho (vermelho e bege) com forno e fogão a lenha, estoque de tijolos e telhas nas prateleiras, caminhão de entrega e pátio. Foto de celular, vertical, com luz natural.
- [observado] Os templates antigos usam fotos de banco (capacete amarelo, plantas, cozinha clara, panelas de ferro, cobogós) recortadas ou com cantos arredondados.
- [observado] Os Reels são talking-head de uma porta-voz da loja, com legenda automática em branco ou amarelo.
- [sugestão] Dar prioridade às fotos reais da loja (são mais autênticas e combinam com o tom "próximo"). Usar banco de imagens só para textura ou ilustração e evitar fotos frias e genéricas.

## 6. Tom e regras de texto (da pauta)
- Tom **comercial, acolhedor e próximo, agradecido aos clientes**. Texto limpo. **Poucos emojis: 🧱🔥.** Sempre com CTA no final. Nos Reels, a pessoa fala em 1ª pessoa.
- **Slogan em toda legenda, antes do CTA:** *Tijoleste. Onde o seu churrasco começa.* (usar sempre igual)
- **CTA padrão:** "Fala com nossos consultores pelo WhatsApp (link na bio)" ou "Passe na Tijoleste: seg a sex a partir das 8h, sábado até as 13h."
- Link da bio: wa.me/5511997954030. Geotag: Tatuapé, São Paulo.
- Hashtags: de 5 a 8 por post, do banco da pauta (locais, nicho e marca #tijoleste #tijolesteresponde).
- Avisos, horários e feriados: só nos Stories, nunca no feed.
- Todo texto em português do Brasil.

## 7. Série "Tijoleste Responde": padrão de capa
Regras da pauta [observado na pauta]: mesma abertura em todo episódio ("Tijoleste Responde: [pergunta]"), pergunta na tela no primeiro segundo, **capa padronizada com fundo de tijolinho e a pergunta em letra grande**, episódios numerados.

Padrão definido na capa #1 (Canva "Tijoleste Responde #1 – Capa Reel"), a ser reutilizado [sugestão]:
| Elemento | Especificação |
|---|---|
| Formato | 1080x1920, PNG |
| Fundo | parede de tijolinho aparente em largura total, escurecida com um véu #1C1A1A a ~50% e uma faixa central um pouco mais escura para leitura |
| Logo | avatar redondo branco com a palavra TIJOLESTE®, 160 px, centralizado, y ≈ 480 |
| Selo da série | "TIJOLESTE RESPONDE #N" em Montserrat Bold caixa alta, espaçado, branco, 24 px, dentro de uma pílula com contorno vermelho #962D18 (880x76, y ≈ 672) |
| Pergunta | Montserrat Black caixa alta, **branco**, ~92 px, centralizada, entrelinha 1,05, largura 940 px, até 4 linhas (y ≈ 800–1200) |
| Assinatura | "@TIJOLESTE" espaçado, branco, 30 px, y ≈ 1340 |
| Zona segura | todos os elementos entre y 480 e 1376, cabem inteiros no recorte 1:1 e no 4:5 |
| Para o próximo episódio | duplicar o design e trocar só o número e a pergunta (até ~50 caracteres). Se passar de 4 linhas, reduzir o corpo para 80 px |

## 8. Fazer / Não fazer

**Fazer**
- Usar só a paleta #962D18 / #1C1A1A / #DBD8D8 / #FFFFFF [observado]
- Títulos em Montserrat Black caixa alta, com uma palavra ou linha de destaque em vermelho quando o fundo for claro [observado]
- Assinar com "@TIJOLESTE" espaçado ou com o avatar do logo [observado]
- Pílula com contorno vermelho para microchamadas ("ARRASTA PARA O LADO", "LEIA A LEGENDA") [observado]
- Fotos reais da loja e das obras entregues [sugestão]
- Slogan + CTA de WhatsApp em toda legenda, com no máximo 1–2 emojis 🧱🔥 [pauta]
- Texto importante da capa de Reel dentro da zona segura central [sugestão]

**Não fazer**
- Não usar as páginas genéricas que sobraram nos templates (Borcelle, Testimonial em inglês, magenta "@grandesite") [observado]
- Não colocar texto vermelho sobre tijolinho ou foto quente (baixo contraste) [sugestão]
- Não deformar, recolorir ou recortar o logo [sugestão]
- Não postar aviso de horário ou feriado no feed [pauta]
- Não exagerar nos emojis nem usar outros além de 🧱🔥 sem motivo [pauta]
- Não deixar textos em inglês ou placeholders ("Inserir um subtítulo", [nome]) [observado nos templates]
- Atenção [observado]: no texto "@tijoleste" do cabeçalho da pág. 31 dos templates existe um **link escondido para instagram.com/isabelaaraujo.nutri**. Remover antes de reutilizar esse layout.

## 9. Pendências / a validar com a Talita
1. Conteúdo real do Brand Kit kAGDKJHvPSA (cores, fontes e logos), que não é legível pela API.
2. Nome exato das fontes (a identificação visual indica Montserrat).
3. Arquivo do logo em alta resolução / vetor / versão negativa.
4. Qual telefone usar nas peças: (11) 99795-4030 (template e WhatsApp da bio) ou (11) 2694-9333 ("Lembrete").
5. Numeração da série: já existem Reels "TIJOLESTE responde" publicados em 01/10 e 19/10. Confirmar se a numeração começa mesmo no #1 com o episódio de hoje.
