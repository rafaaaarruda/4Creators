# 4Creators

O **4Creators** é um aplicativo iOS criado para auxiliar criadores de conteúdo na **organização e no planejamento de suas publicações**, reunindo projetos, conteúdos e informações de planejamento em um único espaço.

> Este repositório apresenta o projeto e suas principais funcionalidades. O código-fonte completo não está público neste momento.

---

## Sobre o projeto

Criadores de conteúdo precisam lidar com diferentes ideias, projetos, plataformas, datas e etapas de produção ao mesmo tempo.

O **4Creators** foi desenvolvido para facilitar esse processo, permitindo organizar publicações dentro de projetos e concentrar informações importantes para o planejamento de cada conteúdo.

Além das funcionalidades de organização, o aplicativo utiliza **Inteligência Artificial como apoio ao processo criativo e de planejamento**, ajudando a transformar ideias iniciais em conteúdos mais estruturados.

O projeto foi desenvolvido por uma equipe composta por **três desenvolvedores e uma designer**.

---

## Inteligência Artificial

O 4Creators possui integração com a **API da OpenAI**, utilizada para interpretar as informações fornecidas pelo usuário e auxiliar na criação e organização de conteúdos dentro do aplicativo.

A partir da entrada do usuário, a IA era capaz de:

* criar projetos;
* criar novas publicações;
* organizar publicações dentro de projetos;
* identificar informações fornecidas pelo usuário e distribuí-las nos campos correspondentes;
* reconhecer informações como **data** e **plataforma de publicação**;
* gerar um pequeno **briefing** para o conteúdo;
* criar um **roteiro inicial** utilizando apenas o título da publicação como contexto.

O objetivo da integração era reduzir o trabalho manual de organização e ajudar o criador de conteúdo a transformar uma ideia inicial em uma publicação mais estruturada.

---

## Tecnologias

* **Swift** — desenvolvimento da aplicação;
* **SwiftUI** — construção das interfaces;
* **Core Data** — persistência local dos dados;
* **OpenAI API** — integração dos recursos de Inteligência Artificial;
* **Xcode** — ambiente de desenvolvimento.

---

## Decisões técnicas e desafios

Durante o desenvolvimento, a equipe trabalhou com diferentes versões do Xcode e diferentes gerações de equipamentos, o que exigiu atenção à compatibilidade entre os ambientes utilizados pelos integrantes.

Embora o **SwiftData** já estivesse disponível, sua utilização não era viável em todos os ambientes da equipe. Por esse motivo, optamos pelo **Core Data** para a persistência local das informações, garantindo maior compatibilidade durante o desenvolvimento colaborativo.

Essa experiência trouxe aprendizados sobre como decisões técnicas precisam considerar não apenas a tecnologia mais recente, mas também fatores como **compatibilidade, ferramentas disponíveis, contexto da equipe e estabilidade do projeto**.

---

## Minha participação

Contribuí principalmente para o desenvolvimento das telas da aplicação com Swift e SwiftUI, trabalhando na implementação das interfaces em colaboração com a equipe de desenvolvimento e design.

---

## Demonstração

Imagens e demonstrações do aplicativo serão adicionadas a este repositório.
