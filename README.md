## 📌 Ferramentas Online

Este projeto reúne links úteis para ferramentas online voltadas para testes de intrusão, segurança, educação e geração de dados. A interface é simples, categorizada e dinâmica — ideal para uso técnico ou acadêmico.

### 🚀 Como executar

1. **Abra o terminal (Prompt de Comando ou PowerShell)**  
2. **Navegue até o diretório do projeto**  
   ```bash
   cd caminho/para/Ferramentas
   ```
3. **Execute o servidor local com Python**  
   ```bash
   python server.py
   ```
4. O navegador será aberto automaticamente com a página `Ferramentas.html`.

### 📂 Estrutura do projeto

- `Ferramentas.html` — Interface principal com categorização dinâmica
- `ferramentas.json` — Lista de ferramentas organizadas por tipo
- `server.py` — Script Python que inicia o servidor e abre o navegador

### 🛠 Contribuições

Qualquer pessoa pode adicionar novas ferramentas ao arquivo ferramentas.json, bem como criar novas categorias. Antes de incluir uma nova entrada, verifique se ela já não está presente para evitar duplicações.

Exemplo de estrutura no JSON:

json
{
  "tipo": "educacao",
  "nome": "Nova Ferramenta",
  "url": "https://exemplo.com"

### 🔄 Como contribuir via Pull Request

Fork este repositório

Crie uma nova branch:

bash
git checkout -b minha-contribuicao

Faça suas alterações no ferramentas.json ou em qualquer outro arquivo relevante

Faça o commit:

bash
git commit -m "Adiciona nova ferramenta"

Envie para seu fork:

bash
git push origin minha-contribuicao

Abra um Pull Request explicando sua contribuição

### 📋 Modelo de contribuição

Ao enviar uma nova ferramenta, inclua:

* Nome da ferramenta
* URL funcional
* Categoria (existente ou nova)
* Verificação se já existe no JSON

Exemplo de descrição no Pull Request:

Adicionei a ferramenta “CyberScan” na categoria “seguranca”. Verifiquei que ela ainda não estava listada. Link: https://cyberscan.io

### 🛑 Encerrando o servidor

Na interface web, clique no botão **“Encerrar Servidor”** para desligar o servidor com segurança.

### 📄 Licença

Uso, modificação e redistribuição são permitidos desde que a fonte seja nomeada:
Sana/Bios Informática & Consultoria — Wilson Sanabio

