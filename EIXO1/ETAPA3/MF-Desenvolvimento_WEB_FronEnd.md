# Microfundamento: Desenvolvimento Web Front-End

## UNIDADE 1: A WEB, EVOLUÇÃO, PADRÕES E ARQUITETURAS

### TEMA 1: Fundamentos da WEB

#### Histórico e evolução 
* [A histório do Front-End para iniciantes em Programação](https://youtu.be/VKmPGmFY7H4?si=n_rTu3V_d_6fSklL) por Fabio Akita

* [A história dos buscadores de internet! – História da Tecnologia](https://youtu.be/zrV3C1DKWiI?si=F8Y-1VYxndACrsyx) Por TecMundo

![Evolucao da Web](/IMAGENS/Evolucao_web.png)

#### W3C e os Padrões Web
O World Wide Web consortium (W3C) é um organização que desenvolve e estabelece padrões aberto para World Wide Web.

O processo de padronização realizado pelo W3C é simular com as RFCs, alguns padrões mantidos pelo W3C:

- Design e Aplicações Web (HTML, CSS, SVG, AJax, Acessibilidade)
- Arquitetura da Web (Protocolo HTTP, URI)
- Web Semântica (linked Data - RDF, OWL, SPARQL)
- Tecnologia XML (XML, XML Schema, XSLT)
- Navegadores e ferramentas de autoria.

Para testar compartibilidade do navegador com os padrões WEB, Teste Acid 3 - http://acid3.acidtests.org

Estágios do desenvolvimento de padrões pela WEC
- Working Draft (WD);
- Candidate release (CR);
- Proposed Recomendation (PR);
- Recomendation(REC).

![Estágios do desenvolvimento de padrões pela W3C](/IMAGENS/Figura_1.png)

### TEMA 2: Arquitetura Web

#### Componentes da Arquitetura Web e URI, URL e URN
* Ambiente do cliente
        
    Web browser, também conhecido como *user-agent*. Se comunica com servidor Web via HTTP(s)

* Ambiente servidor

    Servidor Web recebe processo e responder solicitações HTTP(s), interpreta a URL e retorna com o
    o recurso solicitada (Arquivo HTML, CSS, JavaScript, Imagens, Vídeos, folhas de estilo) pela Rede.

* Rede
    Meio por qual a(s) rede(s) conecta o cliente ao servidor por meio do protocolo IPv4/IPv6.
    DNS é um serviço de rede primordial de rede para traduzir endereços IP em nomes.

* URI, URL, e URN

    * URI (Uniform Resource Identifier): Padrão para endereçamento de recursos de rede que engloba
    ambos conceitos de URL (Uniform Resource locator) e URN Uniform Resource name.

[Wikipedia Uniform Resource Identifier](https://en.wikipedia.org/wiki/Uniform_Resource_Identifier)

![URI](/IMAGENS/URI_URL_URN.png)


* URL (Uniform Resource Lecator) É um padrão de URI que serce para referenciar um recurso e sua localização
composto das seguintes partes:
    
    * Esquema - Identifica o protocol entre cliente e servidor. Ex.: HTTP, HTTPS, FTP, SFTP, etc;
    * user:pass - identifica usuário e senha separado por ":";  
    * Porta - Identifica porta TCP/IP associada ao serviço. Ex.: HTTP (80);
    * Caminho - Indica o local exato onde o recurso se encontra;
    * Query - Dados não hierárquicos, detalhando a consulta normalmente sob a forma de chave=valor indicado por "?".
    Diferentes parametros são separados por "&";
    * Fragmento - Identifica uma seção do recurso.
    * Exemplo: **https://pucminas.com.br:80/admin/index.php?z1=w1&z2=w2**
    
    ![URL](/IMAGENS/URL.png)

* URN (Uniform Resource Name) é um padrão URI que serve identificar um recurso (NSS) pelo nome em um determinado amespace (NID). Ou seja, identifica um recurso sem específicar sua localização.
    
    * Exemplo de urn para identificar livro - **urn:isbn:978-1-491-91866-1**
    * NID - NameSpace Identifier
    * NSS - NameSpace Specific String


    ![URN](/IMAGENS/URN.png)

[Identificando recursos Web por Developer Mozilla](https://developer.mozilla.org/pt-BR/docs/orphaned/Web/HTTP/Basics_of_HTTP/Identifying_resources_on_the_Web)

#

#### Protocolo HTTP

> O HyperText Transfer Protocol (HTTP) é um protocolo da camada de aplicação para sistemas distribuídos de informação no formato hipertextos. 

*RFC-2068*

O protocolo HTTP é mantido pela W3C e possuí variadas versões, sendo a versão 2.0 a mais utilizad pelos 
clientes e servidores do mercados. Abaixo, uma imagem com versões do protocolo.

![httpprotocol](/IMAGENS/http-historico.png)

As interações entre cliente em servidor são compostas por  requisição HTTP (cliente) e respostas HTTP (servidor).
Essas interação contêm um formato de mensagem divido em três partes:

**Cliente**
* Linha de requisição: informa o método da requisição, o recurso e a versão do HTTP;
* Linhas de cabeçalho: Inclui informações complementares sobre a requisição no formato *chave:valor* para cada linha;
* Corpo da entidade: Carrega dados adicionais pessadas pelo cliente, tais como: Dados de formulários, arquivos completos
    em um processo de upload, entre outros.

```http
POST /app/processamento HTTP/1.1

User-Agent: Mozilla/4.o0 (Compatible...)
Host: www.pucminas.br
```