Criando o Banco de Dados:

CREATE DATABASE \`Exame_PI_Guilherme\` /\*!40100 COLLATE
\'utf8mb4_0900_ai_ci\' \*/;

Criando a tabela Clientes:

CREATE TABLE \`Clientes\` ( \`id_cliente\` INT(10) NOT NULL
AUTO_INCREMENT, \`nome\` VARCHAR(255) NOT NULL COLLATE
\'utf8mb4_0900_ai_ci\', \`endereco\` VARCHAR(255) NOT NULL COLLATE
\'utf8mb4_0900_ai_ci\', \`telefone\` INT(10) NOT NULL, \`email\`
VARCHAR(255) NOT NULL COLLATE \'utf8mb4_0900_ai_ci\', PRIMARY KEY
(\`id_cliente\`) USING BTREE ) COLLATE=\'utf8mb4_0900_ai_ci\'
ENGINE=InnoDB ROW_FORMAT=DYNAMIC AUTO_INCREMENT=32 ;

Criando a tabela Produtos:

CREATE TABLE \`Produtos\` ( \`id_produto\` INT(10) NOT NULL
AUTO_INCREMENT, \`nome\` VARCHAR(100) NULL DEFAULT NULL COLLATE
\'utf8mb4_0900_ai_ci\', \`preco\` DECIMAL(20,6) NULL DEFAULT NULL,
\`descricao\` VARCHAR(255) NOT NULL COLLATE \'utf8mb4_0900_ai_ci\',
PRIMARY KEY (\`id_produto\`) USING BTREE )
COLLATE=\'utf8mb4_0900_ai_ci\' ENGINE=InnoDB ROW_FORMAT=DYNAMIC
AUTO_INCREMENT=21 ;

Inserindo os clientes:

INSERT INTO \`Exame_PI_Guilherme\`.\`Clientes\` (\`id_cliente\`,
\`nome\`, \`endereco\`, \`telefone\`, \`email\`) VALUES (1, \'Carlos
Silva\', \'Rua das Flores\', 987654321, \'carlos.silva@hotmail.com\');
INSERT INTO \`Exame_PI_Guilherme\`.\`Clientes\` (\`id_cliente\`,
\`nome\`, \`endereco\`, \`telefone\`, \`email\`) VALUES (2, \'Ana
Santos\', \'Avenida dos Sonhos\', 912345678,
\'ana.santos@hotmail.com\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Clientes\` (\`id_cliente\`, \`nome\`,
\`endereco\`, \`telefone\`, \`email\`) VALUES (3, \'Felipe Oliveira\',
\'Travessa das Estrelas\', 923456789, \'felipe.oliveira@hotmail.com\');
INSERT INTO \`Exame_PI_Guilherme\`.\`Clientes\` (\`id_cliente\`,
\`nome\`, \`endereco\`, \`telefone\`, \`email\`) VALUES (4, \'Gabriela
Souza\', \'Rua das Palmeiras\', 934567890,
\'gabriela.souza@hotmail.com\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Clientes\` (\`id_cliente\`, \`nome\`,
\`endereco\`, \`telefone\`, \`email\`) VALUES (5, \'Thiago Santos\',
\'Avenida das Águas\', 945678901, \'thiago.santos@hotmail.com\'); INSERT
INTO \`Exame_PI_Guilherme\`.\`Clientes\` (\`id_cliente\`, \`nome\`,
\`endereco\`, \`telefone\`, \`email\`) VALUES (6, \'Maria Lima\', \'Rua
das Oliveiras\', 956789012, \'maria.lima@hotmail.com\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Clientes\` (\`id_cliente\`, \`nome\`,
\`endereco\`, \`telefone\`, \`email\`) VALUES (7, \'Lucas Fernandes\',
\'Avenida dos Coqueiros\', 967890123, \'lucas.fernandes@hotmail.com\');
INSERT INTO \`Exame_PI_Guilherme\`.\`Clientes\` (\`id_cliente\`,
\`nome\`, \`endereco\`, \`telefone\`, \`email\`) VALUES (8, \'Beatriz
Santos\', \'Rua das Flores\', 978901234,
\'beatriz.santos@hotmail.com\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Clientes\` (\`id_cliente\`, \`nome\`,
\`endereco\`, \`telefone\`, \`email\`) VALUES (9, \'Pedro Almeida\',
\'Avenida dos Sonhos\', 990123456, \'pedro.almeida@hotmail.com\');
INSERT INTO \`Exame_PI_Guilherme\`.\`Clientes\` (\`id_cliente\`,
\`nome\`, \`endereco\`, \`telefone\`, \`email\`) VALUES (10, \'Laura
Barbosa\', \'Rua das Palmeiras\', 901234567,
\'laura.barbosa@hotmail.com\');

Inserindo os Produtos:

INSERT INTO \`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`,
\`nome\`, \`preco\`, \`descricao\`) VALUES (1, \'Ração Premium\', 59.9,
\'Ração premium de alta qualidade\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (2, \'Brinquedo Interativo\', 19.9,
\'Brinquedo interativo para gatos\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (3, \'Shampoo Hipoalergênico\', 34.9,
\'Shampoo hipoalergênico suave e de alta qualidade\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (4, \'Coleira Antipulgas e
Carrapatos\', 49.9, \'Coleira eficaz no combate a pulgas e
carrapatos\'); INSERT INTO \`Exame_PI_Guilherme\`.\`Produtos\`
(\`id_produto\`, \`nome\`, \`preco\`, \`descricao\`) VALUES (5, \'Cama
Macia e Confortável\', 89.9, \'Cama aconchegante e confortável\');
INSERT INTO \`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`,
\`nome\`, \`preco\`, \`descricao\`) VALUES (6, \'Petisco Dental para
Cães\', 12.9, \'Petisco dental delicioso e saudável para cães\'); INSERT
INTO \`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (7, \'Arranhador para Gatos\', 79.9,
\'Arranhador resistente e durável\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (8, \'Comedouro Automático\', 149.9,
\'Comedouro automático programável\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (9, \'Brinquedo de Pelúcia com Apito\',
14.9, \'Brinquedo de pelúcia divertido e seguro para cães\'); INSERT
INTO \`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (10, \'Areia Sanitária\', 29.9, \'Areia
sanitária de alta qualidade\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (11, \'Osso de Couro Natural\', 9.99,
\'Osso de couro 100% natural para cães\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (12, \'Ração Especial\', 79.9, \'Ração
desenvolvida especialmente para cães idosos\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (13, \'Bebedouro Automático\', 49.9,
\'Bebedouro automático com sistema de fluxo constante de água fresca\');
INSERT INTO \`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`,
\`nome\`, \`preco\`, \`descricao\`) VALUES (14, \'Guia Retrátil\', 59.9,
\'Guia retrátil resistente e segura\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (15, \'Shampoo de Espuma Seca\', 24.9,
\'Shampoo em espuma seca\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (16, \'Comedouro Lento\', 39.9,
\'Comedouro com design especial que desacelera a alimentação do seu
cão\'); INSERT INTO \`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`,
\`nome\`, \`preco\`, \`descricao\`) VALUES (17, \'Creme Dental\', 19.9,
\'Creme dental com sabor agradável e formulação segura\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (18, \'Cama Refrescante\', 129.9,
\'Cama refrescante e autorefrigerante\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (19, \'Coleira de Identificação
Personalizada\', 19.9, \'Coleira de identificação personalizada com nome
e telefone do seu pet\'); INSERT INTO
\`Exame_PI_Guilherme\`.\`Produtos\` (\`id_produto\`, \`nome\`,
\`preco\`, \`descricao\`) VALUES (20, \'Brinquedo Mordedor\', 16.9,
\'Brinquedo mordedor resistente\');

Se quiser selecionar um cliente ou um produto por exemplo:

SELECT \`id_cliente\`, \`nome\`, \`endereco\`, \`telefone\`, \`email\`
FROM \`Exame_PI_Guilherme\`, \`Clientes\` WHERE \`id_cliente\`= 1;
SELECT \`id_cliente\`, \`nome\`, \`endereco\`, \`telefone\`, \`email\`
FROM \`Exame_PI_Guilherme\`, \`Clientes\` WHERE \`id_cliente\`= 2;
SELECT \`id_cliente\`, \`nome\`, \`endereco\`, \`telefone\`, \`email\`
FROM \`Exame_PI_Guilherme\`, \`Clientes\` WHERE \`id_cliente\`= 3;
SELECT \`id_cliente\`, \`nome\`, \`endereco\`, \`telefone\`, \`email\`
FROM \`Exame_PI_Guilherme\`, \`Clientes\` WHERE \`id_cliente\`= 4;
SELECT \`id_cliente\`, \`nome\`, \`endereco\`, \`telefone\`, \`email\`
FROM \`Exame_PI_Guilherme\`, \`Clientes\` WHERE \`id_cliente\`= 5;
SELECT \`id_cliente\`, \`nome\`, \`endereco\`, \`telefone\`, \`email\`
FROM \`Exame_PI_Guilherme\`, \`Clientes\` WHERE \`id_cliente\`= 6;
SELECT \`id_cliente\`, \`nome\`, \`endereco\`, \`telefone\`, \`email\`
FROM \`Exame_PI_Guilherme\`, \`Clientes\` WHERE \`id_cliente\`= 7;
SELECT \`id_cliente\`, \`nome\`, \`endereco\`, \`telefone\`, \`email\`
FROM \`Exame_PI_Guilherme\`, \`Clientes\` WHERE \`id_cliente\`= 8;
SELECT \`id_cliente\`, \`nome\`, \`endereco\`, \`telefone\`, \`email\`
FROM \`Exame_PI_Guilherme\`, \`Clientes\` WHERE \`id_cliente\`= 9;
SELECT \`id_cliente\`, \`nome\`, \`endereco\`, \`telefone\`, \`email\`
FROM \`Exame_PI_Guilherme\`, \`Clientes\` WHERE \`id_cliente\`= 10;

ou

SELECT \`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 1; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 2; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 3; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 4; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 5; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 6; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 7; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 8; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 9; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 10; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 11; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 12; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 13; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 14; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 15; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 16; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 17; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 18; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 19; SELECT
\`id_produto\`, \`nome\`, \`preco\`, \`descricao\` FROM
\`Exame_PI_Guilherme\`, \`Produtos\` WHERE \`id_produto\`= 20;
