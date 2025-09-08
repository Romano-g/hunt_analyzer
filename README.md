# 🧙‍♂️ Hunt Analyzer

<p align="center">
  <img alt="Static Badge" src="https://img.shields.io/badge/Tecnologias-Excel%20VBA-brightgreen">
  <img alt="Static Badge" src="https://img.shields.io/badge/Status-Em%20desenvolvimento-orange">
  <img alt="Static Badge" src="https://img.shields.io/badge/Categoria-An%C3%A1lise%20de%20dados-blue">
</p>
<br>

## 💡 Ideia Inicial


Já se pegou farmando no Tibia estando free account e sentiu que somente o drop tracker não é o suficiente, ou que o lucro por hora da hunt está fora da realidade, ou até mesmo quis saber qual das hunts que você farma tem dado o melhor loot por hora?

Esse foi um dos problemas com que me deparei ao farmar minha primeira premium, então fiz esse projetinho pra ajudar quem estiver passando por isso na comunidade. Nessa tabela temos informações como:

- Em que nível você estava quando fez a hunt
- O dia em que farmou lá
- Se estava com prey ativa ou não
- Uma média de lucro por hora, com e sem prey, separado por hunt
- A média de lucro que você teve em cada hunt que adicionou ao histórico, considerando todas as vezes que farmou nelas
- Um destaque para a hunt que mais te deu profit em média, considerando todas vezes que farmou
- Uma aba para calcular quanto tempo vai demorar pra você upar sua skill (no caso, para treinos free, usando small stones ou mad sheeps, por exemplo)
<br>

## 📝 Como utilizar a tabela


1. Primeiro é necessário habilitar as macros para que o excel funcione devidamente

2. O segundo passo para utilizar a tabela é preencher seu nível e skill no momento da hunt, considerando os itens equipados (esse passo é completamente opcional, mas pode servir para um filtro no futuro desse software)

3. Em terceiro lugar, adicione a hunt que deseja fazer, clicando em `Adicionar Nova Hunt`, que irá abrir o seguinte formulário:
<br>

<p align="center">
  <img width="453" height="283" alt="image" src="https://github.com/user-attachments/assets/d67db4ae-1e3c-42be-bd9e-ada7f26113c4" />
</p>
<br>

Onde deverão ser adicionadas as seguintes informações:

 - Nome da hunt, sem caracteres especiais ou pontuações
 - Loots profitáveis da hunt, onde a cada loot novo adicionado deve-se clicar no botão `Adicionar`

Após clicar em `OK`, a hunt será adicionada e poderá ser selecionada no dropdown do campo `Hunt`, na aba `Main`

4. Seguindo para o quarto passo, preencha as informações dos campos `Hunt`, `Prey` - e, no caso de resposta positiva para o campo anterior, selecione também no dropdown de `% Prey` de quanto é o bônus de loot aplicado -, `Cálculo de Suprimentos` e `Anéis e Colares`

5. Iniciando a sua hunt chegamos ao quinto passo: Clique sobre a célula `Início`, ela irá registrar o horário em que você começou seu farm, seguindo o horário do seu computador

6. Já no sexto passo, ao finalizar sua hunt clique na célula `Final`, assim ela irá marcar a hora em que terminou seu farm, possibilitando que o excel calcule por quanto tempo você ficou naquele spot

7. Em último mas não menos importante, adicione na tabela `Cálculo de Loot` os itens e quantidades de cada um que obteve, bem como o valor pelo qual os vendeu no market ou NPC

Com todas as informações preenchidas, clique em "Inserir Hunt Atual", e todos os dados serão alocados em seu devido lugar na aba `Historico`.
<br>
<br>

### 📈 Informações exibidas no histórico

 - Data
 - Level
 - Skill
 - Suprimentos gastos
 - Nome da hunt
 - Tempo que farmou
 - Porcentagem da prey
 - Profit bruto
 - Profit líquido
 - Média de profit/h
 - Média de profit/h desconsiderando a prey
 - Uma tabelinha mostrando a média de profit que foi obtida em cada hunt, considerando todas as vezes que farmou em cada uma
<br>

## 🚀 Próximos Passos


Caso o projeto continue ganhando força na comunidade, os próximos objetivos serão:

 - Puxar da web os loots profitáveis da hunt
 - Melhorar os designs da interface
 - Tirar o projeto do excel para possibilitar o uso de hotkeys
 - Tentar fazer um track automático dos itens dropados (Caso não infrinja as regras tibianas)
<br>

## 🤝 Contribua com o projeto


O projeto ainda está no início. Toda sugestão, crítica construtiva ou pull request é bem-vinda! Valeu a todos que já deram feedbacks ou clonaram a planilha 🙌
