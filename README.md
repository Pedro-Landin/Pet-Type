# Pet-Type
Neste projeto você gerenciar pode (Cadastrar, Editar, Listar e Excluir) o seu Pet, os Medicamentos que ele usa, e também os Pagamentos dos valores dos Medicamentos.

# Context API
Através do Context nos conseguimos passar dados por uma árvore de componentes, sem a necessidade de passar esses dados através das props por cada nível desejado.
Como ponto focal de acesso a informação nos direcionamos para arquivo desejado e assim conseguimos ter acesso as informações que precisamos.<br/> Na pasta " ./contexts " temos os arquivos para cada parte do aplicação.<br/>
* **AUTH.JS** : É passado para parte de autenticação Login/Logout do Usuario. 
* **MEDICINE.JS** : É passado as rotas de List/Create/Delete do Medicamento do seu pet. 
* **PAYMENT.JS** : É passado as rotas de List/Create/Delete do Pagamento de medicamentos do seu pet. 
* **PET.JS** : É passado as rotas de List/Create/Delete do seu Pet.
* **INDEX.JS** : Aqui é onde é exportado globalmente todos os aquivos acima.

# Hooks 
Com o React Hooks nos podemos utilizar componentes funcionais para guardar estado e gerenciar o ciclo de vida do componente. Dito isso vamos usa-lo para vincular com os Contexts que temos, e passar para o resto da aplicação que necessita das informaçãos de cada conteúdo especifico. <br/>
* **USEAUTH.JS** : Aqui importamos o AUTH.JS para obtermos os dados passado por ele. 
* **USEMEDICINE.JS** : Aqui importamos o MEDCINE.JS para obtermos os dados passado por ele. 
* **USEPAYMENT.JS** : Aqui importamos o PAYMENT.JS para obtermos os dados passado por ele. 
* **USEPET.JS** : Aqui importamos o PET.JS para obtermos os dados passado por ele.
* **USEBACKHADNLER.JS** : Aqui importamos o BACKDANDLER do react-native, trata-se de uma api que permite que quando saímos do api ele o mantém ativo.
* **USEINDEX.JS** : Aqui é onde é exportado globalmente todos os aquivos acima.
