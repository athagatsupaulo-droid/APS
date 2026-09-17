# Projeto APS - Análise de Projeto de Sistemas

## 5W - Estrutura do Projeto

### 🔍 **WHAT** (O Quê?)
Este projeto é um trabalho acadêmico da disciplina **Engenharia de Software** da Universidade do Distrito Federal (UDF). Ele consiste em uma análise e desenvolvimento de um sistema que aplica princípios e boas práticas da engenharia de software.

### 👥 **WHO** (Quem?)
- **Desenvolvedor(es):** Renan Akira, Fernando Rebouças, Paulo Henrique Santos Azevedo
- **Instituição:** Centro Universitário UDF 
- **Disciplina:** Engenharia de Software

### ⏰ **WHEN** (Quando?)
- **Período:** 2026
- **Status:** Em Desenvolvimento

### 📍 **WHERE** (Onde?)
- **Localização do Repositório:** [GitHub - Analise_Projeto_Sistemas](https://github.com/Aslexya/Analise_Proj_Sistemas)
- **Estrutura:** Disponível na pasta `ProjetoAPS`

### 🎯 **WHY** (Por Quê?)
Este projeto foi desenvolvido com os seguintes objetivos:
- Aplicar conceitos fundamentais de engenharia de software
- Demonstrar compreensão de metodologias de desenvolvimento
- Exercitar práticas de análise, design e implementação de sistemas
- Contribuir para o aprendizado acadêmico em desenvolvimento de software

---

## 📋 Conteúdo do Projeto

### Estrutura de Diretórios
```
ProjetoAPS/
├── README.md
├── [documentação/]
├── [código-fonte/]
├── [testes/]
└── [recursos/]
```

### Componentes Principais
- **Documentação:** Análises, diagramas e especificações do sistema
- **Código-fonte:** Implementação do projeto
- **Testes:** Casos de teste e validação
- **Recursos:** Arquivos auxiliares e dependências

---

## 🚀 Como Começar

### Pré-requisitos
- [Listar ferramentas necessárias]
- [Listar dependências]

### Instalação
```bash
# Clone o repositório
git clone https://github.com/Aslexya/Analise_Proj_Sistemas.git

# Navegue até o projeto
cd Analise_Proj_Sistemas/ProjetoAPS
```

### Execução
```bash
# [Comandos para executar o projeto]
```

---

## 📚 Documentação

Consulte os arquivos de documentação para:
- Análise de requisitos
- Diagramas UML
- Especificações técnicas
- Guia de uso

---

## 🛠️ Tecnologias Utilizadas

- [Listar linguagens de programação]
- [Listar frameworks e bibliotecas]
- [Listar ferramentas de desenvolvimento]

---

## ✅ Checklist do Projeto

- [ ] Análise de requisitos completa
- [ ] Design do sistema finalizado
- [ ] Implementação concluída
- [ ] Testes implementados
- [ ] Documentação finalizada
- [ ] Revisão de código

---

## 📝 Notas Importantes

- Projeto acadêmico da disciplina Engenharia de Software
- Siga as melhores práticas de codificação durante o desenvolvimento
- Mantenha a documentação atualizada

---

## 📞 Contato e Suporte

Para dúvidas sobre o projeto, abra uma [issue](https://github.com/Aslexya/Analise_Proj_Sistemas/issues) no repositório.

---

## 📄 Licença

[Especificar licença do projeto]

---

**Última atualização:** Agosto de 2026



1. INTRODUÇÃO

O presente trabalho apresenta a documentação de requisitos e a modelagem de um Sistema de Reserva de Restaurantes. O sistema tem como objetivo facilitar o processo de reserva de mesas, permitindo que os clientes consultem restaurantes, horários disponíveis e realizem suas reservas de forma organizada.

A documentação de requisitos é importante para definir de forma clara o que o sistema deve fazer e quais necessidades dos usuários devem ser atendidas. A modelagem UML também é importante, pois permite representar o funcionamento e a estrutura do sistema de forma visual, facilitando o entendimento entre os integrantes da equipe e apoiando o desenvolvimento do software.


2. JUSTIFICATIVA

A realização de reservas em restaurantes pode apresentar problemas quando é feita por telefone, mensagens ou controles manuais. Essas formas podem dificultar a organização das mesas, causar conflitos de horários e dificultar o controle da quantidade de clientes esperados.

O sistema proposto busca resolver esses problemas ao centralizar as reservas em um único sistema. Com isso, os clientes poderão consultar horários disponíveis e realizar ou cancelar reservas, enquanto os funcionários e gerentes poderão acompanhar e organizar as reservas do restaurante. Espera-se, assim, melhorar a organização do estabelecimento e facilitar a experiência dos clientes.


3. OBJETIVOS

3.1. Objetivo Geral

Desenvolver a documentação de requisitos e a modelagem UML de um Sistema de Reserva de Restaurantes, buscando facilitar a realização e o gerenciamento de reservas de mesas.


3.2. Objetivos Específicos

• Identificar e descrever os requisitos funcionais e não funcionais do sistema.
• Identificar as principais regras de negócio relacionadas às reservas.
• Elaborar diagramas UML que representem diferentes visões do sistema.
• Produzir a documentação de negócios e de requisitos para apoiar o desenvolvimento.
• Aplicar técnicas de levantamento, elicitação e análise de requisitos.
• Definir as principais funcionalidades da primeira versão do sistema.


4. DESCRIÇÃO DO SISTEMA PROPOSTO

O sistema proposto será um Sistema de Reserva de Restaurantes, desenvolvido para permitir que clientes consultem restaurantes e horários disponíveis e realizem reservas de mesas. O sistema também permitirá o cancelamento de reservas e o gerenciamento das reservas pelos funcionários e gerentes dos restaurantes.

O público-alvo é formado principalmente por clientes que desejam realizar reservas e por funcionários e gerentes que precisam organizar as mesas e os horários do estabelecimento.

Entre as principais funcionalidades estão o cadastro e consulta de restaurantes, consulta de disponibilidade, realização e cancelamento de reservas, gerenciamento das reservas, atualização da disponibilidade das mesas e consulta de relatórios.

Para o desenvolvimento, poderão ser utilizadas tecnologias de desenvolvimento web, banco de dados relacional e ferramentas de modelagem UML. A escolha definitiva das tecnologias será definida pelo grupo durante a etapa de desenvolvimento.


5. REQUISITOS

5.1. Requisitos Funcionais

RF01 – Consulta de Restaurantes: o sistema deve permitir que o cliente consulte os restaurantes cadastrados.

RF02 – Consulta de Disponibilidade: o sistema deve permitir que o cliente consulte as datas e os horários disponíveis para realizar uma reserva.

RF03 – Realização de Reserva: o sistema deve permitir que o cliente realize uma reserva informando a data, o horário e a quantidade de pessoas.

RF04 – Cancelamento de Reserva: o sistema deve permitir que o cliente cancele uma reserva realizada anteriormente.

RF05 – Gerenciamento de Reservas: o sistema deve permitir que funcionários visualizem e gerenciem as reservas do restaurante.

RF06 – Atualização de Disponibilidade: o sistema deve atualizar a disponibilidade das mesas após a realização ou o cancelamento de uma reserva.

RF07 – Confirmação de Reserva: o sistema deve enviar uma confirmação ao cliente após a realização de uma reserva.

RF08 – Consulta de Relatórios: o sistema deve permitir que o gerente consulte informações e relatórios sobre as reservas realizadas.


5.2. Requisitos Não Funcionais

RNF01 – Desempenho: o sistema deve apresentar os resultados das consultas de disponibilidade em até 2 segundos em condições normais de uso.

RNF02 – Segurança: o sistema deve exigir autenticação para permitir o acesso a dados pessoais e funções administrativas.

RNF03 – Usabilidade: o sistema deve possuir uma interface simples e permitir que o cliente realize uma reserva em no máximo 5 etapas.

RNF04 – Confiabilidade: o sistema não deve permitir duas reservas para a mesma mesa no mesmo horário.

RNF05 – Compatibilidade: o sistema deve funcionar nos principais navegadores atuais e em dispositivos móveis e computadores.


5.3. Regras de Negócio

RN01 – Disponibilidade da Mesa: uma mesa não pode possuir duas reservas para o mesmo horário. Associada ao RF03 – Realização de Reserva.

RN02 – Dados Obrigatórios: uma reserva deve possuir obrigatoriamente a data, o horário e a quantidade de pessoas. Associada ao RF03 – Realização de Reserva.

RN03 – Disponibilidade para Reserva: uma reserva só poderá ser realizada quando houver disponibilidade para a quantidade de pessoas informada. Associada ao RF03 – Realização de Reserva.

RN04 – Cancelamento: uma reserva cancelada deve liberar a disponibilidade da mesa para aquele horário. Associada ao RF04 – Cancelamento de Reserva e RF06 – Atualização de Disponibilidade.

RN05 – Acesso Administrativo: somente funcionários e gerentes autorizados poderão visualizar e gerenciar as reservas do restaurante. Associada ao RF05 – Gerenciamento de Reservas e RNF02 – Segurança.

RN06 – Confirmação: após uma reserva ser realizada com sucesso, o sistema deve registrar a reserva e disponibilizar uma confirmação para o cliente. Associada ao RF07 – Confirmação de Reserva.

RN07 – Quantidade de Pessoas: a quantidade de pessoas informada na reserva deve ser compatível com a capacidade da mesa disponível. Associada ao RF03 – Realização de Reserva.
