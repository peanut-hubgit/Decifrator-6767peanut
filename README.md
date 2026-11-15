# Decifrator Privado

Uma aplicação web leve para transformar mensagens em textos cifrados e recuperar mensagens compatíveis com o formato utilizado pelo próprio projeto. A interface foi construída para apresentar o processo de forma visual, com animações, etapas e uma tabela de referência.

> **Aviso:** este projeto é voltado a jogos, enigmas e entretenimento. A cifra implementada é simples e não deve ser usada para proteger senhas, informações pessoais, dados financeiros ou qualquer conteúdo confidencial.

## Visão geral

O projeto é uma página web independente, executada diretamente no navegador. Não exige instalação de dependências, servidor de aplicação, banco de dados ou conta de usuário para o funcionamento básico.

A interface oferece dois modos:

- **Cifrar:** recebe uma mensagem e gera uma representação transformada.
- **Decifrar:** recebe um texto produzido no formato esperado pelo projeto e apresenta o conteúdo recuperado.

## Funcionalidades

### Conversão de mensagens
- Entrada de texto com contagem de caracteres.
- Alternância entre os modos de cifragem e decifragem.
- Exibição do resultado em um painel separado.
- Opção para usar o resultado como entrada da operação seguinte.
- Cópia do resultado para a área de transferência.
- Botão para limpar os campos e reiniciar a visualização.

### Texto de distração
No modo de cifragem, é possível adicionar um trecho de distração ao final do conteúdo transformado. O controle permite ativar ou desativar esse recurso e ajustar o tamanho máximo aproximado do trecho.

### Tabela de referência
A página apresenta uma tabela interativa com os caracteres contemplados pela aplicação. Cada item pode ser virado individualmente ou em conjunto. A tabela também destaca os caracteres envolvidos na última operação.

### Interface e acessibilidade
- Layout responsivo para telas grandes e dispositivos móveis.
- Tema claro e suporte a tema escuro conforme a preferência do sistema.
- Animações de transição e feedback visual.
- Estados de foco visíveis para navegação por teclado.
- Respeito à preferência do sistema por movimento reduzido.
- Rótulos e mensagens de estado para auxiliar a utilização.

## Tecnologias

O projeto utiliza tecnologias nativas da web:

- **HTML5** para a estrutura da página.
- **CSS3** para layout, temas, responsividade e animações.
- **JavaScript** para as interações e processamento local das mensagens.
- **Google Fonts** para as famílias tipográficas Bricolage Grotesque e JetBrains Mono.

Não há framework ou etapa de compilação.

## Estrutura do repositório

```text
.
├── Index.html                 # Aplicação completa
├── assets/
│   └── icon.svg               # Favicon vetorial
├── .github/
│   ├── ISSUE_TEMPLATE/         # Modelos para issues
│   └── PULL_REQUEST_TEMPLATE.md
├── README.md                   # Documentação principal
├── LICENSE                     # Licença MIT
├── SECURITY.md                 # Política de segurança
├── CONTRIBUTING.md             # Guia de contribuição
├── CODE_OF_CONDUCT.md          # Código de conduta
└── .gitignore                  # Arquivos ignorados pelo Git
```

## Como executar

1. Baixe ou clone este repositório.
2. Abra o arquivo `Index.html` em um navegador moderno.
3. Escolha o modo desejado.
4. Digite ou cole o conteúdo no campo de entrada.
5. Execute a operação pelo botão correspondente.

Também é possível publicar o arquivo em qualquer hospedagem de páginas estáticas. Não é necessário configurar variáveis de ambiente ou serviços externos para o processamento das mensagens. A fonte tipográfica pode depender de conexão com a internet; caso contrário, o navegador utiliza fontes alternativas.

## Privacidade e segurança

O processamento das mensagens é realizado no próprio navegador. A aplicação não implementa contas, armazenamento remoto de mensagens ou integração com banco de dados.

Isso não torna a cifra adequada para segurança real. O mecanismo é determinístico em sua transformação principal e não foi projetado, auditado ou validado como criptografia moderna. Não insira informações sensíveis.

## Compatibilidade

Recomenda-se utilizar uma versão atualizada de Chrome, Edge, Firefox ou Safari. Algumas funções de interface, como a cópia pela área de transferência, podem depender das permissões e do contexto seguro oferecido pelo navegador.

## Estado do projeto

O repositório contém uma implementação em página única. A documentação descreve as funções e os arquivos presentes, sem prometer recursos que não fazem parte do código atual.

## Licença

Este projeto está licenciado sob a **MIT License**. Consulte o arquivo [LICENSE](LICENSE) para os termos completos.
