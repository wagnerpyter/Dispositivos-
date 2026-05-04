# Dispositivo da Recusa

Arte interativa digital — instalação em tela vertical  
2026

---

## O que é

Uma superfície escura habitada por organismos microscópicos — fragmentos de plâncton, esporos, resíduos de texto ilegível. São dados. Arquivos que existiam antes de um reset não solicitado apagar tudo.

O toque não cria. O toque afasta.

Os organismos desviam com calma, sem urgência, sem drama. O rastro que fica é ausência. Um corredor de vazio permanente onde a vida recuou antes de ser alcançada.

Os organismos não voltam.

Com o tempo e com muitas mãos, a superfície se fragmenta. A vida se concentra nas bordas. O centro esvazia. A obra final é o mapa involuntário de onde as pessoas colocaram os dedos.

---

## Origem

Em menos de dois dias, dois aparelhos Moto E20 reiniciaram sozinhos após atualizações automáticas não solicitadas e instalação de bloatware sem permissão. Pesquisas, arquivos e memória digital acumulada ao longo de anos foram perdidos sem aviso e sem recuperação.

Não houve descuido. Foi feito a alguém.

A obra nasce dessa perda específica e se abre para todas as perdas do mesmo tipo — qualquer sistema que atravessa uma vida, reorganiza sem consentimento e segue em frente.

---

## Referência conceitual

O título e o comportamento dos organismos derivam de *Bartleby, the Scrivener* (Herman Melville, 1853) e da leitura filosófica da não-vontade como forma de resistência.

Bartleby não recusa com violência. Não obedece. Permanece numa zona intermediária onde o gesto perde espessura. Os organismos fazem o mesmo — preferem não estar onde o dedo está. A fuga é sua arquitetura de sobrevivência. O vazio que deixam é o rastro dessa preferência no mundo.

> *"Sua presença se torna um pequeno vazio arquitetônico: tudo continua de pé, mas já não funciona do mesmo modo."*

---

## Comportamento

**Estado inicial**  
A tela está completamente habitada. Organismos em densidade máxima, movendo-se em padrões lentos. Nenhum rastro. A obra existe antes do visitante.

**Durante o toque**  
O dedo cria uma zona de repulsão vetorial. O raio cresce com a velocidade do gesto — movimento lento abre canal fino, pressão rápida abre rasgo largo. Os organismos desviam com calma. As bordas do rastro ficam levemente mais densas com os que fugiram.

**Após o toque**  
O vazio permanece. Sem regeneração. Sem retorno.

**Multi-toque**  
Cada dedo tem raio de repulsão independente. Dois dedos simultâneos criam zonas que se somam. Com muitas mãos, a superfície viva vai sendo fragmentada progressivamente.

**Sessão longa / uso coletivo**  
A obra muda dependendo de quem passou e como. O resultado final é a soma de todos os gestos que não se conheceram. O padrão revela onde a atenção foi intensa e onde não chegou.

**O reset**  
Reiniciar é um gesto com peso próprio. A obra funciona nos dois casos — com ou sem reset diário — sem precisar explicar nenhum dos dois.

---

## Elementos visuais

### Organismos

| Tipo | Forma | Representa |
|------|-------|------------|
| Ponto | Halo difuso + núcleo denso | Dado mínimo — um byte, uma unidade de memória |
| Bastão | Fragmento alongado em rotação lenta | Arquivo parcial — o container sem o conteúdo |
| Texto | Fonte monoespaçada em baixa opacidade | Metadado — o nome que sobrou sem o arquivo |

### Fragmentos de texto

`img_` `nota` `.jpg` `.pdf` `save` `doc_` `foto` `2024` `msg_` `back` `tmp_` `err_` `lost` `///` `...` `reset` `01/0` `rascunho` `sem t` `perdi` `apagou` `—`

### Cor

| Cor | Estado | Significado |
|-----|--------|-------------|
| Branco-azulado frio | Repouso | Organismo não deslocado |
| Âmbar dourado | Borda | Calor que resistiu — densidade de sobrevivência |
| Transição frio → âmbar | Margem | História do deslocamento escrita em cor |

### O vazio

Não é efeito visual. É consequência. A forma revela o gesto: rastro fino = movimento lento; zona ampla = pressão rápida. Múltiplos rastros cruzados = muitas sessões, muitas mãos.

---

## Arquivos

```
recusa/
├── index.html                  — página de entrada do subdomínio
├── dispositivo_da_recusa.html  — a obra (arquivo único, offline)
├── legenda_dispositivo.md      — legenda dos elementos visuais
└── README.md                   — este arquivo
```

---

## Instalação

Nenhuma. Arquivo único HTML.

Abre em qualquer browser moderno. Funciona offline. Não depende de servidor, biblioteca externa, framework ou conexão.

Para instalação física: copiar `dispositivo_da_recusa.html` para o dispositivo. Abrir uma vez. O browser armazena localmente. Modo avião. Tela cheia.

**Dispositivos testados**  
Android (Chrome) — Moto E20 e similares  
Funciona em qualquer dispositivo com tela sensível ao toque e browser moderno

**Formatos possíveis**  
Celular vertical — experiência individual  
Tablet fixo em galeria — instalação de médio porte  
Tela de 55"+ ou projeção no chão — instalação imersiva, escrita por ausência possível  
Múltiplas telas lado a lado — a palavra se fragmenta entre os painéis

---

## Implementação técnica

HTML5 Canvas com renderização em tempo real  
JavaScript puro — sem dependências  
Sistema de agentes autônomos com comportamento de repulsão vetorial  
Grid de vazio permanente em memória (`Uint8Array`)  
Eventos nativos: `touchstart`, `touchmove`, `touchend`, `touchcancel`  
Suporte a múltiplos toques simultâneos por `touch.identifier`  
`touch-action: none` — sem interferência do scroll do browser  
Renderização aditiva (`globalCompositeOperation: lighter`) para bioluminescência  
Camada de cicatriz em canvas offscreen para rastros persistentes  

---

## Referências

**Literatura**  
Herman Melville — *Bartleby, the Scrivener* (1853)

**Teoria**  
Cuthbert, K. (2021) — sexualidade compulsória e allonormatividade  
Vares, T. (2021) — leituras retrospectivas de Bartleby por comunidades assexuais  
Broussard, G. (2022) — personagens que preservam formas de experiência reconhecidas por comunidades futuras

**Luto digital**  
Pesquisas sobre impacto emocional da perda de dados — Universidade de Würzburg  
Revisões sistemáticas brasileiras sobre luto digital (2014–2024)

**Arte interativa**  
Myron Krueger — *Videoplace* (1969–1985)  
teamLab — *Continuity*, *Borderless*  
Tiago Martins & Penousal Machado — *VisualyzARt* (2013)

---

## Sobre a obra

Não oferece recompensa visual imediata.  
Não responde com espetáculo.  
Funciona por subtração.

O visitante não constrói. Ele esvazia.  
E só depois percebe.

---

*Dispositivo da Recusa, 2026*
