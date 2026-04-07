# SGTO — Sistema Gerenciador de Tarefas Online

> Projeto Integrador III–B | Análise e Desenvolvimento de Sistemas | PUC Goiás  
> Parceiro: **Global Parts Importação e Distribuição Aeronáutica**

---

## Sobre o Projeto

O **SGTO** é um sistema web de gerenciamento de chamados e tarefas internas de TI, desenvolvido em parceria com a **Global Parts**, empresa especializada em importação e distribuição de peças aeronáuticas, com sede em Goiânia (GO) e unidades em todo o Brasil e nos Estados Unidos.

O sistema foi proposto para resolver um problema real identificado na organização: a ausência de um canal centralizado para abertura, acompanhamento e controle de chamados de TI. Atualmente as demandas são comunicadas de forma informal (WhatsApp, e-mail, verbal), sem registro estruturado, sem definição de prioridades e sem visibilidade do status de cada solicitação.

---

## Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| Autenticação | Login com perfis: Analista TI, Gestor, Solicitante |
| Abertura de Chamados | Registro com categoria, prioridade e descrição detalhada |
| Quadro Kanban | Visualização por colunas: A Fazer / Em Andamento / Concluído |
| Lista de Chamados | Tabela completa com filtros por status, prioridade e categoria |
| Detalhe do Chamado | Histórico de atualizações, alteração de status, notificações |
| Calendário de Prazos | Visualização de vencimentos por data |

---

## Telas do Protótipo

```
sgto/
├── login.html           → Tela de autenticação
├── dashboard.html       → Painel principal com métricas e Kanban
├── novo_chamado.html    → Formulário de abertura de chamado
├── chamados.html        → Listagem completa de chamados
├── chamado_detalhe.html → Detalhe e histórico de um chamado
└── calendario.html      → Calendário de prazos e vencimentos
```

### Como executar o protótipo

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/sgto-globalparts.git
```

2. Acesse a pasta do projeto:
```bash
cd sgto-globalparts
```

3. Abra o arquivo inicial no navegador:
```bash
# Basta abrir o arquivo diretamente no navegador
open sgto/login.html
# ou clique duas vezes no arquivo login.html
```

> Não requer instalação de dependências — protótipo 100% em HTML/CSS/JS puro.

---

## Organização Parceira

**Global Parts Importação e Distribuição Aeronáutica**

| Unidade | Localização |
|---|---|
| Matriz | Goiânia, GO |
| Oficina de Motores e Acessórios | SBNV — Aeródromo Nacional de Aviação |
| Hangar — Estoque e Venda de Peças | SBNV — Aeródromo Nacional de Aviação |
| Hangar — Manutenção de Hélices | SBNV — Aeródromo Nacional de Aviação |
| Hangar — Manutenção Motores PT6A | SBNV — Aeródromo Nacional de Aviação |
| Hangar — Manutenção de Célula | SBNV — Aeródromo Nacional de Aviação |
| Oficina e Venda de Peças | Jataí, GO |
| Venda de Peças | Várzea Grande, MT |
| Venda de Peças | Barreira, BA |
| Filial de Importação | Estados Unidos |

---

## Metodologia

O projeto foi conduzido com abordagem ágil, organizado em sprints semanais e acompanhado via **Trello**.

🔗 **Quadro Trello:** `https://trello.com/b/6bEWOa5j/sgto`

### Cronograma

| Semana | Atividades |
|---|---|
| Semana 1 | Levantamento de requisitos + documentação inicial |
| Semana 2 | Modelagem dos fluxos + criação do protótipo |
| Semana 3 | Revisão do protótipo + documentação técnica |
| Semana 4 | Vídeo de apresentação + entrega final |

---

## Tecnologias Utilizadas

- **HTML5** — estrutura das telas
- **CSS3** — estilização e layout responsivo
- **JavaScript** — interações e navegação entre telas
- **Google Fonts** — tipografia (Syne + DM Sans)

> Tecnologias sugeridas para implementação futura: PHP + MySQL (back-end), integração com Active Directory (autenticação corporativa).

---

## Estrutura do Repositório

```
sgto-globalparts/
│
├── sgto/                          # Protótipo navegável
│   ├── login.html
│   ├── dashboard.html
│   ├── novo_chamado.html
│   ├── chamados.html
│   ├── chamado_detalhe.html
│   └── calendario.html
└── README.md
```

---

## Autor

**Jordaniel**  
Analista de TI — Global Parts  
Curso: Análise e Desenvolvimento de Sistemas — PUC Goiás  
Projeto Integrador III–B | 2026

---

## Referências

- SOMMERVILLE, I. *Engenharia de Software*. 9. ed. Pearson, 2011.
- PRESSMAN, R. S. *Engenharia de Software: Uma Abordagem Profissional*. 8. ed. McGraw-Hill, 2014.
- SCHILDT, H. *Java: A Beginner's Guide*. 6. ed. McGraw-Hill, 2014.

---

> 📅 Data de entrega: **07 de abril de 2026**  
> 🏫 PUC Goiás — Escola Politécnica e de Artes — CEAD
