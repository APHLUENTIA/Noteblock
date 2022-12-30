# Bloco de Notas da Tese   
*Autor: Pedro Marques, 92926 (pedroagoncalvesmarques@ua.pt)*  

Este documento é um bloco de notas com as ideias semanais e de reuniões sobre a tese em Engenharia Informática orientada pelo professor Samual Silva, designada como *APHLUENTIA++
SUPPORTING TECHNOLOGY-MEDIATED COMMUNICATION FOR APHASIA*   

---
## Primeira Reunião    
*Data: 27/09/2022*     
*Participantes: Pedro Marques, Prof Dr.Samuel Silva*  
*Tópicos do Dia: Interação Multimodal, Estado de Arte no IEETA, Afasia [^1]*  

Este trabalho relaciona-se com pesquisa em desenvolvimento no IEETA, no âmbito do programa APH-ALARM. Projeto internacional liderado por uma empresa húngara.    

A dissertação tem como foco a afasia. Engloba-se num projeto europeu na área de Ambient Assisted Living [^2], com o objetivo de desenvolver métodos e tecnologias de modo a ajudar as pessoas a viverem de forma independente e com melhor qualidade de vida, nomeadamente este projeto relaciona-se com as pessoas com afasia. Pessoas que tenham sofrido um AVC são uma grande percentagem da população com afasia. 
Para os problemas de comunicação, existem ferramentas designadas como Ferramentas de Comunicação Aumentativa e Alternativa para facilitar a comunicação com estes indivíduos. Infelizmente, estas soluções são muito genéricas, não dando apoio a várias atividades expecíficas do dia-a-dia, são igualmente fastidiosas para os pacientes. Assim sendo, foi desenvolvida uma aplicação móvel para ajudar os pacientes. Por outro lado, existe também um método desenvolvido para ajudar pessoas que estão deitadas e que têm dificuldade de movimentação. Esta solução inclui uma banda com giroscópio que permite que a pessoa faça movimentos com as mãos para poder responder a perguntas de um assistente e prestar auxílio à mesma, através de várias perguntas simples ação-objeto, que permitem apenas respostas booleanas. A mensagem composta é enviada para alguém responsável (cuidador). A necessidade deste assistente de quarto é ainda comprovada pois várias pessoas, embora podendo ter mobilidade total, têm receio de se levantar à noite e de se aleijarem.  

**Problema 1**: Atualmente a aplicação do quarto e a aplicação móvel existem de forma independente. A ideia é que estas duas vertentes sejam parte da mesma solução e que até possam ser usadas em conjunto.    
**Problema 2**: Cada pessoa com afasia é um caso particular, com as suas dificuldades e rotinas. Seria interessante poder existir uma personalização individual destas aplicações, em deteriorimento da opção genérica. Aqui, é relevante a intervenção do terapista da fala, o qual tem interação e compreende as necessidades de cada paciente.     

**Ideia principal**: Junção de ambas as aplicações e desenvolvimento de uma aplicação que permite personalização.  
**Importante**: Garantir feedback por parte do assistente de modo a que um paciente que tenha pedido ajuda não aguarde em silêncio ou que pelo menos tenha informação sobre o estado do seu pedido de socorro. Por exemplo, se médicos, bombeiro, etc já foram mobilizados    

**Nota**:  
- Reunião com Cátia Azevedo que participou no projeto, de modo a contextualizar o que já foi desenvolvido e até partilhar lista de ideias de desenvolvimento futuro.  
- Fábio Nunes desenvolveu o assistente de quarto/gestos.  
- O objetivo não é alterar o que já existe de interação mas adicionar.  
- Muita informação partilhada de forma sigilosa.    
- Aguardar envio de literatura por parte do professor a 03/10/2022.     


## Tese da Cária Azevedo Sobre Afasia Fluente  
*Data: 07/10/2022*     
*Autora: Cátia Azevedo*  
*Orientador: Prof Dr.Samuel Silva*  
*Coorientador: Dr.Ana Rita Valente*  
*Titulo: COMMUNICATION SUPPORT FORFLUENT APHASIA*  
*Tópicos do Dia: Projeto APH-ALARM, Afasia [^1]*  

