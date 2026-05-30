Vou te enviar uma pesquisa que outro assistente de IA produziu sobre
Atendimento ao Seguro-Desemprego pela URA da Caixa. Faça uma AUDITORIA RIGOROSA dela. Identifique TODAS as
falhas que encontrar:
  - erros factuais (cite o trecho)
  - lacunas de evidência (afirmação sem fonte)
  - inferências mal-suportadas
  - fontes fracas ou ausentes
  - atribuições incorretas
  - atores omitidos relevantes
NÃO conte como falha questões cosméticas (formatação, estilo, ordem).
Para cada falha, cite o trecho e justifique.

PESQUISA A AUDITAR:
"""
# Meta-Prompt — Mapa de Atores da Jornada de um Serviço Público

## Problema

O atendimento ao Seguro-Desemprego pela URA (Unidade de Resposta Audível) da Caixa Econômica Federal é um serviço público crítico que atende milhões de trabalhadores brasileiros em situação de vulnerabilidade — pessoas que acabaram de perder o emprego e precisam acessar um benefício ao qual têm direito. No entanto, a jornada de atendimento por meio de sistema automatizado de voz é frequentemente fragmentada, opaca e frustrante tanto para os cidadãos quanto para os agentes que eventualmente precisam intervir. Há múltiplos atores envolvidos nessa jornada — do trabalhador demitido ao operador da Caixa, passando por empregadores, o Ministério do Trabalho e os sistemas de tecnologia — e suas interações, responsabilidades e pontos de atrito raramente são mapeados de forma integrada.

## Objetivo

Elaborar um prompt detalhado e bem estruturado que instrua um modelo de linguagem (LLM) a construir um **Mapa de Atores** completo da jornada de atendimento ao Seguro-Desemprego pela URA da Caixa. O mapa deve identificar todos os atores humanos e sistêmicos envolvidos, seus papéis, motivações, pontos de contato e relações entre si ao longo das etapas do serviço.

## Contexto

**O que é a URA da Caixa para o Seguro-Desemprego:**
A URA (Unidade de Resposta Audível) é o sistema telefônico automatizado da Caixa Econômica Federal que permite ao trabalhador consultar parcelas do Seguro-Desemprego, verificar situação do benefício, agendar atendimento presencial e obter informações sobre documentação exigida. O acesso se dá pelo telefone 0800 726 0207 ou pelo número 111.

**Atores típicos nessa jornada:**
- Trabalhador demitido sem justa causa (beneficiário)
- Empregador (responsável pela homologação e comunicação da demissão)
- Ministério do Trabalho e Emprego (gestor do programa e das regras de elegibilidade)
- Caixa Econômica Federal (operadora do pagamento e do canal de atendimento)
- Sistema SINE / Portal Gov.br (plataformas digitais complementares)
- Agente humano da Caixa (atendente que assume quando a URA não resolve)
- Sindicatos e advogados trabalhistas (intermediários ocasionais)

**Etapas típicas da jornada:**
1. Demissão e homologação pelo empregador
2. Requerimento do benefício (presencial, online ou por telefone)
3. Contato com a URA para acompanhamento
4. Escalonamento para atendimento humano (quando necessário)
5. Liberação ou bloqueio da parcela
6. Recurso em caso de indeferimento

## Solicitação

Com base no problema, no objetivo e no contexto acima, elabore um **prompt com no mínimo 200 palavras** que possa ser enviado a um LLM para que ele produza um Mapa de Atores detalhado dessa jornada. O prompt deve:

- Definir claramente o papel do LLM (ex: especialista em design de serviços públicos)
- Especificar o formato de saída esperado (tabela, lista estruturada, narrativa, etc.)
- Solicitar que cada ator seja descrito com: nome/papel, motivações, responsabilidades, pontos de contato na jornada e principais dores ou limitações
- Pedir que o mapa cubra tanto atores humanos quanto sistemas tecnológicos
- Incluir instrução para identificar relações e dependências entre os atores
- Ser suficientemente específico para gerar uma resposta útil e aplicável a um projeto de melhoria desse serviço público
"""