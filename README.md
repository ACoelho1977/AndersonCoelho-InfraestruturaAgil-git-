# AndersonCoelho-InfraestruturaAgil-git-

## VirtualBox

O VirtualBox é uma plataforma de virtualização de máquinas de código aberto que utiliza a técnica de hardware abstraction para criar instâncias virtuais de sistemas operacionais. Através da virtualização, o software proporciona ao usuário a capacidade de executar diferentes sistemas operacionais e aplicativos dentro de um ambiente controlado e isolado, sem a necessidade de hardware dedicado adicional. Ele suporta uma ampla gama de sistemas operacionais, como Windows, Linux, MacOS, entre outros, e oferece recursos como snapshots (capturas do estado da máquina), redes virtuais, e compartilhamento de pastas entre o host e o convidado.

Dessa forma, o VirtualBox é uma ferramenta poderosa para testes de software, desenvolvimento de ambientes de simulação, e aprendizagem sobre sistemas operacionais, além de ser amplamente utilizado em ambientes de servidores e datacenters para otimização do uso de recursos de hardware.

## Ubuntu

O Ubuntu é uma distribuição do sistema operacional Linux, baseada no Debian, que se caracteriza por sua facilidade de uso, acessibilidade e foco na experiência do usuário. Seu desenvolvimento é conduzido pela Canonical Ltd., uma empresa de software, com a colaboração da comunidade global de desenvolvedores e usuários.

O Ubuntu é projetado para ser um sistema operacional robusto, confiável e de código aberto, com uma ênfase especial na interface gráfica intuitiva e na acessibilidade a softwares livres, é um sistema operacional baseado em código aberto, derivado do núcleo Linux, que adota a filosofia de software livre e gratuito. Ele se destaca por sua interface gráfica amigável, foco na usabilidade e inclusão de uma vasta gama de aplicativos, tornando-o acessível tanto para usuários iniciantes quanto avançados. O sistema oferece atualizações regulares de segurança, suporte de longo prazo (LTS) para versões estáveis e uma vasta comunidade de desenvolvedores e usuários, contribuindo para o seu contínuo aprimoramento.

O Ubuntu é amplamente utilizado em ambientes domésticos, educacionais, corporativos e servidores, e é uma das distribuições Linux mais populares em desktops e servidores, devido à sua facilidade de instalação e uso, bem como seu desempenho eficiente e confiável. Em resumo, o Ubuntu é uma distribuição Linux altamente acessível, que combina robustez técnica com uma interface amigável, oferecendo uma plataforma confiável tanto para usuários iniciantes quanto para profissionais experientes. Sua filosofia de software livre e sua forte base comunitária fazem dele uma das escolhas mais populares dentro do ecossistema Linux.

## Git

Git é um sistema de controle de versão distribuído de código aberto utilizado para gerenciar e versionar o desenvolvimento de projetos de software, ou seja, é um sistema de controle de versão distribuído, que permite o gerenciamento de versões de arquivos e a colaboração simultânea entre múltiplos usuários em um projeto de software. Ele mantém um repositório local e remoto, possibilitando o rastreamento de mudanças, a ramificação do desenvolvimento e a fusão de diferentes versões do código.

Desenvolvido por Linus Torvalds em 2005, o Git foi projetado para lidar com projetos de grande escala, oferecendo funcionalidades que permitem a colaboração eficiente entre múltiplos desenvolvedores e a manutenção de um histórico preciso das modificações realizadas no código-fonte. Por ser distribuído, cada desenvolvedor possui uma cópia completa do repositório, o que confere maior flexibilidade e resiliência ao processo de desenvolvimento.

O Git é amplamente utilizado em projetos de desenvolvimento de software devido à sua velocidade, confiabilidade e flexibilidade. O Git é uma ferramenta essencial no ecossistema de desenvolvimento de software moderno, proporcionando controle de versão eficiente e robusto. Sua natureza distribuída, aliada a recursos avançados como ramificação, mesclagem e eficiência no manejo de grandes volumes de dados, faz dele a escolha predominante para gerenciamento de código-fonte em projetos de software, sejam eles pequenos ou de grande escala.

## GitHub

GitHub é uma plataforma de hospedagem e desenvolvimento colaborativo de código-fonte baseada na web "em nuvem", construída sobre o sistema de controle de versão distribuído Git, que oferece aos desenvolvedores a capacidade de hospedar repositórios de código-fonte, colaborar em projetos de software de forma distribuída e gerenciar o ciclo de vida do desenvolvimento de software.

