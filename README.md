# Projeto-Coding
Esse projeto é um sistema de gerenciamentos de estudantes, disciplinas e notas desenvolvidos em Python com interface gráfica feita em Tkinter e persistência em dados via SQLite. 

🎓 Sistema de Registro Acadêmico com Interface Gráfica (Tkinter + SQLite)

Projeto voltado a um sistema completo de cadastro e gestão escolar, com foco na administração de alunos, disciplinas e notas. Ele permite o registro, consulta, atualização e exclusão de dados, além de oferecer um recurso automatizado para geração de boletins em PDF.
A aplicação foi desenvolvida com Python, utilizando a biblioteca Tkinter para construção da interface gráfica e SQLite como banco de dados local. Essa combinação proporciona um sistema leve, intuitivo e funcional, ideal para pequenas instituições de ensino, professores ou projetos educacionais.

📌 Funcionalidades

 👤 Alunos
- Cadastro com nome de registro, nome social, e-mail, gênero, curso e data de nascimento
- Upload de foto do aluno (renderizada automaticamente na interface)
- Atualização e exclusão de dados
- Listagem completa com ID, nome de exibição e e-mail
- Suporte a diversos gêneros, incluindo identidade de gênero e opção de não informar

 📚 Disciplinas
- Cadastro de novas disciplinas
- Remoção de disciplinas
- Listagem de todas as disciplinas registradas

 📝 Notas
- Atribuição de notas (B1, B2, B3, B4) por aluno e disciplina
- Atualização de notas automaticamente
- Exibição de notas por disciplina para cada aluno

 📄 Boletim em PDF
- Geração de boletim escolar personalizado em PDF com:
  - Foto do aluno (se houver)
  - Informações pessoais
  - Tabela de notas, média final e situação (aprovado ou reprovado)
- Estilo visual agradável e bem formatado
- Abertura automática do PDF após geração

🛠️ Tecnologias Utilizadas

- **Python 3.11+**
- **Tkinter** – Interface gráfica
- **SQLite** – Banco de dados local
- **Pillow (PIL)** – Manipulação de imagens
- **ReportLab** – Geração de PDFs

📸 Interface

![Exemplo da interface](./screenshot.png) <!-- Substitua por uma imagem real caso deseje -->

 ▶️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
Instale as dependências:

pip install -r requirements.txt

Ou manualmente:

pip install pillow reportlab

Execute o sistema:
python gui.py

👩‍💻 Desenvolvido por

Anna Alice Oliveira, 
Carolline Barbosa Ferreira, 
Jai Santos Silva, 
Marcelly Arcanjo Soares da Silva, 
Maria Clara Moutinho Albuquerque

Contatos: 

carollinebarbosa225@gmail.com

jaiofarc@hotmail.com

marcellyarcanjo7@gmail.com

Moutinhomaria2910@gmail.com
