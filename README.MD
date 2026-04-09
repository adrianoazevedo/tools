\# 💳 Calculadora Segura - Algoritmo de Luhn



Uma ferramenta leve, 100% offline e executada no lado do cliente (client-side) para descobrir um dígito apagado ou ilegível em um cartão de crédito. 



\## 🛡️ Foco na Privacidade

Este projeto foi desenvolvido com foco total na segurança do usuário. Como não possui back-end e não faz requisições externas, o cálculo é feito diretamente no processador da sua máquina. \*\*Nenhum dado financeiro é salvo, armazenado ou enviado pela rede.\*\* Para máxima segurança, a ferramenta pode ser executada com o computador totalmente desconectado da internet.



\## 🚀 Como funciona

A calculadora utiliza o \*\*Algoritmo de Luhn\*\* (módulo 10), que é o padrão internacional de validação de cartões de crédito. 



Se o seu cartão possui um número ilegível, basta preencher os outros 15 números conhecidos e inserir a letra \*\*`X`\*\* na exata posição do número apagado. O script irá iterar pelas 10 possibilidades (de 0 a 9), aplicando a matemática de validação para encontrar o único dígito que torna o cartão válido.

Referência: https://stripe.com/br/resources/more/how-to-use-the-luhn-algorithm-a-guide-in-applications-for-businesses

\## ✨ Funcionalidades

\* \*\*Identificação de "X" universal:\*\* O dígito desconhecido pode estar em qualquer uma das 16 posições.

\* \*\*Formatação em tempo real:\*\* Agrupa automaticamente os números de 4 em 4 enquanto você digita para evitar erros visuais.

\* \*\*Validação rigorosa:\*\* Impede o cálculo se não houver exatamente 15 números e 1 letra 'X'.



\## 🛠️ Como usar

1\. Faça o clone do repositório ou baixe o arquivo `calculadora.html`.

2\. Dê um duplo clique no arquivo para abri-lo no seu navegador de preferência.

3\. Digite os números do cartão e substitua o número apagado por um `X`.

4\. Clique em "Verificar X".



\## 💻 Tecnologias utilizadas

\* HTML5

\* CSS3

\* Vanilla JavaScript (ES6)

