# Pesquisa v3 — Mapa de Atores da Jornada do Seguro-Desemprego pelo Canal Telefônico da Caixa

> **Nota metodológica:** Esta versão incorpora as falhas novas introduzidas pela v2 (pontos 2.1 a 2.10 da auditoria v2) e os 7 pontos ainda abertos. O registro de respostas está ao final. Limitação estrutural remanescente: as fontes são identificadas por nome de órgão e documento no corpo do texto; links e numeração formal de referências não estão disponíveis neste formato de exercício — isso é uma **limitação séria**, não um atributo adequado de trabalho acadêmico rigoroso.

---

## 1. Descrição do Problema

O Seguro-Desemprego é um dos maiores programas de proteção social do Brasil. Segundo dados do Tribunal de Contas da União (TCU), o programa beneficiou aproximadamente **6,7 milhões de trabalhadores em 2022 e 7,4 milhões em 2024**. *(Correção da falha 2.1: o dado "mais de 8 milhões de requerimentos em 2022" da v2 não tem comprovação verificável nas fontes públicas consultadas e foi substituído por dado auditado pelo TCU. Nota: requerimentos processados ≠ beneficiários pagos; uma análise completa precisaria distinguir as métricas.)*

Alguns trabalhadores beneficiários recorrem ao canal telefônico da Caixa para acompanhar suas parcelas após a concessão. *(Correção da falha 2.2: "parcela expressiva" foi removido — não há dado público sobre tráfego, share de canal ou perfil de usuário do 0800 para Seguro-Desemprego. O canal é um dos canais oficiais disponíveis, não necessariamente o mais usado.)*

A jornada envolve múltiplos atores com competências distintas e três momentos que não devem ser confundidos:

| Momento | Canais oficiais confirmados |
|---|---|
| **Solicitação** | Carteira de Trabalho Digital (CTD), Portal Gov.br, atendimento presencial em unidades do trabalhador / órgãos autorizados pelo MTE |
| **Acompanhamento de parcelas** | App Benefícios Sociais CAIXA, CAIXA Tem, Portal Cidadão, CTD, 0800 726 0207, Portal Emprega Brasil |
| **Recebimento do pagamento** | Conta indicada pelo trabalhador, Conta Poupança Social Digital CAIXA, CAIXA Tem |

---

## 2. Estrutura Institucional e Competências

### Divisão de responsabilidades

A **concessão e a gestão das regras de elegibilidade** decorrem de lei e regulamentação, sendo operacionalizadas pelo **MTE conforme legislação vigente e deliberações do CODEFAT**. O MTE não é o único definidor das regras — a elegibilidade está inscrita em lei (Lei 7.998/1990 e alterações) e o CODEFAT é relevante na estrutura normativa do FAT e do programa. *(Correção da falha 2.4)*

A **Caixa Econômica Federal** atua como **agente pagador e operadora dos canais de atendimento e pagamento**. No âmbito da concessão, a Caixa não decide elegibilidade. *(Correção da falha 2.3: a expressão "exclusivamente agente pagador" foi removida — é imprecisa porque a Caixa também opera apps, portais, SAC e Ouvidoria.)*

O **SAC da Caixa (0800 726 0101)** e a **Ouvidoria da Caixa (0800 725 7474)** são canais para reclamações, sugestões, elogios, pedidos de cancelamento e informações sobre produtos, serviços e atendimento da Caixa, incluindo, mas não limitado a, problemas operacionais de pagamento. *(Correção da falha 2.9)*

### Canais de reclamação além do ecossistema Caixa

