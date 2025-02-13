# Modernização tecnológica

## **1. Storytelling: Transformação Digital da Easy Invest**

A **Easy Invest** é uma renomada empresa de investimentos, com mais de 37 anos de experiência no mercado financeiro. Com um compromisso sólido com a governança e compliance, a empresa busca oferecer aos seus clientes uma rentabilidade segura e eficiente através de orientações personalizadas e transações financeiras ágeis.

**Missão:** Contribuir para o crescimento do patrimônio de nossos clientes, oferecendo soluções de investimento adequadas e transações financeiras seguras.

**Visão:** Ser a empresa de investimentos mais rentável do Brasil, sempre priorizando a satisfação de nossos clientes, colaboradores e acionistas.

**Princípios:**
- Credibilidade
- Segurança nas transações
- Atendimento diferenciado e comprometido

O sistema **Easy Core** é o principal das operações financeiras da Easy Invest, sendo responsável por uma série de funções críticas como avaliação de riscos, consulta de saldo e execução de transações. Este sistema, que possui mais de 7.000 usuários ativos, tem um papel essencial nas transações financeiras que envolvem grandes quantias de dinheiro. O **Easy Core** é de altíssima criticidade, e sua falha pode interromper operações financeiras e gerar enormes perdas.

Por sua estrutura monolítica e obsolescente, o **Easy Core** enfrenta desafios significativos. O sistema foi originalmente desenvolvido em **VB3**, migrando para **VB6**, e utiliza o **SQL Server 2008**. Seu ambiente de execução é restrito a plataformas desatualizadas, como **Windows 8**, e todos os usuários necessitam ter o **runtime VB6** instalado em seus dispositivos. Esse sistema tem sérias limitações, como a necessidade de reiniciar constantemente o **COM+** para restaurar transações travadas, o que impacta negativamente no desempenho.

Apesar de um time de TI altamente qualificado, o processo de manutenção e desenvolvimento é dificultado pela falta de documentação técnica e funcional. As regras de negócios estão espalhadas entre **Stored Procedures** e componentes **COM+**, tornando o sistema difícil de modificar e integrar com outras tecnologias. Além disso, a escassez de profissionais especializados em **VB6** eleva o custo da equipe, e a falta de flexibilidade na arquitetura impede a adaptação a novas soluções e ferramentas.

A **Easy Invest** enfrenta ainda outro problema com suas bases de dados, que não estão normalizadas. Quando adquiriu uma outra empresa do ramo financeiro, trouxe consigo dados desestruturados em arquivos **CSV**, com registros duplicados e divergentes. Isso cria dificuldades na comunicação com os clientes e na análise precisa de seu perfil. A **Easy Invest** identificou que a unificação e limpeza dessas bases de dados são vitais para o sucesso de sua transformação digital e para a obtenção de insights valiosos através de **Business Intelligence** (BI) e **Analytics**.

Além disso, a **Easy Invest** almeja tornar-se uma empresa de investimentos digitais, com todas as operações sendo realizadas através de plataformas online e aplicativos móveis. Para isso, pretende modernizar suas ferramentas de análise de dados e relatórios, além de buscar uma integração mais eficiente entre suas diversas plataformas e a adoção de novas tecnologias.

A companhia também reconhece a necessidade de uma arquitetura mais ágil e escalável, e por isso deseja investir em soluções de **PaaS**, **microsserviços**, **APIs**, e reforçar a segurança de suas operações para garantir a confidencialidade e a conformidade com as regulamentações, como a **LGPD**.

Com o cenário atual repleto de desafios e oportunidades, a **Easy Invest** está se preparando para uma transformação digital profunda. Sua missão é modernizar o **Easy Core**, otimizar processos internos, melhorar a experiência do cliente e garantir uma plataforma de investimentos mais segura, rápida e eficaz, capaz de crescer junto às novas demandas do mercado.

A **Easy Invest** está no caminho para se tornar referência em investimentos digitais, pronta para enfrentar os desafios da modernização e, ao mesmo tempo, manter seu compromisso com a segurança, a eficiência e a rentabilidade das operações de seus clientes.