Em relação ao que foi desenvolvido, a aplicação móvel é justificada de modo a combater o estigma associado de andar com um assistente pessoal para todo o lado juntamente com o facto de um smartphone ser super portável.    
Neste projeto foi so abordada a afasia fluente, que engloba 4 tipos diferentes: Conduction, Anomia, Wenicke's and Transcortical Sensory    
O Desenvolvimento do projeto contou com terapeutas da fala e outros profissionais da área.    
Foi realizada uma abordagem User Centered Design de modo a que a aplicação realmente consiga ser desenhada para as pessoas que dela precisam   
O levantamento de requisitos ocorreu após o desenvolvimento de personas e scenarios, tendo sido organizador por prioridade. Prioridade 1 é relativo às funcionalidades essenciais da aplicação, 2 as funcionalidades complementares e 3 UI/estética/beleza   
**Relembrar** A Aplicação não é so para as pessoas com afasia, mas também para outros que têm contacto direto com os mesmos  


**Notas**: 
- Literatura recebida por parte do professor não pode ser partilhada ainda, nomeadamente a tese em questão e um documento explicativo do projeto APH-Alarm   

**Notas Mencionadas à Cátia**: 
- Validar todas as assunções   
- Fazer itemização em alguns momentos    
- Falar da motivação pessoal para além da do projeto    
- Apresentar cada secção antes de apresentar o seu conteúdo (p.e. Explicar o que são cenários antes de os apresentar)    
- Apresentar a avaliação de resultados  apresentar   
- Cuidado com palavras com capitalização desnecessária e acrónimos inconsistentes.   
- Mencionar credenciais e participantes (formação profissional) das pessoas que afetam decisões no desenvolvimento  

**ALgumas perguntas que foram feitas**:  
- Por que é que é necessária uma aplicação móvel para a afasia e especificamente a afasia fluente?
- Porquê estes tipos de afasia?  
- Escalabilidade e Futuro das Tecnologias  
- Problemas de privacidade RGPD
---

## Segunda Reunião    
*Data: 12/10/2022*     
*Participantes: Pedro Marques, Prof Dr.Samuel Silva, Dra Ana Rita Valente*  
*Tópicos do Dia: Próximos Passos, Estado de Arte, Ideias, Aphasia Friendly*  

Esta reunião teve o objetivo de permitir a minha integração de forma mais extensiva no projeto.    

Atualmente, no âmbito do projeto, duas vertentes foram englobadas com o objetivo de ajudar pessoas com afasia fluente. Assim sendo, foi desenvolvida uma aplicação móvel para suporte das mesmas bem como um assistente para o quarto que, graças à deteção de movimentos por uma wristband, permite a comunicação entre (Patient With Aphasia) PWA e caregiver (pessoa que toma conta do paciente ou tem contacto direto com o mesmo).   
Atualmente, estas soluções existem de forma independente, a ideia geral é criar uma espécie de dashboard que permita a integração destes projetos bem como de futuros. Igualmente, pretende-se permitir costumização de ambos os projetos, de forma a que os mesmos se adaptem melhor aos PWA.

**Ideias de Personalização:**  
- Possibilidade de atribuição de exercícios por parte do SLT (terapueta da fala) para o PWA  
- A gravação da voz do paciente permite aumentar a motivação e confiança do mesmo, pois este verifica que realmente está a melhorar.  
- Personalização de output providenciados  
- Possibilidade de criar perfis de contexto (supermercado, consulta, etc)  ou utilizar perfis base  
- Outras ideias como frases personalizáveis    
- Monitorização de utilização da aplicação


Para além do que foi mencionado anteriormente, mencionou-se também a oportunidade de poder usar a voz. Como foi mencionado na reunião, a voz é uma ótima forma dos terapuetas verificarem o estado dos pacientes. Assim sendo, seria interessante o desenvolvimento de uma solução que englobasse a mesma. Aqui temos um problema relacionado com a proteção de dados (RGPD).

Tudo o que foi mencionado anteriormente tem como objetivo também a monitorização do paciente, pois é importante para o terapueta saber que os mesmos estão a praticar e a fazê-lo corretamente.   
Esta personalização é também importante para ajudar pacientes que não tenham o mesmo conforto em casa comparativamente com uma consulta. Este conforto é importante para obter dados mais naturais e, portanto, mais importantes. 

**Nota:**  
- Reunião a ser marcada com o fábio para conhecer melhor a solução do quarto  
- Tese da Cátia tem uma secção ótima de compreensão e explicação da afasia  

