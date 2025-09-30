# 📋 Mapeamento de Campos dos Widgets

Este documento mapeia todos os campos `WID_FIELD_` utilizados em cada tipo de widget do sistema CRM Imobiliário.

## 📖 Índice

- [Widgets de Artigos](#widgets-de-artigos)
- [Widgets de Imóveis](#widgets-de-im%C3%B3veis)
- [Widgets de Formulários](#widgets-de-formul%C3%A1rios)
- [Widgets de Mídia e Social](#widgets-de-m%C3%ADdia-e-social)
- [Widgets de Mapas](#widgets-de-mapas)
- [Widgets de Conteúdo](#widgets-de-conte%C3%BAdo)
- [Widgets Diversos](#widgets-diversos)

---

## 🔍 Widgets de Artigos

### ARTIGO_DETALHA
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | radio | Mostrar Título | `1` | `1` = Sim, `0` = Não |

### ARTIGO_LISTA
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | select | Ordenação da Lista de Artigos | - | `CONTADOR` = Mais Visualizados, `DATA` = Mais Recentes |
| `WID_FIELD_2` | radio | Listar somente artigos com Imagem | `0` | `1` = Sim, `0` = Não |
| `WID_FIELD_3` | slider | Quantidade de artigos a Listar | `10` | Min: 1, Max: 50 |
| `WID_FIELD_4` | check | Listar Artigos dos portais Marcados | Array | EXAME, INFO_MONEY, LOUCOS_POR_IMOVEIS |

### ARTIGO_LISTA_SIMPLES
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | select | Ordenação da Lista de Artigos | - | `CONTADOR` = Mais Visualizados, `DATA` = Mais Recentes |
| `WID_FIELD_2` | radio | Listar somente artigos com Imagem | `0` | `1` = Sim, `0` = Não |
| `WID_FIELD_3` | slider | Quantidade de artigos a Listar | `10` | Min: 1, Max: 50 |
| `WID_FIELD_4` | check | Listar Artigos dos portais Marcados | Array | EXAME, INFO_MONEY, LOUCOS_POR_IMOVEIS |

---

## 🏠 Widgets de Imóveis

### IMOVEL_BUSCA
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | radio | Layout do Buscador | `ORIGINAL` | `ORIGINAL`, `MODERNO` |
| `WID_FIELD_2` | radio | Espessura do Buscador | `LARGO` | `FINO`, `LARGO` |
| `WID_FIELD_4` | multiple_select_ui | Campos da Busca Principal | `DESC` | Array de campos de busca |
| `WID_FIELD_5` | text | Comentário da Busca | Texto padrão | - |
| `WID_FIELD_6` | radio | Forma de ocupação dos campos | `Grade` | `0` = Indefinido, `Linha`, `Grade` |
| `WID_FIELD_7` | textarea | Configuração auxiliar | - | Campo oculto |

### IMOVEL_BUSCA_MENU
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_2` | radio | Abrir os links em novas abas | `0` | `1` = Sim, `0` = Não |
| `WID_FIELD_4` | textarea | Lista de links (JSON) | - | JSON com DESC e FILTER |

### IMOVEL_LISTA
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | select | Modo de Listagem | - | `ModoGrade`, `ModoListaSimples`, `ModoListaDetalhada` |
| `WID_FIELD_2` | textarea | Opções de Filtro | - | Configuração de filtros |

### IMOVEL_RELACIONADO
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | slider | Quantidade de Imóveis Relacionados | `30` | Min: 4, Max: 50, Step: 2 |
| `WID_FIELD_2` | radio | Modo de Listagem | `1` | `1` = Completa, `2` = Simples |

### IMOVEL_SLIDER_DESTAQUE
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | slider | Quantidade de Imóveis no Slide | `15` | Min: 2, Max: 24 |
| `WID_FIELD_2` | radio | Somente Imóveis em Destaques | `1` | `1` = Sim, `0` = Não |
| `WID_FIELD_3` | textarea | Opções de Filtro | - | Configuração de filtros |
| `WID_FIELD_4` | slider | Tempo para troca do banner (segundos) | `6` | Min: 0, Max: 18 |

### IMOVEL_MAPA
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_2` | slider | Altura do Mapa (pixels) | `300` | Min: 200, Max: 600 |

### IMOVEL_MAPA_STREET
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_2` | slider | Altura do Mapa (pixels) | `300` | Min: 200, Max: 600 |

### IMOVEL_FORM_SIMULADOR_FINANCEIRO
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | slider | Quantidade de Meses | `300` | Max: 500 |
| `WID_FIELD_2` | slider | Porcentagem para Entrada | `10` | 0% a 100%, Step: 0.1 |
| `WID_FIELD_3` | slider | Taxa de Juros Anual | `5` | 0% a 100%, Step: 0.1 |

### IMOVEL_BUTTON
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | radio | Ícones Coloridos | `1` | `1` = Sim, `0` = Não |

---

## 📝 Widgets de Formulários

### SOLICITAR_LIGACAO
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | radio | Formato do Botão | `BTN` | `BTN` = Botão Padrão, `IMG` = Imagem |
| `WID_FIELD_2` | text | Descrição para o Botão | Texto padrão | - |
| `WID_FIELD_3` | image | Imagem para o Botão | - | Obrigatório se WID_FIELD_1 = IMG |

### SOLICITA_IMOVEL_FORM
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | textarea | Resumo para início do Formulário | Texto padrão | - |

### CADASTRO_IMOVEL_FORM
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | textarea | Resumo para início do Formulário | Texto padrão | - |

---

## 🎥 Widgets de Mídia e Social

### YOUTUBE_PLAYLIST
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | radio | Layout do Buscador | `CHANNEL` | `CHANNEL`, `PLAYLIST`, `USER`, `VIDEO` |
| `WID_FIELD_2` | text | Id para Youtube | - | ID do canal/playlist/usuário |
| `WID_FIELD_3` | radio | Layout da lista de vídeos | `vertical` | `vertical`, `horizontal` |

### COMENTARIO_FACEBOOK
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | slider | Quantidade de Comentários a Listar | `6` | Min: 2, Max: 16 |
| `WID_FIELD_2` | radio | Esquema de Cores | `light` | `dark` = Escuro, `light` = Claro |

### FACEBOOK_LIKE_BOX
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | text | Link da Página do Facebook | - | URL da página |
| `WID_FIELD_3` | radio | Esquema de Cores | `light` | `light` = Claro, `dark` = Escuro |

---

## 🗺️ Widgets de Mapas

### MAPA_SIMPLES
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_2` | slider | Altura do Mapa (pixels) | `300` | Min: 100, Max: 600 |
| `WID_FIELD_3` | image | Imagem do Ponto de Localização | - | 130x130px |
| `WID_FIELD_4` | textarea | Informações do Mapa (JSON) | - | Latitude, longitude, etc. |
| `WID_FIELD_10` | radio | Tamanho Grande | `0` | `1` = Sim, `0` = Não |

### MAPA_COM_BUSCA
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | radio | Tamanho Grande | `0` | `1` = Sim, `0` = Não |
| `WID_FIELD_2` | textarea | Opções de Filtro | - | Configuração de filtros |
| `WID_FIELD_4` | multiple_select_ui | Campos que aparecerão na busca | `DESC` | Array de campos |
| `WID_FIELD_5` | slider | Altura do Mapa Fechado (pixels) | `350` | Min: 250, Max: 600 |
| `WID_FIELD_6` | slider | Altura do Mapa Aberto (pixels) | `600` | Min: 450, Max: 900 |
| `WID_FIELD_7` | text | Comentário para o Mapa | Texto padrão | - |

---

## 📄 Widgets de Conteúdo

### BLOCO_HTML
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | code | Código HTML para o bloco | - | HTML personalizado |

### BLOCO_CONTEUDO
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | longtext | Conteúdo do bloco | - | Texto rico |
| `WID_FIELD_2` | radio | Formatar automaticamente | `1` | `1` = Sim, `0` = Não |

### PAGE_TITLE
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | select | Página Pai | - | Lista de páginas |
| `WID_FIELD_2` | radio | Título Automático | `1` | `1` = Sim, `0` = Não |

### BANNER
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | select | Tipo de Banner | - | Lista de grupos de banner |

---

## 📊 Widgets Diversos

### INDICE_IMOBILIARIO
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | check | Lista de Índices para listar | - | Array de índices disponíveis |

### PREVISAO_TEMPO
| Campo | Tipo | Descrição | Padrão | Opções |
|-------|------|-----------|---------|---------|
| `WID_FIELD_1` | radio | Localização Automática | `1` | `1` = Sim, `0` = Não |
| `WID_FIELD_2` | textarea | Localizações Secundárias | - | Lista de cidades (uma por linha) |

---

## 🔧 Campos Comuns

| Campo | Descrição | Valor |
|-------|-----------|-------|
| `WID_TITLE` | Título do widget | `widget.WID_TITLE` |
| `WID_ATIVO` | Se o widget está ativo ou não | `widget.WID_ATIVO` |
| `WID_ID_PAG` (depreciado) | ID da página onde o widget está inserido | `widget.WID_ID_PAG` |
| `PAG_COD` | Código da página | `widget.PAG_COD` |
| `WID_TYPE` | Tipo do widget | `widget.Type` |
| `WID_SIZE` | Tamanho/Layout do widget | `widget.WID_SIZE` |
| `WID_ORDER` | Ordem de exibição do widget na página | `widget.WID_ORDER` |
| `WID_DELETE` | Flag para marcação de exclusão | `widget.WID_DELETE` |

---