**Análise SWOT**

![Análise SWOT](media/image6.png)

## **2. O que esperamos aprender com esse projeto?**

- **Compreender as principais necessidades do negócio e os desafios técnicos:** Como melhorar a arquitetura atual, implementar novos processos e suportar a expansão da empresa de forma eficiente.
- **Entender o impacto das novas tecnologias:** Como as inovações tecnológicas escolhidas (Data Mesh, Cloud, APM, DevSecDataFinOps, entre outras) irão impactar as operações, segurança, custo e escalabilidade.
- **Avaliar a capacidade de adaptação dos sistemas atuais:** Qual o grau de flexibilidade e escalabilidade da arquitetura proposta frente às novas demandas de operação com ETFs, Criptomoedas e integração com o mercado financeiro internacional.
- **Obter insights sobre a jornada do usuário:** Como melhorar a experiência do cliente nas plataformas, principalmente na interação com sistemas de negociação de ações, ETFs e criptomoedas.

## **3. Que perguntas precisamos que sejam respondidas?**

### **Tecnológicas e de Implementação:**
- Como garantir a normalização dos dados sem impactar a operação atual da empresa?
- Quais são as melhores práticas para migrar sistemas legados sem causar interrupções significativas?
- Como garantir a segurança, privacidade e compliance das transações financeiras e dados dos clientes em ambientes multinacionais?
- Quais tecnologias específicas são mais adequadas para integrar as operações de ETFs, criptomoedas e sistemas de trading?

### **De Negócio:**
- Como a migração para a cloud impactará os custos operacionais e a escalabilidade dos serviços?
- Qual a melhor forma de medir o sucesso de cada operação (ETFs, criptomoedas, ações)?
- Como otimizar o tempo de cadastramento de novos clientes, melhorando a experiência do usuário e reduzindo os custos operacionais?

### **De Processos:**
- Quais serão os principais KPIs para os novos sistemas de monitoramento (APM e trace distribuído)?
- Como garantir a automação de processos sem perder controle de qualidade?

## **4. Quais são os nossos principais riscos?**

### **Risco de Segurança e Compliance:**
- A migração para sistemas baseados em cloud pode introduzir vulnerabilidades, especialmente em regiões com regulamentações de dados mais rigorosas.
- O uso de tecnologias antigas (COM+, VB6) representa um risco de segurança devido à falta de atualizações e patches.
- O processo de integração com sistemas regulatórios e financeiros internacionais pode falhar em garantir compliance completo.

### **Risco Operacional:**
- A complexidade da transição para uma nova arquitetura de dados (Data Mesh) pode afetar a integridade e disponibilidade dos dados.
- Falha na implementação de processos DevOps e automatização, resultando em processos manuais que geram retrabalho e baixa qualidade.
- A dependência de profissionais especializados em tecnologias legadas pode gerar dificuldades para escalar a equipe com rapidez.

### **Risco de Experiência do Usuário:**
- Mudanças no fluxo de cadastramento de clientes e na interface de plataformas podem resultar em baixa aceitação ou atrito por parte dos usuários.
- O piloto controlado pode não capturar todos os possíveis cenários de falha no processo, gerando problemas durante o rollout.

## **5. Plano para aprender o que precisamos para responder a perguntas específicas**

### **Análise Técnica e Tecnológica:**
- Realizar um levantamento detalhado das ferramentas de ETL e análise de dados atuais e a viabilidade de adotar novas soluções.
- Realizar sessões de brainstorming e workshops com a equipe técnica para identificar as melhores alternativas de migração de sistemas legados.
- Realizar benchmarking e estudos de mercado sobre soluções de Cloud e APM, analisando a compatibilidade com as regulamentações locais.

### **Pesquisa de Mercado e de Clientes:**
- Conduzir entrevistas com clientes e stakeholders para mapear as expectativas quanto à experiência do usuário.
- Estudo contínuo das tendências do mercado financeiro, particularmente em ETFs e Criptomoedas, para identificar novas oportunidades.

