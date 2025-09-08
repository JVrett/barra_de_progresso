## Projeto 15 - Barras de Progresso Animadas


### 🚀 Sobre o Projeto

Este projeto consiste em uma página com barras de progresso que exibem níveis de habilidade em diferentes tecnologias. Cada barra é preenchida de forma fluida e animada, revelando a porcentagem da habilidade ao final da animação.

### 🛠️ Tecnologias e Conceitos Abordados

#### HTML5

Neste projeto, utilizei a estrutura de divs aninhadas para criar a base de cada barra de progresso. A tag <span> com classes específicas foi usada para segmentar cada elemento da barra, o que permitiu um controle preciso sobre a estilização e a animação.

#### CSS3

O uso de @keyframes foi crucial para criar a animação de "preenchimento", onde a largura da barra aumenta de 0 até o valor desejado. A propriedade animation-delay foi usada para criar um efeito de cascata, fazendo com que cada barra fosse animada em sequência. Além disso, a pseudoclasse ::before foi empregada para criar a "seta" do tooltip (a caixa de porcentagem), e a propriedade transform: translateX() rotate() foi utilizada para posicioná-la e rotacioná-la corretamente. Por fim, a propriedade z-index foi essencial para garantir que a porcentagem estivesse sempre visível acima da barra de progresso.

### 💻 Como Executar:

Instale o arquivo no seu computador, e abra no seu navegador de preferencia.
