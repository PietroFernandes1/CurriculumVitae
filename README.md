# CurriculumVitae
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="" name="curriculum">
        
            <fieldset>
                <legend> <h2>Dados Pessoais</h2> </legend>
                    <fieldset>
                        <legend>Identificação</legend>
                            <label for="nome">Nome Completo:</label><br> 
                                <input type="text" size="90"> <br>
                            <label for="nacionalidade">Nacionalidade:</label>
                                &emsp;

                            <label for="cpf">CPF:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                                
                            <label for="npassaporte">Número do Passaporte:</label> <br>

                                <select name="nacionalidade" size="1">
                                    <option value="br">Brasileira</option>
                                    <option value="fora">Estrangeira</option>
                                </select> &emsp;
                                    <input type="text" size="12"> 
                                        &ensp;
                                    <input type="text" size="12">
                    </fieldset>

                    <fieldset>
                        <legend>Dados de Nascimento</legend>
                            <label for="">País:</label> 
                                &emsp;&emsp;&emsp;&ensp;&ensp;

                            <label for="">UF:</label> 
                                &emsp;&emsp;&emsp;&emsp;&emsp;&ensp;&emsp;

                            <label for="">Cidade:</label> 
                                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;

                            <label for="">Data:</label> <br>

                            <select name="a" size="1">
                                <option value="ar">Argentina</option>
                                <option value="ba">Bahamas</option>
                                <option value="bar">Barbados</option>
                                <option value="be">Belize</option>
                                <option value="bo">Bolívia</option>
                                <option value="br">Brasil</option>
                                <option value="ca">Canadá</option>
                                <option value="co">Colômbia</option>
                                <option value="cos">Costa Rica</option>
                                <option value="cub">Cuba</option> 
                            </select>

                            <select name="b" size="1">
                                <option value="ac">Acre</option>
                                <option value="al">Alagoas</option>
                                <option value="am">Amapá</option>
                                <option value="ama">Amazonas</option>
                                <option value="ba">Bahia</option>
                                <option value="ce">Ceará</option>
                                <option value="di">Distrito Federal</option>
                                <option value="es">Espiríto Santo</option>
                                <option value="go">Goías</option>
                                <option value="ma">Maranhão</option>
                                <option value="mat">Mato Grosso</option>
                                <option value="mi">Minas Gerais</option>
                                <option value="pa">Pará</option>
                                <option value="par">Paraíba</option>
                                <option value="para">Paraná</option>
                            </select>
                                <input type="text" size="14" maxlength="40">
                                <input type="text" size="8" maxlength="10">
                    </fieldset>

                    <fieldset>
                        <legend>Sexo</legend>
                            <input type="radio" name="sexo" value="fem">Feminino <br>
                            <input type="radio" name="sexo" value="mas">Masculino
                    </fieldset>

                    <fieldset>
                        <legend>Identidade</legend>
                            <label for="num">Número:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;

                            <label for="orgao">Órgão Emissor:</label>
                                &emsp;&emsp;&emsp;&emsp;

                            <label for="uf">UF:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&ensp;

                            <label for="data">Data:</label> <br>

                                <input type="text">
                                <input type="text" maxlength="100">
                            <select name="c" size="1">
                                <option value="ac">Acre</option>
                                <option value="al">Alagoas</option>
                                <option value="am">Amapá</option>
                                <option value="ama">Amazonas</option>
                                <option value="ba">Bahia</option>
                                <option value="ce">Ceará</option>
                                <option value="di">Distrito Federal</option>
                                <option value="es">Espiríto Santo</option>
                                <option value="go">Goías</option>
                                <option value="ma">Maranhão</option>
                                <option value="mat">Mato Grosso</option>
                                <option value="mi">Minas Gerais</option>
                                <option value="pa">Pará</option>
                                <option value="par">Paraíba</option>
                                <option value="para">Paraná</option>
                            </select>
                                <input type="text" maxlength="10">
                    
                    </fieldset>

                    <fieldset>
                        <legend>Filiação</legend>
                            <label for="nomepai">Nome do Pai:</label>
                            &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                            &emsp;&emsp;&emsp;&ensp;

                            <label for="nomemae">Nome da Mãe:</label> <br>

                            <input type="text" maxlength="32" size="40">
                            <input type="text" maxlength="32" size="40">

                    </fieldset>
            </fieldset>

            <fieldset>
                <legend> <h2>Endereço</h2> </legend>
                    <fieldset>
                        <legend>Endereço Profissional</legend>
                            <label for="end">Empresa/Instituição:</label> <br>
                            <input type="text" size="65" maxlength="100"> <br>

                            <label for="">Logradouro:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&ensp;

                            <label for="">Endereço:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;

                            <label for="">Bairro:</label> <br>
                            
                            <select name="d">
                                <option value="19">Praça 19 de Dezembro</option>
                                <option value="jap">Praça do Japão</option>
                                <option value="">Praça Rui Barbosa</option>
                                <option value="">Praça Santos Andrade</option>
                                <option value="">Praça Tiradentes</option>
                                <option value="">Praça Gabriel Martins</option>
                                <option value="">Fonte dos Mosaicos</option>
                                <option value="">Praça do Migrante</option>
                                <option value="">Praça Getúlio Vargas</option>
                                <option value="">Praça Parigot de Souza</option>
                                <option value="">Rua XV de Novembro</option>
                                <option value="">Rua Pastor David Koop</option>
                                <option value="">Avenida Paraná</option>
                                <option value="">Rua 15 de Outubro</option>
                            </select>
                            <input type="text">
                            <input type="text"> 
                                <br>

                            <label for="pais">País:</label>
                                &emsp;&emsp;&emsp;&ensp;&ensp;

                            <label for="uf">UF:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;

                            <label for="cidade">Cidade:</label>
                                &emsp;&emsp;&emsp;&nbsp;&emsp;&emsp;&emsp;
                            
                            <label for="cep">CEP:</label> <br>

                            <select name="e" size="1">
                                <option value="ar">Argentina</option>
                                <option value="ba">Bahamas</option>
                                <option value="bar">Barbados</option>
                                <option value="be">Belize</option>
                                <option value="bo">Bolívia</option>
                                <option value="br">Brasil</option>
                                <option value="ca">Canadá</option>
                                <option value="co">Colômbia</option>
                                <option value="cos">Costa Rica</option>
                                <option value="cub">Cuba</option> 
                            </select> 
                            <select name="f" size="1">
                                <option value="ac">Acre</option>
                                <option value="al">Alagoas</option>
                                <option value="am">Amapá</option>
                                <option value="ama">Amazonas</option>
                                <option value="ba">Bahia</option>
                                <option value="ce">Ceará</option>
                                <option value="di">Distrito Federal</option>
                                <option value="es">Espiríto Santo</option>
                                <option value="go">Goías</option>
                                <option value="ma">Maranhão</option>
                                <option value="mat">Mato Grosso</option>
                                <option value="mi">Minas Gerais</option>
                                <option value="pa">Pará</option>
                                <option value="par">Paraíba</option>
                                <option value="para">Paraná</option>
                            </select> 
                                &ensp;
                        
                            <inpunt type="text" maxlength="8">
                                &nbsp;
                        
                            <input type="text" maxlength="8" size="23">
                                <br>

                            <label for="ddd">DDD:</label>
                                &ensp;&nbsp;

                            <label for="fone">Fone:</label>
                                &emsp;&emsp;&emsp;&ensp;

                            <label for="ramal">Ramal:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;

                            <label for="fax">Fax:</label> <br>

                            <input type="text" size="2" maxlength="2">
                            <input type="text" maxlength="9" size="8">
                            <input type="text">
                            <input type="text" size="22"> <br>

                            <label for="home">Homepage Pessoal:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;

                            <label for="email">E-mail:</label> 
                                <br>

                            <input type="text" size="36">
                        
                            <input type="text"size="28">

                    </fieldset>

                    <fieldset>
                        <legend>Endereço Residêncial</legend>

                            <label for="">Logradouro:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&ensp;

                            <label for="">Endereço:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;

                            <label for="">Bairro:</label> <br>
                            
                            <select name="g">
                                <option value="19">Praça 19 de Dezembro</option>
                                <option value="jap">Praça do Japão</option>
                                <option value="">Praça Rui Barbosa</option>
                                <option value="">Praça Santos Andrade</option>
                                <option value="">Praça Tiradentes</option>
                                <option value="">Praça Gabriel Martins</option>
                                <option value="">Fonte dos Mosaicos</option>
                                <option value="">Praça do Migrante</option>
                                <option value="">Praça Getúlio Vargas</option>
                                <option value="">Praça Parigot de Souza</option>
                                <option value="">Rua XV de Novembro</option>
                                <option value="">Rua Pastor David Koop</option>
                                <option value="">Avenida Paraná</option>
                                <option value="">Rua 15 de Outubro</option>
                            </select>
                            <input type="text">
                            <input type="text"> <br>

                            <label for="pais">País:</label>
                                &emsp;&emsp;&emsp;&ensp;

                            <label for="uf">UF:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;

                            <label for="cidade">Cidade:</label>
                                &emsp;&emsp;&emsp;&nbsp;&emsp;&emsp;&emsp;&emsp;
                            
                            <label for="cep">CEP:</label> <br>

                            <select name="h" size="1">
                                <option value="ar">Argentina</option>
                                <option value="ba">Bahamas</option>
                                <option value="bar">Barbados</option>
                                <option value="be">Belize</option>
                                <option value="bo">Bolívia</option>
                                <option value="br">Brasil</option>
                                <option value="ca">Canadá</option>
                                <option value="co">Colômbia</option>
                                <option value="cos">Costa Rica</option>
                                <option value="cub">Cuba</option> 
                            </select> 
                            <select name="i" size="1">
                                <option value="ac">Acre</option>
                                <option value="al">Alagoas</option>
                                <option value="am">Amapá</option>
                                <option value="ama">Amazonas</option>
                                <option value="ba">Bahia</option>
                                <option value="ce">Ceará</option>
                                <option value="di">Distrito Federal</option>
                                <option value="es">Espiríto Santo</option>
                                <option value="go">Goías</option>
                                <option value="ma">Maranhão</option>
                                <option value="mat">Mato Grosso</option>
                                <option value="mi">Minas Gerais</option>
                                <option value="pa">Pará</option>
                                <option value="par">Paraíba</option>
                                <option value="para">Paraná</option>
                            </select> 
                                &ensp;
                        
                            <inpunt type="text" maxlength="8">
                                &nbsp;
                        
                            <input type="text" maxlength="8" size="23 
                                <br>

                            <label for="ddd">DDD:</label>
                                &ensp;&nbsp;

                            <label for="fone">Fone:</label>
                                &emsp;&emsp;&emsp;&ensp;

                            <label for="ramal">Ramal:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;

                            <label for="fax">Fax:</label> <br>

                            <input type="text" size="2" maxlength="2">
                            <input type="text" maxlength="9" size="8">
                            <input type="text">
                            <input type="text" size="22"> <br>

                            <label for="home">Homepage Pessoal:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;

                            <label for="email">E-mail:</label> <br>

                            <input type="text" size="36">
                            <input type="text"size="28">

                    </fieldset>

                    <fieldset>
                        <legend>Endereço Preferencial para Correspondência</legend>

                        <input type="radio" name="sexo" value="pro">Profissional
                            &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;

                        <input type="radio" name="sexo" value="res">Residêncial

                    </fieldset>
            </fieldset>

            <fieldset>
                <legend> <h2>Formação Acadêmica/Titulação</h2> </legend>
                    <fieldset>
                        <legend>Formação</legend>
                            <label for="nivel">Nível:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&ensp;

                            <label for="carga">Carga horária:</label> <br>

                                <select name="j" size="1" required>
                                    <option value="grad">Graduação</option>
                                    <option value="aper">Aperfeiçoamento</option>
                                    <option value="espe">Especialização</option>
                                    <option value="mes">Mestrado</option>
                                    <option value="dout">Doutorado</option>
                                </select>
                                <input type="text">
                    </fieldset>

                    <fieldset>
                        <legend>Instituição/Curso</legend>
                            <label for="inst">Instituição:</label>
                                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;

                            <label for="nomec">Nome do Curso:</label>
                                &emsp;&emsp;&emsp;&emsp;&nbsp;

                            <label for="tatus">Status do Curso:</label><br>

                                <input type="text" maxlength="40">
                                <input type="text" maxlength="40">
                            
                                <select name="k">
                                    <option value="">Em andamento</option>
                                    <option value="">Com título obtido</option>
                                </select> <br>

                            <label for="anoi">Ano do Iníco do Curso:</label>
                                &emsp;&ensp;&nbsp;

                            <label for="anoc">Ano da Conclusão do Curso:</label>
                                &nbsp;

                            <label for="anoo">Ano da Obtenção do Título:</label> <br>

                                <input type="text">
                                <input type="text">
                                <input type="text"> <br>

                            <label for="">Título da Monografia/Dissertação/Tese:</label>
                                &ensp;&nbsp;
                            <label for="">Nome Completo do Orientador:</label> <br>

                                <input type="text" size="29" maxlength="100">
                                    &ensp;
                                <input type="text" maxlength="32"> <br>

                            <label for="bolsa">Bolsa</label>
                                &ensp;
                            <label for="ent">Entidade Financeira</label> <br>

                                <select name="l">
                                    <option value="sim">sim</option>
                                    <option value="sim">não</option>
                                </select>
                                <input type="text">
                    </fieldset>
            </fieldset>

            <fieldset>
                <legend> <h2>Atuação Profissional</h2> </legend>
                    <fieldset>
                        <legend>Instituição de Trabalho</legend> 
                            <label for="inst">Instituição/Empresa</label>
                                &emsp;&ensp;
                            <label for="">Sigla</label> <br>

                            <input type="text">
                            <input type="text">
                    </fieldset>

                    <fieldset>
                        <legend>Atividades Exercidas na Instituição</legend>
                            <input type="checkbox">Conselhos,Comissões e Consultoria <br>
                            <input type="checkbox">Direção e Administração <br>
                            <input type="checkbox">Ensino <br>
                            <input type="checkbox">Estágio <br>
                            <input type="checkbox">Extensão Universitária <br>
                            <input type="checkbox">Pesquisa e Desenvolvimento <br>
                            <input type="checkbox">Serviços Técnicos e Especializados <br>
                            <input type="checkbox">Treinamentos Ministrados <br>
                            <input type="checkbox">Outras Atividade Técnico-Científicas <br>
                    </fieldset>

                    <fieldset>
                        <legend>Vínculo Institucional</legend>
                            <label for="per">Período</label>
                                &emsp;&emsp;&emsp;&ensp;&nbsp;

                            <label for="">Início</label>
                                &emsp;&emsp;&emsp;&ensp;

                            <label for="">Fim</label> <br>

                                <select name="m" size="1">
                                    <option value="anterior">Anterior</option>
                                    <option value="atual">Atual</option>
                                </select> 
                                    &nbsp;
                            <label for="mes">Mês</label>
                                <input type="text" size="5" maxlength="14">
                            <label for="mes">Mês</label>
                                <input type="text" size="5" maxlength="14"> <br>
                                    &emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;

                            <label for="ano">Ano</label>
                                <input type="text" size="5" maxlength="14">
                            <label for="ano">Ano</label>
                                <input type="text" size="5" maxlength="14"> <br>

                            <label for="">Tipo de Vínculo</label>
                                &emsp;&emsp;&emsp;
                            <label for="">Carga Horária Semanal</label> <br>

                                <input type="checkbox">Estágio Profissional
                                    &nbsp;
                                <input type="text"> <br>
                                <input type="checkbox">Trabalhador Autônomo <br>
                                <input type="checkbox">Empregado Doméstico <br>
                                <input type="checkbox">Trabalho Voluntário <br>
                                <input type="checkbox">Trabalho Eventual <br>
                                <input type="checkbox">Trabalhador Avulso <br>
                                <input type="checkbox">Trabalhador Temporário <br>

                    </fieldset>
            </fieldset>
                    
    

    </form>
    
</body>
</html>
