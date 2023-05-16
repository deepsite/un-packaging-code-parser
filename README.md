# UN Packaging Code Parser

This Python-based project provides a robust tool for parsing United Nations (UN) packaging codes, which are utilized worldwide for the safe transportation and handling of hazardous materials. Our software takes in a UN packaging code and breaks it down into its constituent parts, providing the user with detailed information about the packaging and its contents.
## Features

- Parse UN packaging codes into their component parts.
- Provide detailed information about the chemical and physical characteristics of the materials, as identified by the UN code.
- Identify the packaging type (e.g., drums, jerricans) from the UN code.
- Display whether the packaging has passed UN packaging testing, as indicated by the code.


## Usage

```python

from un_packaging_code_parser import UNCodeParser

code = 'UN 1A1/Y1.2/100/21/USA/M4995'
parser = UNCodeParser()

# Parse UN packaging code
parsed_code = parser.parse(code)

print(parsed_code)
```

This will output a dictionary containing the parsed elements of the UN packaging code.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you have any questions or run into any problems, please open an issue on GitHub. We will do our best to assist you.

## Disclaimer

This tool is intended to assist in understanding UN packaging codes. It is the user's responsibility to ensure they are following all relevant safety procedures and regulations when handling hazardous materials. This tool does not absolve the user of that responsibility.

## Acknowledgments

We are grateful to the numerous contributors who made this project possible. Your efforts are highly appreciated.
