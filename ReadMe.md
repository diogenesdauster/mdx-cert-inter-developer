

# Guia para Intermediate Developer Certification


| ![image-20211114101021226](images\image-20211114101021226.png) |
| :----------------------------------------------------------: |

## Instruções 

##### Após cadastro da certificação

Você receberá dois e-mail um contendo a extension do chrome. Que precisa ser instalada e a sala do Zoom e outro e-mail contendo o check up da máquina e a iniciação do teste.

| ![image-20211114102426084](images\image-20211114102426084.png) | ![image-20211114103142093](images\image-20211114103142093.png) |
| :----------------------------------------------------------: | :----------------------------------------------------------: |

** **Atenção** **


>O e-mail com a reunião está no horário correto do Brasil, pois seu gerenciador de e-mail converte automaticamente para você. 


##### No dia da prova

Acesse o Zoom no horário marcado e abra a câmera e não use tela estendida  (outro monitor). Pois seu o instrutor precisa verificar se você está olhando reto para tela e não para cima ou para lado. Espere as instruções que serão apresentadas via slide e o instrutor ira pedir para acessar o e-mail com botão **Start test** e sair da sala do Zoom. No pagina do teste preencha os dados utilizado para fazer a inscrição e tire duas fotos do seu rosto, inclusive na do ID card.

** **Atenção** **


>De maneira nenhum faça um refresh/f5 ou atualize a pagina da prova. Isso vai fazer você sair da sua prova e tera que entrar em contato com a instrutora via sala do Zoom.
>
>Caso a internet caia não pire apenas espere até aparecer o botão retry, sua prova será pausada e não perdera nem tempo nem as questões que já foram respondidas. 

** **Dicas** **

> É possível consulta os docs e os paths, porém só faça isso quando tiver terminado todo os tópicos para ganhar tempo.


## Tópicos vs Qtd Questões

Para passar na prova o score de questões certas é de **38** questões que corresponde a **75%** .

- Agile
  - 5 questões
- Security
  - 7 questões
- Microflows
  - 7 questões
- Pages
  - 7 questões
- Domain Model
  - 7 questões
- Modules
  - 5 questões
- Translation
  - 5 questões
- XPath
  - 7 questões

## Mendix Docs

