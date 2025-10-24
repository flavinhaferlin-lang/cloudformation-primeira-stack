# Implementando minha Primeira Stack com AWS CloudFormation

**Autora:** Flávia Ferlin  
**Curso / Plataforma:** DIO - Implementando sua Primeira Stack com AWS CloudFormation  
**Data:** 2025-10-24  

---

## 🎯 Objetivo
Documentar a criação da minha primeira Stack utilizando **AWS CloudFormation**, aplicando os conhecimentos vistos nas aulas e registrando as etapas da prática.

---

## 📂 Estrutura do Repositório
📁 dio-cloudformation-stack/
├── README.md
└── images/
    ├── captura-de-tela-cloudformation.png
    ├── captura-de-tela-cloudformation-criado.png
    └── captura-de-tela-cloudformation-ultimo.png

## Capturas de tela

![Criação da pilha](images/captura-cloudformation-inicio.png)
![Stack criada com sucesso](images/captura-cloudformation-final.png)
![Eventos da stack](images/captura-cloudformation-eventos.png)


---

## 🚀 Templates Incluídos
### `s3-bucket.yaml`
Template simples que cria um bucket S3 na AWS.

---

## 🧰 Como criar a Stack pelo Console AWS
1. Acesse o **AWS CloudFormation** no console da AWS.  
2. Clique em **Create Stack > With new resources (standard)**.  
3. Escolha **Upload a template file** e envie o arquivo `s3-bucket.yaml`.  
4. Defina um nome para a Stack (ex: `MinhaPrimeiraStack`).  
5. Clique em **Next** até chegar no final e selecione **Create stack**.  
6. Aguarde o status `CREATE_COMPLETE`.  

---

## 🖼️ Prints
As capturas de tela do processo estão na pasta `/images`.

---

## 💡 Lições Aprendidas
- Entendi melhor a estrutura de um arquivo YAML para CloudFormation.  
- Aprendi a criar e organizar repositórios no GitHub.  
- Compreendi como o CloudFormation automatiza a criação de recursos na AWS.  

---

## 🧹 Como apagar a Stack
Pelo Console da AWS:
- Acesse **CloudFormation → Stacks → Delete**.

Pela CLI:
```bash
aws cloudformation delete-stack --stack-name MinhaPrimeiraStack

📚 Recursos úteis

Documentação oficial AWS CloudFormation
GitHub Docs