Quando o problema não é operacional de pagamento, mas de **concessão, recurso ou elegibilidade**, os canais relevantes são do MTE e do sistema federal de ouvidorias: *(resposta ao ponto aberto #6)*

- **Recurso ao MTE** — prazo de 120 dias a partir da notificação de indeferimento (Gov.br confirma)
- **Fala.BR / Ouvidoria federal** — plataforma integrada de ouvidorias do Governo Federal
- **Superintendências Regionais do Trabalho e Emprego (SRTE)** — unidades regionais do MTE para atendimento presencial e recurso administrativo

### Sobre a "homologação" e o papel do empregador

*(Correção da falha 2.5)* A **Reforma Trabalhista (Lei 13.467/2017) eliminou a exigência legal geral de assistência sindical ou do MTE para rescisão de contratos com mais de um ano de duração.** Isso não significa que toda homologação sindical deixou de existir: sindicatos ainda podem atuar em acordos coletivos, normas coletivas, assistência voluntária ou situações específicas previstas em convenção. A formulação adequada é: a exigência legal geral de assistência foi eliminada; atuação sindical voluntária ou convencional permanece possível.

Para o empregado doméstico, o empregador doméstico não emite o Requerimento do Seguro-Desemprego Empregado Doméstico (RSDED) — ele é gerado no ato do requerimento pelo trabalhador.

---

## 3. Mapa de Atores Revisado

### 3.1 Atores Humanos

| Ator | Papel | Motivações | Pontos de contato | Limitações |
|---|---|---|---|---|
| **Trabalhador demitido** | Beneficiário; solicita, acompanha e recebe o benefício; recorre em caso de indeferimento | Manter renda durante desemprego; acessar direito garantido em lei | CTD, Gov.br, 0800 726 0207, App Benefícios Sociais, unidade de atendimento | Dependente de documentação do empregador; pode ter dificuldade de acesso digital; não decide concessão |
| **Empregador** | Fornece documentação da demissão (TRCT, comunicado de dispensa) conforme modalidade de vínculo; empregador doméstico registra no eSocial | Cumprir obrigações trabalhistas | eSocial, sistemas do MTE | Regras variam por modalidade; doméstico não emite RSDED |
| **Atendente humano da Caixa** | Atende no 0800 726 0207 fora do fluxo eletrônico; pode orientar sobre situação de parcelas nos limites da competência da Caixa | Resolver demandas operacionais | 0800 726 0207 (seg–sex 8h–21h; sáb 10h–16h) | Não decide concessão nem elegibilidade; pendências de concessão dependem do MTE. *Pendente/em-aberto: roteiro, escopo exato e SLA do atendimento humano para Seguro-Desemprego não estão disponíveis em fontes públicas. (ponto aberto #3)* |
| **Agente do MTE / unidade de atendimento ao trabalhador** | Processa requerimentos presenciais; orienta trabalhadores; integra fluxo de recurso | Garantir acesso correto ao benefício | Unidades do MTE, SRTE, postos de atendimento, órgãos autorizados | Capacidade variável por região |
| **Sindicatos / advogados trabalhistas** | Podem orientar o trabalhador em casos de recurso, litígio ou situações complexas | Defender direitos do trabalhador | Assessoria direta ao trabalhador | *Pendente/em-aberto: não há fonte oficial que os posicione como atores típicos do fluxo regular de atendimento telefônico. Incluídos como atores periféricos possíveis.* |

### 3.2 Atores Institucionais

| Ator | Papel | Interface com o trabalhador | Observação |
|---|---|---|---|
| **MTE — Ministério do Trabalho e Emprego** | Operacionaliza a concessão conforme legislação e normas; indica trabalhadores para pagamento; processa recursos | Portal Emprega Brasil, CTD, unidades de atendimento, SRTE | Não confundir com definidor exclusivo das regras — elegibilidade decorre de lei e deliberações do CODEFAT |
| **FAT — Fundo de Amparo ao Trabalhador** | Custeia os recursos do Seguro-Desemprego | Sem interface direta com o trabalhador | Ator financeiro estrutural do programa |
| **CODEFAT — Conselho Deliberativo do FAT** | Delibera sobre uso do FAT; normatiza aspectos operacionais e financeiros | Resoluções e normas operacionais que afetam o programa indiretamente | Ator normativo; relevante para governança, não para atendimento direto |
| **Caixa Econômica Federal** | Agente pagador; operadora dos canais de atendimento e pagamento (0800, apps, portais, SAC, Ouvidoria) | 0800 726 0207, App Benefícios Sociais CAIXA, CAIXA Tem, Portal Cidadão, agências, SAC, Ouvidoria | Não decide concessão nem elegibilidade |
| **INSS — Instituto Nacional de Seguro Social** | Base/sistema consultado para verificação de acúmulo de benefício previdenciário com Seguro-Desemprego | Cruzamento sistêmico; sem interface direta com o trabalhador no fluxo telefônico | Ator sistêmico periférico; confirmar benefícios com exceções (auxílio-acidente, pensão por morte em modalidades específicas) |
| **Dataprev** | Desenvolve e opera sistemas integrados usados no processamento dos requerimentos do Seguro-Desemprego | Infraestrutura tecnológica de backend; sem interface direta com o trabalhador | *Ator sistêmico omitido nas versões anteriores; mencionado em documentos do TCU como relevante para o processamento. (correção da falha 2.6)* |

### 3.3 Sistemas e Canais Tecnológicos

| Sistema / Canal | Função | Gestor | Status |
|---|---|---|---|
| **Carteira de Trabalho Digital (CTD)** | Solicitação e acompanhamento do Seguro-Desemprego | MTE / Gov.br | Confirmado |
| **Portal Gov.br / Emprega Brasil** | Solicitação; acompanhamento; informações sobre elegibilidade | MTE / Gov.br | Confirmado (canais distintos, não equivalentes) |
| **0800 726 0207 (Atendimento CAIXA Cidadão)** | Acompanhamento de parcelas; atendimento eletrônico 24h e humano em horário comercial | Caixa | Confirmado para acompanhamento de parcelas |
| **App Benefícios Sociais CAIXA** | Consulta de calendário de parcelas; situação de benefícios; comprovante NIS | Caixa | Confirmado |
| **CAIXA Tem** | Movimentação da Conta Poupança Social Digital; acesso ao crédito das parcelas | Caixa | Confirmado |
| **Portal Cidadão (Caixa)** | Acompanhamento de situação de parcelas | Caixa | Confirmado |
| **SAC Caixa — 0800 726 0101** | Reclamações, sugestões, elogios, cancelamentos e informações sobre serviços da Caixa | Caixa | Confirmado |
| **Ouvidoria Caixa — 0800 725 7474** | Segunda instância de reclamação sobre serviços da Caixa | Caixa | Confirmado |
| **eSocial** | Registro de demissão de empregado doméstico; geração de documentos | Gov.br / RFB | Confirmado para empregador doméstico |
| **PIS/NIS — identificação do trabalhador** | Identificador usado em sistemas da Caixa e do MTE para consultas de benefícios | Caixa / MTE | *Pendente/em-aberto: PIS/NIS pode ser usado como identificador; exigência específica no 0800 não está comprovada em fonte pública. (correção da falha 2.8)* |
| **RAIS / eSocial (base de dados trabalhistas)** | Fontes de dados usadas em cruzamentos de elegibilidade | MTE / RFB | Bases de dados, não atores decisores *(correção da falha 2.7)* |
| **Sistemas de processamento do MTE / Dataprev** | Processamento dos requerimentos; cruzamento de dados de elegibilidade (INSS, RAIS, eSocial) | MTE / Dataprev | Infraestrutura de backend; composição exata dos sistemas *pendente/em-aberto (ponto aberto #5)* |
| **Fala.BR / Ouvidoria federal** | Reclamações sobre concessão, recurso ou elegibilidade fora do escopo da Caixa | CGU / Gov.br | Incluído na v3 *(ponto aberto #6)* |

---

## 4. Modalidades do Seguro-Desemprego

*(Resposta ao ponto aberto #7)* O programa abrange modalidades com regras distintas. O mapa de atores varia conforme a modalidade:

| Modalidade | Particularidades relevantes para a jornada |
|---|---|
| **Empregado formal (CLT)** | Modalidade principal; requerimento via CTD ou presencial; documentação do empregador conforme vínculo |
| **Empregado doméstico** | Empregador doméstico registra demissão no eSocial; RSDED gerado no ato do requerimento; prazo de 7 a 90 dias |
| **Pescador artesanal** | Período de defeso; documentação e fluxo específicos pelo MTE |
| **Trabalhador resgatado de trabalho análogo à escravidão** | Fluxo especial via MTE; documentação distinta |
| **Bolsa Qualificação** | Mantém vínculo empregatício; requerimento durante suspensão do contrato |

O canal telefônico da Caixa (0800 726 0207) é relevante principalmente para **acompanhamento de parcelas** nas modalidades em que o pagamento passa pela Caixa — o que abrange a maioria dos casos, mas deve ser verificado para cada modalidade.

---

## 5. Etapas da Jornada (versão consolidada)

1. **Demissão** — trabalhador é desligado conforme modalidade de vínculo
2. **Documentação pelo empregador** — fornece TRCT, comunicado de dispensa ou equivalente; empregador doméstico registra no eSocial
3. **Requerimento pelo trabalhador** — via CTD, Portal Gov.br ou presencial em unidade do trabalhador / órgão autorizado pelo MTE (não por telefone)
4. **Análise e concessão/indeferimento pelo MTE** — cruzamento de elegibilidade com bases RAIS, eSocial, INSS e sistemas Dataprev
5. **Acompanhamento de parcelas** — múltiplos canais disponíveis, incluindo o 0800 726 0207
6. **Pagamento** — Caixa executa conforme indicação do MTE; conta indicada, Poupança Social Digital ou CAIXA Tem
7. **Transbordo para atendimento humano** — atendimento humano disponível no 0800 nos horários publicados; critérios de transbordo *pendente/em-aberto*
8. **Reclamação operacional** — SAC ou Ouvidoria da Caixa para problemas de pagamento/atendimento
9. **Recurso por indeferimento** — recurso ao MTE em até 120 dias da notificação; vias: SRTE, Fala.BR, Ouvidoria federal
10. **Encerramento do benefício** — após consumo das parcelas ou perda de elegibilidade

---

## 6. Registro de Respostas às Falhas da Auditoria v2

### Falhas novas introduzidas pela v2

| Ponto | Falha | Resposta | Ação na v3 |
|---|---|---|---|
| 2.1 | "8 milhões de requerimentos" — dado não comprovado | **(a) Correção** | Substituído por dado do TCU: 6,7 mi beneficiários em 2022 e 7,4 mi em 2024; métrica esclarecida |
| 2.2 | "Parcela expressiva" sem dado de tráfego | **(a) Correção** | Reformulado para "alguns trabalhadores / um dos canais disponíveis" |
| 2.3 | "Exclusivamente agente pagador" — excessivo | **(a) Correção** | Substituído por "agente pagador e operadora dos canais de atendimento/pagamento; não decide concessão" |
| 2.4 | MTE como único definidor de elegibilidade | **(a) Correção** | Reformulado: MTE operacionaliza a concessão conforme legislação e deliberações do CODEFAT |
| 2.5 | "Homologação extinta" — imprecisão jurídica | **(a) Correção** | Reformulado: exigência legal geral eliminada; atuação sindical voluntária/convencional permanece |
| 2.6 | Dataprev omitida | **(a) Correção** | Dataprev incluída como ator sistêmico relevante |
| 2.7 | RAIS/eSocial como "atores decisores" — vago | **(a) Correção** | Distinguidos como bases de dados, não atores decisores |
| 2.8 | PIS/NIS "necessário para o 0800" — não comprovado | **(a) Correção** | Reformulado como identificador possível; exigência no 0800 marcada como pendente |
| 2.9 | SAC/Ouvidoria limitados a "pagamento" — estreito | **(a) Correção** | Escopo ampliado: reclamações, sugestões, elogios, cancelamentos e informações sobre serviços |
| 2.10 | Ausência de referências formais apresentada como "adequada" | **(a) Correção** | Reformulado: ausência de referências formais é **limitação séria**, não atributo aceitável |

### Pontos ainda abertos da auditoria v2

| # | Ponto aberto | Resposta | Situação na v3 |
|---|---|---|---|
| 1 | Volume real de uso do 0800 para Seguro-Desemprego | **(c) Pendente/em-aberto** | Não há dado público disponível; afirmação sobre uso foi removida |
| 2 | Critérios de transbordo eletrônico → atendimento humano | **(c) Pendente/em-aberto** | Horários confirmados; critérios de transbordo não disponíveis em fonte pública |
| 3 | Competência efetiva do atendente humano da Caixa | **(c) Pendente/em-aberto** | Roteiro, escopo e SLA não disponíveis em fonte pública |
| 4 | Funções não confirmadas do canal telefônico | **(c) Pendente/em-aberto** | Agendamento, documentação e requerimento por telefone permanecem não confirmados |
| 5 | Mapa sistêmico completo (Dataprev, sistemas MTE) | **(a) Correção parcial** | Dataprev incluída; composição exata dos sistemas de backend marcada como pendente |
| 6 | Canais de reclamação externos à Caixa | **(a) Correção** | SRTE, Fala.BR e Ouvidoria federal incluídos |
| 7 | Modalidades distintas do Seguro-Desemprego | **(a) Correção** | Tabela de modalidades incluída (formal CLT, doméstico, pescador, resgatado, bolsa qualificação) |

---

## 7. Limitações Remanescentes desta Versão

1. **Ausência de referências formais verificáveis** — as fontes são identificadas por nome de órgão no corpo do texto, sem link, número de página ou data de acesso. Isso é uma limitação séria para qualquer uso acadêmico rigoroso, operacional ou publicação formal.
2. **Pontos abertos #1, #2, #3** — volume de uso do canal, critérios de transbordo e competência exata do atendente humano não estão disponíveis em fontes públicas consultadas. Uma pesquisa completa exigiria acesso a documentos internos da Caixa, relatórios de atendimento ou pesquisa de campo.
3. **Composição dos sistemas de backend do MTE/Dataprev** — a arquitetura exata dos sistemas de processamento de requerimentos não está documentada publicamente em detalhe suficiente para mapeamento preciso.
