# punigen
PHPUnit Test Generator: A Symfony MakerBundle extension to automatically generate test files for all functions of each PHP classes in each folders (namespaces), streamlining the testing process.

## Requirements

- PHP 8.0 or higher
- Symfony 6.0 or higher
- Symfony MakerBundle

## Installation with Composer
`
composer require kin-jacques/punigen --dev
`

## Usage
PuniGen extends the Symfony MakerBundle to provide commands for automatically generating test files for your PHP classes.

## Basic Usage
```

# Generate test files for all functions of all classes in the src directory  
php bin/console make:test-case

# Generate test files for a specific class
php bin/console make:test-case App\\Service\\ExampleService

# Generate test files for a specific function
php bin/console make:test-case App\\Service\\ExampleService --functions=exampleMethod

```
## Feature Roadmap
- Support for Symfony 7
- Integration with PHPStan/Psalm for more intelligent test generation
- Custom assertions generation based on method return types
- Test data generators for complex types


## Contributing
Contributions are welcome!  
Please feel free to submit a Pull Request.

- Fork the repository
- Create your feature branch (git checkout -b feature/amazing-feature)
- Commit your changes (git commit -m 'Add some amazing feature')
- Push to the branch (git push origin feature/amazing-feature)
- Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Kinton JACQUES - [Github](https://github.com/kin-jacques)
