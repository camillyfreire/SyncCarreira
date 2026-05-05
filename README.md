# SyncCarreira 🚀

## Visão Geral
O SyncCarreira é um software focado na modernização e gestão do processo de orientação vocacional. Desenvolvido como projeto acadêmico no Instituto Federal de São Paulo (IFSP), o sistema substitui os métodos analógicos de aplicação de testes por uma plataforma digital integrada. 

A solução otimiza o fluxo de trabalho das equipes de psicologia escolar por meio de painéis de triagem e relatórios automatizados, enquanto proporciona aos alunos do ensino médio uma jornada de autodescoberta interativa, gamificada (baseada em trilhas) e livre de vieses de diagnóstico fechado.

## 🎯 Proposta de Valor
* **Eficiência Operacional:** Redução de falhas humanas e tempo gasto em correções manuais de testes.
* **Curadoria Pedagógica:** Ferramentas para as equipes de psicologia identificarem rapidamente gargalos de aprendizagem e alunos que necessitam de intervenção (flags de atenção).
* **Escalabilidade B2B:** Estrutura multitenant (isolamento lógico de dados) desenhada para atender múltiplas instituições de ensino e ONGs em um ambiente seguro.

## 🧩 Módulos do Sistema

### 1. Aluno (Interface de Autodescoberta)
* Jornada de testes estruturada em 4 pilares sequenciais e intertravados: **Autoconhecimento, Influências, Informação e Projeto de Futuro**.
* Mecanismos para registro de sínteses textuais e sentimentos ao final de cada etapa, promovendo reflexão autônoma.
* Painel com panorama de possibilidades de carreira geradas a partir do perfil, acompanhadas de curadoria de fontes externas (Enem, ProUni, etc.).

### 2. Psicólogo (Painel de Gestão e Triagem)
* Dashboard analítico de turmas com indicadores de progresso.
* Sistema automatizado de alertas (flags) para alunos com dificuldades ou indecisões, facilitando o direcionamento para sessões individuais ou em grupo.
* Construtor customizável de testes e trilhas.
* Gestão centralizada de agendamentos e emissão de feedbacks.

### 3. Administrador (Governança e Segurança)
* Gestão de instituições cadastradas (escolas/ONGs).
* Controle rigoroso de perfis de acesso (RBAC - Role-Based Access Control) garantindo o isolamento de dados.

## 💻 Arquitetura e Requisitos Não Funcionais (RNFs)
O projeto foi desenhado sob rigorosos padrões de mercado, garantindo performance e segurança (adequação à LGPD):
* **Backend:** Arquitetura em camadas (Controller, Service, Repository, Entity) utilizando **Spring Boot**.
* **Autenticação:** Segurança baseada em tokens JWT.
* **Documentação de API:** Contratos de rotas documentados via Swagger/OpenAPI.
* **Interface:** Design mobile-first voltado para usabilidade fluida e acessível.

## Статус do Projeto
🚧 Em desenvolvimento 🚧
