📚 **Projeto: Alfabetiza+**
Um site desenvolvido para ajudar pessoas analfabetas a aprenderem a ler e escrever de forma simples, interativa e acessível.

🎯 **Objetivo**
O Alfabetiza+ tem como objetivo facilitar o processo de alfabetização por meio de uma plataforma digital intuitiva, utilizando recursos visuais, áudio e atividades práticas do dia a dia.

👥 **Público-Alvo**
Pessoas analfabetas ou com dificuldade de leitura
Adultos em processo de alfabetização
Usuários que precisam de uma abordagem simples e acessível

🚀 **Funcionalidades**
🔊 Áudio explicativo em todas as etapas
🔤 Ensino de letras e palavras básicas
🧠 Exercícios interativos
📈 Acompanhamento de progresso
🎨 Interface simples e visual (sem necessidade de leitura)

🛠️ **Tecnologias Utilizadas**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

📱 **Acessibilidade**
O sistema foi pensado para ser acessível:
Uso de ícones grandes e intuitivos
Navegação simples
Áudios em todas as instruções
Pouco ou nenhum texto complexo
```mermaid
    sequenceDiagram
    Usuario->>Site: Entra no site
    Site-->>Usuario: Mostra opcoes

    Usuario->>Site: Escolhe atividade
    Site->>IA: Pede conteudo

    IA-->>Site: Envia conteudo
    Site-->>Usuario: Mostra atividade

    Usuario->>Site: Responde
    Site-->>Usuario: Mostra resultado
```
```mermaid
    flowchart TD
    Usuario((Usuario))

    UC1[Estudar leitura]
    UC2[Ouvir explicacao]
    UC3[Responder atividade]
    UC4[Ver resultado]

    Usuario --> UC1
    Usuario --> UC2
    Usuario --> UC3
    Usuario --> UC4
 ```
```mermaid
stateDiagram-v2
    [*] --> Inicio

    Inicio --> Menu
    Menu --> Atividade
    Atividade --> Resultado
    Resultado --> Menu

    Menu --> [*]
```
