
<img width="1273" height="674" alt="WhatsApp Image 2026-05-10 at 23 36 07" src="https://github.com/user-attachments/assets/4f271d91-fbcf-456c-b611-17c1773e04fb" />

# ihcux-racha-ai-blazor-
# RachaAi — Dashboard Financeiro em Blazor
## 👤 GRUPO #3
**Nome:** Lucas Gonçalves -  RA: 32617617 
**Curso:** (Ciência da computação)

**Nome:** Sergio Antonio - RA: 326128163 
**Curso:** (Analise e Desenvolvimento de Sistemas) 

**Nome:** Paulo André Lima Patrício – RA: 326128523
**Curso:** (Analise e Desenvolvimento de Sistemas) 

**Nome:** Miguel Oliveira Silva – RA: 326128330 
**Curso:** (Analise e Desenvolvimento de Sistemas) 

**Nome:**Arthur Carvalho Oliveira – RA: 32611916 
**Curso:** (Analise e Desenvolvimento de Sistemas) 




Projeto desenvolvido para a disciplina de Interação Humano Computador e UX.

O sistema apresenta um dashboard de divisão de gastos compartilhados, permitindo visualizar:
- Total a receber
- Total a pagar
- Saldo geral
- Lista de grupos de despesas

---

# Tecnologias Utilizadas

- .NET 10
- Blazor WebAssembly
- Bootstrap 5
- C#

---

# Estrutura do Projeto

```plaintext
Models
    Grupo.cs

Pages
    Dashboard.razor

Shared
    GrupoCard.razor
## Dificuldade Técnica Adicional
Outra dificuldade encontrada foi entender o sistema de roteamento e renderização do Blazor WebAssembly.
Durante o desenvolvimento, a página `Dashboard.razor` compilava corretamente, porém não aparecia no navegador. O problema estava relacionado à configuração do `App.razor` e à estrutura do `MainLayout`, que precisava conter o `@Body` para renderizar as páginas.
Esse processo ajudou a compreender melhor:
como o Blazor gerencia rotas com `@page`
- como funciona o `Router`
- a importância do `Layout` na exibição das páginas
- a relação entre componentes e renderização no ciclo de vida do Blazor
