# Sistemas distribuídos:

## Aula 01 - Conceitos de SIstemas Distribuídos
### Conceito inicial:
Sistemas distribuídos: estuda a camada de aplicação e estão presente em tudo que funciona em mais de um computador. Exemplo:
- Github;
- aplicativos bancários; etc.

### Conceito teórico: 
É a combinação de Dispositivos, Sistemas e Comunicação.
Caracteríticas:
- mais de 1 sistema computacional independente;
- se comunicam entre si;
- Apresentam-se ao usuário com um sistema unico e coerente --> Transparência: uma falha em outra localidade afeta o serviço na minha localidade;

### Histórico:
Mainframe: um único computador que não se comunicava com nenhum outro.

### Características segundo Tanebaum:
- Mais econômico: em relação à sistemas de mainframe tradicionais
- Maior confibialidade: tendo em vista que não um ponto único de falha;
- Maior flexibilidade;
- Ganho incremental: poder computacional pode ser adicionado em pequenos incrementos;
- Compartilhamento de recusos/concorrência;
- Maior complexidade de linguagem de programação, sistemas operacionais, dispositivos, etc;
- Tolerência a falhas;
- Transparência;
- Escalabilidade (crescimento gradativo);
- Deve-se levar em consideração a questão de segurança;
- Extensibilidade;
- Falhas de comunicação podem fazer o sistema falhar;


### Computador para a disciplina: 
Dispositivo que apresenta: procesamento, memória e armazenamento.

### Evolução:
- Evolução dos meios de comunicação;
- Evolução dos dispositivos de entrada e saída;
- Evolução das aplicações;
- Evolução da web:
  
      - Web 1.0: movimento (web estática) - textos, gráficos, imagens;
  
      - web 2.0: compartilhamento (web dinâmica) - blogs, vídeo, wikis, podcasts;
  
      - Web 3.0: inteligência - tempo real, web criativa, mutiverso, 3D, Avatar, mundo virtual;

### Palavra chave de computação em nuvem: serviço
- SaaS (Software as a service):
- PaaS (Plataform as a service):

### Atenção:
- Por algo estar na internet, não significa que o serviço é computação em nuvem.
- Um sistema web é por natureza distribuído, pois a web é um dos mais populares sistemas distribuídos.

## Atividade:
Escolher um sistema distribuído utilizado no dia a dia e descrever porque eu acho que essa aplicação é um sistema distribído em 10 a 15 linhas.


## Aula 02 - Conceitos de SIstemas Distribuídos
- CDN: Rede de Distribuíção de Conteúdo (Content Delivery Network) -  Basicamente, uma CDN reproduz o conteúdo que está armazenado no servidor central. A versão reproduzida do conteúdo vai, então, ser salva em locais de várias regiões do planeta, chamados de Pontos de Presença (PoP, do inglês). Esses Pontos são os locais em que mais de duas redes fazem a conexão consigo mesmas.   
- PTT: interligação de provedor de serviços com provedor de conteúdo;
- IX
- ler sobre a documentação do torrent e serviço de e-mail para saber como funciona

### Tipos de Sistemas distribuídos:
- Sistemas de Computação distribuídos
      - cluster: poder de processamento. Várias máquinas (homogênea: como mesmo sistemas operacional) unidas para conseguir processamento paralelo. Neste caso, não faz sentido utilizar neles softwares de processamento sequencial.
      - grade: heterogênea 

- Sistemas de Informação distribuídos
     - Sistemas de processamento de transações
     - integração de aplicações empresariais

- Sistemas distribuídos pervasisvos 



## Aula de metas de projeto em sistemas distribuídos
### Metas de projeto:
- acesso a recursos: tem o objetivo de facilitar o acesso e compartilhamento de recursos remotos de maneira controlada e eficiente;
- Transparencia da distribuição: ocutação de um recurso ou falha - pode ser de acesso, localização, migração, relocação, replicação, concorrência, falha.
- Abertura - disponibilização do sistema para outras pessoas ou sistemas;
- Escalabilidade: em termos: de capacidade, geográficos e administrativos
- Ciladas

### Problemas de escalabilidade administrativa:
- dificil de estabelecer políticas de uso e pagamento de: recursos, gerenciamento e segurança;


## Sincronização:
- utilizar relógios para medir a duração de "eventos";
- Tempo: série initerrupta da sequência de instantes;
- A medição do tempo é uma aproximação, a medição de um tempo 100% certo não existe;
- O ajuste de relógio precisa ocorrer porque cada dispositivo tem uma contagem de tempo diferente de outro;
- Nosso dia: tem 23 horas, 56 minutos e 4 segundos;
- UTC: Coordenador de tempo universal;
- Centro: Londres (Big Ben). Oriente: positivo, Ocidente: negativo.
- Se não haver a sincronização dos relógios e controle de tempo, haverá um problema de consistência;
#### Tipos de Sincronização:
- ajuste a partir de um contexto de referência (média dos horários);
- algoritmo de lamport;
