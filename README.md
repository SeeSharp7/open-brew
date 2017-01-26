# Open-Brew
Let's design an international json-based standard format, used for exchange and automation of beer brewing recipes

The beer brewing scene changes. Since the craftbeer revolution came along, brewing beer became a popular sport again. Everyone has the ability to brew a custom beer. Everyone can make experiences and develop own recipes. And that's great. But the distribution of these recipes is a disaster. There are so much cool projects (such as [craftbeerpi](https://github.com/Manuel83/craftbeerpi "Goto craftbeerpi"), [kleiner-brauhelfer](https://github.com/Gremmel/kleiner-brauhelfer "Goto kleiner-brauhelfer") and so on) but all of them use individual data exchange formats like sql. So we still miss an offical, fully featured standard for brewing recipes. Let us design a worldwide standard format in json schema together. Let's make the default for home brewing automation. Let's make it easy, sharing brew recipes across the world. Everyone with some experience in brewing and json-skills is welcome! 

#### Requirements:
- Json Schema as definition format
- Versioning for further development
- Multi language support
- Automation details possible but not required
- Free definition of brew steps
- Enums for often used values
- Support for multiple units, etc.

#### Steps to version 1.0.0
- Finalize the [JSON Example](/v1.0.0/open-brew-1-0-0.example.json "JSON Example for Open Brew Version 1.0.0")
- Documentation in Wiki (See progress here [Wiki](https://github.com/SeeSharp7/Open-Brew/wiki))
- Extract json schema from example
- Add description, required fields, enum values
- Release version 1.0.0

#### Thoughts for future versions
- Swagger json definition
- Formula and Codelibs for extrapolating amounts
- Minimum requirements of brew equipment (container size, ...)
- Free online hub for all recipes worldwide (open-brew-hub.com)
- Directly import your favourite recipes to your IoT-Device
- Address all automated parts (SSRs; Pumps; ...) in this json format  
