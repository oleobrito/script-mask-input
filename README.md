Passo a Passo para Adicionar a Máscara de Telefone:
1. Usando JavaScript para Máscara de Telefone
Você pode usar a biblioteca Inputmask para adicionar a máscara ao campo de telefone. Siga as etapas abaixo para adicionar a máscara ao seu formulário de telefone no Contact Form 7.

a) Adicionar o Código JavaScript no functions.php do Tema:
Adicione o seguinte código ao arquivo functions.php do seu tema (ou tema filho) para enfileirar a biblioteca Inputmask:

<CODE SCRIPT>

Esse código faz o seguinte:

Carrega o jQuery (caso ainda não esteja carregado).
Carrega a biblioteca Inputmask.
Adiciona um script que aplica a máscara (99) 99999-9999 ao campo de telefone (input[type="tel"]).
