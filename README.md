📡 Java Redes – RMI, TCP e UDP

Este repositório reúne as atividades desenvolvidas na disciplina de Java Redes, com foco em comunicação distribuída, programação cliente-servidor e invocação remota de métodos (RMI).

A disciplina abordou desde os fundamentos de comunicação em rede até a implementação prática de aplicações distribuídas utilizando Java.

🌐 Fundamentos de Redes

Durante a disciplina foram estudados os principais conceitos de redes de computadores:

Modelo OSI e modelo TCP/IP

Camadas de rede

Comunicação interprocessos (IPC)

Conceitos de cliente e servidor

Endereçamento IP e portas

Comunicação local (localhost – 127.0.0.1)

🔌 Programação com Sockets (TCP)

Foi estudada a comunicação baseada em TCP (Transmission Control Protocol), caracterizada por:

Protocolo orientado a conexão

Garantia de entrega

Garantia de ordenação

Controle de fluxo

Comunicação ponto a ponto (unicast)

📘 Classes principais utilizadas em Java:

ServerSocket

Socket

InputStream

OutputStream

DataInputStream

DataOutputStream

Implementações desenvolvidas:

Servidores que aguardam conexões

Clientes que estabelecem conexão

Troca de dados estruturados entre processos

📦 Programação com UDP

Também foi estudado o protocolo UDP (User Datagram Protocol), caracterizado por:

Não orientado a conexão

Não garante entrega

Não garante ordenação

Maior desempenho (menor overhead)

Comunicação baseada em datagramas

📘 Classes principais utilizadas:

DatagramSocket

DatagramPacket

Foram realizados exercícios envolvendo:

Envio e recebimento de datagramas

Comunicação cliente-servidor sem estabelecimento de conexão

Conceitos de unicast e multicast

🔁 Java RMI (Remote Method Invocation)

Um dos principais tópicos da disciplina foi a implementação de sistemas distribuídos utilizando RMI.

O RMI permite que métodos de um objeto sejam invocados remotamente como se fossem locais.

🔎 Conceitos estudados:

Interface remota (extends Remote)

RemoteException

Stub (proxy do objeto remoto)

Registry RMI (porta 1099)

Naming.lookup

Naming.rebind

UnicastRemoteObject

Serialização de objetos

Transparência na invocação remota

🏗 Estrutura típica de um projeto RMI:

Interface remota

Implementação da interface

Servidor (registro do objeto remoto)

Cliente (lookup e invocação)

🗳 Projeto Final – Sistema de Urna Eletrônica com RMI

Como atividade final da disciplina, foi desenvolvido um sistema distribuído simulando a apuração de votos de uma eleição.

Características do projeto:

Servidor em modo console

Cliente gráfico (Swing)

Cadastro de candidatos

Envio de votos manual pelo presidente da seção

Atualização automática da apuração a cada 5 segundos

Comunicação via RMI na porta 1099

Uso de 127.0.0.1 para comunicação local

Aplicação de boas práticas de organização de código

O projeto simula um ambiente semelhante ao Tribunal Regional Eleitoral (TRE), onde a apuração é centralizada e os votos são enviados em blocos.

🧠 Conceitos consolidados na disciplina

Ao final da disciplina, foram consolidados os seguintes conhecimentos:

Diferença entre TCP e UDP

Comunicação síncrona e bloqueante

Conceitos de unicast, multicast e broadcast

Comunicação cliente-servidor

Programação distribuída

Invocação remota de métodos

Tratamento de exceções em sistemas distribuídos

Serialização de objetos em Java

Uso de logs para monitoramento de chamadas remotas

🎯 Objetivo da disciplina

Capacitar o aluno a:

Compreender os fundamentos da comunicação em rede

Implementar aplicações cliente-servidor

Desenvolver sistemas distribuídos em Java

Utilizar RMI para invocação remota de métodos

Aplicar conceitos de comunicação síncrona e assíncrona

👩‍💻 Tecnologias utilizadas

Java SE

Java Sockets (TCP/UDP)

Java RMI

Swing (para cliente gráfico)

IntelliJ IDEA
