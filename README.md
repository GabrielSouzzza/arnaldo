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
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![Text to Speech](https://img.shields.io/badge/TTS-Voice%20API-purple?style=for-the-badge&logo=googleassistant&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

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
