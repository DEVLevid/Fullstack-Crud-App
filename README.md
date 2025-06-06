# Fullstack CRUD Application

Este é um projeto fullstack completo para gerenciamento de produtos, consistindo em uma aplicação frontend em Angular e uma API backend em Spring Boot.

## Visão Geral do Projeto

O projeto é uma aplicação CRUD (Create, Read, Update, Delete) completa para gerenciamento de produtos, com uma interface moderna e responsiva no frontend e uma API REST robusta no backend.

### Componentes do Sistema

1. **Frontend (Angular)**
   - Interface moderna usando ng-zorro-antd
   - Aplicação responsiva e interativa
   - Gerenciamento de estado com RxJS
   - [Ver documentação detalhada do Frontend](./frontend/README.md)

2. **Backend (Spring Boot)**
   - API REST completa
   - Persistência de dados com MySQL
   - Arquitetura em camadas
   - [Ver documentação detalhada do Backend](./backend/README.md)

## Tecnologias Principais

### Frontend
- Angular 19.2.0
- TypeScript 5.7.2
- ng-zorro-antd 19.3.1
- RxJS 7.8.0

### Backend
- Java 17
- Spring Boot
- Spring Data JPA
- MySQL 8
- Maven

## Pré-requisitos

Para executar o projeto completo, você precisará:

1. **Para o Frontend:**
   - Node.js (versão LTS)
   - npm
   - Angular CLI

2. **Para o Backend:**
   - JDK 17 ou superior
   - MySQL 8
   - Maven

## Como Executar o Projeto

### 1. Configuração do Backend
1. Configure o banco de dados MySQL conforme instruções na [documentação do backend](./backend/README.md)
2. Execute o backend:
   ```bash
   cd backend
   mvn spring-boot:run
   ```

### 2. Configuração do Frontend
1. Instale as dependências:
   ```bash
   cd frontend
   npm install
   ```
2. Execute o frontend:
   ```bash
   npm start
   ```

## Estrutura do Projeto

```
Fullstack-Crud-App-1/
├── frontend/          # Aplicação Angular
│   ├── src/          # Código fonte do frontend
│   └── README.md     # Documentação do frontend
├── backend/          # API Spring Boot
│   ├── src/         # Código fonte do backend
│   └── README.md    # Documentação do backend
└── README.md        # Esta documentação
```

## Documentação Detalhada

Para informações mais detalhadas sobre cada componente do sistema, consulte:

- [Documentação do Frontend](./frontend/README.md)
- [Documentação do Backend](./backend/README.md)

## Contribuição

Para contribuir com o projeto:

1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## Suporte

Para suporte ou dúvidas:
- Abra uma issue no repositório
- Consulte a documentação específica de cada componente
- Entre em contato com a equipe de desenvolvimento

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.