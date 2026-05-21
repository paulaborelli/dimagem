# 🏥 Dimagem — Painel de Gestão

Painel de gestão mensal para a **Dimagem Clínica de Diagnóstico por Imagem**.

## 📁 Estrutura

```
dimagem-painel-gestao/
│
├── dados/                          # Planilhas mensais de entrada de dados
│   └── Dimagem_PainelGestao_2026.xlsx
│
├── painel/                         # Painel online (HTML/JS/CSS)
│   └── index.html                  # (a criar)
│
├── docs/                           # Documentação e instruções
│   └── instrucoes-preenchimento.md
│
└── README.md
```

## 📊 Relatórios cobertos

| # | Relatório |
|---|-----------|
| 1 | Agendamentos por Secretária / Exame / Convênio |
| 2 | Pacientes Cadastrados por Secretária |
| 3 | Procedimentos Agendados por Secretária e Tipo de Exame |
| 4 | Exames Cadastrados por Secretária |
| 5 | Formas de Agendamento por Secretária |
| 6 | Resumo por Tipo de Exame (Agendados × Realizados por Dia) |
| 7 | Entrada Diária por Convênio (Agendados × Realizados) |

## 🔄 Fluxo mensal

1. Abrir `dados/Dimagem_PainelGestao_2026.xlsx`
2. Ir para a aba do mês correspondente
3. Preencher os dados dos 7 relatórios (células azuis)
4. Salvar e fazer commit no Git
5. O painel online atualiza automaticamente

## ✏️ Alterar secretárias / convênios / exames

Acesse a aba **⚙️ Cadastros** na planilha para editar os dados mestres.

---
*Atualizado em: 2026 · Dimagem Clínica de Diagnóstico por Imagem*
