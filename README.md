# Assistente de Testes

**O código não será disponibilizado pois o aplicativo foi criado para suportar a demanda de projetos da EY, no qual teve total apoio pela empresa, entretanto, isso não elimina possíveis contatos para propostas e dúvidas quanto a aplicação.**

Este é um assistente de testes desenvolvido em Python que integra com a API do DevOps. Ele permite que os usuários configurem e gerenciem cenários de teste de maneira eficiente, bem como gerir e buscar informações de bugs e evidências.

## Funcionalidades

### Documentos

- Seleção de arquivo padrão e diretório de imagens.
- Inserção de nome do tester.
- Definição de ID do cenário de teste.
- Seleção do ambiente e produto.
- Definição do perfil do usuário.
- Integração com DevOps.
- Geração de evidências.

## Como Usar

### Documentos

1. **Arquivo Padrão**: Selecione o arquivo padrão clicando em "Procurar" ao lado do campo "Arquivo padrão".
2. **Diretório de Imagens**: Selecione o diretório de imagens clicando em "Procurar" ao lado do campo "Diretório de Imagens".
3. **Nome do Tester**: Insira o nome do tester no campo correspondente.
4. **ID do Cenário de Teste**: Insira o ID do cenário de teste no campo correspondente.
5. **Ambiente**: Selecione o ambiente (HML, PRD, etc.) no menu suspenso.
6. **Produto**: Selecione o produto no menu suspenso.
7. **Perfil**: Insira o perfil do usuário no campo correspondente.
8. **Integração com DevOps**: Marque a opção para integrar com DevOps.
9. **Gerar Relatório**: Clique em "Gerar" para criar o documento de evidência.

![image](https://github.com/user-attachments/assets/c0cf4617-854f-477f-9a41-3dec4f7e2d00)


## Exemplo de Uso

```python
# Importar a biblioteca necessária
import devops_api

# Configurar o assistente de testes
tester = "Renzo Tavares"
cenario_id = 29163
ambiente = "HML"
produto = "Gestão de OPME"
perfil = "Analista PCA"
bug_id = 12345
titulo = "Erro na interface"
descricao = "A interface apresenta um erro ao carregar dados."
chave_m = "CH123"
product_id = "GPRS"
release_id = "1.0.0"

# Integração com DevOps
integrar_com_devops = True

# Função para gerar relatório
def gerar_relatorio(tester, cenario_id, ambiente, produto, perfil, integrar_com_devops):
    # Lógica para gerar relatório
    pass

# Função para buscar bug
def buscar_bug(bug_id):
    # Lógica para buscar bug
    pass

# Chamar a função para gerar o relatório
gerar_relatorio(tester, cenario_id, ambiente, produto, perfil, integrar_com_devops)

# Chamar a função para buscar o bug
buscar_bug(bug_id)
