## Atividade de Sistemas Distribuídos: 02/12/2020
## Aluno: Alisson Freire

# Sistemas Operacionais Distribuídos

Para Tanenbaum a definição de sistema distribuído é um conjunto de computadores independentes que se apresenta como um único sistema. Onde os nós estão fisicamente separados e colaboram entre si.

## Vantagens:

- Transparência: os usuários ou programas não sabem que estão estão usando um sistema distribuído, basicamente onde esta localizado e quantas máquinas estão no sistema.
- Tolerância a falhas: as falhas de hardware e software, onde se houver uma falha em um nó não o comprometa a rede.
- Concorrência: tarefas acontecendo ao mesmo tempo.
- Alta disponibilidade:há um balanceamento de carga e como se houver falhas em alguns nós não atingiram outros sempre vai se dispor de nós para responder às solicitações dos usuários.
- compartilhamento de recursos: processamento, arquivos, impressoras, páginas  web, email e etc..

## Desvantagens:
-	Segurança: pois tem que assegurar que todos os nós estão seguros.
-	Alta complexidade na implementação dos sistemas: pois tem que se levar em consideração vários requisitos que em sistemas convencionais não são necessários.
-	A largura da banda e latência de rede: se a largura for baixa pode facilmente congestionar a rede e se a latência for alta ocorrerá a demora nas respostas das solicitações.

## Exemplos de Sistemas Operacionais Distribuídos:
Inferno OS, Amoeba, Plan9, ChorusOS, LOCUS, QNX, MOSIX, Sprite, Harmony OS e etc..

---------------------------------------


# Sistemas Operacionais Centralizados

Ao contrário dos sistemas distribuídos o centralizado uma única máquina controla tudo, arquitetura cliente-servidor.

## Vantagens:

- Segurança: pois basta se preocupar com um único nó/sistema.
- Facilidade na implementação.
- Baixo custo.

## Desvantagens:

- Tolerância baixa ou inexistente a falha: pois há um único ponto de controle que por sua vez.
- Um único ponto de da falha.

## Exemplos Sistemas Operacionais Centralizados:
Windows, Linux, MacOS, FreeBSD, OpenBSD, SOLARIS, HP-UX e etc…

---------------------------------------

# Sistemas Operacionais de Rede

É um sistema operacional especial que pode estar na arquitetura cliente/servidor ou peer-to-peer. Geralmente são máquinas parrudas. Ambiente multiusuário projetado para compartilhar , controlar recursos, como sistemas de arquivos, bancos de dados, impressoras, dispositivos de entrada e saída. Normalmente uma rede local (LAN), uma rede privada ou outras redes.

## Vantagens:

- Os servidores centralizados são altamente estáveis.
- A segurança é gerenciada pelo servidor.
- A atualização de novas tecnologias e hardware pode ser facilmente integrada ao sistema.
- É possível acessar remotamente servidores de diferentes locais e tipos de sistemas.

## Desvantagens:

- Dependência de um local central para a maioria das operações.
-	Servidores caros.
-	Manutenção e atualizações são necessárias regularmente.

## Exemplos de Sistemas Operacionais de Rede:
Linux, Windows Server 2012, MacOS, Novell Netware, Sun Solaris, FreeBSD, OpenBSD, e IBM OS/2.

---------------------------------------

# Sistemas Operacionais Paralelos:

São sistemas operacionais os quais possibilitam a execução de tarefas paralelas, ou seja, tarefas diferentes ao mesmo tempo. 

## Vantagens:

- Poder realizar mais de uma tarefa ao mesmo tempo.

## Desvantagens:

- Dificil implementação: nem todas as tarefas podem ser divididas para que possa executar simultaneamente.

---------------------------------------






### Support or Contact

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
