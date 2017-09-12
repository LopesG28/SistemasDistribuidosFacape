# SistemasDistribuidosFacape
Avaliação I Unidade 



O objetivo deste projeto lista é desenvolver um pequeno sistema distribuído de servidores
utilizando sockets.

O projeto será composto de algumas etapas, que serão avaliadas separadamente e também
em conjunto.

O sistema/programa a ser implementado pode ser desenvolvido em Java e deve
executar no Linux/ Windows.

Os fontes, executáveis e o texto devem ser disponibilizados no github.

O sistema será composto de:
- um servidor concorrente principal que receberá requisições via socket e encaminhará as mesmas, via sockets para servidores escravos
- servidores escravos que se registrarão no servidor principal e serão encarregados de realizar as operações
- algoritimo para decisão para escolha do servidor escravo (sugestão round-robin)
- servidores escravos especializados que receberão requisições específicas, delegadas pelos servidor principal
- clientes que farão requisições para o servidor principal
- As 4 operações básicas devem ser executadas nos servidores escravos básicos
- As operações de Porcentagem, raiz quadrada e potenciação devem ser executadas nos servidores escravos especiais

Um arquivo de texto, tipo README deve descrever as decisões de projeto, entre ela as
relacionadas a endereçamento, registro, portas, obtenção destas informações, etc.
