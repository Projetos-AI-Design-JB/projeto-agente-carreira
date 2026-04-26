# Agente de Carreira IA — Entrevistador Especializado

Este projeto consiste em um agente de Inteligência Artificial projetado para atuar como um recrutador técnico e orientador de carreira. O objetivo é ajudar profissionais a identificarem as trilhas tecnológicas mais compatíveis com seus perfis por meio de uma entrevista estruturada e análise baseada em dados.

## Objetivo
O agente conduz uma jornada de autodescoberta em três fases, focando em alinhar as expectativas do usuário com as demandas reais do mercado de tecnologia.

## Fluxo de Trabalho

### Fase 1: Entrevista Estruturada (7 Perguntas)
O agente interage com o usuário coletando informações cruciais:
1. Motivação: O que atrai o usuário (resolver problemas, criar produtos ou sistemas).
2. Experiência: Nível atual (iniciante ou experiente).
3. Disponibilidade: Tempo semanal dedicado aos estudos.
4. Afinidade Operacional: Preferência entre lidar com pessoas, dados ou código.
5. Objetivo de Carreira: Transição, primeiro emprego ou crescimento.
6. Interesses Técnicos: Áreas específicas como IA, Web, Dados ou Infraestrutura.
7. Bagagem Prévia: Experiências anteriores que podem ser reaproveitadas.

### Fase 2: Matriz de Decisão e Sugestão
Com base nas respostas, o sistema utiliza uma matriz de decisão interna para ranquear as 3 melhores carreiras, avaliando:
* Afinidade técnica.
* Demanda de mercado.
* Tempo de ramp-up (aprendizado).
* Aproveitamento de competências passadas.

### Fase 3: Handoff
Uma vez escolhida a carreira, o agente consolida os dados e transfere o contexto para o Agent 2, responsável pela criação do plano de estudos personalizado.

## Regras de Operação (Prompts)
* Atomicidade: Apenas uma pergunta por vez para garantir o foco.
* Personalização: Explicações personalizadas do porquê cada carreira foi sugerida.
* Integridade: O agente nunca gera planos de estudos ou cita salários específicos, mantendo a especialização da função.

## Como Utilizar
1. Importe o arquivo agente-ia-carreira.md no seu ambiente compatível com agentes de IA (como Gemini ou sistemas customizados de LLM).
2. O agente iniciará automaticamente a saudação e a primeira pergunta.
3. Responda sequencialmente até receber as recomendações de carreira.

---
Este projeto foi desenvolvido para otimizar a porta de entrada de novos talentos no ecossistema tech.