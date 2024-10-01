# LegendArenaStarknetHHBangkok
On-Chain Game Project to Starknet Hacker House Bangkok

## Projeto Legend Arena On-Chain Game




### Objetivos:

- Alavancagem  de  **ZK-Rollups** da Starknet;
- Exploração as possibilidades únicas de escalabilidade;
- Privacidade e baixo custo;

### **Projeto: Legend Arena - Jogo de Estratégia On-Chain com Privacidade e Provas Zero-Knowledge**

#### **Descrição do Projeto**
"Legend Arena" seria um jogo de estratégia de batalha em que os jogadores competem enviando seus exércitos em batalhas, utilizando **provas zero-knowledge (ZK)** para garantir que as movimentações e estratégias sejam ocultas até que a batalha ocorra, adicionando uma camada de privacidade e incerteza nas jogadas. O jogo alavanca o potencial da Starknet para executar cálculos pesados on-chain com baixo custo, enquanto preserva a privacidade das escolhas estratégicas dos jogadores até o momento de revelação.

#### **Principais Funcionalidades:**
1. **Batalha de Exércitos com Provas ZK**:
   - Cada jogador envia um "exército" com uma combinação de unidades (por exemplo, arqueiros, cavaleiros, magos), mas a composição do exército é mantida em segredo usando **provas ZK**. Apenas após as duas equipes serem enviadas para a batalha, as composições são reveladas e o combate é simulado.
   
2. **Aposta de Tokens**:
   - Para participar da batalha, os jogadores podem apostar tokens que são segurados pelo contrato inteligente. O vencedor recebe a soma das apostas ou outro tipo de recompensa em tokens. Este aspecto incentiva a competição e coloca um elemento econômico no jogo.

3. **Governança Descentralizada**:
   - Jogadores podem votar em futuras atualizações de regras e balanceamento do jogo, utilizando a governança descentralizada. Isso demonstra as capacidades de governança on-chain que podem ser implementadas com contratos inteligentes Starknet.

4. **NFTs de Unidades de Batalha**:
   - Cada unidade do exército é representada como um NFT, e os jogadores podem colecionar, negociar ou melhorar essas unidades com base em suas vitórias e derrotas. A interoperabilidade dos NFTs na Starknet pode ser explorada aqui para criar um mercado secundário robusto.

#### **Por que esse projeto é inovador?**
- **Privacidade nas Estratégias**: A utilização de **provas zero-knowledge** para ocultar as estratégias dos jogadores é algo raro no espaço de jogos blockchain. Isso proporciona uma nova dinâmica de incerteza e suspense, onde a estratégia é oculta até o fim, mas ainda assim verificável.
  
- **ZK-Rollups e Escalabilidade**: A Starknet é projetada para lidar com grande volume de transações e cálculos de forma escalável e barata. A execução on-chain de batalhas, especialmente com as camadas de ZK, seria um exemplo excelente do poder de processamento da rede.

- **NFTs com Utilidade**: A emissão e comercialização de NFTs para representar as unidades de batalha não são apenas colecionáveis, mas têm utilidade direta no jogo, proporcionando um mercado secundário interessante.

- **Interoperabilidade e Composabilidade**: A Starknet permite interações complexas entre contratos inteligentes. Isso poderia ser usado para permitir que os jogadores utilizassem NFTs e tokens adquiridos em outros jogos ou protocolos Starknet dentro do "Starknet Arena", incentivando um ecossistema interconectado.

#### **Por que esse projeto venceria o evento?**
1. **Uso Avançado da Tecnologia Starknet**: O projeto alavanca as capacidades de **provas zero-knowledge**, **escalabilidade** via ZK-Rollups, **interoperabilidade de NFTs**, e **governança descentralizada** — todas tecnologias que a Starknet está buscando promover.
   
2. **Alcance Comercial e Gamer-Friendly**: Jogos de batalha estratégicos têm um apelo intrínseco ao público gamer e aos investidores de NFTs. A mecânica de batalha e recompensas em tokens cria uma plataforma com potencial comercial real.
   
3. **Escopo Viável em 3 Dias**: Focar em uma **versão mínima viável (MVP)** com batalhas básicas e NFTs de unidades permite que o projeto seja concluído em 3 dias, enquanto a infraestrutura para expansão futura está embutida.

4. **Competição e Economia On-Chain**: A inclusão de um sistema de apostas e economia on-chain com tokens proporciona não só diversão, mas também uma mecânica econômica que pode atrair o público interessado em GameFi (jogos com finanças descentralizadas).

