# Zingen - Karaokê App

O **Zingen** é uma landing page de um serviço de karaokê que utiliza Inteligência Artificial para remover vozes de músicas. Este projeto foi desenvolvido para consolidar conhecimentos avançados em **HTML5** e **CSS3**, com foco total em **responsividade** e organização de código profissional.

### Tecnologias Utilizadas

* **HTML5**: Estruturação semântica de todas as seções da página.
* **CSS3**: Estilização avançada com as seguintes técnicas:
    * **Custom Properties (Variáveis)**: Gestão centralizada de cores, fontes e espaçamentos para garantir consistência.
    * **CSS Modular**: Divisão de estilos por componentes para melhor manutenção.
    * **Flexbox & CSS Grid**: Utilizados para criar layouts complexos e grelhas adaptativas.
    * **Responsividade**: Implementação de *Media Queries* para suporte a dispositivos móveis e desktop.

### Destaques Técnicos

### Arquitetura de Estilos Modular
O projeto utiliza uma estrutura modular onde a lógica é dividida em arquivos importados no `index.css`:
* `global.css`: Resets e definições base de root.
* `utility.css`: Classes utilitárias para agilizar o desenvolvimento.
* `buttons.css`: Estilização isolada de botões e estados interativos.

### Componentização de Interface
A página é composta por seções independentes e bem estruturadas:
* **Hero Section**: Área de impacto com chamadas principais e integração visual.
* **Features**: Grelha de funcionalidades com cards que utilizam `overflow: hidden` para estabilidade visual.
* **Pricing**: Tabela de preços com diferentes níveis de assinatura (Básico, Premium e Família).

### Design Responsivo e Mobile First
A estrutura utiliza unidades flexíveis e consultas de largura para garantir que a experiência de navegação seja excelente em qualquer tela:
* **Containers Fluídos**: Uso de `max-width` e margens automáticas para centralização.
* **Adaptação Desktop**: Ajustes específicos para telas largas, geralmente acima de 80em.

### Link do projeto:
* https://jpfreitas-dev.github.io/zingen-landing-page/
