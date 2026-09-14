# 🍱 API Marmitaria

API REST para gerenciamento de pedidos de uma marmitaria, desenvolvida com **NestJS** e **TypeScript**.

O projeto está sendo desenvolvido com foco em boas práticas de desenvolvimento backend, organização de código, separação de responsabilidades e testes automatizados.

---

## 🚀 Tecnologias

- **Node.js**
- **NestJS**
- **TypeScript**
- **Vitest**
- **Supertest**
- **Prettier**
- **Oxlint**

---

## 🏗️ Arquitetura

O projeto utiliza uma estrutura inspirada em **Clean Architecture**, buscando separar as responsabilidades da aplicação entre domínio, casos de uso e infraestrutura.

```text
src/
├── dto/
│   └── create-order.dto.ts
│
├── orders/
│   ├── application/
│   │   └── CreateOrder.ts
│   │
│   ├── domain/
│   │   ├── IOrderRepository.ts
│   │   └── Order.ts
│   │
│   └── infrastructure/
│       └── OrderRepositoryMemory.ts
│
├── order.controller.ts
├── app.controller.ts
├── app.module.ts
├── app.service.ts
└── main.ts
**Geliton**

Projeto desenvolvido para estudos e prática de desenvolvimento backend.

