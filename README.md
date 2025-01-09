GitHub API Integration
Este projeto utiliza a GitHub API para buscar informações sobre usuários e exibir detalhes como repositórios e seguidores em uma tabela dinâmica. Ele permite que você procure por usuários do GitHub e veja as informações relacionadas a eles de forma interativa, sem a necessidade de recarregar a página.

Funcionalidades
Busca de usuário: Permite procurar um usuário do GitHub digitando o nome de usuário no campo de pesquisa.
Exibição de informações: Exibe o avatar, nome, nome de usuário, número de repositórios e seguidores do usuário.
Tabela dinâmica: A tabela é atualizada dinamicamente com os dados do usuário, incluindo a possibilidade de remover o usuário da lista clicando no ícone de remover.
Integração com a GitHub API: Utiliza a GitHub API para buscar os dados do usuário.
Estrutura do Projeto
A estrutura do projeto é a seguinte:

bash
Copiar código
/gitAPI
│
├── /css
│   └── style.css
│
├── index.html
└── README.md
style.css: Contém os estilos para a interface da aplicação.
index.html: Contém a estrutura HTML da página, incluindo a tabela e o campo de busca.
README.md: Documento de instruções e descrição do projeto.
Como Funciona
O usuário insere o nome de usuário do GitHub no campo de pesquisa e clica no botão "Procurar".
O JavaScript faz uma requisição para a GitHub API para buscar as informações do usuário.
Os dados retornados da API são exibidos em uma tabela dinâmica, incluindo o avatar, nome, login, número de repositórios e seguidores.
A tabela pode ter múltiplos usuários adicionados, e cada linha possui um botão de remover que permite excluir o usuário da tabela.
Em caso de erro na requisição ou na ausência do usuário, a aplicação exibe um alerta para o usuário.
Como Rodar o Projeto
Para rodar o projeto localmente, siga os seguintes passos:

Clone o repositório para sua máquina local:

bash
Copiar código
git clone https://github.com/seu-usuario/gitAPI.git
Acesse a pasta do projeto:

bash
Copiar código
cd gitAPI
Abra o arquivo index.html no seu navegador:

bash
Copiar código
open index.html
A aplicação será carregada, e você poderá começar a buscar usuários do GitHub!

Dependências
Este projeto não utiliza dependências externas, exceto a GitHub API para busca de informações sobre os usuários.

Contribuições
Se você quiser contribuir para o projeto, fique à vontade para fazer um fork, criar uma branch e enviar um pull request. Qualquer melhoria ou correção será bem-vinda!

Licença
Este projeto é de código aberto e distribuído sob a licença MIT. Veja o arquivo LICENSE para mais informações.

![image]



![image](https://github.com/user-attachments/assets/6cc44c12-0a82-4850-8674-e29b60016300)
