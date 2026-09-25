# Padrão de Design: Apresentação de Aula e Material de Apoio

Extraído da Oficina "IA na Prática para Negócios" (26/09/2026): apresentação de 44 slides e guia de implementação de 21 páginas, aprovados pela Talita como referência para todo material de aula, oficina, mentoria e evento presencial.

Os dois arquivos seguem o mesmo sistema. A apresentação é projetada na sala (16:9). O guia é o que a pessoa leva e preenche (A4).

---

## 1. Paleta dos materiais

| Papel | Cor | Onde aparece |
|---|---|---|
| Grafite (fundo escuro) | #17171B | Slides escuros, blocos de prompt, card de encerramento |
| Texto escuro | #17181C | Títulos e corpo em fundo claro |
| Off-white | #F6F6F7 | Texto de corpo em fundo escuro, cards claros (#F5F5F6) |
| Branco | #FFFFFF | Fundo dos slides claros, títulos em fundo escuro |
| Azul acinzentado | #94B1C8 | Destaque em fundo escuro: segunda linha do título, ✓ de lista, nome de ferramenta |
| Azul petróleo | #3D6A85 | Destaque em fundo claro: palavra-chave do título, botão, passo ativo, borda de dica |
| Vinho | #6B1F2A | Rótulos pequenos, números de passo, borda de card em destaque, tiles do guia |
| Rosé | #CFA9AE / fundo #F6ECED | Tile claro alternado com o vinho no guia |
| Cinza de apoio | #55575E | Rótulo em fundo claro, texto secundário |
| Creme | #F6F3EC | Fundo de caixas de apoio no guia |
| Azul gelo | #E7ECF1 | Fundo do ícone quadrado dos níveis |

Regra de destaque: **uma** ideia por título ganha cor. Em fundo escuro, azul acinzentado. Em fundo claro, azul petróleo. Vinho nunca vai em título, só em rótulo, número e borda.

