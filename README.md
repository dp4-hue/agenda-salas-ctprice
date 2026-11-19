# Agenda das Salas de Reunião — CT Price

Agendamento das salas **Brasil**, **Itália** e **Dubai** da CT Price Organização Contábil.

**Site:** https://dp4-hue.github.io/agenda-salas-ctprice/

## Funcionamento
- 08:00 às 11:30 e 13:00 às 17:30 (almoço bloqueado)
- Reservas em blocos de 30 minutos, sem conflito na mesma sala
- Visualização por dia e por mês, com foto do analista

## Arquivos
| Arquivo | O que é |
|---|---|
| `index.html` | A página completa (HTML, CSS e JavaScript) |
| `logo-branco.png` | Logo da CT Price em branco, usado no banner |
| `banner-1800.jpg` / `banner-960.jpg` | Banner padrão CT Price (computador / celular) |
| `fotos/` | Fotos dos analistas (`nome-sem-acento.jpg`) |

Se uma imagem não estiver no repositório, a página continua funcionando: mostra o nome CT PRICE em texto, um fundo verde no banner e as iniciais dos analistas.

## Importante
Nesta versão as reservas ficam salvas **no navegador de cada pessoa** (localStorage). Para todos verem a mesma agenda, é preciso ligar a página a um banco de dados online (ex.: Firebase Firestore): basta trocar `localDb()` por `firebase.firestore()` no `index.html`, mantendo a coleção `bookings`.

A versão com agenda compartilhada da equipe está publicada no Claude.
