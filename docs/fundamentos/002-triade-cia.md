# 🛡️ Capítulo 002 — A Tríade CIA

> **Entender antes de decorar.**

---

| Informação | Detalhes |
|---|---|
| **Módulo** | 01 — Fundamentos |
| **Nível** | Iniciante |
| **Tempo estimado** | 15 a 20 minutos |
| **Pré-requisito** | [Capítulo 001 — O que é Cybersecurity?](001-o-que-e-cybersecurity.md) |

---

## 🎯 Objetivo deste capítulo

Ao final deste capítulo, você será capaz de:

- explicar o que é a **Tríade CIA**;
- diferenciar **Confidencialidade, Integridade e Disponibilidade**;
- identificar qual pilar foi afetado em um incidente;
- relacionar cada pilar a controles de segurança;
- analisar situações do cotidiano com uma visão mais profissional.

---

## Antes de começar

Quando pensamos em Segurança da Informação, é comum imaginar antivírus, firewalls, senhas fortes, hackers ou ferramentas complexas.

Mas antes de escolher qualquer ferramenta, precisamos responder a uma pergunta mais importante:

> **O que exatamente estamos tentando proteger?**

Na prática, a Segurança da Informação busca preservar três propriedades fundamentais das informações e dos sistemas:

1. **Confidencialidade**;
2. **Integridade**;
3. **Disponibilidade**.

Esses três pilares formam a chamada **Tríade CIA**.

O nome vem dos termos em inglês:

- **C — Confidentiality**;
- **I — Integrity**;
- **A — Availability**.

!!! note "Não confunda"
    Neste contexto, **CIA** não se refere à agência de inteligência norte-americana. É apenas a sigla usada para representar os três objetivos fundamentais da Segurança da Informação.

---

## O problema

Imagine que você utiliza o aplicativo do seu banco para consultar o saldo e realizar uma transferência.

Para que essa operação seja considerada segura, algumas condições precisam ser atendidas:

- somente você e pessoas autorizadas podem acessar a sua conta;
- o valor da transferência não pode ser alterado durante o processo;
- o aplicativo precisa estar funcionando quando você precisar utilizá-lo.

Observe que estamos protegendo três coisas diferentes:

| Situação | Pilar relacionado |
|---|---|
| Impedir que terceiros acessem sua conta | **Confidencialidade** |
| Impedir a alteração do valor transferido | **Integridade** |
| Manter o aplicativo acessível | **Disponibilidade** |

Esse exemplo mostra que segurança não significa apenas impedir o acesso de uma pessoa não autorizada.

Um sistema também pode ser considerado inseguro quando seus dados são modificados indevidamente ou quando ele fica indisponível.

---

## O que é a Tríade CIA?

A Tríade CIA é um modelo utilizado para compreender os principais objetivos da Segurança da Informação.

Ela ajuda profissionais e organizações a analisar:

- quais informações precisam ser protegidas;
- quais riscos existem;
- qual impacto um incidente pode causar;
- quais controles devem ser implementados.

Podemos representar o conceito da seguinte forma:

```text
              CONFIDENCIALIDADE
                     /\
                    /  \
                   /    \
                  /      \
                 /________\
         INTEGRIDADE    DISPONIBILIDADE
```

Os três pilares são importantes, mas o nível de prioridade de cada um pode mudar de acordo com o contexto.

Em um hospital, por exemplo, a disponibilidade de um sistema pode ser crítica para o atendimento de pacientes. Em uma empresa que armazena documentos sigilosos, a confidencialidade pode receber uma atenção ainda maior.

Isso não significa ignorar os outros pilares. Significa compreender o impacto de cada um para o negócio.

---

# 🔒 Confidencialidade

## O que significa?

**Confidencialidade** é a garantia de que uma informação será acessada somente por pessoas, sistemas ou processos autorizados.

Em outras palavras:

> **Quem pode acessar esta informação?**