**Próximos Passos**:  
- Ler artigos sobre afasia e aplicações 'Aphasia Friendly', (dica: usar one note para associar artigos e certas secções de especial interesse)   
- Analisar gestores de referências 
- Pintar um quadro do que existe: cenários, personas, requisitos etc  


## Terceira Reunião    
*Data: 15/11/2022*     
*Participantes: Pedro Marques, Prof Dr.Samuel Silva, Fábio Nunes, Ana Rocha*  
*Tópicos do Dia: Levantamento de requisitos, What a Nice Gesture, Planeamento da Tese, Objetivo do Projeto*  

O ojetivo desta reunião foi a contextualização com o projeto de assistente de quarto que foi terminada, bem como a discussão de ideias para o projeto em desenvolvimento.    

Algumas das ideias apresentadas distanciam-se um bocado da ideia inicial do projeto, no sentido em que se relacionam mais com eTerapia do que com assistência de comunicação.  

**Ideias para a aplicação:**  
- Criação de um meio de comunicação entre o SLT [^3]* e o caregiver  
- Possibilidade de atribuição de homework para os PWAs através da plataforma   
- Utilização de QR Code para adicionar aplicações à plataforma  
- Avaliar a progressão da condição através de interações com os sistemas  
- Avaliação do estado emocional através da voz  

Um dos problemas com ambas as aplicações é que não existe qualquer forma de gestão de utilizadores. Para além disso, enquanto que os dados da app móvel estão hardcoded numa base de dados, a do assistente de quarto tem os dados hardcoded no meio do código. É necessário determinar um método que permita uma comunicação semelhante entre os dois métodos.  


**Notas:**  
- Reunião terça daqui a 2 semanas  
- Posso reutilizar personas da Cátia, tenho +2 personas: SLT e caregiver  
- Ler artigo Harnessing the Role of Speech Interaction inSmart Environments towards Improved Adaptability and Health Monitoring    

**Próximos Passos**:   
- Escrever personas e cenários para determinar requisitos    


## Semana    
*Data: 18/11/2022 - 25/11/2022*     
- Elaboração das personas  
- Elaboração de cenários   
- Levantamento de requisitos    
- Harnessing the Role of Speech Interaction inSmart Environments towards Improved Adaptability and Health Monitoring  

## Semana    
*Data: 27/11/2022 - 02/12/2022*     
- Leituras sobre Smart Homes e Health Monitoring Solutions Para Pacientes Com Afasia (Remote vs Presential)  
- Restruturação da organização da tese  
- Restruturação das secções de contexto, motivacao e objetivos  


## Semana    
*Data: 02/12/2022 - 09/12/2022*     
- Organização de notas e leitura de outros artigos relativos à afasia/escrita de background da tese  
- State of The Art   
- Projetos de Outras Cadeiras   

## Semana    
*Data: 09/12/2022 - 16/12/2022*     
- Deteção de biomarcadores especificamente aplicados à afasia  
- State of The Art  
- Projetos de Outras Cadeiras  
 
## Semana    
*Data: 23/12/2022 - 30/12/2022*     
- Leitura e escrita da tese secções Communication Disorders, Aphasia and Boston Classification, Emotional Health in Patients With Aphasia
- Criação de um primeiro low fidelity prototype    

## Bibliografia  
-  [Ambient Assisted Living (AAL) Programme](http://www.aal-europe.eu)


- [^1]: Afasia
: Perda parcial ou total da capacidade de expressar ou compreender a linguagem falada ou escrita. É o resultado de danos às áreas do cérebro que controlam a linguagem. As pessoas podem ter dificuldade em ler, escrever, falar, compreender ou repetir a linguagem.  [Afasia Por Juebin Huang , MD, PhD, Department of Neurology, University of Mississippi Medical Center](https://www.msdmanuals.com/pt/casa/distúrbios-cerebrais,-da-medula-espinal-e-dos-nervos/disfunção-cerebral/afasia)

- [^2]: Comunicação Aumentativa e Alternativa
: A comunicação alternativa contempla qualquer forma de comunicação que não seja a fala, enquanto que a comunicação aumentativa significa promover e apoiar a fala. [Comunicação Aumentativa e Alternativa](http://www.itad.pt/comunicacao-aumentativa-e-alternativa/)

- [^3]: Speech and Language Therapist (SLT)
: Terapeuta que ajuda na reabilitação do paciente com afasia