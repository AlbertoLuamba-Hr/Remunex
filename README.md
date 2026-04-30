#  Sistema de Gestão de Folha de Pagamento

##  Descrição
Este projeto é um sistema de gestão de Recursos Humanos focado no processamento salarial. Permite cadastrar funcionários, calcular salários automaticamente e gerar recibos mensais.

---

##  Funcionalidades
- Cadastro de funcionários
- Processamento salarial automático
- Cálculo de INSS e IRT
- Gestão de subsídios e descontos
- Geração de recibos de salário
- Visualização de folha salarial

---

##  Regras de Cálculo
- INSS: 3% (trabalhador)
- INSS: 8% (empresa)
- IRT: conforme tabela fiscal de Angola

---

##  Tecnologias Utilizadas
- Python
- Django
- PostgreSQL
- HTML, CSS e JavaScript

---

##  Estrutura do Projeto
- Funcionários
- Processamento Salarial
- Relatórios
- Gestão de Usuários

---

##  Como usar
1. Importar ficheiro Excel com dados dos funcionários
2. Processar salários automaticamente
3. Gerar recibos
4. Consultar relatórios

---

##  Futuras Melhorias
- Gestão de férias
- Controle de faltas
- Multiempresa
- Integração bancária

---
let salarioBase = 100000;
let desconto = 10000;
let bonus = 5000;

let salarioFinal = salarioBase - desconto + bonus;

console.log(salarioFinal);

##  Autor
Alberto Celestino Luamba
