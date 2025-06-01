# Guia do Investidor Litoral SC

**Desenvolvido por:** Samuel Pedroso - Analista de Mercado Imobiliário

## Descrição

Este projeto é uma Aplicação Web Interativa de Página Única (SPA) concebida como um guia completo e ferramenta de análise para investidores interessados no dinâmico e valorizado mercado imobiliário do Litoral Norte de Santa Catarina. O foco principal recai sobre as cidades de Itapema, Balneário Camboriú e Porto Belo.

A aplicação visa traduzir dados complexos de mercado, tendências de valorização, estratégias de investimento e informações financeiras em uma experiência de usuário intuitiva e de fácil exploração. O objetivo é capacitar investidores com informações claras para uma tomada de decisão mais estratégica e embasada.

## Principais Funcionalidades

O guia interativo está estruturado nas seguintes seções principais:

1.  **Visão Geral:** Uma introdução impactante ao potencial de investimento da região, com destaques estatísticos sobre a valorização e o volume de negócios.
2.  **Comparativo de Cidades:** Uma análise interativa que permite ao usuário explorar e comparar dados específicos de Balneário Camboriú, Itapema e Porto Belo, incluindo perfis de investimento, preços médios de m² e projeções de valorização.
3.  **Estratégias de Investimento:** Detalhamento de abordagens chave para o investidor, como os benefícios de investir na planta, o conceito de alavancagem patrimonial, a importância da liquidez de mercado e a crescente tendência dos apartamentos compactos de luxo para locação por curta temporada.
4.  **CUB/SC & Aluguel por Temporada:** Informações sobre o Custo Unitário Básico (CUB) da construção em Santa Catarina, sua relevância para o investidor, além de dados sobre as principais plataformas de aluguel por temporada e o potencial de ganhos nesse segmento.
5.  **Notícias & Próximos Lançamentos:** Uma seção para manter o investidor atualizado sobre o desenvolvimento da infraestrutura regional e exemplos de futuros empreendimentos imobiliários (conteúdo demonstrativo).
6.  **Sobre o Analista:** Apresentação de Samuel Pedroso, o propósito do guia e um convite para investidores buscarem indicações de consultores imobiliários, bem como um chamado para consultores interessados em parcerias.
7.  **Simulador Financeiro:** Uma ferramenta interativa que permite aos usuários simular um fluxo de pagamento para aquisição de imóveis na planta, ajustando valor do imóvel, percentual de entrada, percentual nas chaves e número de parcelas.
8.  **Contato via WhatsApp:** Um botão flutuante para facilitar o contato direto para mais informações, indicação de consultores ou propostas de parceria.

## Tecnologias Utilizadas

* **HTML5:** Estrutura semântica da página.
* **Tailwind CSS:** Framework CSS para estilização responsiva e moderna.
* **JavaScript (Vanilla JS):** Lógica de interatividade, manipulação de dados e atualizações dinâmicas da interface.
* **Chart.js:** Biblioteca para a criação de gráficos dinâmicos e visualização de dados.

## Como Visualizar e Utilizar

Esta aplicação é um arquivo HTML único. Para visualizá-la:

1.  Faça o download do arquivo `[nome_do_seu_arquivo.html]`.
2.  Abra este arquivo em qualquer navegador web moderno (como Google Chrome, Firefox, Safari, Edge).

A aplicação pode ser hospedada gratuitamente em diversas plataformas de sites estáticos, como:
* GitHub Pages
* Netlify
* Vercel
* Firebase Hosting

## Personalização (Link do WhatsApp)

O número de telefone e a mensagem padrão do botão flutuante do WhatsApp podem ser facilmente personalizados. Abra o arquivo HTML em um editor de texto e localize as seguintes variáveis JavaScript no início da tag `<script>` (próximo ao final do arquivo):

```javascript
// WhatsApp Configuration - EDITE ESTES VALORES
const whatsappPhoneNumber = '5551993278018';
const whatsappDefaultMessage = 'Olá Samuel Pedroso! Pode me indicar algum consultor imobiliário, estou pensando em investir!';
// End WhatsApp Configuration
