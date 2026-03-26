[📄 Página](https://victorgabriel.dev/projetos/webscraper-github-user) · [💻 GitHub](https://github.com/VictorGabriel7Dev/webscraper-github-user)

# webscraper-github-user

Exibe os repositórios favoritados (★) e a lista de usuários seguidos de qualquer perfil do GitHub, direto no terminal — sem token, sem API, sem dependências externas.

---

## Exemplo de saída

```
────────────────────────────────────────────────────────────
  ⬡  webscraper-github-user
  Target → github.com/torvalds
────────────────────────────────────────────────────────────

  ★  Starred repositories — torvalds
  ··················································
     1.  torvalds/linux
         The Linux kernel
     2.  git/git
         Fast, scalable, distributed revision control system
  ...

  ✔  Total starred repositories: 42

  ★  Following — torvalds
  ··················································
     1.  gregkh        https://github.com/gregkh
     2.  davem330      https://github.com/davem330
  ...

  ✔  Total following: 7

────────────────────────────────────────────────────────────
  Summary for torvalds
  ★  Stars     : 42
  ●  Following : 7
────────────────────────────────────────────────────────────
```

---

## Uso

```
python WebScraper-GitHub-User.py <usuario>
python WebScraper-GitHub-User.py torvalds
python WebScraper-GitHub-User.py @VictorGabriel7Dev   # o @ é aceito e ignorado
```

O nome do usuário é recebido como argumento. O `@` é opcional.

---

## Requisitos

* Python 3.8 ou superior
* Sem dependências externas — usa apenas a biblioteca padrão (`urllib`, `re`, `html`, `sys`)

---

## Instalação

```
git clone https://github.com/VictorGabriel7Dev/webscraper-github-user.git
cd webscraper-github-user
python WebScraper-GitHub-User.py torvalds
```

Nenhum `pip install` necessário.

---

## Como funciona

O script acessa diretamente as páginas HTML públicas do GitHub (sem autenticação) e extrai os dados, do mesmo modo que um navegador faria.

---

## Observações

* O script lê apenas páginas **públicas**. Perfis privados ou listas restritas não são acessíveis.
* Os resultados são informativos e refletem o estado das páginas no momento da execução.
* Nenhum dado é armazenado, enviado ou cacheado.

---

## Autor

**Victor Gabriel**  
· [victorgabriel.dev](https://victorgabriel.dev)  
· [victorgabriel.dev.br](https://victorgabriel.dev.br)  
· GitHub: [github.com/VictorGabriel7Dev](https://github.com/VictorGabriel7Dev)  
· LinkedIn: [in/victor-gabriel-182a763b9](https://linkedin.com/in/victor-gabriel-182a763b9/)  
· Discord: `@VictorGabriel.dev`  
· Telegram: [t.me/VictorGabriel_Dev](https://t.me/VictorGabriel_Dev)  
· E-mail: contato@victorgabriel.dev  

Gerado por [Claude](https://claude.ai).

---

## Licença

Este projeto está licenciado sob a [Licença Pública Geral Affero GNU v3.0](https://www.gnu.org/licenses/agpl-3.0.html)  
Para mais detalhes, consulte o arquivo [LICENSE](LICENSE).

---

---

[📄 Page](https://victorgabriel.dev/projetos/webscraper-github-user) · [💻 GitHub](https://github.com/VictorGabriel7Dev/webscraper-github-user)

# webscraper-github-user

A python script for Web Scrapping GitHub Users.  
Lists starred repositories (★) and followed users from any public GitHub profile, directly in the terminal — no token, no API, no external dependencies.

---

## Output example

```
────────────────────────────────────────────────────────────
  ⬡  webscraper-github-user
  Target → github.com/torvalds
────────────────────────────────────────────────────────────

  ★  Starred repositories — torvalds
  ··················································
     1.  torvalds/linux
         The Linux kernel
     2.  git/git
         Fast, scalable, distributed revision control system
  ...

  ✔  Total starred repositories: 42

  ★  Following — torvalds
  ··················································
     1.  gregkh        https://github.com/gregkh
     2.  davem330      https://github.com/davem330
  ...

  ✔  Total following: 7

────────────────────────────────────────────────────────────
  Summary for torvalds
  ★  Stars     : 42
  ●  Following : 7
────────────────────────────────────────────────────────────
```

---

## Usage

```
python WebScraper-GitHub-User.py <username>
python WebScraper-GitHub-User.py torvalds
python WebScraper-GitHub-User.py @VictorGabriel7Dev   # @ prefix is accepted and ignored
```

The username is received as argument. The `@` prefix is optional.

---

## Requirements

* Python 3.8 or higher
* No external dependencies — uses only the standard library (`urllib`, `re`, `html`, `sys`)

---

## Installation

```
git clone https://github.com/VictorGabriel7Dev/webscraper-github-user.git
cd webscraper-github-user
python WebScraper-GitHub-User.py torvalds
```

No `pip install` required.

---

## How it works

The script fetches the public HTML pages of GitHub directly (no authentication) and extracts data using regular expressions, the same way a browser would.

---

## Notes

* The script only reads **public** pages. Private profiles or restricted lists are not accessible.
* Results are informational and reflect the page state at the time of execution.
* No data is stored, sent or cached.

---

## Author

**Victor Gabriel**  
· [victorgabriel.dev](https://victorgabriel.dev)  
· [victorgabriel.dev.br](https://victorgabriel.dev.br)  
· GitHub: [github.com/VictorGabriel7Dev](https://github.com/VictorGabriel7Dev)  
· LinkedIn: [in/victor-gabriel-182a763b9](https://linkedin.com/in/victor-gabriel-182a763b9/)  
· Discord: `@VictorGabriel.dev`  
· Telegram: [t.me/VictorGabriel_Dev](https://t.me/VictorGabriel_Dev)  
· E-mail: contato@victorgabriel.dev  

Generated by [Claude](https://claude.ai).

---

## Licença / License

This project is licensed under the [GNU Affero General Public License v3.0](https://www.gnu.org/licenses/agpl-3.0.html)  
For details, see the [LICENSE](LICENSE) file.
