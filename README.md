# 🧠 StudyOS - Sistema Inteligente de Estudos

![StudyOS](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-finalizado-success)

> Sistema personalizado de planejamento de estudos para Carla Vicktoria - Engenharia de Software (UniCEUB)

## 📋 Sobre o Projeto

O **StudyOS** é um sistema web desenvolvido exclusivamente para organizar a rotina de estudos da Carla. Ele integra:

- 📅 **Planos de aula** de todas as disciplinas
- 🗓️ **Prazos** de provas, trabalhos e entregas
- ⏰ **Timer de 2h30** de estudo diário
- 📝 **Caderno de notas** por matéria
- 🔄 **Reorganização inteligente** quando você termina atividades antes do prazo
- 🚫 **Finais de semana OFF** (respeitando seu descanso)
- 📊 **Gráficos de progresso** e estatísticas

## 🚀 Acesse o Sistema

🔗 **URL:** [https://SEU-USUARIO.github.io/studyos](https://SEU-USUARIO.github.io/studyos)

### 🔐 Dados de Acesso

| Campo | Valor |
|-------|-------|
| **Usuário** | `Carla` |
| **Senha** | `Cacau` |

> ⚠️ O site é público, mas o acesso é protegido por login. Apenas quem sabe a senha consegue visualizar o conteúdo.

## 📚 Disciplinas Incluídas

| Disciplina | Código | Dia da aula |
|------------|--------|-------------|
| 🔧 Engenharia de Software | `es` | Terças 14h |
| 💻 Introdução à Computação | `ic` | Quartas 14h |
| 🐍 Lógica de Programação | `lp` | Quintas 14h |
| 🗄️ Banco de Dados I | `bd` | Sextas 14h |
| 🚀 Bootcamp I | `bootcamp` | Quintas 8h (online) |
| 📐 Fundamentos de Engenharia | `fundamentos` | Segundas (online) |

## 📅 Prazos Cadastrados

### Abril/2026
- `09/04` - Prova LP
- `12/04` - Desafio Bootcamp (Entrega Inicial) ✅
- `12/04` - Sistematização 01 (Fundamentos)
- `14/04` - Seminário ES
- `15/04` - Prova IC
- `21/04` - Prova ES
- `24/04` - Prova BD

### Maio/2026
- `03/05` - Exercícios 3 e 4 (Fundamentos)
- `17/05` - Desafio Bootcamp (Intermediária)
- `21/05` - Prova LP
- `31/05` - Sistematização 02 (Fundamentos)

### Junho/2026
- `03/06` - Seminário IC
- `06/06` - Avaliação Online (Fundamentos)
- `09/06` - Seminário ES
- `10/06` - Prova IC
- `14/06` - Desafio Bootcamp (Final)
- `16/06` - Prova ES
- `17/06` - Relatório ACE (IC)
- `25/06` - Prova Online LP + Lista LP
- `26/06` - Prova BD

## ✨ Funcionalidades

### 🎯 Hoje
- Visualização do dia atual
- Prazos urgentes (menos de 14 dias)
- Timer de 2h30 para controle de estudo
- Grade do dia (manhã = pré-aula, tarde = aula)
- Sugestões de estudo personalizadas

### 📝 Notas
- Caderno digital separado por matéria
- Criação, edição e exclusão de notas
- Tags para organização
- Salvamento automático no navegador

### 🗓️ Prazos
- Todos os prazos organizados
- Filtros por tipo (prova, trabalho, entrega)
- Cores indicando urgência
- ✅ Atividades já concluídas

### 📅 Calendário
- Visualização mensal
- Indicadores coloridos por tipo de evento
- Navegação entre meses
- Lista dos próximos prazos

### 📖 Planos de Aula
- Cronograma detalhado por matéria
- Conteúdo programático de cada aula
- Preparação necessária para cada encontro

### 📊 Progresso
- Percentual de conclusão por matéria
- Gráfico de horas de estudo
- Histórico de atividades concluídas

## 🧠 Lógica de Reorganização

Quando você conclui uma atividade **antes do prazo**, o sistema:

1. Pergunta **quantos dias você gastou**
2. Calcula os **dias ganhos** (previsto - gasto)
3. Usa esses dias extras para:
   - **Prioridade 1:** Adiantar estudo de provas próximas (menos de 14 dias)
   - **Prioridade 2:** Incluir cursos extras (Python, HTML)
   - **Prioridade 3:** Revisões espaçadas

## 💻 Tecnologias Utilizadas

- **HTML5** - Estrutura do site
- **CSS3** - Estilização (tema escuro, glassmorphism)
- **JavaScript** - Lógica e interatividade
- **Font Awesome** - Ícones
- **LocalStorage** - Persistência de dados

## 🎨 Identidade Visual

- **Tema escuro** para conforto visual
- **Cores específicas por matéria**:
  - 🔧 ES: Laranja (`#f97316`)
  - 💻 IC: Azul (`#3b82f6`)
  - 🐍 LP: Verde (`#10b981`)
  - 🗄️ BD: Roxo (`#8b5cf6`)
  - 🚀 Bootcamp: Rosa (`#ec4899`)
  - 📐 Fundamentos: Cinza (`#64748b`)

## 📱 Responsividade

O sistema se adapta a:
- 💻 Desktop
- 📱 Tablets
- 📱 Celulares

## 🔒 Privacidade

Apesar de hospedado publicamente no GitHub Pages, o sistema possui **tela de login** com usuário e senha fixos (`Carla` / `Cacau`), garantindo que apenas você acesse seus dados.

## 🚀 Como Usar

1. Acesse a URL do sistema
2. Faça login com `Carla` / `Cacau`
3. Na aba **Hoje**, veja o que estudar
4. Clique em **Concluir** quando terminar uma atividade
5. Informe quantos dias gastou
6. O sistema **reorganiza automaticamente** seu cronograma
7. Use as **Notas** para fazer resumos e anotações
8. Acompanhe seu **Progresso** nas matérias

## 📦 Instalação Local (para desenvolvimento)

```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/studyos.git

# Entre na pasta
cd studyos

# Abra o arquivo index.html no navegador
# ou use um servidor local:
python -m http.server 8000
