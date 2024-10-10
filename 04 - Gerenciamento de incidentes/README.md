
# Pratica e processos para gestão de incidentes. 

- Incidente: É qualquer evento que interrompa ou reduza a qualidade normal de um serviço ou sistema. Isso pode incluir falhas no sistema, bugs em software, problemas de rede, degradação de desempenho ou qualquer outro problema técnico.

- Todo incidente precisa ser categorizado com base na sua gravidade, e os nívels de gravidade vai determinar o grau de resposta necessária.

- Plano de reposta ao incidente: Uma vez que o incidente tenha sido identificado e resolvido, o serviço afetado deve ser restaurado ao seu estado normal de operação. Isso pode envolver a validação da correção para garantir que o problema foi realmente solucionado, e que o sistema esteja operando de acordo com as expectativas.

## Comunicação e colaboração durante os incidentes. 
- Se o diagnóstico inicial não puder resolver o incidente, ele deve ser escalado para equipes mais especializadas (ex.: desenvolvedores, arquitetos de infraestrutura, engenheiros de rede) com o conhecimento necessário para resolver o problema.

## Análise de causa raiz (Root Cause Analysis, RCA)

- É uma abordagem sistemática utilizada para identificar as causas subjacentes de um problema ou incidente. O objetivo da RCA é descobrir a causa primária de uma falha ou evento indesejado, de modo que as ações corretivas possam ser tomadas para evitar sua repetição no futuro. No contexto de TI, DevOps e SRE, a análise de causa raiz é essencial para melhorar a confiabilidade e resiliência dos sistemas, ajudando a evitar incidentes semelhantes.

## Análise de Postmortem

- Postmortem: Um aspecto crítico da gestão de incidentes é a análise pós-incidente (ou post-mortem), que envolve uma revisão detalhada do incidente para entender o que aconteceu, por que aconteceu e como prevenir que ocorra novamente. As post-mortems geralmente incluem:

   - Linha do tempo do incidente.
   - Causa raiz do problema.
   -  Medidas de mitigação que foram aplicadas.
   - Lições aprendidas e recomendações para melhorar a resiliência e a resposta futura.

Um princípio importante aqui é realizar post-mortems sem culpabilização, focando em melhorar processos e sistemas ao invés de atribuir culpa a indivíduos.

## Melhoria contínua.

- Os aprendizados dos incidentes devem ser usados para melhorar os processos e as infraestruturas. Isso pode incluir:

   -  Automação de respostas a incidentes comuns.
   -   Melhorias no monitoramento para detectar problemas antes que se tornem incidentes.
   - Ajuste dos SLOs e SLAs para refletir as expectativas de confiabilidade e disponibilidade.