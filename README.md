# Sistema Autobots - Exercício 1

Este repositório contém os exercícios propostos pelo Professor Gerson da Penha Neto, da FATEC SJC, para a disciplina de 'Desenvolvimento Web III' no terceiro semestre. Cada exercício está organizado em uma pasta separada.

## Pré-requisitos

Antes de iniciar, certifique-se de ter os seguintes pré-requisitos instalados:

1. Java Development Kit (JDK) - Versão 11 ou superior
2. Apache Maven - Ferramenta de construção de projetos
3. MySQL - Banco de dados
4. Eclipse IDE - Ambiente de desenvolvimento integrado (ou outra IDE de sua preferência)
5. Git - Controle de versão

## Configuração do Banco de Dados

1. Crie um banco de dados MySQL com o nome `sistema_autobots`. Você pode fazer isso usando uma ferramenta como o phpMyAdmin ou executando o seguinte comando:

```sql
CREATE DATABASE sistema_autobots;
```

Configure as credenciais do banco de dados no arquivo
`src/main/resources/application.properties` ou `src/main/resources/application.yml`,
dependendo de como sua aplicação está configurada, substitua seu_usuario e sua_senha pelas suas credenciais.

## Importando no Eclipse

1. Abra o Eclipse IDE (ou a IDE de sua preferência).

2. Importe o projeto para o workspace do Eclipse:

   - No menu "File", selecione "Import".
   - Na janela de importação, escolha "Existing Maven Projects".
   - Clique em "Next" e navegue até o diretório do projeto. Selecione o diretório raiz do projeto e clique em "Finish".

3. Certifique-se de que o projeto foi importado com sucesso.

## Notas do Exercício 1:
# Testando a Aplicação
Você pode testar a aplicação enviando um exemplo de JSON conforme mostrado abaixo:
```
{
  "nome": "Maria Silva",
  "nomeSocial": "Maria da Silva",
  "dataNascimento": "1995-08-20",
  "dataCadastro": "2023-09-14",
  "documentos": [
    {
      "tipo": "RG",
      "numero": "123456789"
    },
    {
      "tipo": "CPF",
      "numero": "987654321"
    }
  ],
  "endereco": {
    "estado": "SP",
    "cidade": "São Paulo",
    "bairro": "Centro",
    "rua": "Rua Principal",
    "numero": "123",
    "codigoPostal": "12345-678",
    "informacoesAdicionais": "Prédio Azul, Apto 101"
  },
  "telefones": [
    {
      "ddd": "12",
      "numero": "987654321",
      "tipo": "Residencial"
    },
    {
      "ddd": "12",
      "numero": "987654322",
      "tipo": "Celular"
    }
  ]
}

```
 
