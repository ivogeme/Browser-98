# README.md - Browser 98 (v1.2)
> Um navegador web minimalista, leve e focado na preservação da Small Web, protocolos retrô e arquiteturas clássicas, desenvolvido em Python com Tkinter e Pillow.
>
>
 ## Por que Browser98?
 Os navegadores modernos são poderosos, mas também são grandes e dependentes de padrões web cada vez mais complexos.

O Browser98 explora uma direção diferente:
um navegador compacto focado em leitura, hiperlinks,
HTML clássico e protocolos alternativos, como Gemini e Gopher.

O projeto visava originalmente a compatibilidade com o Windows 9x.
A implementação atual em Python é um protótipo funcional;
planeja-se uma futura reescrita em Rust/Rust9x para os sistemas mais antigos.

## **Visão Geral**
O **Browser 98** foi projetado para resgatar a essência da navegação clássica dos anos 90 e início dos anos 2000. Sem o peso de motores de renderização modernos ou execução de scripts complexos, ele oferece uma experiência veloz, focada em texto, hiperlinks e leitura limpa. Além do suporte a HTTP/HTTPS tradicional, ele traz implementações nativas para protocolos alternativos e descentralizados.
## **Principais Recursos da Versão 1.2**
 * **Suporte Multi-protocolo Coeso:** Navegue por páginas HTTP/HTTPS clássicas, explore o espaço com o protocolo **Gemini** (com tratamento de certificados e status) e acesse diretórios e arquivos via **Gopher**.
 * **Sistema de Cache Inteligente:** Gerenciamento duplo de cache (páginas e imagens) com limites estritos em bytes e limpeza automática (FIFO/insertion-order eviction), garantindo economia de memória.
 * **Carregamento em segundo plano:** Carregamento de páginas e mídias executado inteiramente em *background threads*, mantendo a interface gráfica do Tkinter sempre fluida e sem travamentos.
 * **Persistência Simples e Portável:** Histórico de navegação, lista de favoritos e configurações salvos em arquivos de texto plano locais (historico.txt, favoritos.txt, config.ini).
 * **Resiliência de Rede:** Tratamento avançado de exceções que traduz falhas complexas de sockets e SSL em mensagens amigáveis para o usuário.
* **Requisitos de Sistema**
 * **Python:** Versão 3.8 ou superior (recomendado Python 3.10+)
 * **Dependências Externas:** Biblioteca **Pillow** (PIL) para processamento e exibição de imagens.
 * **Hardware:** Requisitos mínimos ainda não foram oficialmente determinados.

 * **LIMITAÇÕES ATUAIS:** - O Browser 98 não visa à compatibilidade com a Web moderna
 * Sem JavaScript
- Suporte limitado a HTML/CSS
- Sem motor de CSS moderno
- Formulários POST limitados
- Sem motor HTML5 completo
- Compatibilidade com Windows 9x ainda não alcançada
- Requer Python 3.8+
- 
**Status em relação ao Windows 9x:**
O Browser98 foi criado originalmente com a compatibilidade com o Windows 9x como um objetivo de longo prazo. A implementação atual em Python funciona em ambientes Python modernos, mas ainda não oferece compatibilidade direta com o Windows 9x. Está planejada uma futura reescrita em Rust/Rust9x para solucionar essa limitação arquitetônica.

Aviso: o modo de compatibilidade desativa a verificação de certificados TLS e deve ser usado apenas quando necessário

Projetado para manter baixo o uso de recursos; a implementação atual em Python é leve em comparação com os mecanismos de navegadores modernos

## **Como Instalar e Executar**
 1. Certifique-se de ter o Python instalado em seu sistema.
 2. Instale a biblioteca de manipulação de imagens Pillow via terminal:
   ```bash
   pip install -r requirements.txt
   
   ```
 3. Baixe ou clone o código-fonte do navegador.
 4. Execute o script principal:
   ```bash
   python browser98.py
   
   ```

Licensed under GPL-3.0.
