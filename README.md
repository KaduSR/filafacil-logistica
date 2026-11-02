# FilaFácil Logística — Sistema de Coletas


![workflow](https://github.com/KaduSR/filafacil-logistica/actions/workflows/codeql.yml/badge.svg)


## Visão Geral

O filafacil-logistica é o sistema de gerenciamento de coletas da FilaFácil Logística, desenvolvido como parte da trilha de formação Desenvolvedor Júnior para Pleno (Escola Mundo Dev). O projeto organiza o fluxo de coletas de entregas — cadastro, listagem, filtragem por status e prioridade, atualização de status e geração de resumo operacional — com separação clara entre camadas de entrada, regras de negócio e persistência

## Tecnologias

- Node.js 18+
- TypeScript

## Estrutura do Projeto

```
filafacil-logistica/
├── .github/
│   └── workflows/
├── src/
│   ├── controller/     # Entrada de comandos (terminal ou API)
│   ├── service/        # Regras de negócio das coletas
│   ├── repository/     # Acesso a dados (arquivo local ou banco)
│   └── domain/         # Contratos e entidades de domínio
├── tests/              # Testes unitários e de integração
├── README.md
├── .gitignore
└── package.json / pom.xml
```


## Como Rodar

### Pré-requisitos
- Node.js 18+
- Git

### Instalação
```bash
git clone https://github.com/KaduSR/filafacil-logistica
cd filafacil-logistica
npm install
```

### Execução
```bash
npm start
```

## Como Contribuir

1. Crie uma branch para sua feature: `git checkout -b minha-feature`
2. Faça commits descritivos: `git commit -m "feat: ..."
3. Push: `git push origin minha-feature`
4. Abra um Pull Request

## Licença

[MIT / Apache 2.0 / etc]