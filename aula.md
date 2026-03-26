# 1 - Cenário

"Um técnico de ar-condicionado precisa de um sistema onde o cliente consiga solicitar orçamento, agendar atendimento, acompanhar o serviço e realizar o pagamento em um único lugar."

# 2 - Briefing

## Qual o objetivo real do site?

Centralizar orçamento, agendamento, acompanhamento do serviço e pagamento em um fluxo digital simples e contínuo.

## Qual é o público-alvo?

Técnicos de ar-condicionado autônomos ou pequenas equipes que precisam organizar e escalar o atendimento.

## O que esse site precisa ter?

1. Formulário simples (tipo de serviço, local, fotos opcionais)
2. Geração automática de valor estimado
3. Agenda com horários disponíveis
4. Confirmação automática para o cliente
5. Status do serviço: orçado → agendado → em execução → finalizado
6. Atualizações simples (inclusive pelo técnico)
7. Histórico de serviços
8. Dados do atendimento
9. Reagendamento e cancelamento
10. Integração com Pix e cartão
11. Link de pagamento após conclusão

# 3 - Requisitos (FURPS)

## Funcionalidade (RF)

1. O sistema deve permitir que o cliente solicite orçamento informando tipo de serviço, endereço e detalhes do atendimento.
2. O sistema deve permitir o agendamento de visitas com base na disponibilidade do técnico.

## Usabilidade (RNF)

1. A interface deve ser simples e intuitiva, permitindo que o cliente conclua uma solicitação em até 3 minutos.
2. O sistema deve ser responsivo e utilizável em diferentes dispositivos sem perda de funcionalidade.

## Confiabilidade (RNF)

1. O sistema deve garantir a integridade dos dados de agendamento, evitando conflitos de horário.
2. O sistema deve manter disponibilidade mínima de 99%.

## Performance (RNF)

1. O tempo de resposta das páginas deve ser inferior a 3 segundos.
2. O sistema deve suportar múltiplos acessos simultâneos sem degradação perceptível.

## Suportabilidade (RNF)

1. O sistema deve permitir fácil manutenção e atualização de preços e serviços pelo técnico.
2. O sistema deve ser compatível com integrações de pagamento e notificações.

# Mapa do Site / Aplicação

## 1. Página Inicial

- Apresentação do serviço
- Botão de “Solicitar orçamento”
- Acesso rápido ao acompanhamento
- Destaque de benefícios (rapidez, praticidade, pagamento fácil)

## 2. Solicitação de Orçamento

- Formulário:
- Tipo de serviço
- Endereço
- Descrição do problema
- Upload de fotos (opcional)
- Geração automática de valor estimado
- Botão para avançar para agendamento

## 3. Agendamento

- Exibição de horários disponíveis (baseado na agenda do técnico)
- Seleção de data e hora
- Confirmação do agendamento
- Envio de confirmação automática (mensagem ou e-mail)

## 4. Área do Cliente (Acompanhamento)

- Consulta por login simples ou código do atendimento
- Status do serviço:
- Orçado
- Agendado
- Em execução
- Finalizado
- Detalhes do atendimento
- Histórico de serviços

## 5. Gestão do Atendimento (Técnico)

- Visualização de agenda
- Atualização de status do serviço
- Edição de valores (se necessário)
- Registro de execução do serviço

## 6. Pagamento

- Exibição do valor final
- Opções de pagamento:
- Pix
- Cartão
- Geração de link de pagamento
- Confirmação automática de pagamento