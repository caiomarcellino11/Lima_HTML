#### AULA 02 – COMPATIBILIDADE ENTRE NAVEGADORES E ESTRUTURA BÁSICA DO HTML5
#### Curso: Técnico em Desenvolvimento de Sistemas
Unidade Curricular
LIMA – Linguagem de Marcação
Carga Horária
4 horas
Unidade Temática
Compatibilidade Web e Estrutura Inicial do HTML5
Referência
Capítulos 2 e 3 do documento 


Situação de Aprendizagem
Uma empresa desenvolveu um website que apresenta erros em diferentes navegadores. Em alguns computadores o site funciona normalmente, em outros elementos desaparecem ou são exibidos incorretamente.

A equipe de desenvolvimento foi contratada para investigar as causas do problema e desenvolver páginas seguindo os padrões do HTML5 para garantir maior compatibilidade entre navegadores e dispositivos. 


Competência
Compreender a importância da padronização web, identificando os principais motores de renderização e construindo documentos HTML5 seguindo a estrutura recomendada pelo W3C. 

Capacidades Técnicas
Identificar motores de renderização utilizados pelos navegadores.
Compreender o conceito de compatibilidade web.
Reconhecer a importância do HTML5 na interoperabilidade.
Construir documentos HTML5 com estrutura correta.
Utilizar DOCTYPE, html, head, body e meta charset adequadamente. [html5-web | P

Capacidades Básicas
Interpretação de documentação técnica.
Organização lógica de informações.
Comunicação técnica.


Capacidades Socioemocionais
Atenção aos detalhes.
Organização.
Pensamento analítico.
Responsabilidade técnica.


Conhecimentos
1. Compatibilidade Web
Quando desenvolvemos um site, ele precisa funcionar em diferentes:

Navegadores
Sistemas operacionais
Smartphones
Tablets
Computadores

Essa característica é chamada de:
Interoperabilidade
Significa que um único código pode ser interpretado por diferentes plataformas.


2. Motores de Renderização
O navegador utiliza um componente chamado:
Motor de Renderização
Responsável por interpretar HTML, CSS e JavaScript e exibir a página ao usuário.
Principais motores
Motor
Navegadores
WebKit
Safari
Gecko
Firefox
Trident
Internet Explorer
Presto
Opera (antigo)


Representação da tabela presente no material

Debate
Pergunta para a turma:

Por que devemos testar um site em mais de um navegador?

Possíveis respostas:

Diferentes implementações do padrão
Atualizações distintas
Variação no suporte a recursos modernos
Experiência do usuário


3. HTML5 e Compatibilidade
O HTML5 foi desenvolvido para:

✅ Padronizar recursos.

✅ Facilitar o desenvolvimento.

✅ Melhorar acessibilidade.

✅ Reduzir dependência de plugins.

✅ Melhorar integração com CSS e JavaScript. [html5-web | PDF]


4. Estrutura Básica de um Documento HTML5
Todo documento HTML5 deve possuir uma estrutura mínima.

Exemplo:

<!DOCTYPE html><html lang="pt-BR"><head>    <meta charset="UTF-8">    <title>Minha Primeira Página</title></head><body></body></html>


Explicando cada elemento
DOCTYPE
<!DOCTYPE html>

Indica ao navegador que o documento está utilizando HTML5. 


Elemento HTML
<html lang="pt-BR">

Representa a raiz do documento.
Atributo lang
Indica o idioma principal.

Exemplos:

lang="pt-BR"

Português do Brasil

lang="en"

Inglês

lang="es"

Espanhol



HEAD
<head></head
Contém as informações que não aparecem diretamente ao usuário.

Exemplos:

Título da página
Arquivos CSS
Configuração de caracteres
Metadados


Meta Charset
<meta charset="UTF-8">
Permite exibir corretamente:

Acentos
Símbolos
Caracteres especiais

Sem UTF-8:

InformaÃ§Ã£o
EducaÃ§Ã£o

Com UTF-8:

Informação
Educação


TITLE
<title>Portal Corporativo</title>

Exibe o nome da página na aba do navegador.


BODY
<body></body>

Área onde o conteúdo visível é inserido.

Exemplos:

Textos
Imagens
Vídeos
Tabelas
Formulários



Estrutura Gráfica do Documento
HTML
│
├── HEAD
│   ├── META
│   ├── TITLE
│   └── LINK
│
└── BODY
    ├── Texto
    ├── Imagens
    ├── Tabelas
    └── Formulários


Demonstração Prática (Laboratório)
Passo 1
Criar uma pasta:

Aula02


Passo 2
Criar o arquivo:

index.html


Passo 3
Digitar o código:

<!DOCTYPE html><html lang="pt-BR"><head>    <meta charset="UTF-8">    <title>Meu Primeiro Site</title></head><body>    <h1>Bem-vindo ao HTML5</h1>    <p>Minha primeira página web.</p></body></html>


Passo 4
Executar no navegador.

Observar:

Aba do navegador
Conteúdo exibido
Código fonte



Evidência de Aprendizagem
Ao término da aula, o estudante deverá ser capaz de:

✅ Explicar o que é compatibilidade web.

✅ Identificar motores de renderização.

✅ Compreender a função do DOCTYPE.

✅ Construir um documento HTML5 completo.

✅ Utilizar corretamente HTML, HEAD, BODY, TITLE e META CHARSET. 


Tarefa para a Próxima Aula
Pesquisar:

O que são tags HTML?
O que são elementos HTML?
Qual a diferença entre tag de abertura e fechamento?
O que significa HTML semântico?
Próxima Aula
Aula 03 – Modelos de Conteúdo HTML e Principais Tags Estruturais.
