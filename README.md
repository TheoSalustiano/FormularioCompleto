# FormularioCompleto

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario Completo</title>
</head>
<body>
    <main>
        <h2>Entre em contato</h2>
        <p>Por favor, preencha o formulario abaixo para entrar em contato conosco</p>
        <form action="">
            <fieldset>
                <legend> Informações Pessoais</legend>
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>
            <br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            <br>
                <label for="telefone">Telefone:<label>
                <input type="tel" id="telefone" name="telefone">
            <br> 
            </fieldset>  
            <fieldset> 
                <legend>Selecione o Tópico</legend>
                <label for="assunto">Assunto</label>
                <select name="assunto" id="assunto">
                <option value="Portal do Aluno">Portal do Aluno</option>
                <option value="Matricula">Matricula</option>
                <option value="Blackboard">Blackboard</option>
                <option value="Outros">Outros</option>
                </select>
            </fieldset>  
            <fieldset>
                <legend>Escreva uma Mensagem</legend>
                <label for="Mensagem">Mensagem</label>
                <textarea id="Mensagem" name="Mensagem" rows="4" cols="50" required></textarea>
            </fieldset>
            <fieldset>
                <legend>Preferência De Contato</legend>
                <input type="radio" id="contato_email" name="preferencia_contato" value="email">
                <label for="contato_email">Email</label>
                <input type="radio" id="contato_telefone" name="preferencia_contato" value="telefone">
                <label for="contato_telefone">Telefone</label>
            </fieldset>
            <fieldset>
                <legend>Escolha o Campus</legend>
                <label for="onde_encontrou">Campus</label>
                <input type="text" id="onde_encontrou" name="onde_encontrou" list="Campus">
                <datalist id="Campus">
                    <option value="Analia Franco">Analia Franco</option>>
                    <option value="Guarulhos">Guarulhos</option>>
                    <option value="Liberdade">Liberdade</option>>
                    <option value="Paulista">Paulista</option>>
                    <option value="Santo Amaro">Santo Amaro</option>>
                    <option value="São Miguel">São Miguel</option>>
                    <option value="Villa-Lobos">Villa-Lobos</option>>
                </datalist>
            </fieldset>
            <fieldset>
                    <legend>Opções Adicionais</legend>
                    <input type="checkbox" id="newsletter" name="Opções" value="newsletter">
                    <label for="newsletter">Eu aceito receber newsletter</label>
            <br>
                    <input type="checkbox" id="promoções" name="Opções" value="promoções">
                    <label for="promoções">Eu aceito receber promoções por E-mail</label>
            <br>
                    <input type="checkbox" id="novidade" name="Opções" value="novidade">
                    <label for="novidade">Eu aceito receber novidades sobre eventos e cursos</label>
            <br>
                    <input type="checkbox" id="termos" name="Opções" required>
                    <label for="termos">Eu aceito os termos e condições</label>
             </fieldset>
             <fieldset>
                    <legend>Seleção de Período</legend>
                    <label for="datemax">Entre com uma data antes de 1980/12/31</label>
                    <input type="date" id="datemax" name="datemax" max="1979-12-31">
            <br>
                    <label for="datemin">Entre com uma data após de 2000/12/31</label>
                    <input type="date" id="datemin" name="datemin" min="2000-12-31">
            <br>
                    <label for="quantity">Quantity (between 1 and 5)</label>
                    <input type="number" id="quantity" name="quantity" min="1" max="5">
             </fieldset>
             <input type="submit">
        </form>
    </main>   
</body>
</html>