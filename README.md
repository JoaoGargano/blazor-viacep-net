# BlazorViaCep 

Aplicação web desenvolvida em **Blazor WebAssembly (WASM)** (.NET) para consulta de endereços a partir do CEP utilizando a API pública do [ViaCEP](https://viacep.com.br/).

## Funcionalidades

- **Campo para Digitação do CEP:** Suporta digitação com ou sem formatação.
- **Validação de Entrada:**
  - Verifica se o campo foi preenchido.
  - Remove caracteres especiais e valida se contém exatamente 8 dígitos.
- **Consulta à API do ViaCEP:** Requisição assíncrona para https://viacep.com.br/ws/{cep}/json/.
- **Exibição do Resultado:** Tabela com os dados retornados:
  - CEP
  - Logradouro
  - Complemento
  - Bairro
  - Localidade (Cidade)
  - UF
  - DDD
- **Tratamento de Erros:** Exibe mensagens caso o CEP não seja encontrado ou ocorra falha de conexão.

## API Utilizada

- **Endpoint:** `https://viacep.com.br/ws/{cep}/json/`

## Tecnologias Utilizadas

- **C#** / **.NET**
- **Blazor WebAssembly (Standalone App)**
- **System.Net.Http.Json** 
- **System.Text.Json.Serialization** 
- **Bootstrap 5** 