5. **Demonstração do Futuro dos Jogos Blockchain**: Este projeto destacaria como jogos on-chain podem ser não apenas transparentes, mas também privados, utilizando o poder das provas ZK. Isso diferencia o projeto de outros jogos tradicionais on-chain, onde tudo é visível e previsível.

---

### **Roadmap de Desenvolvimento de 3 Dias**:

#### **Dia 1**:
- Especificar as regras do jogo e a lógica de batalha.
- Implementar a lógica básica do jogo em contratos inteligentes Starknet.
- Integrar a mecânica de apostas de tokens e gerenciamento do pool de recompensas.

#### **Dia 2**:
- Desenvolver e integrar o sistema de **provas ZK** para ocultar a composição dos exércitos dos jogadores.
- Criação e emissão dos **NFTs** para representar as unidades do exército.
- Construir uma interface simples para permitir que os jogadores formem seus exércitos e participem das batalhas.

#### **Dia 3**:
- Testar a lógica de batalha e a geração de provas ZK para assegurar que a privacidade e a execução funcionem corretamente.
- Implementar um sistema de governança básica para que os jogadores possam votar em pequenas mudanças no jogo.
- Finalizar a interface e preparar uma apresentação polida para o evento.

---

Com esse projeto, a inovação em privacidade, o uso de NFTs com utilidade real, e a integração das capacidades avançadas da Starknet formariam uma proposta competitiva e de alto impacto em uma Hacker House.


**Legend Arena** seria um jogo de estratégia onde dois jogadores se enfrentam, cada um comandando um exército. A principal ideia do jogo é que você precisa planejar sua estratégia em segredo, sem que o seu oponente saiba o que você está fazendo até o momento da batalha.

### **Como funciona o jogo?**

1. **Montando seu Exército**:
   - Cada jogador começa com um **número limitado de unidades** para formar seu exército. As unidades podem ser soldados, arqueiros, cavaleiros, entre outros, cada um com suas próprias habilidades e forças.
   - Você decide como quer organizar seu exército: por exemplo, pode escolher 5 arqueiros e 5 cavaleiros, ou 7 arqueiros e 3 cavaleiros. No entanto, seu oponente não sabe como você está montando seu exército, e você também não sabe como ele está montando o dele.

2. **Apostando Tokens**:
   - Antes da batalha, os jogadores podem fazer uma **aposta** usando tokens do jogo. O jogador que vencer a batalha ficará com a soma dos tokens apostados pelos dois jogadores.
   - Isso adiciona um elemento de risco e recompensa, tornando a vitória ainda mais emocionante.

3. **Enviando o Exército para a Batalha**:
   - Depois de montar seu exército, você "envia" suas unidades para a batalha. Neste momento, a composição do seu exército (quantos arqueiros, quantos cavaleiros) ainda está **escondida** do seu oponente, o que adiciona uma camada de mistério e estratégia ao jogo.

4. **A Batalha**:
   - Quando ambos os jogadores enviam seus exércitos, o jogo revela como cada jogador organizou suas tropas.
   - O combate então acontece automaticamente, seguindo regras simples. Por exemplo, cavaleiros podem ser mais fortes que arqueiros, mas os arqueiros podem atacar de longe e causar mais dano antes de serem atingidos pelos cavaleiros. Quem tiver a combinação mais forte de unidades vence a batalha.

5. **Recompensas**:
   - O jogador vencedor recebe os **tokens apostados** por ambos os jogadores como recompensa.
   - Além disso, ele pode ganhar **novas unidades** (representadas como NFTs) que podem ser usadas em batalhas futuras ou negociadas com outros jogadores.

### **Como ganhar o jogo?**
Você vence o jogo ao **derrotar o exército do seu oponente** em combate, o que depende de como você organiza suas tropas de maneira estratégica. Escolher a combinação certa de unidades é a chave para o sucesso.

Além disso, como você e seu oponente não sabem o que o outro está planejando até o último momento, existe um grande elemento de **estratégia e surpresa**. Vencer o jogo também te permite ganhar tokens e novas unidades que te ajudam a fortalecer seu exército para batalhas futuras.

### **Por que é divertido?**
- **Mistério e Estratégia**: Como você não sabe qual é a composição do exército do seu oponente até o momento da batalha, há um elemento de surpresa. Você precisa pensar em estratégias inteligentes para vencer.
- **Recompensas**: Além de vencer batalhas, você pode ganhar tokens que podem ser usados no jogo ou trocados por outros itens, além de **unidades exclusivas** que podem ser trocadas ou vendidas como NFTs.
- **Competição**: O sistema de apostas torna cada batalha emocionante, porque há algo em jogo além do simples "quem vence ou perde". 

