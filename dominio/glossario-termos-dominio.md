# Glossário de Termos do Domínio (Plataforma "PrettyFlights")

> **ATENÇÃO:**
> 
> Este artefato pode receber incrementos pelo professor ao longo da disciplina, portanto acesse seu conteúdo sempre com a base de código atualizada.

## Núcleo Operacional (Core Business)

| Termo | Descrição |
| --- | --- |
| **Aeronave (Aircraft)** | Recurso físico principal, que possui prefixo (matrícula), modelo e capacidade de carga/passageiros. |
| **Voo (Flight)** | Instância de operação aérea identificada por um código (Ex: G3-1234). Conecta origem a destino em horário planejado. |
| **Slot** | Intervalo de tempo exato autorizado para pouso ou decolagem. Recurso escasso e base da **Aula 02**. |
| **Trecho (Leg)** | Uma parte de um voo (ex: SP -> Madri em um voo com destino final a Paris). |

---

## Gestão de Passageiros e Carga

| Termo | Descrição |
| --- | --- |
| **PNR (Passenger Name Record)** | O "localizador". Registro no banco de dados com todas as informações da reserva do passageiro. |
| **Check-in** | Processo de validar a presença e emitir o cartão de embarque. **Ponto de maior stress (carga)** do sistema. |
| **Cartão de Embarque** | Artefato (digital ou físico) que autoriza o acesso às áreas restritas e à aeronave. |
| **No-Show** | Quando um passageiro com reserva confirmada não se apresenta para o embarque. |

---

## Infraestrutura de Solo (Ground Operations)

| Termo | Descrição |
| --- | --- |
| **Pátio (Apron)** | Área onde as aeronaves estacionam para embarque, desembarque e abastecimento. |
| **Gate (Portão)** | Interface física entre o terminal e a aeronave. Um desafio crítico de **otimização**. |
| **Finger / Ponte** | Estrutura móvel que conecta o portão diretamente à porta do avião. |
| **Pushback** | Procedimento de rebocar a aeronave da posição de parada até a *taxiway*. |

---

## Movimentação e Logística

| Termo | Descrição |
| --- | --- |
| **BHS (Baggage Handling)** | Sistema de esteiras e sensores para transporte de bagagens. Componente crítico de integração. |
| **Conexão (Connection)** | Quando o passageiro **troca de aeronave** no aeroporto para seguir viagem. |
| **Escala** | Quando a aeronave para no aeroporto, mas o passageiro **permanece no mesmo avião**. |

---

## Controle e Segurança

| Termo | Descrição |
| --- | --- |
| **Manifesto de Passageiros** | Registro oficial para controle de fronteiras e cálculo de **peso e balanceamento**. |
| **Manifesto de Carga** | Documento legal que lista todos os itens a bordo. Essencial para auditoria. |
| **ETD / ETA** | Horários estimados de saída e chegada (*Departure / Arrival*). Alimentam os painéis em tempo real. |
| **Ground Handling** | Serviços de solo (limpeza, buffet, degelo) realizados enquanto a aeronave está no pátio. |
