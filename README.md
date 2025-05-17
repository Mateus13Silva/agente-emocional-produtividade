🧠 Agente Emocional Inteligente
 
Um assistente emocional que ajuda a gerenciar tarefas e emoções com sugestões personalizadas, gamificação e visualizações interativas. Desenvolvido para a Imersão IA Alura & Google 2025. Este projeto combina IA generativa, gamificação e uma interface amigável para promover produtividade e bem-estar.
📋 Tabela de Conteúdos

Instalação
Como Usar
Exemplos
Tecnologias Usadas
Licença
Contato

⚙️ Instalação
Pré-requisitos

Conta no Google Colab para executar o notebook.
Chave de API do Google Gemini (obtenha em ai.google.dev).
Conexão com a internet para downloads e execução.

Passos

Clone o repositório


Abra o arquivo Agente_Emocional_Inteligente_definitivo.ipynb no Google Colab.
Configure sua chave de API do Gemini na célula 1:genai.configure(api_key="SUA_API_KEY")


Execute todas as células na ordem para instalar dependências (ex.: gradio, matplotlib) e carregar o projeto.

🚀 Como Usar

Execute o notebook no Google Colab.
Use a interface Gradio (célula 7) para interagir(experimental, rsrs): 
Insira sua tarefa (ex.: "Estudar") e emoção (ex.: "Ansioso").
Clique em "Enviar" para receber uma sugestão personalizada.
Clique em "Gerar Gráfico" para visualizar suas emoções.
Clique em "Sair" para ver seus pontos e nível.


Alternativamente (recomendado, na verdade) use a célula 5 para interagir via texto e ganhar pontos ao aceitar sugestões ("sim").

📸 Exemplos
Interação na Interface Gradio

Tarefa: Estudar  
Emoção: Motivado  
Resultado:🤖 Sugestão: Que ótimo se sentir motivado para estudar! Aproveite esse impulso criando um pequeno cronograma com pausas curtas para relaxar a cada hora. Você vai arrasar!
🎮 Pontos: 20 | Nível: Focado


Gráfico de Emoções:![Gráfico de Emoções](emocoes_plot (4).png)

🛠️ Tecnologias Usadas

Python 3.11: Linguagem principal do projeto.
Google Gemini API: Para sugestões emocionais personalizadas.
Gradio: Interface interativa no Colab.
Matplotlib: Visualização de gráficos.
Google Colab: Ambiente de execução.


📜 Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para detalhes.
📬 Contato
Desenvolvido por Mateus Silva para a Imersão IA Alura & Google 2025. 

GitHub: Mateus13Silva  
E-mail: mateussilvaamqt13@gmail.com  
Discord: mts_sm

