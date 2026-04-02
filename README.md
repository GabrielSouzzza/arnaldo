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
HTML5
CSS3
JavaScript
(Opcional) API de Text-to-Speech (TTS)
(Opcional) Banco de dados (Firebase, MongoDB, etc.)

📱 **Acessibilidade**
O sistema foi pensado para ser acessível:
Uso de ícones grandes e intuitivos
Navegação simples
Áudios em todas as instruções
Pouco ou nenhum texto complexo


    participant U as Usuário
    participant S as Site
    participant IA as Sistema de Apoio (IA)
    participant DB as Banco de Dados
    participant A as Áudio/Leitura Guiada

    U->>S: Acessa o site
    S->>U: Mostra interface simples (ícones/voz)

    U->>S: Escolhe atividade (leitura, escrita, números)
    S->>IA: Solicita conteúdo adaptado

    IA->>DB: Busca nível do usuário
    DB-->>IA: Retorna progresso

    IA-->>S: Envia conteúdo simplificado
    S->>A: Gera áudio explicativo
    A-->>U: Reproduz instruções por voz

    U->>S: Interage (responde atividade)
    S->>IA: Avalia resposta

    IA-->>S: Feedback simples (cor, áudio, símbolos)
    S->>U: Mostra resultado (acerto/erro)

    S->>DB: Atualiza progresso do usuário
    DB-->>S: Confirma atualização

    S->>U: Sugere próxima atividade
