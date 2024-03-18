O HackInSDN tem como objetivo prover mecanismos de capacitação em temas de segurança cibernética utilizando ambientes de testbeds. Trata-se de um pacote de ferramentas que oferecerá um ambiente mais robusto e completo para capacitação em tópicos avançados de segurança, através da programabilidade de redes. Além dos sistemas de detecção de intrusão, o HackInSDN incorpora outras características como mecanismos de detecção de anomalias apoiados pela Inteligência Artificial, mecanismos de contenção e filtragem de ataques dinâmicos, ferramental para simulação de ataques, base de dados para inteligência de ameaças dentre outros.

HackInSDN está projetada para ser operada no ambiente distribuído de testbeds da RNP, beneficiando o sistema RNP com um serviço de capacitação em segurança cibernética que adotará a sua infraestrutura de testbeds.

# Visão Geral

A Figura abaixo apresenta uma visão geral do HackInSDN.

![HackInSDN big picture](/assets/img/hackinsdn.png)

Os principais módulos da ferramenta são:
- **AI-Powered Anomaly Detection**: este componente será integrado ao Orquestrador de redes e receberá uma série de métricas de rede para então processar algoritmos de detecção de anomalias via Aprendizagem de Máquina Estatística e então gerar Alertas de Anômalia.
- **Zeek Network Security Monitoring**: A solução de IDS Zeek é uma plataforma aberta que permite integração com outros sistemas para detecção de anomalias customizadas ou com base em assinaturas conhecidas de ataques.
- **Programmable Network Orchestrator**: o Orquestrador de Redes programável desempenha papel central na arquitetura provendo os serviços de gerenciamento e provisionamento da rede, e também integrando os demais componentes. O Kytos-ng (https://kytos-ng.github.io) é a plataforma de orquestração SDN que será usada como base no HackInSDN, pois incorpora uma solução de controle SDN escalável, flexível e altamente customizável/programável. 
- **Adaptive Mirroring**: este módulo será desenvolvido no contexto do projeto HackInSDN para permitir o espelhamento de tráfego granular e elástico nos serviços de rede provisionados pelo Orquestrador.
- **Intelligent Containment and Filtering**: o papel deste módulo é prover serviços de contenção e filtragem de ataques a partir das anomalias e alertas detectados, ou a partir da solicitação do operador de redes.
- **MISP Threat Intelligence and Sharing**: mecanismos de inteligência de ameaça e compartilhamento de informações de segurança são essenciais para defesa e pesquisa em segurança atualmente.
- **Adversary Simulator**: um conjunto de ferramentas do estado da arte e voltadas para offensive security será disponibilizada como parte do projeto HackInSDN para ser utilizadas na perspectiva de hacking ético e simular tráfego malicioso no ambiente descrito acima.

# Instituições parceiras

[![UFBA logo](/assets/img/ufba.png)](https://www.ufba.br)
[![IFBA logo](/assets/img/ifba.png)](https://www.ifba.edu.br)
[![FIU logo](/assets/img/fiu.png)](https://www.fiu.edu)

[![INSERT logo](/assets/img/insert.png)](http://insert.ufba.br)
[![Amlight Logo](/assets/img/amlight.png)](https://www.amlight.net)


# Agradecimentos

O projeto HackInSDN foi contemplado na Chamada Hackers do Bem, [chamada pública para Pesquisa e Desenvolvimento 2023](https://www.rnp.br/noticias/hackers-do-bem-resultado-da-chamada-publica-para-pesquisa-e-desenvolvimento-2023){:target="_blank"}.

Leia mais sobre o [Projeto Hackers do Bem](https://hackersdobem.org.br){:target="_blank"}.

# Mais informações

 - [Download, Instalação e Execução](./getting-started.html)
 - [Publicações](./publications.html)
 - [Tutoriais e documentações de uso](./technical-guides.html)
 - [Equipe de desenvolvimento](./hackinsdn-team.html)
 - [Código-fonte e Licenciamento](./source-code-license.html)

# Suporte

Encontrou um bug ou quer requisitar uma funcionalidade? [Reporte aqui!](https://github.com/hackinsdn/hackinsdn/issues)

Para manter contato com a equipe de desenvolvimento, escreva para **hackinsdn [AT] ufba.br**.