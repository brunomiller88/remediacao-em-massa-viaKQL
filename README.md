# remediacao-em-massa-viaKQL
Remediação em massa para busca avançada em KQL
Ações em Massa via Caça Avançada (Advanced Hunting) no Microsoft Defender

Este repositório documenta uma otimização operacional no uso da Caça Avançada (Advanced Hunting) com KQL no Microsoft Defender for Endpoint, voltada à remediação em larga escala diretamente a partir dos resultados da consulta.

Contexto

Historicamente, as consultas em KQL na Caça Avançada permitiam apenas análise e visualização de dados.
Mesmo identificando claramente os dispositivos afetados, não era possível executar ações corretivas diretamente a partir da consulta, sendo necessário abrir outras telas ou fluxos paralelos para realizar a remediação.

Evolução da Plataforma

Atualmente, o Defender permite executar ações diretamente associadas aos resultados da Caça Avançada, eliminando etapas manuais e tornando o processo mais eficiente, seguro e escalável.

Procedimento Utilizado

Acesse Caça Avançada (Advanced Hunting) no portal do Defender.
(busca-avancada-001.png)

Execute sua consulta em KQL, conforme o objetivo da análise.

Exemplo prático: consulta para identificar dispositivos com Full Scan cancelado nos últimos 7 dias.

Nos resultados, clique sobre o DeviceId do dispositivo desejado.

Selecione a opção “Take actions”.

Escolha a ação de remediação adequada, como:

Isolar o dispositivo

Iniciar um Full Scan

Coletar pacote de investigação

Revise a ação, defina um nome e uma descrição para auditoria e rastreabilidade.

Confirme a execução.

Benefícios

Redução de etapas operacionais

Remediação mais rápida e centralizada

Maior eficiência em cenários de grande escala

Melhor rastreabilidade das ações executadas

Integração direta entre detecção e resposta

Considerações Finais

Este recurso ainda é pouco divulgado e relativamente oculto dentro da plataforma, mas representa um ganho significativo de produtividade para times de segurança que trabalham com resposta a incidentes, hunting e automações operacionais.
