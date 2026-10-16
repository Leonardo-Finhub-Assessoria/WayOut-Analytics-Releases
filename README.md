# WayOut Analytics para Windows

Aplicativo local de consulta ao WayOut ERP. Os dados e a senha SQL permanecem na máquina/rede do cliente.

## Novidades da versão 1.1.0

[Versão 1.1.0 e instalador](https://github.com/Leonardo-Finhub-Assessoria/WayOut-Analytics-Releases/releases/tag/v1.1.0), com as três frentes de evolução de BI:

- **Explorador de BI:** tabelas dinâmicas, filtros, detalhamento, CSV e visões locais por origem.
- **Gestão e alertas:** metas e limites locais, prioridades, responsável, ações e prazos.
- **Análises e cenários:** tendências com médias móveis, comparação de períodos e hipóteses de caixa com premissas exportáveis.

Distribuição autorizada na sessão de 15/10/2026. Ativação e homologação no ERP de cada cliente continuam sendo conferências separadas. O cliente mantém a escolha de baixar e instalar.

## Instalação

Baixe o arquivo `WayOut-Analytics-Setup-VERSAO-x64.exe` na [versão mais recente](https://github.com/Leonardo-Finhub-Assessoria/WayOut-Analytics-Releases/releases/latest) e siga o assistente. Windows 10/11 de 64 bits. Não é necessário instalar Node.js. Abra o atalho WayOut Analytics e configure a conexão de leitura do seu próprio ERP.

## Atualização opcional

A partir da versão 1.0.2, o aplicativo verifica novas versões 15 segundos após abrir e a cada seis horas enquanto estiver aberto. Uma notificação do Windows informa a disponibilidade; clique nela para escolher **Baixar atualização**, **Lembrar amanhã** ou **Ignorar esta versão**. Depois do download, confirme **Instalar e reiniciar** quando desejar. Não há download ou instalação automática, inclusive ao fechar.

**Ajuda → Verificar atualizações** permite buscar e instalar manualmente, inclusive uma versão adiada ou ignorada. **Ajuda → Avisar automaticamente de novas versões** liga/desliga as verificações automáticas. As preferências ficam salvas no computador. O Windows pode silenciar notificações pelo modo Não incomodar; o menu Ajuda continua indicando a versão disponível. Não há serviço de avisos com o programa fechado.

As configurações e preferências dos painéis permanecem salvas; a senha SQL deve ser informada novamente após reiniciar. Sem internet, o programa continua funcionando localmente. Novas melhorias são oferecidas após validação técnica, declaração explícita em nossas sessões de que a versão está válida para disponibilização aos clientes e publicação. Cada cliente continua escolhendo se deseja baixar e instalar a atualização.

Este repositório publica somente instaladores e metadados de atualização. O código-fonte é privado. Não envie dados, senhas ou relatórios do ERP aqui.

O instalador ainda não possui certificado digital do editor; o Windows pode exibir aviso de editor desconhecido.