### **Prototipagem e Testes:**
- Criar protótipos de fluxos e interfaces para validar as melhorias na experiência do usuário.
- Conduzir testes de stress nos sistemas propostos, focando em performance, escalabilidade e segurança.

## **6. Plano para reduzir riscos**

### **Segurança e Compliance:**
- Garantir auditorias contínuas durante o processo de migração para identificar falhas de segurança antes que se tornem problemas críticos.
- Adotar soluções de cloud que atendam aos requisitos de compliance internacional, com foco na proteção e anonimização dos dados.

### **Operacional:**
- Priorizar a construção de uma arquitetura escalável e modular, permitindo atualizações contínuas sem impactar a operação.
- Implementar uma metodologia ágil, com revisões constantes e pequenos ciclos de feedback, para mitigar os riscos durante a implementação.

### **Experiência do Usuário:**
- Validar todas as mudanças e novos fluxos com usuários reais antes de realizar a implementação em grande escala.
- Fornecer treinamento adequado para os usuários finais sobre as mudanças e melhorias nos sistemas e plataformas.

## **7. Quem são as partes interessadas?**

- **Executivos da Empresa:** Esperam ver a melhoria na eficiência dos sistemas, redução de custos operacionais e aumento da competitividade no mercado financeiro.
- **Equipe Técnica de TI:** Esperam melhorias nas ferramentas de desenvolvimento e na infraestrutura de sistemas, além de obter processos mais eficientes.
- **Compliance e Reguladores:** Precisam garantir que todas as mudanças estão em conformidade com as regulamentações de dados e transações financeiras internacionais.
- **Equipe de Produto/Negócios:** Estão focados em garantir que a nova arquitetura permita um crescimento sustentável e suportar novos produtos e mercados, como ETFs e Criptomoedas.

## **8. O que eles esperam ganhar?**

- **Executivos:** Maior controle sobre os custos operacionais, aumento da escalabilidade, redução de riscos tecnológicos e aumento da inovação.
- **Equipe Técnica:** Ferramentas modernas, arquitetura eficiente e práticas que possibilitem maior agilidade e melhores resultados.
- **Compliance:** Garantia de que a empresa estará operando de acordo com as regulamentações locais e internacionais.
- **Produto/Negócios:** Maior satisfação do cliente, aumento das operações financeiras e expansão para novos mercados.

## **9. Quem são os usuários?**

- **Clientes de ETFs, Criptomoedas e Ações:** Buscam plataformas de fácil uso, seguras, com um processo simples de cadastro e transações financeiras ágeis e confiáveis.
- **Traders e Profissionais do Mercado Financeiro:** Precisam de ferramentas avançadas de análise de dados, relatórios e execução de ordens em tempo real.
- **Equipe Interna de TI e Operações:** Responsáveis por garantir que as plataformas e sistemas funcionem com eficiência e segurança.

## **10. O que eles estão tentando realizar?**

- **Clientes:** Realizar transações financeiras com facilidade e segurança, utilizando plataformas confiáveis e ágeis.
- **Traders e Profissionais:** Acompanhar e realizar operações financeiras de forma eficiente e precisa, com acesso a dados em tempo real.
- **Equipe de TI:** Melhorar a infraestrutura tecnológica, garantindo que a empresa seja capaz de suportar novas operações financeiras e processos de forma escalável.

## **11. Qual o pior que pode acontecer?**

- **Risco de falha técnica:** Interrupção dos serviços financeiros, impacto na confiança do cliente e perda financeira significativa.
- **Risco de Compliance:** Multas, ações legais ou a proibição de operar em certos mercados devido a falhas de compliance.
- **Risco de rejeição pelo Usuário:** Mudanças que não sejam bem recebidas pelos clientes, resultando em perda de usuários e diminuição da competitividade.

Esse projeto requer uma execução cuidadosa, com foco em reduzir riscos e maximizar a inovação. Através de uma abordagem estruturada, envolvendo todas as partes interessadas e mantendo a qualidade como prioridade, será possível alcançar os objetivos propostos.

## **12. Desenhe uma arquitetura (Modelo Freeform - Versão inicial) AS-IS:**

