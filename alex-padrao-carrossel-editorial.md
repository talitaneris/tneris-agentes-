# Padrão de Design: Carrossel Editorial

23 de set. de 2026 · Talita Neris

Guia para criar carrosséis na estética editorial minimalista: tipografia grande, pouco texto por slide, muito respiro e fotos com textura de filme. Todas as medidas partem de um canvas de 1080 px de largura.

## 1. Formato e grid

**Canvas:** 1080 × 1350 px (retrato 4:5). Carrossel de 8 a 11 slides.

### Margens
- Margem lateral mínima: 110 px. Padrão recomendado: 160 px.
- Margem superior e inferior mínima: 110 px.
- Área de segurança inferior: nada importante abaixo de 1240 px (os pontinhos do carrossel ficam ali).

### Colunas invisíveis (a assinatura do layout)

| Guia | Posição no eixo X | Uso |
|---|---|---|
| Coluna A | 160 px (15%) | Títulos, frases de abertura, conceitos |
| Coluna B | 430 a 540 px (40% a 50%) | Texto de apoio, definições, respostas |
| Limite direito | 920 px | Fim de qualquer linha |

O texto de apoio nunca começa alinhado ao título. Ele desce e recua para a Coluna B, formando um degrau diagonal. Esse degrau é o que dá o ar editorial.

### Zonas verticais
- Terço superior: microtexto, pergunta de abertura ou título solto.
- Centro óptico (cerca de 45% da altura): bloco principal de texto.
- Terço inferior: resposta, texto de apoio ou assinatura.

Deixe pelo menos 40% da área do slide sem texto.

## 2. Tipografia

**Família única:** Inter Display (gratuita no Google Fonts). Alternativas equivalentes: Inter Tight, SF Pro Display, Helvetica Now Display. Nunca misturar duas famílias no mesmo carrossel.

**Pesos permitidos:** Regular (400), Semibold (600), Bold (700) e ExtraBold (800). Nada de Light, itálico ou caixa alta.

### Escala tipográfica

| Nível | Uso | Tamanho | Peso | Tracking | Entrelinha |
|---|---|---|---|---|---|
| Display | Palavra gigante solta ("o problema?") | 140 a 160 px | Bold | –4% | 1.0 |
| Conceito | Termo principal do slide | 100 a 120 px | ExtraBold | –4% | 1.0 |
| Título | Capa, frase de impacto | 85 a 100 px | Bold | –3% | 1.05 |
| Abertura | Frase que introduz o conceito | 60 a 70 px | Bold | –3% | 1.1 |
| Frase média | Pergunta, resposta curta | 48 a 56 px | Semibold ou Bold | –2% | 1.15 |
| Apoio | Definição, explicação | 38 a 42 px | Regular | –2% | 1.25 |
| Assinatura | Nome no rodapé | 26 px | Bold + Regular | –1% | 1.0 |
| Microtexto | Eco decorativo no topo | 14 a 16 px | Semibold | 0% | 1.4 |

### Regras de escala
- No máximo três níveis por slide.
- O salto entre níveis vizinhos deve ser grande (cerca de 1,5×). Contraste de tamanho é o que cria hierarquia, não enfeite.
- Tracking sempre negativo em títulos. No Canva, espaçamento de letras entre –30 e –40; no texto de apoio, entre –10 e –20.
- Entrelinha fechada em títulos (as linhas quase se tocam) e mais aberta no apoio.

## 3. Regras de texto e ênfase

### Quebra de linha
- De 3 a 5 palavras por linha. Quebre pelo sentido da frase, nunca deixe a caixa de texto decidir.
- Sem hifenização e sem palavra sozinha na última linha.
- Alinhamento à esquerda como padrão. Centralizado só no slide de resolução e no CTA.

### Como dar ênfase
- A ênfase vem apenas da troca de peso: Regular para Bold dentro da mesma frase. Exemplo: "Talvez seu conteúdo precise mais de **você**."
- Destaque no máximo uma ideia por bloco.
- Proibido: sublinhado, caixa alta, itálico, marca-texto, ícones, setas, emojis, caixas ou balões atrás do texto.

### Texto justificado forçado (recurso gráfico)
- Use em uma frase curta de 2 linhas, esticada até a margem direita, para os espaços entre palavras abrirem bastante.
- Também no microtexto do topo da capa e do CTA, repetindo frases de outros slides como um eco.
- No máximo duas vezes no carrossel.

### Quantidade de texto
- Máximo de 40 palavras por slide.
- Um slide, uma ideia.
- Parênteses funcionam como sussurro: "(a síndrome que todo criador já viveu)" vai em tamanho de apoio, recuado à direita.

## 4. Fundos e imagem

### Tipos de fundo (alternar ao longo do carrossel)
- **Foto com clima:** paisagem, objeto, textura, espaço vazio. Nunca foto de banco de imagem com pessoas sorrindo.
- **Fundo liso texturizado:** cor chapada com textura de papel ou linho por cima (opacidade entre 15% e 25%, modo multiplicar ou sobrepor).
- **Tecido ou papel claro:** para os slides de respiro e resolução.

