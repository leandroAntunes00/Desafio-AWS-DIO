# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 03 de junho de 2025
Empresa: FarmaTech Solutions Ltda
Responsável: Leandro Antunes - Engenheiro de Software

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa FarmaTech Solutions Ltda, realizado por Leandro Antunes - Engenheiro de Software. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:
- Amazon S3 (Simple Storage Service)
- Armazenamento de dados e documentos
- Migração inicial de arquivos estáticos, documentos regulatórios e backups para o S3. Esta etapa foi escolhida como primeira por ser a mais simples, não requerer downtime e permitir migração gradual dos dados farmacêuticos, garantindo conformidade com ANVISA desde o início.

Etapa 2:
- Amazon RDS (Relational Database Service)
- Banco de dados gerenciado em nuvem
- Migração dos bancos de dados de controle de estoque, rastreabilidade de lotes e registros de pacientes para RDS. Esta etapa intermediária aproveita o S3 já configurado para backups automáticos e requer planejamento de janela de manutenção para migração dos dados críticos.

Etapa 3:
- Amazon EC2 (Elastic Compute Cloud)
- Infraestrutura de servidores virtuais
- Migração final dos servidores de aplicações farmacêuticas para instâncias EC2. Esta etapa mais complexa depende do S3 e RDS já estarem operacionais, permitindo escalabilidade automática e finalização da redução de custos com infraestrutura física.



## Conclusão
A implementação de ferramentas na empresa *FarmaTech Solutions Ltda tem como esperado redução de custos operacionais em até 40%, melhoria na segurança e compliance regulatória, escalabilidade automática dos sistemas e eliminação de custos com manutenção de infraestrutura física*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- Manual de configuração AWS S3 para setor farmacêutico
- Documentação de migração RDS com backup de segurança
- Guia de implementação EC2 para aplicações críticas
- Planilha comparativa de custos AWS vs infraestrutura local
- Cronograma detalhado das 3 etapas de migração

Assinatura do Responsável pelo Projeto:

Leandro Antunes - Engenheiro de Software