![Arquitetura AS-IS](media/image1.png)

## **TO BE:**

### Arquitetura de Tecnologia:

![Arquitetura de Tecnologia](media/image7.png)

### Arquitetura de Dados:

![Arquitetura de Dados](media/image8.png)

## **13. Faça uma descrição de cada um dos componentes que você desenhou**

Realizado a descrição no desenho de arquitetura anterior.

## **14. Descreva os requisitos que você (s) considera importante e por quê?**

### **1. Segurança e Conformidade Regulatória**

A proteção de dados e a conformidade com regulamentações como a LGPD e as normas financeiras são essenciais para garantir a segurança das informações dos clientes e evitar multas e danos à reputação da empresa.

### **2. Unificação e Normalização das Bases de Dados**

Unificar e normalizar as bases de dados, eliminando duplicidades e divergências, é fundamental para garantir a consistência das informações, facilitando a análise de dados e a geração de insights para tomar decisões mais precisas e estratégicas.

### **3. Modernização da Infraestrutura e Arquitetura de TI**

Atualizar a infraestrutura de TI e adotar arquiteturas modernas, como microsserviços e plataformas de nuvem, é crucial para aumentar a escalabilidade, reduzir custos e facilitar a integração com novas ferramentas e sistemas.

### **4. Experiência do Cliente (UX/UI e Plataformas Digitais)**

Melhorar a experiência do cliente, oferecendo plataformas digitais intuitivas e acessíveis, é essencial para reter clientes e melhorar a competitividade da empresa, proporcionando um ambiente mais eficiente para realizar transações financeiras.

### **5. Agilidade no Desenvolvimento e Implantação de Novas Funcionalidades (DevOps)**

Implementar práticas de DevOps, como automação e integração contínua, permitirá à empresa lançar melhorias e atualizações de forma mais rápida e com maior qualidade, melhorando a eficiência operacional e o tempo de resolução a problemas críticos.

Esses requisitos são fundamentais para a transformação digital da Easy Invest, garantindo maior segurança, eficiência e agilidade na operação.

## **15. Sobre o que o diagrama ajuda você a raciocinar/pensar?**

Ajuda a entender a estrutura do sistema, identificar pontos críticos, visualizar fluxos de dados e processos, e planejar soluções para problemas de integração, escalabilidade e desempenho.

## **16. Quais são os padrões essenciais no diagrama?**

- Camadas de abstração;
- Componentes;
- Interações e Fluxos de Dados;
- Conectores e Interfaces;
- Tecnologias e Ferramentas;
- Segurança e Governança;
- Escalabilidade e Redundância.

## **17. Existem padrões ocultos?**

Os padrões ocultos que podemos observar podem ser, como dependências implícitas na arquitetura monolítica (VB6 + COM+), onde integrações não documentadas dificultam a migração, além da herança tecnológica oculta, com regras de negócio enterradas no código legado. Há também padrões de dados não óbvios, pois bases desnormalizadas e registros duplicados podem comprometer a qualidade das análises. Fluxos de trabalho não estruturados, como a necessidade de reiniciar o COM+ para restaurar transações, indicam fragilidades operacionais. Além disso, a adoção de microsserviços, CQRS e Data Mesh pode aumentar a complexidade se não houver governança adequada.

## **18. Qual é o Metamodelo?** Modelo Archimate

## Business Capabilities

![Business Capabilities](media/image3.png)

## **19. Pode ser discernido no diagrama único?**

Não pode ser discernido em um diagrama único, devido a existência de padrões ocultos que não constam dentro do diagrama também por existir falta de documentação em áreas como dependências não documentadas.

## **20. O diagrama está completo?**

O diagrama não está completo pois existem incertezas relacionadas aos serviços e regras de negócios das aplicações, também a interdependências das aplicações entre as equipes.

## **21. Poderia ser simplificado e ainda assim ser eficaz?**

Não poderia ser simplificado, pois perderia muitas informações relevantes para entendimento do projeto.

## **22. Houve alguma discussão importante que vocês tiveram
