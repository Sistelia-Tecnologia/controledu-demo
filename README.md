<p align="center">
  <img width="1200" height="600" alt="ControlEDU" src="https://github.com/user-attachments/assets/7819d940-fb89-4135-a643-bb1046719b6a" />
</p>

<h1 align="center">ControlEDU</h1>

<p align="center">
  <strong>Plataforma completa de gestão educacional</strong><br/>
  ERP modular para instituições de ensino — do financeiro ao LMS
</p>

<p align="center">
  <a href="https://controledu.com.br" target="_blank">
    <img src="https://img.shields.io/badge/Demo%20Live-flexiuni.com-blue?style=for-the-badge" alt="Demo Live" />
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Laravel-12+-red?style=for-the-badge&logo=laravel" />
  &nbsp;
  <img src="https://img.shields.io/badge/FilamentPHP-v5-orange?style=for-the-badge" />
  &nbsp;
  <img src="https://img.shields.io/badge/PHP-8.3+-777BB4?style=for-the-badge&logo=php" />
</p>

---

## Sobre o Projeto

O **ControlEDU** é um ERP educacional proprietário desenvolvido pela [SISTELIA Tecnologia](https://sistelia.com.br), projetado como substituto de alta performance ao WordPress para instituições de ensino.

Construído com **Laravel 12+**, **FilamentPHP v5** e **Livewire 3**, oferece uma suíte completa de módulos para gerenciar todos os aspectos de uma escola ou instituição de ensino — da secretaria ao financeiro, do LMS à cantina.

---

## Demo

> **Acesse agora:** [https://controledu.com.br](https://controledu.com.br)

### Credenciais de Teste

| Perfil | E-mail | Senha |
|--------|--------|-------|
| **Administrador** | `demo@flexiuni.com` | `demo1234` |
| **Aluno** | `aluno@flexiuni.com` | `demo1234` |
| **Professor** | `professor@flexiuni.com` | `demo1234` |

> **Acesso ao painel admin:** [https://controledu.com.br/admin](https://controledu.com.br/admin)

### O que testar

- **Painel Administrativo** — navegue pelos módulos no menu lateral
- **Financeiro** — explore o DRE, Fluxo de Caixa e Extrato de Conta
- **LMS** — acesse os cursos, módulos e sistema de quizzes
- **Cantina POS** — veja o ponto de venda e relatórios de caixa
- **RH** — explore vagas, currículos e candidaturas
- **Estoque** — gerencie produtos, pedidos e movimentações
- **CMS** — crie páginas e posts com múltiplos tipos de conteúdo

---

## Módulos

### Secretaria

Gestão central de pessoas e documentos da instituição.

- Cadastro completo de **alunos** e **professores** com perfis vinculados ao sistema de usuários
- Gerenciamento de **entidades** (fornecedores, responsáveis, parceiros)
- Sistema de **anexos e documentos** com versionamento
- Relacionamento aluno-responsável via tabela pivot

---

### Acadêmico

Estrutura do calendário e organização pedagógica.

- **Anos letivos** com períodos configuráveis
- **Turmas** e **disciplinas** hierárquicas
- **Eventos escolares** integrados ao calendário
- Controle de **frequência** e boletim de notas

---

### LMS — Cursos Online

Plataforma completa de aprendizado online (Learning Management System).

- Cursos **gratuitos** (`livre`) e **pagos** (`regular`) com descontos
- Organização em **módulos** e **aulas** com progresso individual por aluno
- Sistema de **quizzes** com questões dissertativas e objetivas
- **Tentativas de quiz** com correção e pontuação automática
- **Notas finais** com pesos configuráveis:
  - Quizzes de aulas
  - Provas de módulo
  - Prova final
- **Certificados** automáticos ao concluir cursos
- **Canal de dúvidas** (fórum por curso)
- **Matrículas** com datas de vigência e controle de vagas
- SEO integrado por curso (meta_title, meta_description, og_image)
- Avaliações e comentários de alunos

---

### Financeiro

Sistema contábil completo, multi-conta e multi-método de pagamento.

- **Plano de contas** (Caixa, PIX, Débito, Crédito e personalizados)
- **Lançamentos** de receitas, despesas e transferências entre contas
- **Contas a pagar e a receber** com controle de vencimentos
- **Recorrências** automáticas de transações
- **Relatórios gerenciais:**
  - Visão Geral do Financeiro
  - Saldo em Conta
  - DRE (Demonstração do Resultado do Exercício)
  - Fluxo de Caixa
  - Análise por Categoria
  - Relatório de Inadimplência
  - Lucros e Perdas (P&L)
  - Extrato de Conta (com impressão)
- **Contabilidade:**
  - Conciliação bancária
  - Fechamento de período
  - Apuração de impostos
- Rastreabilidade completa com auditoria de criação/edição

---

### Cantina (POS)

Ponto de venda integrado para cantinas e lanchonetes escolares.

- **PDV (Ponto de Venda)** com múltiplos métodos de pagamento
- **Gestão de produtos** com precificação (custo e venda)
- **Controle de estoque** com movimentações de entrada/saída
- **Caixas** com abertura, fechamento e operadores
- **Leitura X** (sangria/suprimento) e **Redução Z** (fechamento fiscal)
- **Relatórios de vendas** com emissão de recibos para impressão
- Integração automática com o módulo financeiro

---

### Estoque

Gestão de inventário e pedidos de compra/venda.

- **Produtos** com SKU, código de barras, variantes, dimensões e peso
- **Múltiplos armazéns** com saldo por localização
- **Variantes de produto** (tamanho, cor, etc.) com preços específicos
- **Movimentações** rastreadas por motivo e número de lote
- **Pedidos de compra** com status e datas de entrega
- **Pedidos de venda** com:
  - Múltiplos status (pendente → processando → enviado → entregue)
  - Endereço de entrega
  - Tipos de desconto
  - Taxas de serviço e frete
  - Impressão de recibo

---

### Recursos Humanos

Recrutamento, seleção e gestão de colaboradores.

- **Cadastro de funcionários** com dados pessoais, cargo, contrato e salário
- **Documentos** de funcionários com upload de arquivos
- **Vagas** com publicação no site, requisitos, benefícios e faixa salarial
- **Portal de currículos** com sistema de tags
- **Candidaturas** com funil de seleção e conversão para funcionário
- Dashboard de RH com métricas de contratação

---

### Patrimônio

Controle de ativos físicos da instituição.

- Cadastro com código patrimonial, marca, modelo e número de série
- **Status** configurável (ativo, em manutenção, desativado, etc.)
- **Localização** e responsável por ativo
- Dados de aquisição (valor, data, nota fiscal) e garantia
- **QR Code** automático para identificação física
- Histórico de manutenções e trilha de auditoria completa

---

### Agendamento de Visitas

Sistema de agendamento de visitas ao campus.

- **Disponibilidade** configurável com capacidade por horário
- **Bloqueios de agenda** para datas específicas
- Formulário público com dados do visitante e interesse pedagógico
- Fluxo de aprovação (pendente → confirmado → realizado)
- Notificações automáticas e lembretes
- Sistema de avaliação pós-visita
- Calendário visual para administradores

---

### Classificados

Marketplace comunitário para a comunidade escolar.

- Anúncios de **compra, venda e troca**
- Categorias e destaque de anúncio
- Galeria de imagens e contador de visualizações
- Sistema de **denúncias** e moderação
- Canal de contato entre interessados

---

### CMS — Gestão de Conteúdo

Plataforma de conteúdo com múltiplos tipos de renderização.

- **Páginas** com tipos: HTML, View Blade, Componente Livewire, Componente Blade
- Roteamento dinâmico por slug com catch-all
- **Blog** com posts, categorias e tags
- **Menus** hierárquicos com gerenciador de itens
- **Sliders** para carrossel de destaque
- SEO por conteúdo (meta, og:image)

---

### Gamificação

Engajamento da comunidade escolar.

- **XP e níveis** de progressão por atividade
- **Conquistas/Badges** com critérios configuráveis
- **Streaks** de atividade consecutiva
- Ranking e histórico de pontuação

---

### Administração do Sistema

- **Usuários** com avatares, bios e tipos de acesso
- **Papéis e permissões** com ACL granular
- **Tipos de usuário** (aluno, professor, responsável, admin, funcionário, etc.)
- **Mensagens de contato** do site
- Portal público de **Trabalhe Conosco**

---

## Stack Tecnológica

| Camada | Tecnologia |
|--------|-----------|
| Backend | Laravel 12+ / PHP 8.3+ |
| Admin Panel | FilamentPHP v5 |
| Frontend | Livewire 3 + Tailwind CSS 4 |
| Banco de Dados | MySQL 8+ |
| Cache | Redis |
| Storage | Laravel Filesystem (S3-compatible) |

---

## Licença e Comercialização

O **ControlEDU** é um produto **proprietário** da [SISTELIA Tecnologia](https://sistelia.com.br).

Este repositório é exclusivamente para **demonstração pública** das funcionalidades do sistema.

Para licenciamento, implementação ou parcerias, entre em contato:

- **Site:** [sistelia.com.br](https://sistelia.com.br)
- **E-mail:** contato@sistelia.com.br

---

<p align="center">
  Desenvolvido com ♥ por <strong>SISTELIA Tecnologia</strong>
</p>