- **Security**
  - [App Security - Studio Pro 9 Guide | Mendix Documentation]( https://docs.mendix.com/refguide/project-security)
  - [Security - Studio Pro 9 How-to&#39;s | Mendix Documentation](https://docs.mendix.com/howto/security/)
- **XPath**
  - [XPath - Studio Pro 9 Guide | Mendix Documentation](https://docs.mendix.com/refguide/xpath)

- **Domain Model**
  - [Domain Model - Studio Pro 9 Guide | Mendix Documentation](https://docs.mendix.com/refguide/domain-model)

- **Microflows**
  - [Microflows &; Nanoflows - Studio Pro 9 Guide | Mendix Documentation](https://docs.mendix.com/refguide/microflows-and-nanoflows)

- **Translate**
  - [Language Menu - Studio Pro 9 Guide | Mendix Documentation](https://docs.mendix.com/refguide/translatable-texts)

- **Pages**
  - [Pages - Studio Pro 9 Guide | Mendix Documentation](https://docs.mendix.com/refguide/pages)

## Mendix Paths

Não é necessário passar por todos os paths da mendix, então para esse trilha apenas faça os cursos listados abaixo: 



![image-20211119133504595](images\image-20211119133504595.png)

![image-20211119133517040](images\image-20211119133517040.png)



## Questões / Simulado

**Agile**

- Qual é quem conduz a Daily Meeting 
  - Scrum Master
- Para que ser o Definition of Done 
  - Para que todas as partes saibam o que é pronto ("não é a questão do steakholders") 
- Qual é o tamanho aconselhado do team Mendix
  -  3 pessoas
- O projeto precisa de P.O 
  - Precisa de P.O para fazer a ponte entre o cliente 
- É aconselhado ter times em diferente times zone 
  - Não é recomendado, times scrum trabalham melhor juntos
- Para que serve a reunião de refinamento
- 5 pilares do scrum

**Modules**

- Como instalo Apps da Loja  
  - Fazendo download pelo marketing place
- Pq devemos usar customizações em módulos separados e não direto do módulo da loja 
  - Para evitar que elas sejam sobrescrita quando atualizar o modulo )
- Em que pasta fica a library do Java 
  - libuser
- Como renomamos o nome do modulo
  - botão direto renema
- Existe um convensão para escrita de nome de modulos 

**Microflows**

- Qual das List operation precisa apenas de um parâmetro
  - Tail
- É possível fazer interações usando Loop Activity em uma lista de objetos
  - Sim
- Quais dos elementos podemos usar dentro de um Loop
  - Retrive Data, Agreggation, ,break , change object   (End e Start Event não pode descarta essa opções)
- Quais são as opções de uma agreggation List
  - Sum. Average, Count, Max, Min
- Quais são as opções de uma List Operation
  - Union, Intersect , contains , Equals (Existe mais, porém na opcão só vai ter 4)
- Para que serve Object Type Decision
  - Para verificar o tipo do Objeto
- Qual será o retorno do Tail de uma lista objetos de 7 item
  - a lista sem um primeiro registro
- Para extrair um sub flow de um microflow
  -  devemos selecionar apenas as activitys sem os eventos de start e and e sem os parâmetros de entrada.

**Translate**

- E possível fazer tradução para qualquer língua 
  - Sim, até para Klingo (Start Strek muito boa essa xD)
- Podemos Modificar o formato de data default 
  - Sim
- Onde troco a linguagem default
  - No menu Language
- Qual ferramenta do translate tool eu consigo alterar um text dentro do projeto
  - Batch Replace / Batch Translate (é uma dessa duas)

**Domain Model**

- Qual propriedade configuro para usar many to many association
  - type=Reference Set
- É possivel é escolher uma System.members de uma tabela filha (Generalization)
  - Não (Quando a tabela pai seta um atributo System.menbers na tabela filha vc não consegue marca nada)
- Como eu configuro herança 
  - set Generelization
- Onde configuro uma cross-module association
  - Entity properties windows / assosiation properties windows (uma das duas)
- Onde são armazenados os dados de uma tabela não persistente
  - na memoria
- Onde posso definir mensagem customizada na deleção em cascata
  - na Properties assosiation windows
- Com substituo many to many association
  - criando duas one to many association
- Quais tipo de association uma tabela não persistente possui 

**Security**

- Demo user pode ser usada em license nodes 
  - Não
- É preciso setar segurança (rules) para todo microflow  
  - Não (por causa do subflow) 
- Anonymous roles name tem alguma convenção
  - None
- Para que serve Anonymous User
  - Para permitir que usuário acesse feature do app sem logar
- Quando eu habilitar Anonymous User o que devo fazer
  - Setar a Anonymous role
- Anonymous user Roles tem que ter outra Role associada a ela 
  - Não
- Anonymous user cria uma session para acessar o mendix project app
  - Sim
- Diferença entre user roles e module rules
- Todos os módulos da loja tem roles configuradas

**Pages**

- Qual a tecnologia css utilizada no Layout Grid
  - Flexing Box 
- Qual melhor pratica recomendado pela Mendix para construir tela de login customizada
  - Widget Autentication 
- Para que ser Scroll Widget
  - Para deixar parte dentro do Scroll  widget como : Div / PlaceHolder  com Scroll
- É possivel ter mais de um placeholder em uma page
  - Sim
- Qual a função do snippet widget
  - reutilização da mesma estrutura 
- É possível criar properties Design customizadas
  - Sim
- É possível criar properties Desgin customizadas de Widget da loja

**XPath**

- Quais desse Operators são validos
  - =, !=, >= , or and
- É possível criar suas proprias functions
  - Não
- Qual retorno desse XPath //Sales.Customer[contains(Name, 'an')]
  - Todas os 3 nomes com"an" dois nome estão em minúsculos um e maiúsculo ("Andy") 
- Quais da opcões não é um Expression valida
  - //Sales.Customer[length(FirstName) >= 5]
  - //Sales.Customer[contains(Name, 'an')]
  - //Sales.Customer[not(IsValido)]
  - //Sales.Customer[isValido = false] (Marquei esse)
- Qual desse XPath é valido para trazer o usuário corrente
  - [%CurrentUser%]	
  - [%UserRole_Administrator%]
  - [%UserCurrent%]	
- É possivel criar suas proprias XPath constraints
  - False
- Não é um Operator valido 
  - {}  

------------------


**Boa Sorte no seu teste, caso queira contruir basta fazer um pull request atualizando as questões**

# GO Make it 👊😎