Em resumo, **Legend Arena** é um jogo onde você monta estrategicamente um exército, enfrenta seu oponente sem saber o que ele planejou, e luta para ganhar recompensas e se tornar mais forte para as próximas batalhas.

Um **ZK-Rollup** é uma solução de escalabilidade para blockchains, especialmente usada em redes como a Ethereum, que combina duas tecnologias-chave: **rollups** e **provas de conhecimento zero (ZK, do inglês "zero-knowledge proofs")**. Vou explicar cada uma dessas partes de forma simples e depois como elas funcionam juntas.

### 1. **O que é um Rollup?**
Um **rollup** é uma forma de agrupar várias transações fora da blockchain principal e, em seguida, "enrolá-las" em uma única transação que é enviada de volta para a blockchain principal. A ideia é processar um grande número de transações fora da blockchain (off-chain) para reduzir o congestionamento e os custos.

- **Como funciona?**
  Imagine que, ao invés de registrar cada compra de ingresso em um evento em um grande livro público (a blockchain principal), você faz essas compras em um sistema separado. No final do dia, esse sistema envia um único resumo com todas as transações de uma vez para o livro público, dizendo: "Aqui está o resultado final de todas essas transações."

Esse "resumo" das transações é mais leve e rápido de ser processado pela blockchain principal.

### 2. **O que é uma Prova de Conhecimento Zero (ZK)?**
Uma **prova de conhecimento zero (ZK)** é um método criptográfico que permite provar que algo é verdadeiro **sem revelar os detalhes** do que está sendo provado.

- **Como funciona?**
  Um exemplo clássico é: Imagine que você quer provar para alguém que você sabe a senha de um cofre, mas sem dizer qual é a senha. Com provas ZK, você pode provar que sabe a senha, sem nunca revelar o que é. O verificador acredita que você tem o conhecimento, mas não sabe exatamente qual é a senha.

Essa ideia de "provar sem revelar" é o que torna as ZK-Proofs muito poderosas para privacidade e segurança.

### 3. **Como ZK-Rollups funcionam juntos?**
No contexto de **ZK-Rollups**, as transações são agrupadas (ou **"roladas"**) em uma única transação fora da blockchain, como no conceito de rollups, mas com um detalhe importante: para garantir que essas transações sejam válidas e seguras, é gerada uma **prova de conhecimento zero** (ZK-proof).

- **Validação via ZK-Proof**: Em vez de enviar todas as transações de volta para a blockchain principal (o que seria caro e demorado), o ZK-Rollup gera uma prova criptográfica que mostra que todas as transações agrupadas são válidas, sem precisar verificar cada transação individualmente.
  
- **Eficiente e Seguro**: Essa prova é então enviada à blockchain principal, que a valida de forma rápida e eficiente. Como o ZK-Rollup já fez todo o trabalho de garantir que as transações são válidas, a blockchain principal só precisa verificar a prova, economizando muito tempo e espaço.

### **Benefícios dos ZK-Rollups**:
1. **Escalabilidade**: Como as transações são agrupadas e só um resumo criptográfico é enviado à blockchain principal, muito mais transações podem ser processadas fora da blockchain, reduzindo congestionamento.
   
2. **Segurança**: Mesmo sendo processadas fora da blockchain, as transações ainda têm a mesma segurança, porque a blockchain principal valida a prova criptográfica que garante que todas as transações no rollup são válidas.

3. **Baixo custo**: As transações agrupadas em um ZK-Rollup são muito mais baratas, já que o custo é dividido entre todas as transações no grupo.

4. **Privacidade**: Como as ZK-proofs permitem provar algo sem revelar os detalhes, os ZK-Rollups também podem melhorar a privacidade, ocultando as transações exatas enquanto ainda garantem que elas são válidas.

### **Exemplo Simples**:
Imagine um banco de dados onde milhares de pessoas estão fazendo transações financeiras. Ao invés de registrar todas as transações no livro-razão (blockchain), o banco usa um ZK-Rollup. Ele agrupa todas as transações, faz uma prova de que todas elas foram executadas corretamente, e depois envia essa prova para o livro-razão, que verifica a prova e a aceita. Dessa forma, o livro-razão só precisa registrar um único resumo, mas com a segurança de que todas as transações no grupo são válidas.

### Resumo:
O **ZK-Rollup** é uma técnica que combina o agrupamento de transações fora da blockchain com provas criptográficas (ZK-proofs), garantindo que essas transações sejam válidas e seguras, sem sobrecarregar a blockchain principal. Isso melhora a escalabilidade, reduz custos e mantém a segurança e, em alguns casos, a privacidade.

