# Projeto Contínuo UC Testes de Sistemas (Firjan SENAI)

## 📌 Sobre o Projeto
Aplicação web em PHP/Laravel desenvolvida para a prática automatizada de testes de software (Unitários, Integração e E2E).

## 🛠️ Requisitos do Ambiente
- PHP 8.2+
- Composer 2.x
- SQLite
- Git & GitHub

## 🎯 Objetivos de Qualidade (QA)
- Garantir alta cobertura de testes unitários na camada de negócio[cite: 21].
- Validar endpoints HTTP e formulários[cite: 21].
- Prevenir regressões através da integração contínua (CI/CD)[cite: 21].

## 👥 Cultura de QA (Síntese do Debate em Grupo)

**1. Quais os riscos operacionais e financeiros de lançar um software em produção sem testes automatizados?**
Aumenta o risco de falhas críticas no sistema e perdas financeiras, perda da reputação no mercado e prejuízos que poderiam ser evitados.

**2. Como os testes automatizados evitam regressões durante novos deploys?**
Os testes funcionam como uma segurança automatizada a cada alteração no código. Se uma funcionalidade nova ou correção mexe em algo que já funcionava, os testes acusam a falha antes que o código vá para o ar.

**3. Por que a cultura de testes deve ser praticada desde o primeiro dia de código e não deixada para o final?**
Porque construir o sistema pensando em testes desde o início obriga o desenvolvedor a escrever um código limpo. Deixar os testes para o final deixa o código mais difícil de testar, pois o sistema não foi projetado para as validações.
