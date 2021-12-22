<div align="center">
  <h1>Fundamentos técnicos de Java</h1>
</div>

## Programação Orientada a Objetos - POO

### 4 Pilares

#### Abstração
É utilizada para a definição de entidades do mundo real. Sendo onde são criadas as classes. Essas entidades são consideradas tudo que é real, tendo como consideração as suas características e ações. Como exemplo: a entidade sendo o Carro, a característica sendo seu tipo, cor e tamanho e ações sendo acelerar, ligar

#### Encapsulamento 
É o processo utilizado para proteger os campos e operações de uma classe (atributos e métodos), permitindo apenas aos membros públicos de serem acessados. Como por exemplo os métodos GET/SET sendo acessados por usuários da mesma classe.

#### Herança
A herança é um princípio que permite criar uma nova classe a partir de uma já existente. ... A principal vantagem da herança é a capacidade para definir novos atributos e métodos para a subclasse, que se somam aos atributos e métodos herdados.

#### Polimorfismo
Polimorfismo é o princípio pelo qual duas ou mais classes derivadas de uma mesma superclasse podem invocar métodos que têm a mesma identificação, assinatura, mas comportamentos distintos, especializados para cada classe derivada, usando para tanto uma referência a um objeto do tipo da superclasse. 
Como por exemplo o método calcularVelocidade().  Ele pode ser usado pela classe carro() e pela classe moto(), são métodos com a mesma identificação mas com comportamentos diferentes.

### Coesão e Acoplamento
Coesão se refere ao princípio da responsabilidade única de uma classe. </br>
E acoplamento se refere ao quanto um classe depende de outra para funcionar 

Um código com alta coesão e baixo acoplamento, é um código com mais facilidade de manutenção e mudança no negócio.

## Arquitetura de Microsserviços
Esse tipo de arquitetura é uma abordagem para escrever programas de software. Onde a aplicação é dividida em diversos componentes mínimos e independentes, sendo cada serviço.

#### Um dos princípios dos Microsserviços são:

- Que cada serviço tem a sua responsabilidade, ou seja, um serviço de login não pode cadastrar usuário
- Um serviço deve ser independente, não deve depender de outros serviços que interajam com ele
- Tratativas de falhas inesperadas sem quebras a aplicação 
- [Entre outros](https://medium.com/introducao-a-arquitetura-de-microservicos/introdu%C3%A7%C3%A3o-a-microsservi%C3%A7os-25378269e6f9)

#### Seus benefícios são:

- Atualização independente sem afetar outros serviços
- Facilidade de manutenção. Sendo mais fácil de entender um erro pelo fato de um serviço ser restrito apenas a um recurso
- Liberdade de escolha de tecnologias, ferramentas ou estruturas dentro de um serviço

## Design Patterns
Design Patterns ou padrões de projetos são soluções generalistas para problemas recorrentes durante o desenvolvimento de um software. Ou seja, um conjunto de soluções/arquiteturas de projetos específicos para cada situação.

### MVC - Model-View-Controller
O princípio básico do MVC é a divisão da aplicação em três camadas: a camada de interação do usuário [View], a camada de manipulação dos dados [Model] e a camada de controle [Controller].

