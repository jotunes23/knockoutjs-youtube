# Introdução

## O que é o KnockoutJS?

O KnockoutJS é uma biblioteca que simplifica a construção de interfaces dinâmicas com Javascript através da utilização do padrão MVVM.

- Atualiza automaticamente os elementos da UI sempre que ocorre alguma alteração no modelo de dados.
- Utiliza contextos para criação de UIs dinâmicas e complexas.
- Implementação de bindings para facilitar a reutilização.
- Javascript puro, funciona em qualquer navegador (IE 6+, Firefox 2+, Chrome, Safari, Edge, outros).
- Pode ser adicionado sobre sua aplicação Web existente sem a necessidade de grandes mudanças de arquitetura.

## O que é MVVM?

É um padrão de projeto (design pattern) criado por John Gossman. O padrão de projeto Model-View-ViewModel (MVVM) foi originalmente criado para aplicativos Windows Presentation Foundation (WPF) usando XAML para separar a interface do usuário (UI) da lógica de negócios e aproveitando ao máximo o data binding (a vinculação de dados).

## Model

Os dados relevantes ao sistema são processados aqui.

- Tem todo o desenho e formatação da interface com usuário,
- Costuma ter validações específicas da UI,
- Processa os dados obtidos na UI para ser disponibilizada de forma adequada para outras camadas.

## View

É onde realmente há uma forma de apresentar os dados. E só a apresentação visual é feita. Não há processamento dos dados do sistema.

- Tem todo o desenho e formatação da interface com usuário
- Costuma ter validações específicas da UI
- Processa os dados obtidos na UI para ser disponibilizada de forma adequada para outras camadas.