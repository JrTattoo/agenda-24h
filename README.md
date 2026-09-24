Agenda 24h — fonte oficial do projeto
Este diretório é a fonte oficial de informações, decisões, arquitetura e acompanhamento do Agenda 24h.
Regra de trabalho
A partir de agora, decisões confirmadas devem ser registradas neste projeto.
Conversas antigas, anotações dispersas e erros históricos não são fontes oficiais.
Conteúdo antigo somente será reaproveitado quando for apresentado novamente, revisado e confirmado.
Quando existir conflito entre uma conversa e um documento deste projeto, prevalece o documento mais recente confirmado aqui.
Informações incertas devem ser marcadas como pendentes, nunca tratadas como fato.
Credenciais, tokens, senhas, chaves e dados pessoais não devem ser armazenados na documentação.
Situação atual
Estamos construindo e organizando as bases do produto. A prioridade atual não é acrescentar recursos aleatórios, mas entender o sistema, eliminar inconsistências e preparar uma versão confiável para o cliente-teste.
O cliente-teste será um salão fictício operado pelo responsável do projeto. Depois da validação completa, a mesma estrutura será usada para cadastrar clientes reais.
A arquitetura de automação é híbrida: cada empresa terá um workflow principal próprio; as tools de agenda e os workflows de lembretes e reativação serão compartilhados.
Documentos principais
Pacote de especificação de 24/09/2026: PRD, TRD, app flow, briefing UI/UX, schema do backend e plano de implementação. Os seis documentos separam produto desejado, implementação local e homologação remota pendente.
Produto
Portal web: aplicação React/Vite incorporada ao projeto oficial; interface mobile-first, agenda, indicadores, relatórios, automações e gestão. A integração real com Supabase ainda é parcial.
Solicitações administrativas do portal: decisão de 17/09/2026; inclusão/remoção de profissionais e alterações de plano dependem de aprovação e efetivação pelo responsável da plataforma; ausências/fechamentos continuam com o administrador.
Funcionalidades do sistema: catálogo oficial do que o produto oferece, suas regras, valor e novas ideias em avaliação; não acompanha progresso de implementação.
Portal — decisões consolidadas em 16/09/2026: referência prioritária para revisar o diagnóstico do VS Code; agenda, permissões, métricas, reativações, relatórios, gestão de profissionais/serviços e alteração de plano.
Visão do produto: público-alvo, estratégia, jornada ideal, MVP e decisões de produto.
Status atual: decisões confirmadas, pontos ainda a decidir e trabalho técnico necessário.
Controle de progresso V2: contador das frentes de trabalho, estado, próxima ação e critério de conclusão.
Regras operacionais: antecedência, cancelamento, buffer, profissionais e permissões.
Portal administrativo — métricas: indicadores de agenda, lembretes, reativações e estado das automações para o contratante.
Planejamento de implantação do portal: estrutura da página, fluxo de consulta, segurança e hospedagem recomendada.
Infraestrutura
Servidor Ubuntu: máquina, sistema, Docker, serviços, rede, armazenamento e backups.
Capacidade e escala: meta de empresas, indicadores e testes progressivos.
Banco de dados
Plano de mudanças do Supabase — 7 de setembro de 2026: comparação da estrutura real com as funções do produto e sequência recomendada de migrações.
Agendamentos e banco: inventário anterior, preservado como contexto histórico.
n8n
Reconstrução dos workflows V3 — 19/09/2026: sete JSONs inativos sobre o banco V2, texto/áudio, tools, fila e pausa humana; migration e testes locais preparados, implantação e testes integrados pendentes.
Workflow de comparecimento — entrega preparada em 18/09/2026: JSON inativo, migration não aplicada, regra confirmada de liberação a partir do início, testes locais e roteiro de homologação.
Auditoria completa dos workflows — 7 de setembro de 2026: revisão dos 16 JSON entregues, bloqueadores, cobertura do MVP e ordem de correção.
Auditoria inicial de agendamentos: levantamento anterior preservado como histórico técnico.
Inteligência artificial
Arquitetura de IA: modelo, memória, ferramentas, prompts, proteção e contingência.
WhatsApp
Integração Evolution API: instância, webhook, rede, persistência e pontos de atenção.
Provisionamento
Onboarding presencial no iPad: cadastro assistido, arquivo local e conferência da cobrança presencial.
Onboarding e ativação: compra, formulário, revisão manual e criação do cliente no Supabase.
Mapeamento do onboarding: destino de cada informação no Supabase, prompt e tools.
Comercial
Cobrança e planos: implantação, assinatura mensal, estados de cobrança e pendências comerciais.
Scripts de levantamento
Coleta de consultas do n8n
Coleta da Evolution API
Ordem de construção
Consolidar as decisões de produto.
Modelar e proteger a agenda oficial no Supabase.
Corrigir o banco e as regras de disponibilidade.
Ajustar os workflows para o banco oficial.
Validar o atendimento e as ferramentas da IA.
Validar WhatsApp, intervenção humana e prevenção de loops.
Validar lembretes e reativação.
Entregar o portal administrativo mínimo.
Executar testes completos com o cliente-teste.
Preparar o provisionamento do primeiro cliente real.
Como decisões serão registradas
Cada definição ficará em um destes estados:
Confirmada: decidida pelo responsável e adotada pelo projeto.
Proposta: recomendação ainda aguardando decisão.
Pendente: informação que ainda precisa ser levantada ou escolhida.
Substituída: decisão antiga mantida apenas para preservar o histórico.
O objetivo é que alguém consiga entender o Agenda 24h lendo este diretório, sem depender do histórico das conversas.
