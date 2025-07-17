# 💻 MovimentosManuais.Frontend

Frontend desenvolvido em **Angular** para gerenciar os movimentos contábeis manuais, conforme requisitos do desafio prático. A aplicação consome a API backend desenvolvida em .NET.

---

## 📸 Prévia

> Interface de cadastro e consulta de movimentos, com layout responsivo e experiência otimizada.

---

## 🧰 Tecnologias Utilizadas

- [Angular ](https://angular.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [Bootstrap ](https://getbootstrap.com/)
- [RxJS](https://rxjs.dev/)
- HTTP Client Module
- FormsModule (formulários reativos e template-driven)

---

## 🎯 Funcionalidades

- ✅ Tela de **consulta** de movimentos manuais por mês/ano
- ✅ Tela de **cadastro** de novos movimentos com validações
- ✅ Componente de mensagens reutilizável com exibição automática
- ✅ Seleção dinâmica de códigos COSIF conforme o produto escolhido
- ✅ Boas práticas com estrutura em módulos, serviços e componentização

---

## 🗂️ Estrutura de Pastas

src/app/
├── features/
│ └── movimento-manual/
│ ├── movimento-manual-consulta/
│ └── movimento-manual-cadastro/
├── models/
├── services/
├── shared/
│ └── component/message/


---

## ▶️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/MovimentosManuais.Frontend.git
cd MovimentosManuais.Frontend

npm install

ng serve -o

🔗 Backend
Este frontend depende da API .NET que deve estar configurada e em execução.

📄 Licença
Este projeto é licenciado sob os termos da MIT License.
