
Changelog

Todas as mudanças importantes do Browser 98 serão documentadas neste arquivo.

[1.2] - 2026

Adicionado

- Nova etapa pública de desenvolvimento do Browser 98.
- Suporte ampliado e melhorias nos protocolos HTTP, HTTPS, Gemini e Gopher.
- Melhor gerenciamento de cache, incluindo cache separado para páginas e imagens.
- Controle de tamanho máximo para dados recebidos pela rede.
- Controle de tamanho máximo para imagens carregadas.
- Controle de tamanho máximo para downloads.
- Sistema de redirecionamentos com limite de segurança.
- Melhor tratamento de erros de rede.
- Melhor gerenciamento de carregamentos em segundo plano.
- Melhor gerenciamento de imagens carregadas de forma assíncrona.
- Persistência local de histórico, favoritos e configurações.
- Sistema de configurações do navegador.
- Suporte a temas da interface.
- Ferramenta de localização de texto na página.
- Atalhos de teclado para operações do navegador.
- Páginas internas para histórico e favoritos.
- Melhor tratamento de arquivos locais através de "file://".
- Identificação de arquivos e controle de tamanho durante downloads.
- Melhor identificação do navegador através do User-Agent.

Melhorado

- Renderização de documentos HTML.
- Renderização de páginas Gemini.
- Renderização de menus Gopher.
- Navegação entre páginas.
- Sistema de histórico.
- Sistema de favoritos.
- Sistema de cache.
- Carregamento de imagens.
- Gerenciamento de downloads.
- Interface gráfica.
- Indicadores de estado durante operações de rede.
- Tratamento de redirecionamentos.
- Tratamento de erros de conexão.
- Segurança no tratamento de URLs e esquemas suportados.
- Controle de operações realizadas em segundo plano.
- Organização interna do código.

Limitações conhecidas

- O suporte a HTML ainda é limitado e não implementa completamente os padrões modernos da Web.
- JavaScript não é executado.
- CSS moderno não é suportado.
- O suporte a formulários POST ainda é limitado.
- O processamento de texto atualmente é orientado principalmente a UTF-8.
- O suporte a Gopher ainda está em desenvolvimento.
- A validação tradicional de certificados TLS do Gemini possui um modo de compatibilidade que pode desativar verificações para permitir o acesso a servidores antigos ou incompatíveis.
- A compatibilidade direta com Windows 9x ainda não foi alcançada na versão Python.
- Os requisitos mínimos de hardware para sistemas antigos ainda não foram oficialmente determinados.

[Versão pública anterior]

A versão pública anterior do Browser 98 estabeleceu a base do navegador e implementou:

- HTTP;
- HTTPS;
- HTML básico;
- Gemini;
- Gopher;
- histórico de navegação;
- cache;
- renderização de imagens.

Essa versão serviu como base para o desenvolvimento da versão 1.1 Beta.

[Histórico]

2021

Início do desenvolvimento do Browser 98.

O projeto passou por diferentes versões, experimentos e recriações ao longo de seu desenvolvimento.

2022  

Criação do conceito de o Web clássica

 o conceito de Web clássica é internet antiga de 1989 a 2013 seria uma camada da internet a internet comercial moderna enterrou por parte dessa camada ela seria parte da deep Web e Surface Web o navegador tenta principalmente pegar a parte a partir Dos anos 90 no início dos anos 2000  reconhecendo os problemas da internet atual e que a internet antiga não tinha mas sem cometer os erros do passado 

2024

Uma versão do Browser 98 foi integrada ao projeto NewXP, um projeto desenvolvido em colaboração com um colega e baseado no Windows XP, com uma interface inspirada no Windows 10.

O projeto NewXP foi posteriormente descontinuado.

2026

O desenvolvimento do Browser 98 continua como um projeto independente.

A versão 1.1 Beta trouxe melhorias de navegação, cache, downloads, favoritos, Gemini e Gopher.

A versão 1.2 amplia essa base, consolidando a implementação Python como a versão mais funcional do Browser 98 até então.

O desenvolvimento também passou a considerar uma futura reimplementação do núcleo em Rust, com o objetivo de criar uma arquitetura mais adequada para compatibilidade com sistemas antigos e, posteriormente, permitir o desenvolvimento de uma versão compatível com Windows 9x através do Rust9x.
