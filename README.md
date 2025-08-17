# Projeto: Automação de Consulta de Situação de CPF
Descrição:
Projeto que automatiza a verificação da situação de CPFs de clientes em uma plataforma web. Ele integra Python, Selenium e OpenPyXL para consultar, processar e registrar informações de forma rápida e precisa. O sistema lê dados de uma planilha de clientes, realiza consultas automáticas e atualiza uma planilha de fechamento com os resultados.

Funcionalidades Implementadas:
Leitura de Dados do Cliente

O sistema importa informações de uma planilha contendo nome, valor, CPF e data de vencimento dos clientes.

Permite processar grandes volumes de dados automaticamente.

Consulta Automática em Plataforma Web

Para cada cliente, o sistema acessa o site de consulta de CPFs e preenche os campos necessários.

Verifica o status do CPF (em dia ou pendente) e coleta informações adicionais, como data de pagamento e método utilizado, quando disponíveis.

Registro de Resultados em Planilha

Atualiza uma planilha de fechamento com os resultados da consulta, incluindo status do CPF e informações de pagamento.

Organiza os dados de forma estruturada, permitindo fácil análise e acompanhamento.

Benefícios do Projeto:
Redução de trabalho manual: Consulta dezenas ou centenas de CPFs de forma automática.

Precisão: Evita erros humanos no registro e processamento de dados.

Organização: Mantém todas as informações atualizadas em uma planilha estruturada.

Eficiência: Otimiza tempo e recursos em processos de verificação financeira.

Próximos Passos / Melhorias Futuras:
Implementar tratamento de exceções para CPFs inválidos ou páginas inacessíveis.

Criar interface gráfica para seleção de planilhas e visualização dos resultados em tempo real.

Integrar envio automático de relatórios por e-mail.

Adicionar logs detalhados para auditoria e monitoramento do processo.
