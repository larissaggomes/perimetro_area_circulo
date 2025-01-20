# Cálculo do Perímetro e da Área de um Círculo

Este projeto é um exemplo simples de código em HTML e JavaScript que calcula o perímetro e a área de um círculo com base no valor do raio fornecido pelo usuário.
📋 Funcionalidades

    Solicita ao usuário:
        O valor de π (pi).
        O valor do raio (r) do círculo.
    Calcula:
        Perímetro do círculo:
        Perimetro=2⋅π⋅r
        Área do círculo:
        Area=π⋅r2
    Exibe os resultados diretamente na página web.

🚀 Como executar o código

    Salve o código em um arquivo com a extensão .html.
    Abra o arquivo em qualquer navegador.
    Siga as instruções no navegador:
        Insira o valor de π (pode ser 3.14 ou o número exato do π se disponível).
        Insira o valor do raio do círculo.
        O programa calculará e exibirá o perímetro e a área na página.

📌 Exemplo de Saída

Se o usuário fornecer:

    Valor de π: 3.14
    Valor de r: 5

A saída será:

Perímetro do círculo: 31.400000000000002
A área do círculo: 31.4

🛠️ Tecnologias utilizadas

    HTML: Para a estrutura da página.
    JavaScript: Para a lógica de cálculo e exibição dos resultados.

⚠️ Observações

    Correção da fórmula da área: A fórmula da área está incorreta no código fornecido. O cálculo correto é:

var area = (pi * (r * r)); // Correto

Ajuste o código para garantir resultados precisos.

Uso de valores predefinidos para π:

    Se preferir evitar a entrada manual, você pode definir π no código como 3.14 ou usar o valor exato em JavaScript:

    var pi = Math.PI;

Arredondamento de resultados: Para limitar os resultados a duas casas decimais, utilize o método toFixed(2):

    perimetro.toFixed(2);
    area.toFixed(2);

📄 Licença

Este projeto é um exemplo didático e está disponível para uso e modificação livremente.
