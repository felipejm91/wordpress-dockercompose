<!DOCTYPE html>
<html>
    <head></head>
    <div id="cabeçalho">
        <h1>WORDPRESS DOCKER COMPOSE</h1>
            <p>Repositorio com arquivos YAML para deploy de uma aplicação Wordpress utilizando Docker Compose</p>    
    </div>
    <div id="descricao">
        <h2>DESCRIÇÃO DOS ARQUIVOS</h2>
            <p>Os arquivos estão separados da seguinte maneira</p>
        <b>docker-compose.yaml</b>
            <p>Arquivo com a descrição do ambiente docker que será utilizado, informando a rede, volumes e containers.</p>
        <b>mysql.env</b>
            <p>Onde é configurado os environments necessários para execução do container do MySQL.</p>
        <b>wordpress.env</b>
            <p>Onde é configurado os environments necessários para execução do container do Wordpress.</p>
    </div>
    <div id="comandos">
        <h2>EXECUÇÃO DO AMBIENTE</h2>
        <p><b>OBS: Caso o ambiente for utilizado para algum projeto wordpress existente, faça download dos arquivos do projeto em uma pasta junto com os arquivos do docker compose, antes de executar os comandos abaixo. Caso seja utilizado um ambiente novo, basta seguir os passos a seguir.</b></p>
        <h3><b>PASSOS PARA EXECUÇÃO DO AMBIENTE</b></h3>
            <ol>
                <li>Faça download dos arquivos do repositório</li>
                <li>Edite os arquivos docker-compose.yaml, mysql.env e wordpress.env de acordo com sua necessidade, informando nome dos volumes e versões dos containers.</li>
                <li>Execute o comando:</li>
                <code>docker compose up -d</code>
            </ol>            
    </div>
</html>
