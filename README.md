# Task Manager Dashboard

Aplicação web full-stack desenvolvida com **Blazor WebAssembly** para o front-end e **ASP.NET Core Web API** para o back-end.  
Permite gerenciar tarefas, visualizar gráficos e estatísticas em tempo real.

---

## 🚀 Tecnologias
- C# / .NET 8
- Blazor WebAssembly (Front-end)
- ASP.NET Core Web API (Back-end)
- Entity Framework Core + SQLite
- Chart.js (visualização de gráficos)
- Bootstrap / MudBlazor (UI)

---

## ⚙️ Funcionalidades
- CRUD completo de tarefas
- Dashboard com gráficos de tarefas concluídas, pendentes e atrasadas
- Filtros por prioridade, categoria e prazo
- Comunicação via API RESTful
- Interface responsiva para desktop e mobile

---

## 🧩 Como executar

```bash
# Clonar o repositório
git clone https://github.com/ajoao42/task-manager-dashboard.git
cd task-manager-dashboard

# Restaurar dependências
dotnet restore

# Executar a API
cd Backend
dotnet run

# Executar o Front-end
cd ../Frontend
dotnet run
