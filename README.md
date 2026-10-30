# WayOut Analytics para Windows

Aplicativo local de consulta ao WayOut ERP, somente de leitura e com senha SQL apenas em memória. O chatbot local não usa serviço externo. O assistente com IA permite compartilhar, por escolha do usuário, o texto e indicadores agregados preparados com o provedor selecionado.

## Novidades da versão 1.2.0

[Baixar a versão 1.2.0](https://github.com/Leonardo-Finhub-Assessoria/WayOut-Analytics-Releases/releases/tag/v1.2.0), com Assistente com IA generativa:

- ChatGPT/OpenAI, Gemini, Claude e DeepSeek, com modelo editável e chave de API somente na sessão.
- Solicitações livres, análises, gráficos interativos e relatórios, com exportação TXT/CSV.
- Compartilhamento opcional dos indicadores: prepare e confira a prévia antes de enviar. Texto e dados selecionados são transmitidos ao provedor escolhido, usando os créditos e as permissões da própria conta de API.
- Gráficos de barras/linhas, seleção de séries e tabelas com os valores; respostas de IA precisam ser conferidas com as fontes.

Distribuição autorizada explicitamente em 30/10/2026. Nenhuma chave ou configuração de cliente acompanha o instalador. APIs conferidas com transporte simulado; chamadas reais dependem de uma chave válida e de acesso ao modelo. A publicação não homologa regras/documentos do ERP de cada cliente. Download e instalação continuam opcionais.


## Novidades da versão 1.1.2

[Baixar a versão 1.1.2](https://github.com/Leonardo-Finhub-Assessoria/WayOut-Analytics-Releases/releases/tag/v1.1.2), com correções do financeiro:

- Pagar e receber juntos, vencimentos em 7/15 dias, 1/2/3 meses e futuro completo, inclusive após três meses.
- Preservação de classificações já conferidas na reconexão, atalhos para conferir regras pendentes e contas a pagar consultáveis quando falta vínculo fiscal de receber.
- Cadastro bancário antes da leitura do histórico quando ainda não existe perfil de saldos; referências históricas continuam identificadas por data.
- Conferência de páginas corrigida para contagens retornadas como texto pelo driver.

Distribuição autorizada em 20/10/2026. Use **Ajuda → Verificar atualizações** para baixar e depois confirmar **Instalar e reiniciar**. Configurações e preferências são preservadas; após reiniciar, informe novamente a senha SQL. Cada cliente mantém suas próprias regras e evidências; nenhum perfil ou dado do desenvolvimento é distribuído.

## Novidades da versão 1.1.1

[Versão 1.1.1 e instalador](https://github.com/Leonardo-Finhub-Assessoria/WayOut-Analytics-Releases/releases/tag/v1.1.1), com busca no período completo e páginas de 50/100/200 para documentos e recebimentos de compras e grupos de movimentos de estoque. Totais e CSV completos preservados; eventos e grupos continuam separados. A rotina local de validação também confere as novas páginas contra o CSV.

Distribuição autorizada explicitamente em 16/10/2026. SQL real das novas consultas, ativação e homologação independente no ERP continuam pendentes. Download e instalação permanecem opcionais.

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
