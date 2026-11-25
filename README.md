# TimeSync Frontend

Interface web do TimeSync para gestão de agendamentos. A API está no [repositório do backend](https://github.com/MatheusHVM/time-sync-backend).

## Funcionalidades

- Cadastro de clientes e login.
- Calendário de agendamentos por empresa, com reagendamento.
- Telas de empresas e serviços.
- Painel com gráficos de agendamentos mensais, serviços mais realizados e faturamento semestral, com filtros por empresa e funcionário.

## Executar localmente

Com Node.js e npm instalados, execute na raiz do repositório.

```sh
npm ci
npm start
```

Abra [http://localhost:3000](http://localhost:3000). Inicie também o backend. O cliente Axios usa `http://localhost:8080`, definido em [src/api/axiosInstance.ts](src/api/axiosInstance.ts).

| Comando | Finalidade |
| --- | --- |
| `npm start` | Inicia o servidor de desenvolvimento |
| `npm test` | Abre o executor de testes |
| `npm run build` | Gera a build de produção em `build/` |

## Tecnologias

React 18, TypeScript, React Router, PrimeReact, Axios, React Scheduler e Create React App.
