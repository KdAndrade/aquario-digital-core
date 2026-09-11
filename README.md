# 🌊 Missão: Controle de Qualidade da Água

Bem-vindo ao repositório do projeto **Controle de Qualidade da Água**. Este sistema foi desenvolvido para realizar o monitoramento automatizado e a validação de parâmetros físico-químicos vitais em ambientes aquáticos.

---

## 📌 Sobre o Sistema

O módulo principal do sistema, implementado na classe `ControleQualidadeAgua`, é responsável por avaliar se as condições da água estão dentro das especificações seguras.

### Parâmetros Monitorados:

- **pH:** O nível ideal deve estar estritamente entre **6.8 e 7.6**.
- **Temperatura:** A faixa segura de operação é de **22.0 °C a 28.0 °C**.

Caso qualquer um dos parâmetros saia do limite aceitável, o sistema dispara um alerta de Quality Assurance (QA) informando a irregularidade.

---

## 🚀 Camadas do Ambiente

Para garantir a confiabilidade das medições e a estabilidade do software, utilizamos a seguinte estrutura de ambientes (branches):

| Ambiente            | Nome      | Descrição                                                                                                           |
| :------------------ | :-------- | :------------------------------------------------------------------------------------------------------------------ |
| **Desenvolvimento** | `develop` | Espaço para implementação de novas funcionalidades, testes de novas regras de negócio e experimentos da equipe.     |
| **Homologação**     | `stage`   | Ambiente pré-produtivo utilizado para validação rigorosa dos testes de QA e integração antes do lançamento oficial. |
| **Produção**        | `main`    | Código estável, homologado e em execução contínua no monitoramento do ambiente aquático.                            |

---

## 🧬 Biólogos e Desenvolvedores Responsáveis

- **Biólogo:** Kauan de Andrade Oliveira