O objetivo é evitar a exposição, o vazamento ou o acesso indevido a dados.

### Exemplos de informações confidenciais

- senhas;
- dados bancários;
- prontuários médicos;
- documentos internos;
- dados pessoais de clientes;
- segredos comerciais;
- informações estratégicas;
- credenciais de acesso.

## Quando a confidencialidade é comprometida?

A confidencialidade é violada quando alguém acessa ou visualiza uma informação sem autorização.

### Exemplos

- um invasor obtém a lista de clientes de uma empresa;
- um funcionário acessa documentos que não fazem parte de sua função;
- uma senha é enviada em um grupo público;
- um banco de dados fica exposto na internet;
- uma pessoa encontra um computador desbloqueado e lê informações internas;
- um e-mail confidencial é enviado para o destinatário errado.

!!! example "Exemplo prático"
    Um colaborador do setor de vendas consegue acessar a folha salarial de todos os funcionários, mesmo sem precisar dessas informações para realizar seu trabalho.

    Nesse caso, houve uma falha de **Confidencialidade**.

## Controles que ajudam a preservar a confidencialidade

Alguns controles comuns são:

- autenticação;
- autorização;
- controle de acesso;
- criptografia;
- classificação da informação;
- princípio do menor privilégio;
- autenticação multifator;
- bloqueio automático de tela;
- políticas de senhas;
- conscientização dos usuários.

### Autenticação não é a mesma coisa que autorização

Esses dois conceitos são frequentemente confundidos:

- **Autenticação:** confirma quem você é;
- **Autorização:** define o que você pode acessar.

Por exemplo, ao entrar em um sistema com usuário, senha e segundo fator, você está se autenticando. Depois disso, o sistema verifica quais arquivos, páginas e funções sua conta está autorizada a utilizar.

## Pergunta-chave da confidencialidade

> **Apenas pessoas autorizadas conseguem acessar essa informação?**

---

# 🧩 Integridade

## O que significa?

**Integridade** é a garantia de que a informação permanece correta, completa e sem alterações indevidas.

Em outras palavras:

> **Podemos confiar que esse dado não foi alterado?**

A integridade não impede necessariamente que uma informação seja modificada. Ela garante que qualquer alteração seja realizada de maneira autorizada e controlada.

## Quando a integridade é comprometida?

A integridade é violada quando uma informação é alterada, excluída ou corrompida sem autorização.

### Exemplos

- o valor de uma transferência é modificado;
- uma nota escolar é alterada indevidamente;
- um arquivo é corrompido durante o armazenamento;
- um invasor modifica registros de um banco de dados;
- um malware altera arquivos do sistema;
- uma configuração crítica é modificada sem aprovação;
- dados são digitados de forma incorreta e não passam por validação.

!!! example "Exemplo prático"
    Um cliente solicita uma transferência de **R$ 100,00**, mas o valor é alterado para **R$ 1.000,00** antes de a operação ser concluída.

    Mesmo que os dados não tenham sido divulgados e o sistema continue funcionando, houve uma falha de **Integridade**.

## Controles que ajudam a preservar a integridade

Alguns controles comuns são:

- hashes;
- assinaturas digitais;
- controle de versões;
- validação de dados;
- trilhas de auditoria;
- logs;
- permissões de escrita;
- revisão e aprovação de mudanças;
- backups;
- monitoramento de alterações;
- segregação de funções.

## Hash e integridade

Um **hash** é um valor gerado a partir do conteúdo de um arquivo ou conjunto de dados.

Quando o conteúdo é alterado, mesmo que a mudança seja pequena, o hash esperado também muda.

```text
arquivo_original.txt  →  hash: A1B2C3
arquivo_alterado.txt   →  hash: D4E5F6
```

Ao comparar os valores, podemos identificar que o arquivo foi modificado.

