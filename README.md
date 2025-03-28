# Blockchain, Criptomoedas & Tecnologias Decentralizadas
Este é o site aberto com o material da disciplina "Blockchain, criptomoedas e tecnologias descentralizadas", oferecida como parte do currículo de Engenharia de Computação da USP desde Ago/2023, e também como uma disciplina aberta para qualquer interessado. Este é um site em contínua evolução, que deve ser atualizado juntamente com atualizações feitas na disciplina oficial: novas video-aulas, slides etc.

Esta disciplina foi construída com o apoio da [Decentralization Foundation](https://d24n.org) e da [Ripple](https://ripple.com) (por meio da University Blockchain Research Initiative).

As video-aulas estão disponíveis no [youtube](https://www.youtube.com/playlist?list=PLcbbqdJgPgcXlRlPNHF2itTotEwr9kckl).
<br>
<br>
<details>
<summary><h2>Slides das aulas (com as referências)</h2><summary>
[1a. Intro](slides/1a. Intro.pdf)

[1b. Intro - Classificação P2P](slides/1b. Intro - Classificação P2P.pdf)

[2a. Fundamentos de Criptografia - Serviços de Segurança](slides/2a. Fundamentos de Criptografia - Serviços Segurança.pdf)

[2b. Fundamentos de Criptografia - Criptografia Simétrica](slides/2b. Fundamentos de Criptografia - Criptografia simétrica.pdf)

[2c. Fundamentos de Criptografia - Assinaturas Digitais](slides/2c. Fundamentos de Criptografia - Assinaturas Digitais.pdf)

[2d. Fundamentos de Criptografia - Certificação Digital](slides/2d. Fundamentos de Criptografia - Certificação Digital.pdf)

[2e. Fundamentos de Criptografia - Construções Avançadas](slides/2e. Fundamentos de Criptografia - Construções Avançadas.pdf)

[3a. Blockchain sem Hype - Motivacao](slides/3a. BlockChain sem Hype-Motivacao.pdf)

[3b. Blockchain sem Hype - Blockchains](slides/3b. BlockChain sem Hype-Blockchains.pdf)

[3c. Blockchain sem Hype - Logs Transparentes (v3)](slides/3c. BlockChain sem Hype-Logs Transparentes - v3.pdf)

[3d. Blockchain sem Hype - Considerações](slides/3d. BlockChain sem Hype-Considerações.pdf)

[3e. Blockchain sem Hype - Aplicações](slides/3e. BlockChain sem Hype-Aplicações.pdf)

[3f. Blockchain sem Hype - Aplicacoes, mas não](slides/3f. BlockChain sem Hype-Aplicacoes, mas não.pdf)

[3g. Blockchain sem Hype - Privacidade](slides/3g. BlockChain sem Hype-Privacidade.pdf)

[3h. Blockchain sem Hype - Forks](slides/3h. BlockChain sem Hype - Forks.pdf)

[3z. (Bônus) Blockchain sem Hype- Criptomoedas e crimes (v2)](slides/3z. (Bônus) BlockChain sem Hype- Criptomoedas e crimes - v2.pdf)

[4a. Universo descentralizado - Tor](slides/4a. Universo descentralizado - Tor.pdf)

[4b. Universo descentralizado - Buscas de dados e DHT](slides/4b. Universo descentralizado - Buscas de dados e DHT.pdf)

[4c. Universo descentralizado - Broadcast e Gossip](slides/4c. Universo descentralizado - Broadcast e Gossip.pdf)

[4d. Universo descentralizado - Bittorrent e Compartilhamento de Arquivos](slides/4d. Universo descentralizado - Bittorrent e Compartilhamento de Arquivos.pdf)

[4e. Universo descentralizado - OAuth + OIDC](slides/4e. Universo descentralizado - OAuth + OIDC.pdf)

[4f. Universo descentralizado - IPFS](slides/4f. Universo descentralizado - IPFS.pdf)
<details>
<br>
<br>
## Introdução ao Hyperledger Fabric
### Máquina Virtual
Atualmente, para realizar as atividades de Hyperledger Fabric é necessário utilizar a Máquina Virtual.

1. Baixe o (ZIP)[http://www2.larc.usp.br/tmp/vm/hyperledger.zip]

2. Extraia o ZIP. O resutlado deve ser uma pasta chamada VM com dois arquivos: ubuntu.vdi e ubuntu.vbox.

3. Siga as (instruções)[https://www.youtube.com/watch?v=4aKbthqxKEY&list=PLcbbqdJgPgcXlRlPNHF2itTotEwr9kckl&index=23]

**OBS**: Para usuários de **Mac com chip M2**, talvez ainda não haja suporte oficial do VirtualBox (a verificar). Neste caso, o recomendado é utilizar outra máquina.

**OBS2**: Ao utilizar a VM, é possível que o script init, introduzido no vídeo 2.2, não execute conforme esperado. Isso pode ocorrer devido a conflitos gerados ao se interromper abruptamente a inicialização dos containers docker. Nesse caso, execute no terminal: `docker system prune --volumes --force &&  docker rmi $(docker images -q)`

### Slides (com as referências)
[1.1 Intro Curso](fabric/1.1 Intro Curso.pdf)

[1.2 Intro HLF](fabric/1.2 Intro HLF.pdf)

[2.1 Instalação](fabric/2.1 Instalação.pdf)

[3.1 Chaincode - Contratos Inteligentes](fabric/3.1 Chaincode - Contratos Inteligentes.pdf)

[3.2 - API com Node.js](fabric/3.2 - API com Node.js.pdf)

[4.1 Padrões ERC](fabric/4.1 Padrões ERC.pdf)
<br>
<br>
## Roteiros
### Roteiros oficiais (criados pelo professor)
[Tor](roteiros/Roteiro Tor.pdf)

[BitTorrent](roteiros/Roteiro BitTorrent.pdf)

### Roteiros criados por alunos
[Programação de Onion Route simulada](roteiros/Construindo+o+próprio+onion+routing.zip)

[Inserindo e recuperando arquivos no IPFS](roteiros/Roteiro+IPFS.pdf)

[Explorando conceitos em uma blockchain simples](roteiros/Roteiro+Explorando conceitos em uma blockchain simples.pdf)
