# API REST com PHP
Criação e consumo de API REST com PHP, padrão PSR-4. A API tem função de intermediar a comunicação do banco de dados com o sistema, utilizando protocolo de comunicação HTTP (XML/JSON). O exemplo foi desenvolvido sem utilização de routes e o conceito de services, ao invés de controller (Somente nomeclatura difrente)

## Pré-requisitos
- LAMPP executando
- Composer (https://getcomposer.org/download)
- Módulo Apache Rewrite (Ver se ativado)

## Passo a Passo
1. Criar diretórios App/Models, App/Services, public_html/.htaccess, public_html/index.php, composer.json, config.php
2. No diretório do projeto, executar 'composer update', onde os arquivos de configurações serão criados
3. Executar banco de dados, seguindo os dados no config.php