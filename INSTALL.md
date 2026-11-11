# Instalação do NPPJSONViewer

Este documento explica como instalar o plugin `NPPJSONViewer` para o Notepad++.

## Requisitos

- Notepad++ instalado no seu computador.
- Compatibilidade com a arquitetura do seu Notepad++:
  - 32 bits
  - 64 bits

## Passo a passo

1. Feche o Notepad++ antes de instalar o plugin.
2. Localize a pasta de plugins do Notepad++.
   - Em instalações normais de 64 bits:
     `C:\Program Files\Notepad++\plugins\NPPJSONViewer\`
   - Em instalações de 32 bits:
     `C:\Program Files (x86)\Notepad++\plugins\NPPJSONViewer\`
3. Crie a pasta `NPPJSONViewer` dentro da pasta `plugins` da instalação do Notepad++.
4. Copie o arquivo `NPPJSONViewer.dll` para essa pasta.
5. Abra novamente o Notepad++.

## Verificação da instalação

- No menu superior do Notepad++, acesse `Plugins`.
- Verifique se o plugin `NPPJSONViewer` aparece na lista.
- Caso não apareça, confirme:
  - se a pasta foi criada corretamente;
  - se a DLL foi copiada para a pasta correta;
  - se a arquitetura do plugin corresponde à arquitetura do Notepad++.

## Observações importantes

- Use uma compilação do plugin compatível com a arquitetura da sua instalação do Notepad++.
- Se o plugin não aparecer, revise o caminho da pasta e a arquitetura do sistema.
- Este repositório contém o binário compilado do plugin e não inclui o código-fonte completo.

## Dicas adicionais

- Se você estiver instalando em um ambiente de trabalho compartilhado ou em um sistema com permissões restritas, pode ser necessário executar o processo com privilégios administrativos.
- Sempre faça backup da instalação antes de alterar arquivos da pasta `plugins`.
