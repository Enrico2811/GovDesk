# Checklist e Mapeamento LGPD - Projeto GovDesk

1. Objetivo
Este documento visa mapear o fluxo de dados pessoais tratados pelo sistema GovDesk, que atua na automação de processos de RH, onboarding e suporte interno. O objetivo é garantir a conformidade com a LGPD (Lei 13.709/2018), assegurando que os dados dos colaboradores sejam tratados com transparência, segurança, e acesso restrito apenas aos responsáveis pelas resoluções dos chamados.

2. Tabela de Mapeamento de Dados Pessoais
Abaixo estão listados os dados pessoais coletados dos colaboradores para o funcionamento do fluxo de atendimento e automação:

Dado Pessoal.
Finalidade no GovDesk.
Base Legal (LGPD).
Quem tem acesso?.
Tempo de Armazenamento.

**Nome e E-mail Corporativo**
Identificação do colaborador que abriu o chamado e envio de notificações em tempo real.
Art. 7º, V - Execução de contrato (trabalho).
Analistas de RH, Suporte TI e Gestores diretos.
Durante a vigência do contrato de trabalho (e até 5 anos após rescisão para histórico trabalhista).

**Cargo e Departamento**
Utilizado pelo sistema para a atribuição automatizada de responsáveis.
Art. 7º, IX - Legítimo Interesse (otimização de processos internos).
Sistema automatizado, Analistas de RH.
Idem ao Nome e E-mail.

**CPF ou Matrícula**
Autenticação no painel de tickets e vinculação das solicitações ao prontuário do funcionário.
Art. 7º, V - Execução de contrato.
Apenas Administradores do sistema e RH nível Sênior.
Idem ao Nome e E-mail.

3. Tratamento de Dados Sensíveis
**Dado Sensível Identificado:**
Informações de Saúde (Ex: Condições especiais do paciente).

**Contexto no Sistema:**
Como o GovDesk gerencia solicitações de RH, um dos fluxos do sistema é a abertura de chamados para **justificativa de faltas ou licença médica**. Nesse processo, o colaborador fará o upload de um atestado médico contendo informações de saúde (CID - Classificação Internacional de Doenças). Pela LGPD (Art. 5º, II), dados de saúde são estritamente sensíveis.

**Como o GovDesk fará o tratamento (Mitigação de Riscos):**
*   **Base Legal:** Tratamento amparado pelo **Art. 11, II, 'a'** (Cumprimento de obrigação legal ou regulatória - CLT) e **'f'** (Exercício regular de direitos em contrato).

*   **Controle de Acesso Rigoroso:** Diferente de chamados comuns de suporte, tickets que contenham atestados médicos ("Categoria: Saúde/Licença") **não** passarão por atribuição automatizada genérica. Eles serão restritos *exclusivamente* à visualização do Departamento Médico/Segurança do Trabalho ou RH autorizado.

*   **Minimização e Descarte:** O sistema não extrairá os dados do CID para o banco de dados. O arquivo (PDF/Imagem) ficará armazenado em um servidor seguro apenas pelo tempo necessário para o abono na folha de pagamento, sendo bloqueado para download por perfis não autorizados.