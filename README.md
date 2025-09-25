# Sistema de Gestão de Ordens de Serviço

## Nome do Aplicativo
OS Manager – Sistema de Ordens de Serviço

## Problema
Dificuldade no controle e acompanhamento das Ordens de Serviço (OS), falta de centralização de informações e comunicação ineficiente entre administradores e colaboradores.

## Solução
Aplicativo que centraliza a gestão de OS, permitindo criação, edição, acompanhamento de status em tempo real e gerenciamento de usuários.

## Utilidade
Facilita o dia a dia de empresas e colaboradores, melhora a organização, aumenta a produtividade e reduz falhas de comunicação.

## Justificativa Pessoal
Útil no dia a dia de trabalho por garantir controle das OS, clareza das tarefas e eficiência na comunicação entre a equipe.

## Funcionalidades
- Autenticação e Usuários: login, cadastro de usuários pelo administrador, recuperação de senha via administrador, edição de perfil.
- Ordens de Serviço: criar OS, acompanhar status (abertas, em andamento, concluídas).
- Outras funcionalidades: onboarding, logout, interface simples e responsiva.

## Fluxo do Usuário
1. Primeiro acesso: telas de apresentação.
2. Login com credenciais fornecidas pelo administrador.
3. Recuperação de senha apenas pelo administrador.
4. Uso: visualização e registro de OS.
5. Perfil: editar dados, ver notificações e contatos.
6. Configurações (administrador): gerenciar usuários e acessos.

## Protótipo (Telas)
- Tela de Login.
- Tela de Ordens de Serviço.
- Tela de Perfil.

## Dados da API – DER
**Tabelas:**
- Usuário (id_usuario, nome, email, senha, perfil, endereco, foto)
- OrdemServico (id_os, numero_os, cidade, bairro, rua, data_os, descricao, status)
- ColaboradorOS (id_colaborador, id_os, id_usuario)

**Relações:**
- Um usuário pode estar em várias OS.
- Uma OS pode ter vários colaboradores.
- Administrador pode criar e editar usuários e OS.
