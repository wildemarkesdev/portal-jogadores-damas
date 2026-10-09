# Portal do Damista - Maranhão

Bem-vindo ao repositório oficial do **Portal do Damista**, uma vitrine profissional dedicada aos jogadores de Damas do estado do Maranhão.

## 🎯 Sobre o Projeto

Este portal foi criado com o objetivo de dar visibilidade aos damistas profissionais maranhenses, reunindo informações essenciais de cada atleta em um formato limpo, moderno e acessível. A plataforma busca automaticamente as estatísticas do atleta em duas frentes:
1. **Lidraughts (Plataforma Online)**: Busca em tempo real o rating Blitz, partidas jogadas e o status atual do atleta, extraindo estatísticas avançadas como maiores e menores pontuações, além de recordes de vitórias/derrotas.
2. **RatingDamas (CBJD)**: Busca em tempo real a pontuação nacional oficial na modalidade 100 Casas (100-C), garantindo transparência no nível dos atletas perante a Confederação.

## ✨ Funcionalidades

- **Mural de Jogadores**: Exibição em formato de cards responsivos de todos os jogadores cadastrados.
- **Perfil Profissional Detalhado**: Páginas individuais com foto, biografia, links oficiais e estatísticas importadas via API.
- **Integração Externa**: Conexões diretas via proxy CORS com *Lidraughts* e *RatingDamas*.
- **Cadastro Seguro via ViaCEP**: Validação inteligente de CEP, bloqueando o cadastro de jogadores que não residam no estado do Maranhão.
- **Modo Administrador**: Interface oculta para moderação de dados direto da vitrine.

## 🛠️ Tecnologias Utilizadas

- **Frontend**: HTML5 Semântico, CSS3 (Vanilla), JavaScript.
- **Banco de Dados**: Firebase Firestore (NoSQL, Serverless).
- **APIs Consumidas**: Lidraughts API, ViaCEP API, RatingDamas (Scraping via CORS Proxy).

## 🚀 Como Executar Localmente

1. Clone o repositório para sua máquina local.
2. O site não exige Node.js ou ferramentas complexas de build. Para abri-lo de forma que os módulos JS do Firebase funcionem corretamente, utilize uma extensão como o **Live Server** (no VS Code) ou sirva o diretório localmente com Python:
   ```bash
   python -m http.server 8000
   ```
3. Acesse `http://localhost:8000/index.html` em seu navegador.

---
*Projeto coordenado pela Coordenação Técnica.*
