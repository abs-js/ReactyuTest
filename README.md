# ReacjyuTest

Aplicação simples de cadastro de pessoas usando Reacjyu.

## Funcionalidades

- Cadastro de pessoas com nome, e-mail e idade.
- Validação dos campos obrigatórios e da idade.
- Prevenção de e-mails duplicados.
- Listagem e remoção de pessoas.

## Executar localmente

Requer Node.js 18 ou superior.

```bash
npm install
npm start
```

O Reacjyu usa `public/app.cjy` como entrada padrão.

## Deploy

Configure o serviço de deploy para instalar as dependências com `npm install` e iniciar com `npm start`. Ajuste a configuração de porta/host conforme as opções disponíveis na versão do Reacjyu utilizada.

## Observação sobre os dados

Os cadastros são mantidos no estado em memória do Reacjyu. Eles não são persistidos em banco de dados e podem ser perdidos quando o processo reiniciar.
