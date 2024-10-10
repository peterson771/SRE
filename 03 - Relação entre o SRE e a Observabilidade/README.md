
# Relação entre o SRE e a Observabilidade

-  É fundamental, pois a observabilidade fornece as métricas e os dados necessários para que as equipes de SRE possam garantir a confiabilidade, disponibilidade e desempenho dos sistemas em produção. 
- Observabilidade é essencial para monitorar e entender o comportamento dos sistemas, identificar problemas rapidamente e aplicar melhorias contínuas.

## Pilares da observabilidade

- Logs: São registros detalhados de eventos no sistema, que fornecem contexto e histórico para entender o comportamento do sistema ao longo do tempo.

- Métricas: São medições quantitativas do desempenho do sistema, como tempo de resposta, utilização de CPU, número de requisições, etc. Métricas são frequentemente usadas como SLIs (Service Level Indicators).

- Traces: são Rastreamentos que seguem o ciclo de vida de uma solicitação através dos diferentes serviços e componentes de um sistema distribuído, permitindo que os engenheiros vejam onde ocorrem gargalos ou falhas.

## Definição e objetivos da observabilidade

- Definição: É a capacidade de um sistema expor seu estado interno e comportamento através de dados gerados durante sua operação. Esses dados permite que as equipes de engenheira entendam, monitorem e resolvam os problemas de desempenho e confiabilidade.

- Objetivo: Entender o comportamento de um sistema, isso ajuda as equipes a detectarem anomalias ou falhas de forma proativa. E dar transparencia para equipes de engenheira em sistemas altamente complexos.

## Ferramentas e soluções de observabilidade no mercado.

- Datadog: Uma plataforma completa de monitoramento e observabilidade, que inclui métricas, logs e tracing. É muito usada em ambientes de microsserviços, oferecendo dashboards detalhados e integrações com diversas tecnologias.

- New Relic: Fornece observabilidade em toda a pilha, com monitoramento de infraestrutura, logs, tracing distribuído e análise de desempenho de aplicações (APM). Oferece uma visão unificada de sistemas complexos.

- Dynatrace: Uma plataforma com recursos de monitoramento de infraestrutura, logs, traces e APM. Utiliza inteligência artificial para detectar automaticamente anomalias e problemas de desempenho.

- Elastic Observability (ELK Stack): Uma solução open-source que combina Elasticsearch (para busca e armazenamento), Logstash (para coleta de logs), e Kibana (para visualização). Pode ser usada para coletar logs, métricas e traces de aplicações distribuídas.

## Monitoramento métricas

- Prometheus: Um sistema open-source para coleta e armazenamento de métricas, muito usado em Kubernetes e ambientes de microsserviços. Prometheus usa um modelo de scraping (coleta de dados em intervalos regulares) e permite alertas baseados em métricas.

- Grafana: Uma ferramenta de visualização de métricas amplamente usada em conjunto com Prometheus. O Grafana permite criar dashboards interativos e visualizações detalhadas com base em dados de várias fontes, incluindo Prometheus, InfluxDB,

## Logging

- ELK Stack (Elasticsearch, Logstash, Kibana): Uma das soluções mais populares para gerenciamento de logs. Logstash coleta os logs, Elasticsearch os armazena e Kibana permite a visualização e análise.

- Graylog: Uma plataforma de gerenciamento de logs que fornece coleta, análise e monitoramento em tempo real, com foco em sistemas distribuídos. Ele usa o Elasticsearch para armazenamento e pode ser usado como alternativa ao ELK.

## Tracing

- Jaeger: Uma solução open-source de tracing distribuído desenvolvida pela Uber, que ajuda a rastrear a jornada de requisições entre serviços, permitindo identificar problemas de latência e gargalos.

- OpenTelemetry: Um projeto open-source da CNCF que unifica as ferramentas e padrões de observabilidade (métricas, logs e tracing). Ele está se tornando a base para observabilidade em muitos sistemas distribuídos e é amplamente suportado por várias plataformas.