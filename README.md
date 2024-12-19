# Laboratório _Análise de Sentimentos com Language Studio no Azure AI_

Este documento descreve os passos para realizar dois laboratórios utilizando os serviços cognitivos da Microsoft: **Conversão de Fala em Texto** e **Análise de Sentimento**.

## Laboratório 1: Conversão de Fala em Texto

Este laboratório utiliza o **Estúdio de Fala** para transcrever áudio em texto e vice-versa.

![image](https://github.com/user-attachments/assets/cd12ee84-0522-4253-8cf0-16e213e8e87c)

### Passos:

1.  **Acessar o Portal do Estúdio de Fala**:
    *   Vá para `speech.microsoft.com/portal`.
    *   Faça login com as mesmas credenciais usadas para criar o portal.
2.  **Criar um Recurso (se necessário)**:
    *   Clique na chave de configurações.
    *   Se não houver recursos, clique em "Criar novo recurso".
    *   Selecione a sua assinatura, dê um nome ao recurso, selecione a região e o grupo de recursos.
    *   Selecione o novo recurso.
3.  **Selecionar "Conversão de fala em texto"**:
    *   Vá para "Conversão de fala em texto" e selecione "Conversão de fala em texto em tempo real".
4.  **Importar o Arquivo de Áudio**:
    *   Selecione o idioma do arquivo de áudio.
    *   Clique em "procurar arquivos" e selecione o arquivo desejado.
    *   O sistema irá transcrever o áudio para texto automaticamente.
5.  **Explorar Recursos Adicionais**:
    *   Consulte a documentação no GitHub para entender como criar um repositório, exemplos, e as linguagens suportadas.
    *   Explore os cenários comuns de uso, como legendagem de vídeos, transcrição de call centers em vários idiomas e serviços relacionados (fala personalizada, galeria de voz).
    *   Verifique os preços do serviço e o modelo de categorias (padrão, personalizado).
6. **Uso Responsável da IA**:
   * Considere a funcionalidade necessária e o problema que precisa ser resolvido. A conversão de fala em tempo real pode ajudar na tradução e identificação em tempo real.

## Laboratório 2: Análise de Sentimento com Language Studio

Este laboratório utiliza o **Language Studio** para análise semântica de texto, com foco na análise de sentimento.

![image](https://github.com/user-attachments/assets/c591187f-4eee-4bf6-848c-6cc88584337a)

### Passos:

1.  **Criar um Recurso de Idioma**:
    *   No portal Azure, vá para "Inteligência artificial e machine learning".
    *   Selecione "Serviço de idioma".
    *   Crie um novo recurso com o tipo de preço F0 (30 dias sem cobrança).
2.  **Conectar ao Language Studio**:
    *   Acesse o Language Studio (Cognitive Services).
    *   Selecione a sua assinatura e o recurso de idioma criado.
3.  **Criar um Novo Recurso no Language Studio**:
    *   Selecione a opção "Classificação de texto" e "Analisar sentimentos e opiniões".
    *   Mantenha o idioma em inglês.
    *   Importe um arquivo de texto de exemplo.
4.  **Analisar os Resultados**:
    *   O sistema irá analisar o texto, identificando o sentimento geral (positivo, negativo, neutro).
    *   Verifique as palavras-chave e a análise de sentimento em cada frase.
    *   Explore a análise de sentimentos em diferentes idiomas.
5. **Uso do Serviço**
    *   Considere utilizar essa ferramenta para analisar o sentimento de clientes em relação a um produto, serviço ou promoção.
    *   A ferramenta é eficaz para análise de grandes volumes de texto.
6.  **Explorar Recursos Adicionais**:
    *   Consulte o GitHub para informações sobre SDKs e custos.
    *   Use as informações de forma responsável.
