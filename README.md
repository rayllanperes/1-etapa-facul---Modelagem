# 1ª Etapa – Modelo Entidade-Relacionamento (MER)
Dadas as regras de negócio abaixo listadas, referentes ao estudo de caso de uma
Clínica Médica, elabore o Modelo Entidade-Relacionamento (MER), isto é, o modelo
conceitual.
O Modelo Entidade-Relacionamento (MER) deve contemplar os seguintes itens:
• Entidades;
• Atributos;
• Relacionamentos;
• Cardinalidades;
• Chaves primárias;
• Chaves estrangeiras.

Uma Clínica Médica necessita controlar os dados das consultas realizadas. Para isso, contratou um profissional de Banco de Dados, a fim de modelar o Banco de Dados que armazenará os dados das consultas.
As regras de negócio são:

• Médico – Deverão ser armazenados os seguintes dados: CRM, especialidade, nome, telefone, e-mail e endereço, sendo o endereço composto por rua, número, complemento, bairro, CEP, cidade e estado;

• Consulta – Deverão ser armazenados os seguintes dados: identificação da consulta, data e horário;

• Paciente – Deverão ser armazenados os seguintes dados: CPF, nome, telefone, email e endereço, sendo o endereço composto por rua, número, complemento, bairro, CEP, cidade e estado;

• Convênio – Deverão ser armazenados os seguintes dados: identificação do convênio, empresa, tipo, vencimento e percentual de coparticipação;

• Um médico pode realizar zero ou várias consultas, assim como zero ou várias consultas podem ser realizadas por um médico;

• Um médico pode atender zero ou vários convênios, assim como zero ou vários convênios podem ser atendidos por um médico;

![image](https://github.com/user-attachments/assets/a64c7cde-82fb-42a1-baaa-d884b138e034)
