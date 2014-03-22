Demo-Menu-Bootstrap
===================

Demo simples para o Carlos verificar a utilização da classe "active" em menus utilizando o Bootstrap.

Basicamente é assim:

- Crie itens de listas (li) com id's.
- Em seus arquivos js ou no próprio editor do cshtml (de preferência Razor Emoji), adicione um seção de script e via jquery adicione a classe responsável do Bootstrap (active):

@section scripts {
    <script>
        $(function () {
            //Aqui q está o segredo! -> olhe no _Layout.cshtml o li li-mnu-Home
            $("#li-mnu-Home").addClass("active");
        });
    </script>
}

By ©FabianoNalin.net.br
