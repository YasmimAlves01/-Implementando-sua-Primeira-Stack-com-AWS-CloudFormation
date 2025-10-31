# -Implementando-sua-Primeira-Stack-com-AWS-CloudFormation

## 🎯 Objetivo do Projeto

- Aplicar os conceitos aprendidos sobre infraestrutura como código (IaC) com AWS CloudFormation.
- Criar uma stack funcional que provisiona recursos na AWS de forma automatizada.
- Documentar o processo técnico de forma clara, estruturada e acessível.
- Compartilhar conhecimento e experiência com a comunidade tech.

---

## 🧠 O que é AWS CloudFormation?

**AWS CloudFormation** é um serviço que permite modelar e provisionar recursos da AWS usando arquivos de template (em YAML ou JSON). Com ele, podemos definir toda a infraestrutura como código, garantindo consistência, versionamento e automação.

---

## 🛠️ Recursos Provisionados na Stack

Durante a prática, a stack criada incluiu os seguintes recursos:

- ✅ Bucket S3 para armazenamento de arquivos
- ✅ Função Lambda simples para processamento
- ✅ Role IAM com permissões básicas
- ✅ Saídas organizadas para facilitar integração

---

## 📋 Etapas Realizadas

1. **Estudo das aulas e conceitos fundamentais**
   - Infraestrutura como código
   - Componentes de uma stack
   - Sintaxe YAML para templates

2. **Criação do template CloudFormation**
   - Definição de recursos: `AWS::S3::Bucket`, `AWS::Lambda::Function`, `AWS::IAM::Role`
   - Uso de parâmetros e outputs

3. **Deploy da stack via Console AWS**
   - Upload do template
   - Monitoramento da criação dos recursos

4. **Validação dos recursos**
   - Teste da função Lambda
   - Verificação do bucket S3
   - Análise das permissões IAM

---

## ✨ Insights e Aprendizados

- Diferença entre `Resources`, `Parameters` e `Outputs`
- Como evitar erros comuns na sintaxe YAML
- A importância de versionar templates no Git
- Como CloudFormation se integra com outros serviços AWS



Se quiser, posso te ajudar a montar o `template.yaml` ou revisar o conteúdo do seu repositório antes de publicar. Vamos deixar esse projeto impecável!
