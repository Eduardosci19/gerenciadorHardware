# gerenciadorHardware


# 🚀 Gerenciador de Hardware para Laboratórios

**Data**: 24/10/2024  

**Responsável**: Eduardo Krüger e Lucas Brito

---

## 📜 Introdução dos Levantamentos de Requisitos

### 🎯 Objetivo
Este documento apresenta os requisitos do sistema **Gerenciador de Hardware para Laboratórios**, que permitirá o controle e monitoramento de máquinas, consertos, peças trocadas e inventário de componentes em laboratórios.

### 🛠️ Escopo
O sistema gerenciará:
- Cadastro e controle de máquinas.
- Registro de manutenções, consertos e peças trocadas.

### 📖 Definições
- **Máquina**: Equipamento disponível no laboratório.
- **Peça**: Componente de hardware que pode ser trocado.
- **Conserto**: Reparação realizada em uma máquina.
- **Inventário**: Registro de componentes disponíveis.

---

## ✅ Requisitos Funcionais

### 📋 Cadastro de Máquinas
- **RF-01**: Permitir o cadastro de máquinas e suas especificações.
- **RF-02**: Associar máquinas a laboratórios específicos.
- **RF-03**: Exibir o status atual da máquina (funcionando, em manutenção, fora de uso).

### ⚙️ Controle de Consertos e Manutenções
- **RF-04**: Registrar manutenções corretivas e preventivas.
- **RF-05**: Associar peças utilizadas no conserto à manutenção.
- **RF-06**: Armazenar histórico de manutenções realizadas.
- **RF-07**: Criar agendamentos de manutenções preventivas.

### 📦 Controle de Peças e Inventário
- **RF-08**: Permitir o cadastro de peças de hardware no inventário.
- **RF-09**: Registrar peças retiradas do estoque para consertos.
- **RF-10**: Emitir alertas de baixa quantidade no estoque.

### 🏢 Gerenciamento de Laboratórios
- **RF-11**: Gerenciar múltiplos laboratórios.
- **RF-12**: Exibir um painel geral do status das máquinas.

### 📊 Relatórios e Auditorias
- **RF-13**: Gerar relatórios de consertos e manutenções.
- **RF-14**: Gerar relatórios sobre o uso e troca de peças.
- **RF-15**: Permitir exportação de relatórios em PDF ou Excel.

### 🔑 Controle de Acesso e Usuários
- **RF-16**: Criar perfis de usuário com diferentes níveis de acesso.
- **RF-17**: Manter logs de todas as ações dos usuários.

### 🔔 Notificações e Alertas
- **RF-18**: O sistema deve enviar notificações para os usuários sobre manutenções programadas e vencimentos de garantias de peças.
- **RF-19**: Permitir que os usuários personalizem suas preferências de notificação (e-mail, notificações no aplicativo, etc.).

### 📊 Análise de Desempenho
- **RF-20**: O sistema deve fornecer relatórios de desempenho das máquinas, incluindo tempos de operação, falhas e manutenções realizadas.
- **RF-21**: Permitir a visualização de tendências de uso e manutenção de máquinas ao longo do tempo.

### 📅 Agendamento e Planejamento
- **RF-22**: Permitir o agendamento de recursos (máquinas e peças) para atividades específicas, com um calendário integrado.
- **RF-23**: Criar um painel de planejamento para visualizar as manutenções e agendamentos futuros.

---

## ⚙️ Requisitos Não Funcionais

### 📈 Desempenho
- **RNF-01**: Processar informações de até 1000 máquinas sem perda de desempenho.

### 🎨 Usabilidade
- **RNF-02**: Interface intuitiva para facilitar o uso por técnicos.

### 🔒 Confiabilidade
- **RNF-03**: Backup automático dos dados a cada 24 horas.

### 🌐 Portabilidade
- **RNF-04**: Funcionar em Windows, Linux e macOS.

### 🛡️ Segurança
- **RNF-05**: Controle de acesso por autenticação de usuário.
- **RNF-06**: Registro de ações dos usuários para auditoria.

### 📈 Escalabilidade
- **RNF-07**: O sistema deve suportar um crescimento de até 50% no número de máquinas e usuários sem comprometer o desempenho.

### 🔍 Acessibilidade
- **RNF-08**: O sistema deve atender a diretrizes de acessibilidade, garantindo que usuários com deficiência possam utilizar todas as funcionalidades.

### 📚 Documentação e Suporte
- **RNF-09**: O sistema deve ter documentação técnica e guias de usuário acessíveis, atualizados conforme novas funcionalidades são adicionadas.
- **RNF-10**: Disponibilizar suporte técnico via chat ou e-mail para resolução de problemas dos usuários.

---

## 🖥️ Requisitos de Interface

### 🎨 Interface Gráfica
- **RI-01**: Baseada em JavaFX ou Swing.
- **RI-02**: Exibir gráficos de desempenho através de JFreeChart.

### 📄 Relatórios
- **RI-03**: Geração de relatórios em tempo real com filtros.

---

## 🔚 Considerações Finais
O sistema **Gerenciador de Hardware para Laboratórios** visa facilitar o controle e monitoramento das máquinas e peças, aumentando a eficiência na gestão de manutenção e inventário. Este documento será revisado periodicamente para atualizar novas funcionalidades e necessidades.

---

🌟 **Agradecemos por usar o Gerenciador de Hardware!** 🌟
