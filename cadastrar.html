<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro de Paciente</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>
    <div class="container">
        <h2>Cadastro de Paciente</h2>
        <form id="cadastroForm">
            <div class="form-group">
                <label for="nome">Nome Completo</label>
                <input type="text" class="form-control" id="nome" required>
            </div>
            <div class="form-group">
                <label for="dataNascimento">Data de Nascimento</label>
                <input type="date" class="form-control" id="dataNascimento" required>
            </div>
            <div class="form-group">
                <label for="email">E-mail</label>
                <input type="email" class="form-control" id="email" required>
            </div>
            <div class="form-group">
                <label for="telefone">Telefone</label>
                <input type="text" class="form-control" id="telefone" required pattern="\d{10,11}">
            </div>
            <div class="form-group">
                <label for="endereco">Endereço</label>
                <input type="text" class="form-control" id="endereco" required>
            </div>
            <div class="form-group">
                <label for="sexo">Sexo</label>
                <select class="form-control" id="sexo" required>
                    <option value="" disabled selected>Selecione...</option>
                    <option value="masculino">Masculino</option>
                    <option value="feminino">Feminino</option>
                    <option value="outro">Outro</option>
                </select>
            </div>
            <button type="submit" class="btn btn-primary">Cadastrar</button>
        </form>
        <div id="feedback" class="mt-3"></div>
    </div>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script>
        $('#cadastroForm').on('submit', function(event) {
            event.preventDefault();
            // Validações
            const nome = $('#nome').val().trim();
            const dataNascimento = new Date($('#dataNascimento').val());
            const hoje = new Date();
            const idade = hoje.getFullYear() - dataNascimento.getFullYear();
            const meses = hoje.getMonth() - dataNascimento.getMonth();
            const maiorIdade = idade > 18 || (idade === 18 && meses >= 0);
            const email = $('#email').val().trim();
            const telefone = $('#telefone').val().trim();
            
            if (!nome || !maiorIdade || !validateEmail(email) || !validatePhone(telefone)) {
                $('#feedback').text('Erro: Verifique os dados fornecidos.').addClass('alert alert-danger');
            } else {
                $('#feedback').text('Cadastro realizado com sucesso!').addClass('alert alert-success');
                // Aqui você pode enviar os dados para o backend (AJAX ou fetch)
            }
        });

        function validateEmail(email) {
            const re = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            return re.test(email);
        }

        function validatePhone(phone) {
            return /^\d{10,11}$/.test(phone);
        }
    </script>
</body>
</html>
