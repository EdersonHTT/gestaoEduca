# Sitema de Gestão Escolar

## Requisitos Funciomais:

- RF1. O sistema deve permitir o cadastro de professores e de matriculas de alunos pela parte da gestao escolar;

- RF2. O sistema deve permitir dar notas aos alunos(Aplicação de notas de cada trimestre);

- RF3. O sistema deve deixar todos os alunos com presença e então permitir dar faltas;

- RF4. O sistema deve permitir o gerenciamento de matriculas(Cancelar e etc);

- RF5. O sistema deve permitir que os alunos possam visualizar as notas e a frequência;

- RF6. O sistema deve alertar os alunos se sua frequência estar abaixo da media escolar;

- RNF7. Um mural de avisos para os alunos, onde apenas os professores poderão fazer postagens;

- RNF8. Sistema de chat privado entre aluno e professor;

- RF9. Após fazer login o usuario deve completar um captcha apenas para uma verificação basica, para evitar um ataque DDOS;

- RF10. O sistema deve ter um boletim do aluno, apenas sera gerado no final do trimestre ou bimestre. Mostrando frequência, nota media, anual, e nota final;

- RF11. O sistema deve ter um Historico do aluno (Suspenções, Advertencias) com motivo de cada Suspenção ou Advertencia;

- RF12. O sistema deve ter uma Hata onde armazena os atestados dos alunos que faltaram com justificativa(deve ser reiniciado a cada trimestre ou bimestre);

- RF13. O sistema deve ter um portal do estudante e professores (Na hora de login sera possivel a escolha entre "aluno ou professor").

## Requisitos Não Funciomais:

- RNF1. O sistema deve garantir que em caso de erro de formulário o sistema salve o progresso de dar notas;

- RNF2. O sistema deve ser intuitivo e rapido para poder dar faltas aos alunos;

- RNF3. O sistema deve ser uma aplicação para dispositivos moveis(aplicativo), desktop e web;

- RNF4. O gerenciamento das matriculas deve ser por desktop ou web;

- RNF5. O aplicativo voltado para os professores dar falta e notas e os alunos de visualizá-las;

- RNF6. Compatibilidade (deve funcianar bem em qualquer dispositivo);

- RNF7. Segurança de ponta (todos os dados são criptografados);

- RNF8. Capacidade de fazer manutenções;

- RNF9. Suporte com uma IA que possa ajudar caso haja alguma duvida dentro do aplicativo;

- RNF10. Desempenho (cumpre com as tarefas de forma estável e sem erros);

- RNF11. Comunicação com os pais e alunos;

- RNF12. Garantir que o sistema funcione de forma consistente e correta.

## Regras de Negócio do Sistema de Gestão Escolar:

- Os usuários devem acessar o sistema com login, com email(dependendo do portal escolhido: professor ou aluno), senha e CPF;

- Apenas o professor e a gestão da escola podem dar notas, faltas e editar o boletim dos alunos. Os alunos apenas podem visualizar notas, faltas e boletim;

- Apena a gestão escolar tem acesso e gerencia as matriculas;

- A gestão escolar gerencia as permições dos professores e alunos; 

- O login do aluno só sera liberado após algum responsavel da gestão escolar o matricular no sistema. Assim gerando um Email; "nomedoaluno-id@aluno**.***";

- O login dos professores também sera liberado pela gestão escolar, gerando um email como de exemplo "nomedoprofessor-id@professor**.*** ";

- O sistema deve verificar se o usuário já está cadastrado antes de permitir um novo cadastro;

- A recuperação de senha deve ser por meio do CPF ou pela gestão escolar;

- O sistema deve notificar o email do usuario para logins feitos em outros dispositivos.