!!! warning "Atenção"
    O hash pode ajudar a verificar se ocorreu uma alteração, mas sozinho não informa necessariamente quem fez a mudança ou se ela foi autorizada. Para isso, outros controles podem ser necessários.

## Pergunta-chave da integridade

> **A informação continua correta e livre de alterações não autorizadas?**

---

# ⚡ Disponibilidade

## O que significa?

**Disponibilidade** é a garantia de que informações, sistemas e serviços estarão acessíveis quando usuários autorizados precisarem deles.

Em outras palavras:

> **O serviço está funcionando quando precisamos utilizá-lo?**

Um sistema pode proteger muito bem os dados contra acessos indevidos e alterações, mas ainda assim falhar em segurança caso fique constantemente indisponível.

## Quando a disponibilidade é comprometida?

A disponibilidade é afetada quando um sistema, serviço ou informação não pode ser acessado no momento necessário.

### Exemplos

- um site fica fora do ar;
- um servidor apresenta falha de hardware;
- um ransomware bloqueia o acesso aos arquivos;
- um ataque de negação de serviço sobrecarrega o ambiente;
- uma queda de energia interrompe a operação;
- uma atualização mal planejada causa indisponibilidade;
- um link de internet apresenta falha;
- um banco de dados deixa de responder.

!!! example "Exemplo prático"
    Durante uma emergência, os profissionais de um hospital não conseguem acessar os prontuários dos pacientes porque o sistema está fora do ar.

    Nesse caso, a **Disponibilidade** foi comprometida — e o impacto pode ser muito grave.

## Controles que ajudam a preservar a disponibilidade

Alguns controles comuns são:

- redundância;
- backups;
- balanceamento de carga;
- monitoramento;
- alta disponibilidade;
- plano de continuidade de negócios;
- plano de recuperação de desastres;
- fontes alternativas de energia;
- atualização e manutenção dos sistemas;
- proteção contra ataques de negação de serviço;
- testes de restauração;
- capacidade adequada de infraestrutura.

## Backup não é sinônimo de disponibilidade

Ter backup é importante, mas isso não significa que o ambiente esteja automaticamente disponível.

É necessário considerar:

- quanto tempo será necessário para restaurar os dados;
- se o backup está íntegro;
- se ele está protegido;
- se o processo de restauração já foi testado;
- quanto tempo o negócio pode permanecer parado.

Um backup que nunca foi testado pode falhar justamente no momento em que for necessário.

## Pergunta-chave da disponibilidade

> **A informação ou o serviço estará acessível no momento em que for necessário?**

---

# A Tríade CIA na prática

## Cenário 1 — Vazamento de dados

Uma empresa deixa um banco de dados de clientes exposto na internet. Pessoas não autorizadas conseguem visualizar nomes, endereços e documentos.

**Pilar principal afetado:** Confidencialidade.

Também podem existir impactos legais, financeiros e reputacionais.

---

## Cenário 2 — Alteração de registros

Um invasor acessa um sistema acadêmico e modifica as notas de vários alunos.

**Pilar principal afetado:** Integridade.

O sistema pode continuar disponível, mas os dados deixaram de ser confiáveis.

---

## Cenário 3 — Site fora do ar

Uma loja virtual fica indisponível durante uma grande campanha de vendas.

**Pilar principal afetado:** Disponibilidade.

Mesmo que nenhum dado seja vazado ou alterado, a empresa pode perder vendas e prejudicar sua reputação.

---

## Cenário 4 — Ransomware

Um ransomware criptografa os arquivos de uma organização e impede que os funcionários acessem os sistemas.

**Pilares possivelmente afetados:**

- **Disponibilidade:** os arquivos e sistemas ficam inacessíveis;
- **Integridade:** dados podem ser alterados ou corrompidos;
- **Confidencialidade:** o invasor pode copiar informações antes de criptografá-las.

Esse exemplo mostra que um único incidente pode comprometer mais de um pilar ao mesmo tempo.