A plataforma oferece ferramentas para rastrear e versionar mudanças no código, gerenciamento de issues (problemas e tarefas), revisão de código, integração contínua e automação de fluxos de trabalho.

Criada em 2008 por Tom Preston-Werner, Chris Wanstrath, PJ Hyett e Scott Chacon, a plataforma oferece um repositório remoto onde os desenvolvedores podem armazenar, versionar, compartilhar e colaborar no desenvolvimento de software. GitHub facilita o gerenciamento de código-fonte, a colaboração entre equipes e a contribuição de desenvolvedores de diferentes locais, além de fornecer recursos avançados de controle de versões e integração com outras ferramentas de desenvolvimento. GitHub é amplamente adotado em projetos de código aberto, bem como em ambientes empresariais e educacionais.

GitHub é uma plataforma robusta e amplamente adotada para hospedagem, gerenciamento e colaboração em projetos de software. Ao combinar as funcionalidades do sistema de controle de versão Git com uma interface web intuitiva e ferramentas de colaboração e automação, GitHub se tornou um pilar fundamental no ecossistema de desenvolvimento de software moderno. Sua adoção generalizada em projetos de código aberto e em ambientes corporativos reflete sua eficácia em promover a transparência, o controle de versões e a colaboração em larga escala.

A crescente demanda por ambientes virtuais, sistemas operacionais (SOs) de código aberto e controle de versão de código têm impulsionado o desenvolvimento e a adoção de ferramentas como o VirtualBox, o Ubuntu, o GIT e o GitHub.

# 2. OBJETIVOS

Este relatório tem como objetivo explorar o uso conjunto dessas ferramentas, abordando os métodos de instalação, configuração e uso, além de apresentar os resultados obtidos durante o processo e concluir sobre a eficácia dessa combinação de ferramentas no contexto do desenvolvimento de software, no qual descreve a instalação e configuração do GIT em uma máquina virtual Ubuntu, utilizando o VirtualBox, e a integração com o GitHub para a gestão de repositórios remotos.

O objetivo é ilustrar como configurar um ambiente de desenvolvimento colaborativo e realizar operações básicas com GIT e GitHub.

# 3. MATERIAIS E MÉTODOS

Os materiais usados foram um notebook com SO Windows 10 com processador Intel(R) Core (TM) i5 CPU M 480 @ 2.67GHz 2.66 GHz e 8GB de memória RAM, navegadores web (browsers), VirtualBox, Ubuntu, GIT, GitHub e internet.

## VirtualBox

O VirtualBox foi instalado em um sistema operacional Windows, seguindo os seguintes passos:

Foi realizado o download da versão mais recente do VirtualBox no site oficial () e seguido as instruções de instalação.

Executado o instalador foi realizado as etapas para concluir o processo de instalação.

Iniciado o VirtualBox, foi criado uma nova máquina virtual (VM) com o Ubuntu como sistema operacional convidado, e configurado recursos como memória RAM, espaço em disco e número de CPUs, ou seja, alocando recursos de hardware e selecionando a ISO do Ubuntu para a instalação do sistema operacional.

## Ubuntu

O Ubuntu é uma distribuição Linux amplamente utilizada em ambientes de desenvolvimento devido à sua estabilidade e suporte comunitário e foi escolhido como sistema operacional a ser instalado na máquina virtual criada. Para isso:

Baixou-se a imagem ISO mais recente do Ubuntu diretamente do site oficial ().

A ISO foi montada no VirtualBox, e a instalação do Ubuntu foi iniciada seguindo as etapas de instalação do sistema operacional.

Durante a instalação, escolheu-se a opção de atualização automática de pacotes e a criação de um usuário com privilégios administrativos.

## GIT

Git é um sistema de controle de versão distribuído que permite o rastreamento de alterações no código, enquanto o GitHub é uma plataforma para hospedagem de repositórios Git, facilitando a colaboração.

Primeiramente, foi utilizado o VirtualBox para criar uma máquina virtual com o sistema operacional Ubuntu e após a inicialização do Ubuntu, os pacotes necessários foram instalados utilizando o comando:

	sudo apt-get update
	sudo apt-get install git

A seguir, foi criado e inicializado um repositório GIT local com o comando:

	git init

Onde estará contido todos os arquivos de controle:

	mkdir AndersonCoelho-InfraestruturaAgil-git
	cd AndersonCoelho-InfraestruturaAgil-git

