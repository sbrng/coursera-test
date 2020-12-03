# Descrição de algumas funções importantes

### 1. Manipulação do banco de dados

- **createUser(userID)** -> Adiciona um novo usuário ao banco de dados;
- **getUser(userID)** -> Retorna os dados de um usuário cadastrado no banco de dados a partir do seu ID;
- **updateFields(userID, setData)** -> Atualiza os dados de um usuário cadastrado no banco de dados;
- **saveMessage(message, sender, userId)** -> Salva uma mensagem e seu remetente nos registros de um usuário;
- **setChannelToUser(channel, userID)** -> Seleciona para o usuário o canal que está sendo usado pelo flex;
- **getChannelForUser(userID)** -> Retorna o canal do flex que está sendo usado por um determinado usuário;
- **getUserForChannel(channelID)** -> 
- listNumbers() -> lista os telefones de todos os usuários cadastrados no banco(?)
- imediateMessage(scheduleData) -> envia uma mensagem imediatamente(para onde? o bot?)