---

# Nem todos os sistemas possuem a mesma prioridade

A importância de cada pilar depende do contexto.

| Ambiente | Pilar que pode receber maior prioridade | Motivo |
|---|---|---|
| Hospital | Disponibilidade | Sistemas precisam estar acessíveis durante atendimentos e emergências |
| Banco | Integridade | Valores e transações precisam permanecer corretos |
| Escritório de advocacia | Confidencialidade | Documentos e comunicações podem conter informações sigilosas |
| Comércio eletrônico | Disponibilidade e Integridade | A loja precisa funcionar e os pedidos devem permanecer corretos |
| Sistema de folha de pagamento | Confidencialidade e Integridade | Salários não devem ser expostos nem alterados indevidamente |

!!! tip "Pense no impacto"
    O trabalho de Segurança da Informação não consiste apenas em perguntar se existe uma vulnerabilidade. Também precisamos entender o que pode acontecer com o negócio caso um dos pilares seja comprometido.

---

# Segurança é equilíbrio

Em alguns casos, fortalecer um pilar pode afetar a experiência do usuário ou a operação.

Por exemplo:

- exigir muitas etapas de autenticação pode aumentar a confidencialidade, mas dificultar o acesso;
- bloquear completamente alterações pode preservar a integridade, mas impedir processos legítimos;
- manter vários ambientes redundantes melhora a disponibilidade, mas aumenta custos e complexidade.

Por isso, segurança não significa aplicar o máximo de restrições possível.

> Segurança significa aplicar controles proporcionais ao risco e às necessidades do negócio.

O objetivo é encontrar um equilíbrio entre proteção, usabilidade, custo e continuidade operacional.

---

# Como pensar como um profissional de Segurança

Ao analisar um sistema, faça perguntas como:

## Confidencialidade

- Quem pode acessar essas informações?
- Todos esses acessos são realmente necessários?
- Os dados estão protegidos durante o armazenamento e a transmissão?
- Existe autenticação multifator?
- As permissões são revisadas periodicamente?

## Integridade

- Quem pode alterar os dados?
- Existe registro das alterações realizadas?
- É possível identificar quem fez uma mudança?
- Os dados passam por validação?
- Existem mecanismos para detectar alterações indevidas?

## Disponibilidade

- O que acontece se o servidor falhar?
- Existe redundância?
- Os backups são testados?
- O ambiente é monitorado?
- Existe um plano para responder a incidentes e restaurar o serviço?

Essas perguntas ajudam a transformar um conceito teórico em uma forma prática de analisar riscos.

---

# Exercício de fixação

Leia cada situação e tente identificar o pilar principal afetado antes de abrir a resposta.

??? question "1. Um funcionário envia uma planilha com dados de clientes para a pessoa errada."
    **Confidencialidade**, porque as informações foram expostas a alguém sem autorização.

??? question "2. Um invasor modifica o endereço de entrega de vários pedidos."
    **Integridade**, porque os dados foram alterados indevidamente.

??? question "3. O sistema de atendimento fica fora do ar durante quatro horas."
    **Disponibilidade**, porque o serviço não pôde ser utilizado quando necessário.

??? question "4. Um ransomware copia dados e depois bloqueia o acesso aos servidores."
    **Confidencialidade e Disponibilidade**, com possível impacto também na **Integridade**.

??? question "5. Um usuário consegue visualizar apenas os documentos relacionados ao seu departamento."
    Esse é um exemplo de controle de acesso ajudando a preservar a **Confidencialidade**.

---

# Erros comuns

## “Segurança é apenas confidencialidade”

Não. Impedir vazamentos é importante, mas dados incorretos ou sistemas indisponíveis também podem causar grandes prejuízos.

## “Se o sistema está funcionando, ele está seguro”

Não necessariamente. O serviço pode estar disponível enquanto informações são acessadas ou alteradas por pessoas não autorizadas.

