
## Automação Robótica de Processos.

## 📌Problema


O monitoramento da chegada dos lotes à fábrica era realizado diretamente no SAP, mas dependia de verificações manuais ao longo do dia. Em um ambiente de produção com alta demanda, acessar o sistema repetidamente para consultar o status de cada lote tornava o processo operacionalmente pesado e aumentava o risco de atrasos na identificação da chegada.

Essa visibilidade era essencial para que as próximas etapas fossem acionadas no momento certo, como coleta de amostra, inspeção do lote e envio das informações para análise da Qualidade. Quando havia algum desvio ou suspeita de não conformidade, identificar rapidamente a chegada do lote ajudava a antecipar tratativas, apoiar a análise de causa raiz e contribuir para a liberação do produto para venda com mais agilidade.


## 🤖 Solução

Foi desenvolvida uma automação RPA para monitorar a chegada dos lotes no SAP de forma automática e padronizada. A solução utiliza uma planilha Excel como base de entrada, onde são informados os números dos lotes que precisam ser acompanhados.

A partir dessa base, o robô realiza a leitura dos lotes, acessa o SAP, consulta individualmente cada número informado e identifica se o lote já chegou à fábrica. Quando a chegada é confirmada, a automação atualiza o status na planilha de controle e envia uma notificação automática por e-mail para as áreas responsáveis, permitindo que as próximas etapas do processo sejam iniciadas com mais agilidade.

Com isso, o acompanhamento deixou de depender de consultas manuais recorrentes, tornando o processo mais eficiente, confiável e organizado.




## 🚀 Impacto

A automação reduziu a dependência de consultas manuais no SAP e melhorou o tempo de resposta entre a chegada do lote à fábrica e o acionamento das áreas responsáveis.

Antes, se um lote chegasse à fábrica em determinado horário, ele só seria identificado quando o especialista realizasse uma nova consulta no SAP, o que poderia ocorrer horas depois. Com o robô, a chegada passou a ser identificada automaticamente, com notificações simultâneas por e-mail e Microsoft Teams para Especialistas e Produção.

Com isso, o processo ganhou mais agilidade, visibilidade e padronização, antecipando etapas como coleta, inspeção, análise da Qualidade e tratativa de possíveis desvios, além de contribuir para reduzir atrasos na liberação do produto para venda.







📄	Leitura automática de planilha Excel

🤖	Execução automatizada do processo via RPA

🖥️	Consulta automática de lotes no SAP

✅	Identificação do status de chegada do lote

📊	Atualização automática da base de controle

📧	Envio de notificações automáticas por e-mail