Após a instalação, configurou-se o GIT em um repositório local com as credenciais de usuário no qual foram criadas, utilizando o editor vim, padrão utilizado pelo GIT assim como as informações do usuário (nome e e-mail) utilizando os seguintes comandos:

	git config --global user.email anderson.ohleoc@gmail.com
	git config --global user.name "Anderson Coelho"
	git config --global core.editor "vim"

Foi criado dois arquivos de teste, denominados "meu primeiro arquivo" e "meu segundo arquivo", utilizando editor de texto no Ubuntu. Para adicionar os arquivos ao repositório, utilizei os comandos:

	git add "meu primeiro arquivo"
	git add "meu segundo arquivo"
	git commit -m "Adicionando arquivos de teste"

Criei um repositório no GitHub com acesso via SSH, garantindo a segurança na comunicação e foi gerado uma chave SSH com o comando:

	ssh-keygen -t rsa -b 4096 -C "anderson.ohleoc@gmail.com"

## GitHub

Para integrar o GIT com o GitHub, foram seguidos os seguintes passos:

Criou-se uma conta no GitHub e configurou-se um novo repositório e gerou uma chave SSH no Ubuntu utilizando o comando:

	ssh-keygen -t rsa -b 4096 -C "anderson.ohleoc@gmail.com"

A chave SSH foi adicionada à conta no GitHub para permitir a autenticação sem senha ao realizar operações Git e configurei o repositório remoto no Ubuntu com:

	git remote add origin git@github.com:usuario/repo.git

Foi realizado o clone de um repositório remoto do GitHub para o Ubuntu, utilizando o comando:

git clone git@github.com:usuario/repositorio.git

Por fim, realizou-se a criação de uma branch, a realização de commits e o envio das alterações para o repositório remoto e realizamos a sincronização do repositório local com o remoto utilizando:

git push -u origin master

# 4. RESULTADOS E DISCUSSÃO

Ao final dos procedimentos descritos, obteve-se os seguintes resultados:

VirtualBox: A máquina virtual foi criada com sucesso, permitindo o funcionamento adequado do Ubuntu, incluindo a instalação e o uso de software nativo do Linux.

Ubuntu: O sistema operacional Ubuntu foi instalado na máquina virtual e configurado corretamente, com a capacidade de acessar a internet e realizar atualizações de pacotes.

GIT: A instalação do GIT foi corretamente instalada e configurado no Ubuntu, concluída sem problemas, e a configuração do usuário foi feita com sucesso também. O repositório local foi criado e os arquivos foram adicionados, no qual foi possível realizar operações como commit, checkout e branch dentro de um repositório local.

O repositório remoto foi criado no GitHub e a comunicação entre o repositório local e remoto foi estabelecida com sucesso via SSH. O processo de sincronização entre os repositórios foi validado, garantindo que os arquivos locais fossem corretamente enviados para o repositório remoto.

GitHub: A integração com o GitHub ocorreu sem dificuldades. O repositório foi clonado, modificações foram feitas localmente e as alterações foram enviadas para o repositório remoto sem erros. O uso de SSH garantiu uma autenticação segura e sem necessidade de inserir senhas repetidamente. A sincronização foi realizada sem erros e as alterações realizadas no repositório local refletiram com precisão no GitHub, confirmando que o ambiente de desenvolvimento colaborativo estava funcionando adequadamente.

# 5. CONCLUSÃO

A combinação de VirtualBox, Ubuntu, GIT e GitHub demonstrou ser uma solução eficiente para o desenvolvimento de software em um ambiente controlado e seguro onde o VirtualBox permitiu a criação de um ambiente isolado, enquanto o Ubuntu oferece um sistema operacional robusto, flexível e popular para desenvolvimento de código. O GIT e o GitHub são essenciais para o controle de versão e colaboração, garantindo que equipes possam trabalhar juntas de forma eficiente e organizada facilitando a colaboração entre desenvolvedores.

A instalação e configuração do GIT no Ubuntu, bem como a integração com o GitHub, demonstram a eficácia dessa ferramenta no gerenciamento de versões e colaboração em projetos de desenvolvimento de software. A capacidade de rastrear e controlar alterações nos arquivos, permitindo que múltiplos desenvolvedores colaborem de maneira eficiente e sem riscos de sobrescrita de dados, é uma das grandes vantagens do uso do GIT.

A configuração do repositório remoto no GitHub facilitou ainda mais o compartilhamento de código entre equipes, proporcionando um ambiente seguro e controlado para o desenvolvimento de projetos. O exercício foi bem-sucedido e atingiu seus objetivos de promover uma compreensão prática das ferramentas GIT e GitHub no contexto de desenvolvimento colaborativo.

