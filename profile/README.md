<div align="center">

<img src="https://raw.githubusercontent.com/tatustack/.github/main/profile/teo.png" alt="Teo, o tatu — mascote do TatuStack" width="160" />

# TatuStack 🛡️

### A AWS do jeito certo, sem você precisar entender a AWS.

*Suba suas aplicações em uma conta AWS só sua — segura, otimizada e Well-Architected de fábrica.*
*Sem console. Sem VPC. Sem susto na fatura. Você conversa com o **Teo**, e o app sobe.*

</div>

---

## 🚀 O que é

O **TatuStack** provisiona infraestrutura **Well-Architected de fábrica** na AWS, a partir de
blueprints aprovados. O dev ganha uma **conta AWS isolada** e interage só com a nossa camada de
abstração (o chatbot **Teo**) — nunca com o console cru da AWS.

O que foge do catálogo vira **projeto de consultoria AWS**. Duas camadas de receita, um só fluxo.

## 📦 Os 5 blueprints (catálogo)

| Blueprint | Stack | Caso de uso |
|---|---|---|
| 🌐 **Site/Frontend** | S3 + CloudFront + ACM | Site/app estático |
| ⚡ **API Serverless** | API Gateway + Lambda + DynamoDB | API sem servidor |
| 🐳 **Fullstack** | CloudFront + Fargate + RDS | App completo (front + back + banco) |
| 🗄️ **Banco** | RDS/Aurora + Secrets + backup | Banco gerenciado |
| ⚙️ **Worker/Jobs** | SQS + EventBridge + Lambda/Fargate | Processamento assíncrono |

## 🏗️ Como funciona

```
1. Ganhe sua conta AWS   →  isolada, já nasce segura e otimizada
2. Converse com o Teo    →  ele casa seu pedido com um blueprint aprovado
3. App no ar             →  Well-Architected, HTTPS, backup e custo sob controle
```

## 🧭 Princípios

- 🔒 **Conta isolada por cliente** — blast radius zero
- 🏛️ **Well-Architected de fábrica** — seguro e otimizado por padrão
- 📊 **Custo transparente** — faixas controladas + alertas, sem conta-surpresa
- 🤖 **Teo é um tradutor, não um gênio** — só provisiona o que está no catálogo aprovado

## 🛠️ Stack técnica

`AWS Organizations` · `Control Tower + AFT` · `Service Catalog` · `CloudFormation (CDK)` ·
`Cognito` · `Step Functions` · `Bedrock` · `GitHub Actions + OIDC`

---

<div align="center">

*Mascote: **Teo, o tatu** 🛡️ · Marca: **TatuStack** · Feito no Brasil 🇧🇷*

</div>
