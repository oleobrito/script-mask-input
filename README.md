Script para adicionar uma máscara no campo de telefone e celular.
Máscara (99) 99999-9999 ao campo de celular ou telefone (99) 9999-9999

Instalação:
Wordpress
1. Cole o script no functions.php.
2. Valide o ID do campo telefone no formulário.
3. Substitua o atual que está no script pelo ID do campo definido no formulário.
4. Caso tenha mais de um campo ou formulários diferentes definir da seguinte forma, exemplo:
        const campos = [
            '#form-field-telefonecontato',
            '#form-field-telefonetrabalhe',
			      '#form-field-telefoneparceiro',
			      '#telefonepopup'
        ]; 