Essa paleta é a mesma família da referência da cadeira vermelha (creme, azul #94B1C8, vinho, quase preto): foi adotada para os materiais de aula.

---

## 2. Tipografia

- Família: **Inter** (uma só). Os PDFs saíram com fonte substituta (Liberation/Arial) porque a Inter não carregou na exportação; ao refazer, exportar com a Inter embutida.
- Exceção única: **Caveat Bold** (manuscrita) só para legenda de print, como anotação à mão ("Rotina Claude", "Tarefas Agendadas Cowork"). Nunca em título ou corpo.
- Sem itálico, exceto em citação e em texto de prompt de exemplo.

### Escala da apresentação (slide 960 × 540)

| Nível | Tamanho | Peso | Uso |
|---|---|---|---|
| Título de abertura, seção ou encerramento | 60 | Bold | "IA na Prática para Negócios", "Contexto Você", "Uma função real. Rodando." |
| Título de slide | 36 | Bold | "Projetos = seu cérebro reutilizável" (2 linhas, centralizado) |
| Subtítulo | 18 | Regular, cinza | Uma frase que explica o título |
| Frase de fechamento do slide | 17 | Bold | "A resposta pode ser da IA. A decisão continua sendo sua." |
| Título de card | 12,5 a 14 | Bold | "Identidade", "Claude + Gmail →" |
| Texto de card | 9,5 a 10 | Regular | Descrição curta, 1 ou 2 linhas |
| Rótulo (eyebrow) | 8,5 a 9,5 | Bold, caixa alta, espaçado | "• CAPÍTULO 1 · O PAPEL DA IA", "NÍVEL 2", "PROMPT DE EXEMPLO · COMO USAR" |

Em 1920 × 1080, multiplicar tudo por 2.

### Escala do guia (A4, 595 × 842 pt)

| Nível | Tamanho | Peso |
|---|---|---|
| Título da capa | 47 | Regular (fino), alinhado à esquerda |
| Título de seção | 23 | Bold |
| Lead (primeiro parágrafo) | 12,5 | Regular, cinza |
| Corpo | 11,5 a 12 | Regular, com **negrito** na palavra que importa |
| Título de card ou tile | 13,5 a 14,5 | Bold |
| Rótulo | 8 a 8,5 | Bold, caixa alta, vinho, com ponto "•" antes |

---

## 3. Apresentação (slides 16:9)

**Estrutura fixa de todo slide**
- Tudo centralizado no eixo vertical do slide. Bloco de conteúdo ocupa de x 160 a x 800 (dois terços da largura)
- Ordem de cima para baixo: ícone (opcional) → rótulo → título → subtítulo → conteúdo visual → frase de fechamento (opcional)
- Rodapé discreto: contador "1 / 44" em pílula no canto inferior esquerdo e setas ‹ › no inferior direito

**Ritmo**
- Alterna fundo grafite e fundo branco. Nunca mais de dois seguidos iguais
- Slide de abertura de bloco (60 pt) sempre em fundo grafite ou branco sozinho, sem card
- Abertura e encerramento em grafite, com a segunda linha do título em azul acinzentado

**Componentes**
| Componente | Como é |
|---|---|
| Rótulo com ponto | "• CAPÍTULO 2 · DIVISÃO DE PAPÉIS", ponto na cor de destaque |
| Pílula de nível | "NÍVEL 3" dentro de pílula com borda fina, acima do título |
| Ícone de nível | Ícone de linha pequeno dentro de quadrado arredondado azul gelo |
| Fórmula no título | "Chat = conversa", "Skill = ensine seu jeito de fazer": conceito, sinal de igual, tradução simples |
| Fluxo em cards | 3 cards lado a lado ligados por →. O card do meio (o que a IA faz) é invertido: fundo grafite no slide claro |
| Card de destaque | Mesmo card, com borda fina vinho |
| Grade de passos | 2 × 3 cards claros, número em vinho pequeno (01, 02), título bold, descrição de uma linha |
| Lista numerada | Número em vinho à esquerda, título bold, detalhe em cinza embaixo, linha fina entre itens |
| Duas colunas | "A IA faz bem" × "Continua sendo humano", rótulo de cada coluna colorido, linhas finas entre itens |
| Caixa de prompt | Card grafite com borda esquerda vinho, rótulo azul "PROMPT DE EXEMPLO · COMO USAR", texto em itálico entre aspas |
| Card de ferramenta | Logo do Claude + logo da ferramenta, pílula "CONECTOR 3", nome grande, descrição curta, caixa de prompt |
| Chips | Tags em pílula com borda fina ("Pesquisar", "Resumir", "Sites e aplicativos") |
| Print de tela | Pequeno, centralizado, com sombra suave e bordas esfumadas. Legenda manuscrita em Caveat quando precisa apontar algo |
| Linha do tempo | Círculos numerados ligados por →, o último preenchido em azul petróleo |
| Oferta | Card escuro centralizado, rótulo azul, preço grande com centavos pequenos ("R$ 2.500,00"), condição em rótulo embaixo |

**Texto**
- Título em até 2 linhas, quebra pelo sentido
- Subtítulo em uma frase, até 2 linhas
- Card com no máximo 1 ou 2 linhas de descrição
- Slide de conteúdo com no máximo 6 cards

---

## 4. Guia de implementação (A4 impresso ou PDF)

**Capa**
- Barra de navegação no topo com as seções em caixa alta pequena (MANHÃ · SETUP · CONTEXTO VOCÊ · ...)
- Rótulo espaçado "OFICINA PRESENCIAL"
- Título grande e fino, alinhado à esquerda, em 2 linhas
- Linha de informações em colunas: DATA, MANHÃ, TARDE, com rótulo bold e valor regular embaixo, separadas por linhas finas

**Seções**
- Rótulo vinho com ponto ("• BLOCO 1", "• CAPÍTULO 3", "• TARDE · PARTE 2"), título bold, lead em cinza, corpo com negrito nas palavras-chave
- Linha fina separando seções

**Componentes**
| Componente | Como é |
|---|---|
| Tiles 2 × 2 | Alternam vinho (texto branco) e rosé (texto vinho) em xadrez, número pequeno em cima ("01") |
| Bloco de prompt | Card grafite, rótulo "PROMPT · COPIE E COLE NA IA", texto claro, botão em pílula azul petróleo "COPIAR PROMPT", nota "Salve como: ..." embaixo |
| Perguntas de referência | Título "Referência · Pilar 01: ...", instrução em cinza, lista com linhas finas e a palavra-chave de cada pergunta em negrito |
| Cards de escolha | Rótulo colorido em pílula ("CONECTA WHATSAPP", "COWORK"), título bold, descrição, linha "Roda direto no WhatsApp" no pé |
| Espaço de resposta | Pergunta em bold seguida de linha em branco para escrever |
| Dica | Caixa com borda azul petróleo, rótulo "• DICA RÁPIDA" |
| Checklist | Caixas de seleção quadradas por nível, para imprimir e riscar |
| Kit para copiar | Cards pequenos com rótulo "• ABRIR E COPIAR", título e onde roda |
| Encerramento | Card grafite, rótulo "• ENCERRAMENTO", título em itálico, texto claro, rodapé com evento, data e nome |

---

## 5. Relação com as outras peças do mesmo evento

Tudo de um mesmo evento sai com a mesma paleta, a mesma fonte e o mesmo nome escrito do mesmo jeito:
- Arte de divulgação (feed e stories): ver seção "ARTE DE EVENTO E DIVULGAÇÃO" no SKILL.md
- Apresentação: este documento, seção 3
- Guia: este documento, seção 4
- Certificado, crachá, slide de oferta: usar os componentes acima (card escuro, rótulo, título em dois tons)

---

## 6. Checklist antes de entregar material de aula

- [ ] Inter embutida no PDF (sem fonte substituta)
- [ ] Um destaque de cor por título, na cor certa para o fundo (azul acinzentado no escuro, azul petróleo no claro)
- [ ] Vinho só em rótulo, número e borda
- [ ] Slides alternando grafite e branco
- [ ] Contador de página e setas no rodapé
- [ ] Todo prompt em caixa própria, com rótulo e instrução de onde salvar
- [ ] Prints legíveis ou esfumados de propósito, nunca pixelados sem intenção
- [ ] Nenhum dado pessoal ou de cliente aparecendo em print
