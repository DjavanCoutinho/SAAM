# SAAM

Activity Login (Paciente/Médico) -- LoginActivity.java

Activity AlterarSenha(Paciente/Médico) --- AlterarSenhaActivity.java

Activity cadastro basico (ao criar conta) - dados pessoais, endereço, etc --- CadastroActivity.java

--------------------------------- Paciente ---------------------------------

Activity tela principal (Paciente) - Menu --- MainActivity.java

Activity Cadastro paciente (visualização/edição) {obs: foto não editavel pelo paciente} --- CadastroDadosPessoaisActivity.java

Activity Meus exames (sub menu - ao clicar exibe exames de determinado tipo de exame) --- MeusExamesActivity.java

Activity Minhas Consultas (1ª tela de filtro, 2ª tela resultado busca) --- CadastroEnderecoActivity.java {MinhasConsultasActivity.java}

Activity Informações complementares (seríes de perguntas com radio buttom de sim ou não e com justificativa) --- PerfilActivity.java {InfoComplementares.java}

--------------------------------- Médico ---------------------------------

Activity tela principal (Medico) - Menu --- MainActivity.java

Activity Cadastro medico (visualização/edição) {acesso total} --- CadastroDadosPessoaisActivity.java

Activity Consultas

1ª tela com informações do médico com 4 botões (inserir foto paciente, inserir prontuário, inserir exames, visualizar prontuário) InicioActivity.java

2ª tela (clique primeiro botão) barra pesquisa {cpf/nome}, após pesquisa exibe campo foto para incluir e nome paciente ConsultaPacienteDadosActivity.java

3ª tela (clique segundo botão ) barra pesquisa {cpf/nome}, após pesquisa exibe campo para inserir prontuário paciente ConsultaPacienteProntuarioActivity.java

3ª tela (clique terceiro botão ) barra pesquisa {cpf/nome}, após pesquisa vai aparecer um botão para inserir foto dos exames do paciente ConsultaPacientoFotoExamesActivity.java

4ª tela (clique quarto botão ) barra pesquisa {cpf/nome}, após pesquisa exibe os relatórios realizados do paciente ConsultaPacienteRelatorioActivity.java