## “Backup resolve qualquer problema de disponibilidade”

Não. O backup precisa estar protegido, íntegro e testado. Além disso, a restauração pode levar mais tempo do que o negócio consegue suportar.

## “Integridade significa impedir qualquer alteração”

Não. Alterações legítimas fazem parte da operação. A integridade busca garantir que elas sejam autorizadas, corretas e rastreáveis.

---

# Resumo

A **Tríade CIA** representa três objetivos fundamentais da Segurança da Informação:

| Pilar | Objetivo | Pergunta principal |
|---|---|---|
| **Confidencialidade** | Impedir acessos e divulgações não autorizadas | Quem pode acessar? |
| **Integridade** | Manter os dados corretos e livres de alterações indevidas | O dado continua confiável? |
| **Disponibilidade** | Garantir acesso aos sistemas e informações quando necessário | O serviço está acessível? |

Lembre-se:

- um incidente pode afetar apenas um pilar;
- um único incidente também pode afetar os três;
- a prioridade de cada pilar varia conforme o contexto;
- controles de segurança devem ser escolhidos com base nos riscos e nas necessidades do negócio.

> Antes de pensar em ferramentas, entenda qual informação está sendo protegida e o que aconteceria se sua confidencialidade, integridade ou disponibilidade fosse comprometida.

---

# 🧠 Checkpoint

Antes de seguir para o próximo capítulo, confirme se você consegue responder:

- [ ] O que significa a sigla CIA?
- [ ] Qual é a diferença entre confidencialidade e integridade?
- [ ] Um sistema fora do ar afeta qual pilar?
- [ ] Um mesmo incidente pode afetar mais de um pilar?
- [ ] Quais controles podem ajudar a proteger cada objetivo?
- [ ] Por que a prioridade dos pilares muda conforme o negócio?

---

# Glossário

| Termo | Definição |
|---|---|
| **Autenticação** | Processo de confirmar a identidade de um usuário, sistema ou dispositivo. |
| **Autorização** | Definição das ações e recursos que uma identidade pode acessar. |
| **Backup** | Cópia de dados utilizada para recuperação em caso de perda, corrupção ou indisponibilidade. |
| **Confidencialidade** | Proteção contra acesso ou divulgação não autorizada. |
| **Controle de acesso** | Mecanismo usado para permitir ou negar acesso a recursos. |
| **Disponibilidade** | Garantia de acesso confiável e oportuno a informações e sistemas. |
| **Hash** | Valor calculado a partir de dados, frequentemente utilizado para verificar alterações. |
| **Integridade** | Garantia de que informações não foram alteradas ou destruídas indevidamente. |
| **Redundância** | Uso de recursos adicionais para reduzir o impacto de falhas. |
| **Ransomware** | Tipo de malware que restringe o acesso a dados ou sistemas, geralmente por meio de criptografia. |

---

# Referências

- [NIST CSRC — Confidentiality, Integrity and Availability](https://csrc.nist.gov/glossary/term/confidentiality_integrity_availability)
- [NIST CSRC — Information Security](https://csrc.nist.gov/glossary/term/information_security)
- [NIST FIPS 199 — Standards for Security Categorization of Federal Information and Information Systems](https://csrc.nist.gov/pubs/fips/199/final)
- [NIST SP 800-12 Rev. 1 — An Introduction to Information Security](https://csrc.nist.gov/pubs/sp/800/12/r1/final)

---

## Próximo capítulo

No próximo capítulo, vamos estudar o **Princípio do Menor Privilégio** e entender por que usuários, sistemas e aplicações devem possuir somente os acessos realmente necessários.

[← Capítulo anterior: O que é Cybersecurity?](001-o-que-e-cybersecurity.md){ .md-button }
[Próximo: Princípio do Menor Privilégio →](003-principio-do-menor-privilegio.md){ .md-button .md-button--primary }
