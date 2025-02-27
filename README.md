# ASMedia
<p align="center">
<img src="https://github.com/user-attachments/assets/11bbe2f6-56f2-4f6e-99b4-b2827d55cb19" alt="ASIptvServer Logo" />
</p>

ASMedia é um media server escrito em C# que fornece uma solução robusta para gerenciamento de conteúdo como filmes, séries e TV ao vivo, além de gerenciar usuários. Este projeto é ideal para quem deseja uma plataforma completa de mídia com suporte à leitura de arquivos e URLs no formato M3U e arqvuios de mídia interno e externo.

## Principais Recursos

- **Suporte a arquivosde mídia e URLs M3U**: Permite a importação e o gerenciamento de canais, filmes e séries.
- **Gerenciamento de usuários**: Controle de acesso e perfis de usuários.
- **Compatível com multiplataforma**: Disponível para Linux e Windows.

## Requisitos

- **.NET 8 SDK**: Certifique-se de ter o .NET 8 instalado no seu sistema.

## Instalação

### Linux
1. Clone o repositório:
   ```bash
   git clone https://github.com/AdrianoSenaS/ASMedia-Master.git
   cd ASMedia-Master
   ```

2. Inicie o servidor:
   ```bash
   sudo dotnet run --project ASMedia
   ```

### Windows
1. Baixe o projeto e abra-o no Visual Studio.
2. Certifique-se de que o .NET 8 SDK está instalado.
3. Compile e inicie o projeto pressionando `F5` ou utilizando a opção "Iniciar Depuração" no Visual Studio.

## Como Usar
1. Acesse a API através do endpoint principal para gerenciar os recursos.
2. Use a interface da API para configurar os seguintes itens:
   - Importação de arquivos/URLs M3U
   - Gerenciamento de usuários e revendedores
   - Configuração de métodos de pagamento

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para enviar *pull requests* ou relatar problemas na página do repositório.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