O uso dessas ferramentas não só melhoram a organização e a segurança no processo de desenvolvimento, como também facilitaram a colaboração entre equipes distribuídas. Com a integração bem-sucedida dessas tecnologias, o ambiente de desenvolvimento ficou mais ágil e produtivo, evidenciando a importância do uso dessas ferramentas em projetos de software modernos.

# 6. BIBLIOGRAFIA

AMARAL, D. C. et al. Gerenciamento ágil de projetos: aplicação em produtos inovadores. São Paulo: Saraiva, 2011.

BACK, N.; LEAL, L. C. M. Uma metodologia de planejamento de teste de produtos industriais. Produção, Rio de Janeiro, v. 2, n. 1, p. 61-69, out. 1991. Disponível em: https://bit.ly/3xEAe8d. Acesso em: 13 dez. 2021.

BASSO, D. E. Administração de redes de computadores. Curitiba, PR: Contentus, 2020.

BECK, K. et al. O Manifesto Ágil. Trad. João Rotta Neto. [S. l.: s. n.], 2002. Disponível em: https://bit.ly/3CNSRKE. Acesso em: 13 dez.  2021.

BELMIRO, N. J. Tecnologia da informação gerencial. São Paulo: Pearson Education do Brasil, 2015.

BERMAN, D. Prometheus x grafite: qual você deve escolher para séries temporais ou monitoramento?. Logz.io, 2020. Disponível em: https://bit.ly/3lXfA13. Acesso em:13 dez. 2021.

BEYER, B. et al. Engenharia de Confiabilidade do Google: como o Google administra seus sistemas de produção. São Paulo: Novatec, 2016.

BOAGLIO, F. Jenkins, automatize tudo sem complicações. São Paulo: Casa do Código, 2016.

BOSCARI, R. P. Implantando e testando o CACTI em uma rede empresarial. Curitiba, PR: Pontifícia Universidade Católica do Paraná, 2010. Disponível em: https://bit.ly/3AAqY6U. Acesso em: 13 dez. 2021.

COUTINHO, T. Lean Manufacturing: por que adotar o sistema toyota de produção? Por que adotar o Sistema Toyota de Produção?. Voitto, 2020. Disponível em: https://bit.ly/3iOxelP. Acesso em: 13 dez. 2021.

CONTRIBUIDOR. Surpresa! Amplo acordo sobre a definição de DevOps. DevOps, 2015. Disponível em: https://bit.ly/3xLMfc9. Acesso em: 13 dez. 2021.

CORREIA, P. Monitoração para suporte de auto-gestão em aplicações de micro-serviços. 2019, 147f. Dissertação (Mestrado em Engenharia Informática) – Universidade Nova de Lisboa, Lisboa, 2019.

CRITES, A. What devops means to me. Medium, 2016. Disponível em: https://bit.ly/3AJECF7. Acesso em: 13 dez. 2021.

DENARDIN, G. W; BARRIQUELLO, C. H. Sistemas operacionais de tempo real e sua aplicação em sistemas embarcados. São Paulo: Blucher, 2019.

ELASTIC. O que é o ELK Stack?. 2021. Disponível em: https://bit.ly/2VNVco0. Acesso em: 13 dez. 2021.

ELASTIC. Conheça os principais produtos – todos gratuitos e abertos. 2021. Disponível em: https://bit.ly/3jLusg4. Acesso em:13 dez. 2021.

ELASTIC STACK. Disponível em: https://bit.ly/2VNWLCo. Acesso em:13 dez. 2021.

FLUENTD. Disponível em: https://bit.ly/3g17Jvu. Acesso em:12 dez. 2021.

GAEA. O guia completo sobre CALMS em DevOps. GAEA, 2020. Disponível em: https://bit.ly/2VWqeKG. Acesso em: 18 abr. 2021.

GAEA. Quais são as características dos profissionais especialistas em DevOps. GAEA, 2020. Disponível em: https://bit.ly/3sdm0tW. Acesso em: 23 mar. 2021.

GOLDIN, P. 25 vantagens do DevOps. DevOps Digest, 2016. Disponível em: https://bit.ly/37CIRFZ. Acesso em: 13 dez. 2021.

GOMES, R.; SOUZA, R. Docker: infraestrutura como código, com autonomia e replicabilidade. In: WORKSHOP DE TECNOLOGIA DA INFORMAÇÃO E COMUNICAÇÃO DAS IFES, 9., 2015, Belo Horizonte. Anais [...]. Belo Horizonte, MG: IFES, 2015.

