<h1 align="center">
  <br>
  📊 DATApesquise
  <br>
</h1>

<h4 align="center">Plataforma inteligente de gestão de pesquisas de campo e detecção de fraudes.</h4>

<p align="center">
  <a href="#sobre-o-projeto">Sobre</a> •
  <a href="#funcionalidades">Funcionalidades</a> •
  <a href="#tecnologias">Tecnologias</a> •
  <a href="#acesso-ao-projeto">Acesso ao Projeto</a>
</p>

---

## 💻 Sobre o Projeto

O **DATApesquise** é um sistema completo e robusto desenvolvido para orquestrar operações de pesquisa de campo de ponta a ponta. Focado em alta confiabilidade de dados e prevenção de fraudes, o sistema permite criar formulários complexos, gerenciar equipes em campo e visualizar respostas em tempo real com suporte a geolocalização.

*(Nota: O código-fonte deste projeto é mantido em um repositório privado por questões de propriedade intelectual e segurança das regras de negócio. Este repositório serve como um portfólio técnico da arquitetura e recursos do sistema.)*

## ✨ Funcionalidades Principais

* **Construtor de Formulários (Form Builder):** Interface drag-and-drop avançada, inspirada no KoboToolbox, permitindo a criação de questionários dinâmicos com lógicas de pulo, validações matemáticas e suporte à importação/exportação de XLSForm.
* **Integração Mobile Offline (ODK Collect):** Suporte nativo ao protocolo OpenRosa. Pesquisadores utilizam o aplicativo ODK Collect no Android para coletar dados em áreas sem internet, enviando para o servidor assim que reconectados.
* **Gestão de Equipes e Permissões:** Controle de acesso granular baseado em RBAC (Role-Based Access Control). Perfis distintos para Administradores, Coordenadores, Analistas e Pesquisadores.
* **Análise e Dashboards em Tempo Real:** Visualização gráfica de resultados com Chart.js e painéis analíticos dinâmicos.
* **Mapeamento e Geolocalização:** Integração com mapas interativos (Leaflet) para rastreamento de entrevistas de campo por GPS e detecção de anomalias (prevenção de fraudes).
* **Auditoria de Logs:** Registro completo de atividades críticas para garantir a transparência da operação.

## 🛠 Tecnologias e Arquitetura

O sistema foi construído utilizando uma arquitetura monolítica moderna focada em performance e fácil manutenção:

**Backend:**
- **Node.js** com **Express** para roteamento e APIs REST.
- Autenticação de dupla camada (JWT para a Web e Basic/Digest Auth para comunicação com o aplicativo ODK).
- **SQLite** para armazenamento de dados, otimizado com queries estruturadas.

**Frontend:**
- **Vanilla JavaScript** (Sem frameworks pesados) para garantir carregamento instantâneo.
- **HTML5 e CSS3** com design responsivo, Glassmorphism e micro-animações.
- **Leaflet.js** para renderização de mapas geolocalizados.
- **Chart.js** para gráficos estatísticos.

## 🚀 Acesso ao Projeto

Como o código é fechado, disponibilizei uma versão funcional do sistema hospedada na nuvem para testes práticos. 

🔗 **[https://datapesquie.onrender.com](#)** 

> **Credenciais de Teste:**
> - **Usuário:** visitante
> - **Senha:** visitante123

---

<p align="center">
  Desenvolvido com dedicação focado em escalabilidade e experiência do usuário.
</p>
