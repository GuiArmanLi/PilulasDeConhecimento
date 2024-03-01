<div>
    <div>
        <h2  style="text-align:center;">Como funciona um Commit</h2>
        <p>O processo de levar pastas e arquivos para o repositório local acontece em 3 etapas, representadas na imagem abaixo:</p>
        <img src="assets\img/gitCommit.png" alt="Git Commit" style="width:100%"/>
        <p>A primeira parte, em laranja, representa <strong>pastas e arquivos no computador do desenvolvedor</strong>, onde ele as criou, alterou ou as deletou. Para enviar para a etapa seguinte, basta utilizar <code>git add</code>.</p>
        <p>A segunda parte, em amarelo, representa algo chamado <strong>Área de Teste ou Índice</strong>. É uma área intermediária onde os commits podem ser formatados e revisados antes de serem concluídos. Para enviar para a etapa seguinte, basta utilizar <code>git commit -m ""</code> ou <code>git commit -am ""</code> para enviar o commit da primeira etapa até a terceira.</p>
        <p>Por fim, na terceira parte, em azul, representa o repositório local, Git. Lugar onde são armazenados, de forma cronológica, os commits do desenvolvedor.</p>
        <ul style="text-align:center; list-style-type: none;">
            <li>&#128193; Working Directory = Pasta de Trabalho
            <li>&#9888; Staging Area = Área de Teste
            <li>&#9745; Repository = Repositório
        </ul>
    <div>
</div>