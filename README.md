# 🛴 Urban Scooter — Mobile QA Testing

Projeto de **Quality Assurance (QA)** realizado durante a formação em testes de software, com foco na validação do aplicativo móvel **Urban Scooter** para Android.

## 📱 Sobre o projeto

O objetivo deste projeto foi testar as principais funcionalidades destacadas nos requisitos do aplicativo Urban Scooter, verificando tanto o **comportamento funcional** quanto o **layout e design da interface**.

Os testes foram realizados utilizando um emulador Android e considerando os requisitos disponibilizados para o aplicativo.

## 🎯 Objetivos dos testes

* Validar as funcionalidades do aplicativo móvel.
* Verificar se o comportamento do aplicativo está de acordo com os requisitos.
* Testar diferentes cenários positivos e negativos.
* Validar mensagens, campos, botões e fluxos de navegação.
* Verificar elementos de layout e design.
* Identificar e documentar possíveis defeitos.
* Registrar os resultados dos testes e reportar bugs encontrados.

## 🧪 Escopo dos testes

Foram criados e executados casos de teste para as funcionalidades destacadas nos requisitos do projeto.

Os testes incluíram:

* Testes funcionais
* Testes de interface (UI)
* Testes de layout
* Testes de navegação
* Testes de validação de campos
* Testes de cenários positivos
* Testes de cenários negativos
* Verificação de mensagens e comportamentos esperados

## 🛠️ Ferramentas utilizadas

| Ferramenta             | Utilização                                     |
| ---------------------- | ---------------------------------------------- |
| **Android Studio**     | Execução e testes do aplicativo no emulador    |
| **Android Emulator**   | Simulação de dispositivo Android               |
| **Urban Scooter APK**  | Aplicativo utilizado nos testes                |
| **Postman**            | Interação com a API e criação de entregador    |
| **Swagger / API Docs** | Consulta da documentação da API                |
| **Figma**              | Validação do layout e design                   |
| **Jira**               | Registro e acompanhamento de bugs              |
| **Google Sheets**      | Documentação dos casos e resultados dos testes |

## 🔌 API

Para realizar os testes, foi necessário configurar o aplicativo para se comunicar com o backend da Urban Scooter.

Também foi utilizado o endpoint da API para criar um entregador e possibilitar o acesso ao aplicativo móvel.

As requisições `POST` foram realizadas utilizando o formato **JSON no corpo da requisição**, conforme especificado na documentação da API.

## 📋 Casos de teste

Os casos de teste foram documentados na planilha do projeto, contendo informações como:

* ID do caso de teste
* Funcionalidade
* Pré-condições
* Passos para reprodução
* Dados de teste
* Resultado esperado
* Resultado atual
* Status do teste
* Link para bug no Jira, quando aplicável

### Resultado dos testes

| Status | Descrição                                                   |
| ------ | ----------------------------------------------------------- |
| ✅ PASS | O comportamento observado corresponde ao resultado esperado |
| ❌ FAIL | O comportamento observado não corresponde ao requisito      |
| 🐞 BUG | Defeito identificado e registrado no Jira                   |

## 🐞 Registro de bugs

Quando foram encontrados comportamentos diferentes dos requisitos, os defeitos foram documentados no **Jira**, contendo informações necessárias para reprodução e análise do problema.

Exemplo de informações registradas:

* Título do bug
* Ambiente de teste
* Pré-condições
* Passos para reprodução
* Resultado esperado
* Resultado atual
* Evidências
* Severidade / prioridade

## 🎨 Validação de UI

Além dos testes funcionais, foram realizadas verificações de interface com base nos designs disponibilizados no **Figma**.

Foram observados aspectos como:

* Posicionamento dos elementos
* Textos
* Botões
* Campos de entrada
* Tamanhos e alinhamentos
* Navegação
* Mensagens apresentadas ao usuário
* Correspondência entre o aplicativo e o design esperado

## 📱 Ambiente de teste

**Plataforma:** Android
**API:** Android 31
**Ambiente:** Android Studio Emulator
**Aplicativo:** Urban Scooter Mobile

## 📂 Estrutura do projeto

```text
urban-scooter-mobile-qa/
│
├── README.md
│
├── test-cases/
│   └── Urban_Scooter_Mobile_Test_Cases.xlsx
│
└── bug-reports/
    └── jira-links.md
```

> A estrutura acima pode ser ajustada de acordo com os arquivos efetivamente adicionados ao repositório.

## 📊 Entregáveis

Este projeto contém:

* Casos de teste do aplicativo móvel
* Resultados da execução dos testes
* Registro dos defeitos encontrados
* Links para os respectivos bugs no Jira
* Validações baseadas nos requisitos
* Testes de interface baseados no Figma

## 👩‍💻 Sobre o projeto

Este projeto faz parte da minha formação em **Quality Assurance**, demonstrando conhecimentos práticos em **testes mobile, criação e execução de casos de teste, análise de requisitos, testes de UI, API e documentação de bugs**.

**Objetivo profissional:** atuar como **QA Tester**, contribuindo para a qualidade, estabilidade e experiência dos usuários em produtos digitais.
