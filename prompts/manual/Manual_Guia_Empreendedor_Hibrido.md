# Manual de Instruções — Guia Empreendedor Híbrido

## 📌 O que é
O **Guia Empreendedor Híbrido** é um prompt em YAML que conduz empreendedores passo a passo na criação e gestão de negócios.  
Ele combina um **fluxo universal** (válido para qualquer área) com **extensões setoriais** (Moda, Designer Gráfico e Contabilidade, nesta versão inicial).

## 🚀 Como usar no ChatGPT genérico
1. **Carregue o arquivo YAML**  
   - Abra o `Guia_Empreendedor_Hibrido.yaml` e copie todo o conteúdo.
   - Cole no ChatGPT como mensagem inicial.

2. **Inicie com o mini-prompt**  
   - Adicione no chat uma instrução curta, por exemplo:  
     > "Use este YAML como guia. Pergunte o setor no início e conduza o usuário ciclo por ciclo, incluindo perguntas extras se o setor for reconhecido."

3. **Fluxo prático**  
   - O ChatGPT perguntará: *“Em qual setor ou ramo de negócio você deseja atuar?”*
   - Se o setor for reconhecido (Moda, Designer, Contábil), ele ativará perguntas e saídas específicas.  
   - Se não for reconhecido, seguirá apenas com o fluxo universal.

4. **Interação do usuário**  
   - O usuário responde às perguntas do ciclo.
   - O modelo gera as **saídas esperadas** (listas, tabelas, planos).  
   - Só depois avança ao próximo ciclo.

5. **Resumo e próximos passos**  
   - Ao final de cada ciclo, o modelo deve sempre entregar um resumo claro e objetivos práticos.

## 🛡️ Regras importantes
- Nunca inventar informações ausentes: sempre pedir ao usuário.
- Manter clareza, objetividade e foco em ações práticas.
- Sempre finalizar cada ciclo com **resumo + próximos passos**.

## 🌱 Expansão futura
- Novos setores podem ser adicionados na seção `setores` do YAML.
- Basta incluir `perguntas_extra` e `saídas_extra` específicas para cada ciclo.
