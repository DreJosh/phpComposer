# phpComposer

Aqui criamos um caminho para realizar o autoload da classe com o composer
`"Belmo\\BuscadorDeCursos\\": "src/"`

### Classmap

O Composer lê o arquivo que definimos no classmap e mapeia as classes dentro dele para sempre executar um require quando elas forem acessadas. Com isso, já resolvemos o problema de classes que não implementem a PSR4, por exemplo - inclusive problemas maiores, como arquivos que contêm mais de uma classe ou nos quais o nome da classe não é igual ao nome do arquivo.

### PHPUnit

Para instalar o PHPUnit é preciso rodar o seguinte parametro.
`composer require --dev phpunit/phpunit`
Quando colocamos um --dev na frente estamos falando que queremos que instale só para desenvolvimento, quando não queremos instalar no dev colocamos um --no-dev.
