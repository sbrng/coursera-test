# Descrição de algumas funções importantes

### 1. Manipulação do banco de dados

- **createUser(userID)** -> Adiciona um novo usuário ao banco de dados;
- **getUser(userID)** -> Retorna os dados de um usuário cadastrado no banco de dados a partir do seu ID;
- **updateFields(userID, setData)** -> Atualiza os dados de um usuário cadastrado no banco de dados;
- **saveMessage(message, sender, userId)** -> Salva uma mensagem e seu remetente nos registros de um usuário;
- **setChannelToUser(channel, userID)** -> Seleciona como canal de um usuário o canal que está sendo usado pelo flex;
- **getChannelForUser(userID)** -> Retorna o canal do flex que está sendo usado por um determinado usuário;
- **getUserForChannel(channelID)** -> Retorna os IDs dos usuários que estão usando um detreminado canal do flex;
- **listNumbers()** -> lista os telefones de todos os usuários cadastrados no banco(?)
- **imediateMessage(scheduleData)** -> envia uma mensagem imediatamente;
- **scheduleMessages(scheduleData)** -> Agenda o envio de uma mensagem ativa;
- **unscheduleMessages(id)** -> Cancela um agendamento de uma mensagem a partir do ID do agendamento;
- **retrieveSchedules(status)** -> Retorna todos os agendamentos que estão em um determinado staus;
- **saveScheduleExecution(id, userStatus)** -> (id do agendamento, status de envio da mensagem para um usuário)
Salva no banco o status de envio de um agendamento (se realmente foi enviado ou se houve falhas);
- **** ->
- **** ->
- **** ->
- **** ->
- **** ->
- **** ->
- **** ->
- **** ->
