# Sistemas de Chamados Técnicos

## Descrição

Uma grande distribuidora estava enfrentando problemas na resolução de chamados técnicos em seus departamentos devido à descentralização das solicitações, que chegavam por diversos canais de atendimento.

Diante desse cenário, foi proposto um sistema centralizado para registrar, organizar e acompanhar os chamados de suporte técnico.

## Objetivo

O objetivo do projeto é centralizar as solicitações de suporte técnico em um único sistema, permitindo que os funcionários abram chamados e que os técnicos acompanhem e realizem os atendimentos.

O sistema busca melhorar o controle dos chamados, prioridades, responsáveis, status e histórico dos atendimentos.

## Perfis

**Funcionário:** pode somente abrir chamados. Não possui acesso à lista de chamados.

**Técnico:** possui acesso aos chamados, podendo alterar o status, definir o responsável, registrar a solução e encerrar o chamado.

## Senhas de Acesso

- **Funcionário:** `funcionario` / `1234`
- **Técnico:** `tecnico` / `1234`

## Fluxo

Funcionário abre chamado  
↓  
Chamado fica com status 'Aberto' 
↓  
Técnico acessa o chamado  
↓  
Define o responsável  
↓  
Altera para 'Em atendimento' 
↓  
Registra a solução  
↓  
Chamado é 'Encerrado'

## Tecnologias

- HTML
- CSS
- JavaScript
- LocalStorage

## Funcionalidades

- Login por perfil de acesso
- Abertura de chamados
- Geração de número do chamado
- Definição de categoria
- Definição de prioridade
- Definição de responsável
- Alteração de status
- Registro do histórico
- Registro da solução
- Encerramento de chamados

## Status do Projeto

**MVP — versão mínima funcional.**
