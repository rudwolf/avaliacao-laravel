# Teste prático - Laravel

Esse teste prático visa avaliar os conhecimentos do candidato a vaga de programador PHP Laravel.

# Objetivos
  - Conhecer um pouco de suas habilidades em:
    - Laravel;
    - Entendimento e análise dos requisitos;
    - Capacidade de inovar;
    - Determinação na busca de soluções;
    - Responsabilidade na tomada de decisões.

# Fique tranquilo
  - Todo e qualquer código desenvolvido nesse teste não será utilizado em quaisquer outros softwares nem comercializados pela empresa.
  - O propósito deste teste é apenas avaliar o conhecimento em programaçao do candidato.

# Vamos lá! A aplicação é...
Criem uma aplicação utilizando Laravel, MySql e quaisquer outras tecnologias que julgar benéficas ao projeto.
A aplicação deve prover um sistema de Login e nível de acesso simples.
O administrador do sistema deverá Manter(Guardar em banco de dados) permissões e Manter(Guardar em banco de dados) usuários, cada usuário com uma ou mais permissões para a execução das seguintes tarefas:
 - Manter(Inserir/Editar/Exibir/Deletar) produtos - A tabela deve conter: id do produto(chave primaria), nome do produto (string), estoque (inteiro), preço(float), categoria a qual pertence(id de tabela externa), marca a qual pertence(id de tabela externa);
 - Manter(Inserir/Editar/Exibir/Deletar) categorias - A tabela deve conter: id da categoria(chave primaria) e nome da categoria(string);
 - Manter(Inserir/Editar/Exibir/Deletar) marcas - A tabela deve conter: id da marca(chave primaria) e nome da marca(string).
	
Crie uma tela principal com um menu para cada área contendo o CRUD de cada tabela;
- Não é necessário CRUDs de usuário porém os usuários comuns devem apenas poder consultar (exibir os produtos) e apenas os administradores podem criar/editar e excluir usuários ou quaisquer outros itens.

### Sobre os usuários
- Administrador (Acesso total);
- Comum (Apenas exibir/consultar produtos)

### Requisitos
- Usar Laravel (Última versão estável);
- Usar banco de dados Mysql;
- Usar migrations para criação das tabelas quando necessário, ou exportar o arquivo SQL com a estrutura criada.
- Usar o github ou gitlab;
- Explicar de forma breve como instalar e rodar o projeto.
- No demais fique a vontade para utilizar todos os seus conhecimentos e técnicas possíveis.

### Para participar basta...
- Construir a aplicação solicitada;
- Enviar para nós o link do projeto no github ou bitbucket;

Fique a vontade para entrar em contato conosco se você tenha alguma dúvida ou assim que terminar a aplicação.

# Encontre o Erro

O código abaixo feito em PHP e Laravel contém um erro, você deve encontrá-lo e dizer por que o código abaixo não irá funcionar.

    <?php
    use Psr\Log\LoggerService; // Esta é a classe do serviço de Log

    class Worker {
      protected $logger;
     
      public function __construct(Psr\Log\LoggerInterface $logger) {
        $this->logger = $logger;
      }
      public function log($error) {
        $this->logger->service = new ServiceLog(); // Criando instância do serviço de Log...
        $this->logger->service->log($error);
      }
    } ?>
    
Identifique em qual linha se encontra o erro. Onde é iniciado o código `<?php` é a linha 1.
