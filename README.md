# Missão Aquário Digital: Protocolo de Versionamento e Gestão de Ecossistema

Sistema de monitoramento e controle de qualidade para o ecossistema do Aquário Digital.

## 🌿 Descrição do Projeto
Este projeto tem como objetivo monitorar parâmetros vitais da água (pH e Temperatura) para assegurar o equilíbrio do ecossistema aquático e a sobrevivência das espécies marinhas e de água doce.

---

## 🏗️ Camadas do Ambiente e Fluxo de Versionamento

O fluxo corporativo de versionamento segue uma arquitetura em 3 camadas:

* **`develop` (Desenvolvimento):** Branch onde novas funcionalidades (`features`) são integradas após validação inicial. Ambiente de integração contínua do time de desenvolvimento.
* **`stage` (Homologação / Testes):** Branch correspondente ao ambiente de homologação e Quality Assurance (QA). Utilizada para testes de carga, simulações de biótopos e validações pré-produção.
* **`main` (Produção):** Branch estável contendo a versão final de produção pronta para operação em tempo real no ecossistema do aquário.

---

## 💻 Módulo de Controle de Qualidade da Água

Classe principal: `ControleQualidadeAgua.java`

* **Faixa Ideal de pH:** 6.8 a 7.6
* **Faixa Segura de Temperatura:** 22.0°C a 28.0°C

---

## 👥 Biólogos e Desenvolvedores Responsáveis

* **Desenvolvedor / Analista:** Fernando Almeida
* **Curso:** Análise e Desenvolvimento de Sistemas
* **RA:** 326132695
* **Instituição:** Una Barreiro
* **GitHub:** [@vivoeasy100](https://github.com/vivoeasy100)