GONÇALVES, R. C. Gestão da informação em redes com servidores virtualizados: um modelo de apoio para gestores de microempresas e analistas de sistemas. 2017, 152f. Dissertação (Mestrado em Gestão Organizacional) – Universidade Federal de Goiás, Catalão, 2017.

GOOGLE CLOUD. Medição de DevOps: monitoramento e observabilidade. 2021. Disponível em: https://bit.ly/2VSXp1C. Acesso em: 13 dez. 2021.

GRAFANA. Disponível em: https://bit.ly/2VSHLnc. Acesso em:13 dez. 2021.

GRAPHITE. Disponível em: https://bit.ly/3jUlrBG. Acesso em: 13 dez. 2021.

HUMBLE, J.; FARLEY, D. Entrega Contínua: como entregar de forma rápida e confiável. Porto Alegre, RS: Bookman, 2014.

IESE BUSINESS SCHOOL. The 5 keys to a digital mindset. Forbes, 2014. Disponível em: https://bit.ly/3jPnWVH. Acesso em: 13 dez.  2021.

JUNIOR, P. R. Monitoramento de servidores e infraestrutura. [S. I.: s. n.], 2015. Disponível em: https://bit.ly/3CLmv3b. Acesso em: 13 dez. 2021.

KIBANA. Disponível em: https://bit.ly/37Jtewt. Acesso em: 13 dez. 2021.

LIMA, J. dos R. Monitoramento Zabbix. 2. ed. Rio de Janeiro: Brasport, 2020.

MARTIN, R. C. Desenvolvimento ágil limpo: de volta às origens. Rio de Janeiro: Alta Books, 2020.

OLIVEIRA, K. C. de A. Um processo de gerência de configuração baseado no 2 de CMMI estagiado para fábricas de softwares orientadas para produtos. 2007, 146f. Dissertação (Mestrado em Ciências da Computação) – Universidade Federal de Pernambuco, Recife, 2007. Disponível em: https://bit.ly/3AGBXvS. Acesso em: 13 dez. 2021.

OPENNMS. Disponível em: https://bit.ly/3AIxglk. Acesso em: 13 dez.  2021

POPPENDIECK, M.; POPPENDIECK, T Implementando o desenvolvimento lean de software: do conceito ao dinheiro. Porto Alegre, RS: Bookman, 2011.

PROMETHEUS. Disponível em: https://bit.ly/3jYOCng. Acesso em: 13 dez. 2021.

ROSSATO, C. A. Comparativo entre o método ágil e o tradicional. 2015, 20f. Artigo (Especialização em Governança de TI) – Universidade do Sul de Santa Catarina, Tubarão, 2017. Disponível em: https://bit.ly/3jQLE3W. Acesso em: 5 maio 2021.

SENS, E.; RODRIGUES, J. R. S. O tripwire e a integridade de sistemas GNU/Linux. Lavras, MG: Universidade Federal de Lavras, 2003. Disponível em: https://bit.ly/2VVt6aT. Acesso em: 13 dez. 2021.

SHAHIN, M.; BABAR, M. A.; ZHU, L. Continuous Integration, Delivery and Deployment: a systematic review on approaches, tools, challenges and practices. Ieee, Sidney, v. 5, p. 3909-3943, mar. 2017. Disponível em: :. Acesso em:13 dez. 2021.

SOUSA, L.; TRIGO, A.; VARAJÃO, J. DevOps – fundamentos e perspectivas. In: CONFERÊNCIA DA ASSOCIAÇÃO PORTUGUESA DE SISTEMAS DE INFORMAÇÃO, 19., 2019, Lisboa. Anais [...]. Lisboa, Portugal: APSI, 2019.

TANENBAUM, A. S. Sistemas operacionais modernos. 3. ed. São Paulo: Pearson Prentice Hall, 2009.

THE (SHORT) HISTORY OF DEVOPS. [S. l.: s. n.], 2012. Publicado pelo canal Damon Edwards. Disponível em: https://bit.ly/3jREi03. Acesso em: 13 dez. 2021.

TRANSFORMAÇÃO DIGITAL. Mindset Digital: onde começa a transformação. Transformação digital, 2018. Disponível em: https://bit.ly/3jOGENj. Acesso em: 13 dez. 2021.

TRIPWIRE. Disponível em: https://bit.ly/3m1oo63. Acesso em: 13 dez. 2021.

TURNBULL, J. Pulling Strings with Puppet. New York: Apress, 2007.