### Critérios de foto
- A foto conversa com a frase por metáfora, não por ilustração literal (manequim para "ideal", cinema para "palco", conchas para "se esconder").
- Precisa ter uma área calma e sem detalhe onde o texto vai morar.
- Enquadramento amplo, com assunto pequeno e muito espaço negativo.
- Pode ser colorida ou preto e branco. Evite fotos muito nítidas e digitais.

### Grão de filme (obrigatório)
- Aplicar a mesma camada de grão em todos os slides, inclusive nos lisos. É isso que unifica fotos de origens diferentes.
- No Canva: Editar foto > Ajustes > Granulado entre 20 e 35. Ou sobrepor uma textura de ruído em PNG com cerca de 20% de opacidade.
- Opcional: vinheta leve nas bordas e sombras um pouco levantadas para o aspecto analógico.

### Legibilidade
- Texto sempre sobre a área mais uniforme da foto.
- Se não houver contraste, escureça ou clareie a foto inteira. Nunca coloque retângulo atrás do texto.
- Texto semitransparente (60% a 80%) só em títulos grandes, quando a foto precisa aparecer através das letras.

## 5. Modelos de slide

Sete layouts reutilizáveis. Posições em px no canvas de 1080 × 1350.

**M1. Capa**
- Microtexto justificado no topo (y 110), de margem a margem, repetindo as perguntas do slide seguinte.
- Título em 4 linhas na Coluna A, começando em y 270. Nível Título.
- Frase entre parênteses na Coluna B, logo abaixo do título. Nível Apoio.
- Assinatura no canto inferior esquerdo (x 190, y 1080): nome em Bold, sobrenome em Regular.

**M2. Pergunta e resposta em diagonal**
- Pergunta no terço superior, Coluna A. Nível Frase média, Regular com o final em Bold.
- Resposta no terço inferior, Coluna B. Mesmo nível.
- A foto ocupa o meio e liga os dois blocos.

**M3. Conceito com definição**
- Fundo liso texturizado.
- Abertura na Coluna A, a partir de y 300.
- Conceito logo abaixo, colado (espaço de 0 a 10 px).
- Definição na Coluna B, 60 a 80 px abaixo do conceito.
- Bloco inteiro centralizado na vertical.

**M4. Texto sobre foto lateral**
- Foto com o assunto de um lado (ex.: à direita).
- Texto no quadrante oposto, parte superior. Primeiro parágrafo em Regular, segundo em Bold, separados por 50 px.

**M5. Virada**
- Palavra Display no topo, semitransparente, ocupando quase toda a largura.
- Frase justificada forçada no centro.
- Texto curto de apoio na Coluna B, terço inferior.

**M6. Respiro**
- Fundo claro (tecido ou papel).
- Uma frase só, de 5 a 12 palavras, em tamanho de Frase média ou Apoio.
- Deslocada do centro (Coluna B) ou centralizada. Pelo menos 75% do slide vazio.

**M7. CTA**
- Microtexto em eco no topo e no rodapé, com baixa opacidade.
- Título centralizado explicando onde o assunto continua.
- Prova visual no centro (print, lista de aulas, capa do produto) com cantos arredondados de 24 px.
- Chamada em uma linha abaixo, nível Frase média Regular.
- Assinatura igual à da capa.

## 6. Sequência narrativa

| Slide | Função | Modelo | Fundo |
|---|---|---|---|
| 1 | Gancho: afirmação que incomoda | M1 Capa | Foto escura |
| 2 | Identificação: pergunta e primeira resposta | M2 | Foto |
| 3 | Autoridade: nome do conceito e definição | M3 | Liso texturizado |
| 4 | Consequência: por que isso importa | M4 | Foto P&B |
| 5 | Aprofundamento: segundo conceito | M3 | Liso texturizado |
| 6 | Virada: o problema | M5 | Foto intensa |
| 7 | Metáfora visual | M4 ou texto dentro da cena | Foto |
| 8 | Desaceleração | M6 | Tecido claro |
| 9 | Resolução: a frase que fica | M6 centralizado | Papel claro |
| 10 | Pergunta de reflexão | Título grande no terço inferior | Foto clara |
| 11 | Chamada para ação | M7 | Liso escuro |

### Ritmo
- Nunca repetir o mesmo tipo de fundo em dois slides seguidos.
- O carrossel vai ficando mais claro e mais vazio até a resolução, e volta a escurecer no CTA.
- Tamanho do texto cai do início para o meio: gritar na capa, sussurrar na resolução.
- Para carrosséis de 8 slides, junte 4 e 5, e 7 e 8.

## 7. Checklist antes de publicar

- [ ] Canvas em 1080 × 1350 px.
- [ ] Uma família tipográfica, no máximo três níveis por slide.
- [ ] Tracking negativo em todos os títulos.
- [ ] Texto de apoio recuado na Coluna B.
- [ ] Nenhuma linha com mais de 5 palavras e nenhuma palavra sozinha no fim.
- [ ] Ênfase feita só com Bold, uma ideia por bloco.
- [ ] Pelo menos 40% de cada slide vazio.
- [ ] Mesmo grão aplicado em todos os slides.
- [ ] Nada importante abaixo de y 1240.
- [ ] Tipos de fundo alternados, sem repetição em sequência.
- [ ] Assinatura na capa e no CTA, na mesma posição.
- [ ] Leitura testada no celular, com o brilho baixo.
