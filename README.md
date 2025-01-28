Recebi a seguinte missão, realizar cinco testes diferentes em um código de formulário. O primeiro teste foi de verificar o carregamento da página estava correto e com os elementos visuais estáveis, para a realização desse, fiz o seguinte processo: describe('Cadastro', () => {
    it('acessar site',() => {
        cy.visit('../cypress/fixtures/FormCadastro/index.html');
        cy.wait(1000)
    })

O segundo teste era para ver se a mensagem de erro aparecia quando o usuário não preenchia todos os campos.

O terceiro era para ver se o cadastro apareceria na lista dinâmica.

O quarto era para ver se o site evita a duplicação de cadastros.

O quinto era para ver se o botão "limpar" apagaria a lista de cadastros.
