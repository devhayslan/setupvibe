# SetupVibe Aliases

Esta é a lista exaustiva de todos os aliases configurados pelo SetupVibe em todas as plataformas.

**Legenda de Disponibilidade:**
- 🖥️ **Desktop**: Disponível na edição Desktop (macOS e Linux Desktop).
- ☁️ **Server**: Disponível na edição Server (Linux).
- 🌐 **Ambos**: Disponível em todas as edições.

---

## AI CLIs

- **`ge`** (🌐 Ambos)
  - Comando: `gemini --approval-mode=yolo`
  - Descrição: Gemini CLI sem confirmações.
  - Exemplo: `ge`

- **`cc`** (🌐 Ambos)
  - Comando: `claude --permission-mode=auto --dangerously-skip-permissions`
  - Descrição: Claude CLI sem confirmações.
  - Exemplo: `cc`

## Skills CLI

- **`skl`** (🌐 Ambos)
  - Comando: `npx skills list`
  - Descrição: Lista todas as skills instaladas.
  - Exemplo: `skl`

- **`skf`** (🌐 Ambos)
  - Comando: `npx skills find`
  - Descrição: Busca skills no registro.
  - Exemplo: `skf react`

- **`ska`** (🌐 Ambos)
  - Comando: `npx skills add`
  - Descrição: Instala uma nova skill.
  - Exemplo: `ska owner/repo`

- **`sku`** (🌐 Ambos)
  - Comando: `npx skills update`
  - Descrição: Atualiza todas as skills instaladas.
  - Exemplo: `sku`

- **`skun`** (🌐 Ambos)
  - Comando: `npx skills remove`
  - Descrição: Remove uma skill instalada.
  - Exemplo: `skun nome`

- **`skc`** (🌐 Ambos)
  - Comando: `npx skills check`
  - Descrição: Verifica atualizações disponíveis.
  - Exemplo: `skc`

## Shell & Utilitários

- **`zconfig`** (🌐 Ambos)
  - Comando: `nano ~/.zshrc`
  - Descrição: Edita o arquivo de configuração do ZSH.
  - Exemplo: `zconfig`

- **`reload`** (🌐 Ambos)
  - Comando: `source ~/.zshrc`
  - Descrição: Recarrega as configurações do ZSH sem reiniciar o terminal.
  - Exemplo: `reload`

- **`path`** (🌐 Ambos)
  - Comando: `echo -e ${PATH//:/\\n}`
  - Descrição: Exibe cada entrada do PATH em uma linha separada.
  - Exemplo: `path`

- **`h`** (🌐 Ambos)
  - Comando: `history | grep`
  - Descrição: Busca no histórico de comandos.
  - Exemplo: `h docker`

- **`cls`** (🌐 Ambos)
  - Comando: `clear`
  - Descrição: Limpa o terminal.
  - Exemplo: `cls`

- **`please`** (🌐 Ambos)
  - Comando: `sudo`
  - Descrição: Atalho amigável para sudo.
  - Exemplo: `please apt update`

- **`week`** (🌐 Ambos)
  - Comando: `date +%V`
  - Descrição: Exibe o número da semana atual.
  - Exemplo: `week`

## Navegação & Filesystem

- **`..`** (🌐 Ambos)
  - Comando: `cd ..`
  - Descrição: Sobe um nível de diretório.
  - Exemplo: `..`

- **`...`** (🌐 Ambos)
  - Comando: `cd ../..`
  - Descrição: Sobe dois níveis de diretório.
  - Exemplo: `...`

- **`....`** (🌐 Ambos)
  - Comando: `cd ../../..`
  - Descrição: Sobe três níveis de diretório.
  - Exemplo: `....`

- **`ll`** (🌐 Ambos)
  - Comando: `ls -lhA` (macOS) / `ls -lhA --color=auto` (Linux)
  - Descrição: Lista arquivos com detalhes e tamanho legível.
  - Exemplo: `ll`

- **`la`** (🌐 Ambos)
  - Comando: `ls -A` (macOS) / `ls -A --color=auto` (Linux)
  - Descrição: Lista todos os arquivos incluindo ocultos.
  - Exemplo: `la`

- **`lsd`** (🌐 Ambos)
  - Comando: `ls -d */ 2>/dev/null`
  - Descrição: Lista apenas diretórios.
  - Exemplo: `lsd`

- **`md`** (🌐 Ambos)
  - Comando: `mkdir -p`
  - Descrição: Cria diretório e subdiretórios automaticamente.
  - Exemplo: `md projeto/src/css`

- **`rmf`** (🌐 Ambos)
  - Comando: `rm -rf`
  - Descrição: Remove arquivos e diretórios recursivamente sem confirmação.
  - Exemplo: `rmf pasta_velha`

- **`du1`** (🌐 Ambos)
  - Comando: `du -h -d 1` (macOS) / `du -h --max-depth=1` (Linux)
  - Descrição: Uso de disco do diretório atual, um nível de profundidade.
  - Exemplo: `du1`

## Tmux

- **`t`** (🌐 Ambos)
  - Comando: `tmux`
  - Descrição: Atalho para o tmux.
  - Exemplo: `t`

- **`tn`** (🌐 Ambos)
  - Comando: `tmux new -s`
  - Descrição: Cria nova sessão tmux.
  - Exemplo: `tn meu-projeto`

- **`ta`** (🌐 Ambos)
  - Comando: `tmux attach -t`
  - Descrição: Reconecta a uma sessão existente.
  - Exemplo: `ta meu-projeto`

- **`tl`** (🌐 Ambos)
  - Comando: `tmux ls`
  - Descrição: Lista todas as sessões tmux ativas.
  - Exemplo: `tl`

- **`tk`** (🌐 Ambos)
  - Comando: `tmux kill-session -t`
  - Descrição: Encerra uma sessão tmux.
  - Exemplo: `tk meu-projeto`

- **`tka`** (🌐 Ambos)
  - Comando: `tmux kill-server`
  - Descrição: Encerra todas as sessões tmux.
  - Exemplo: `tka`

- **`td`** (🌐 Ambos)
  - Comando: `tmux detach`
  - Descrição: Desconecta da sessão sem encerrá-la.
  - Exemplo: `td`

- **`tw`** (🌐 Ambos)
  - Comando: `tmux new-window`
  - Descrição: Cria nova janela na sessão atual.
  - Exemplo: `tw`

- **`ts`** (🌐 Ambos)
  - Comando: `tmux split-window -v`
  - Descrição: Divide painel horizontalmente (novo painel abaixo).
  - Exemplo: `ts`

- **`tsh`** (🌐 Ambos)
  - Comando: `tmux split-window -h`
  - Descrição: Divide painel verticalmente (novo painel à direita).
  - Exemplo: `tsh`

- **`trename`** (🌐 Ambos)
  - Comando: `tmux rename-session`
  - Descrição: Renomeia a sessão atual.
  - Exemplo: `trename novo-nome`

- **`twrename`** (🌐 Ambos)
  - Comando: `tmux rename-window`
  - Descrição: Renomeia a janela atual.
  - Exemplo: `twrename editor`

- **`treload`** (🌐 Ambos)
  - Comando: `tmux source ~/.tmux.conf`
  - Descrição: Recarrega as configurações do tmux.
  - Exemplo: `treload`

- **`tconfig`** (🌐 Ambos)
  - Comando: `nano ~/.tmux.conf`
  - Descrição: Edita o arquivo de configuração do tmux.
  - Exemplo: `tconfig`

## Git

- **`gs`** (🌐 Ambos)
  - Comando: `git status`
  - Descrição: Exibe o estado atual do repositório.
  - Exemplo: `gs`

- **`ga`** (🌐 Ambos)
  - Comando: `git add`
  - Descrição: Adiciona arquivos ao stage.
  - Exemplo: `ga arquivo.txt`

- **`gaa`** (🌐 Ambos)
  - Comando: `git add .`
  - Descrição: Adiciona todos os arquivos modificados ao stage.
  - Exemplo: `gaa`

- **`gc`** (🌐 Ambos)
  - Comando: `git commit`
  - Descrição: Abre o editor para escrever a mensagem do commit.
  - Exemplo: `gc`

- **`gcm`** (🌐 Ambos)
  - Comando: `git commit -m`
  - Descrição: Commit com mensagem inline.
  - Exemplo: `gcm 'fix: typo'`

- **`gco`** (🌐 Ambos)
  - Comando: `git checkout`
  - Descrição: Troca de branch ou restaura arquivos.
  - Exemplo: `gco main`

- **`gcb`** (🌐 Ambos)
  - Comando: `git checkout -b`
  - Descrição: Cria e troca para uma nova branch.
  - Exemplo: `gcb feature/nova-funcao`

- **`gp`** (🌐 Ambos)
  - Comando: `git push`
  - Descrição: Envia commits para o repositório remoto.
  - Exemplo: `gp`

- **`gpl`** (🌐 Ambos)
  - Comando: `git pull`
  - Descrição: Baixa e integra mudanças do repositório remoto.
  - Exemplo: `gpl`

- **`gf`** (🌐 Ambos)
  - Comando: `git fetch`
  - Descrição: Busca atualizações do remoto sem aplicar.
  - Exemplo: `gf`

- **`gfa`** (🌐 Ambos)
  - Comando: `git fetch --all --prune`
  - Descrição: Busca de todos os remotos e remove branches deletadas.
  - Exemplo: `gfa`

- **`gm`** (🌐 Ambos)
  - Comando: `git merge`
  - Descrição: Faz merge de uma branch.
  - Exemplo: `gm feature/x`

- **`grb`** (🌐 Ambos)
  - Comando: `git rebase`
  - Descrição: Reaplica commits sobre outra base.
  - Exemplo: `grb main`

- **`gcp`** (🌐 Ambos)
  - Comando: `git cherry-pick`
  - Descrição: Aplica commit específico na branch atual.
  - Exemplo: `gcp abc123`

- **`gl`** (🌐 Ambos)
  - Comando: `git log --oneline --graph --decorate`
  - Descrição: Log compacto com grafo de branches.
  - Exemplo: `gl`

- **`glamelog`** (🌐 Ambos)
  - Comando: `git log --pretty=format:"%h %ad %s" --date=short`
  - Descrição: Log compacto com datas.
  - Exemplo: `glamelog`

- **`gd`** (🌐 Ambos)
  - Comando: `git diff`
  - Descrição: Exibe diferenças não staged.
  - Exemplo: `gd`

- **`gds`** (🌐 Ambos)
  - Comando: `git diff --staged`
  - Descrição: Exibe diferenças já em stage.
  - Exemplo: `gds`

- **`gb`** (🌐 Ambos)
  - Comando: `git branch`
  - Descrição: Lista branches locais.
  - Exemplo: `gb`

- **`gba`** (🌐 Ambos)
  - Comando: `git branch -a`
  - Descrição: Lista todas as branches incluindo remotas.
  - Exemplo: `gba`

- **`gbd`** (🌐 Ambos)
  - Comando: `git branch -d`
  - Descrição: Remove uma branch local.
  - Exemplo: `gbd feature/x`

- **`gtag`** (🌐 Ambos)
  - Comando: `git tag`
  - Descrição: Cria ou lista tags.
  - Exemplo: `gtag v1.0.0`

- **`gclone`** (🌐 Ambos)
  - Comando: `git clone`
  - Descrição: Clona um repositório.
  - Exemplo: `gclone https://github.com/user/repo.git`

- **`gst`** (🌐 Ambos)
  - Comando: `git stash`
  - Descrição: Salva mudanças temporariamente no stash.
  - Exemplo: `gst`

- **`gstp`** (🌐 Ambos)
  - Comando: `git stash pop`
  - Descrição: Restaura as últimas mudanças do stash.
  - Exemplo: `gstp`

- **`grh`** (🌐 Ambos)
  - Comando: `git reset HEAD~1`
  - Descrição: Desfaz o último commit mantendo as alterações.
  - Exemplo: `grh`

- **`gundo`** (🌐 Ambos)
  - Comando: `git restore .`
  - Descrição: Descarta todas as alterações não staged.
  - Exemplo: `gundo`

- **`gwip`** (🌐 Ambos)
  - Comando: `git add -A && git commit -m "WIP"`
  - Descrição: Salva trabalho em progresso rapidamente.
  - Exemplo: `gwip`

## GitHub CLI

- **`ghpr`** (🌐 Ambos)
  - Comando: `gh pr create`
  - Descrição: Abre wizard para criar um Pull Request.
  - Exemplo: `ghpr`

- **`ghprl`** (🌐 Ambos)
  - Comando: `gh pr list`
  - Descrição: Lista Pull Requests abertos.
  - Exemplo: `ghprl`

- **`ghprv`** (🌐 Ambos)
  - Comando: `gh pr view`
  - Descrição: Exibe detalhes do PR atual.
  - Exemplo: `ghprv`

- **`ghprc`** (🌐 Ambos)
  - Comando: `gh pr checkout`
  - Descrição: Faz checkout de um PR por número.
  - Exemplo: `ghprc 42`

- **`ghprs`** (🌐 Ambos)
  - Comando: `gh pr status`
  - Descrição: Status dos PRs relacionados ao branch atual.
  - Exemplo: `ghprs`

- **`ghrl`** (🌐 Ambos)
  - Comando: `gh repo list`
  - Descrição: Lista repositórios do usuário autenticado.
  - Exemplo: `ghrl`

- **`ghrc`** (🌐 Ambos)
  - Comando: `gh repo clone`
  - Descrição: Clona um repositório.
  - Exemplo: `ghrc owner/repo`

- **`ghiss`** (🌐 Ambos)
  - Comando: `gh issue list`
  - Descrição: Lista issues abertas do repositório.
  - Exemplo: `ghiss`

- **`ghissn`** (🌐 Ambos)
  - Comando: `gh issue create`
  - Descrição: Abre wizard para criar uma nova issue.
  - Exemplo: `ghissn`

- **`ghrun`** (🌐 Ambos)
  - Comando: `gh run list`
  - Descrição: Lista execuções de CI/CD do GitHub Actions.
  - Exemplo: `ghrun`

- **`ghrunw`** (🌐 Ambos)
  - Comando: `gh run watch`
  - Descrição: Acompanha a execução do workflow em tempo real.
  - Exemplo: `ghrunw`

- **`ghwf`** (🌐 Ambos)
  - Comando: `gh workflow list`
  - Descrição: Lista workflows do GitHub Actions.
  - Exemplo: `ghwf`

- **`ghwfr`** (🌐 Ambos)
  - Comando: `gh workflow run`
  - Descrição: Dispara um workflow manualmente.
  - Exemplo: `ghwfr deploy.yml`

- **`ghrel`** (🌐 Ambos)
  - Comando: `gh release list`
  - Descrição: Lista releases do repositório.
  - Exemplo: `ghrel`

- **`ghrelc`** (🌐 Ambos)
  - Comando: `gh release create`
  - Descrição: Cria uma nova release.
  - Exemplo: `ghrelc v1.0.0`

- **`ghgist`** (🖥️ Desktop)
  - Comando: `gh gist create`
  - Descrição: Cria um Gist a partir de arquivo.
  - Exemplo: `ghgist file.sh`

- **`ghssh`** (🖥️ Desktop)
  - Comando: `gh ssh-key list`
  - Descrição: Lista chaves SSH cadastradas na conta GitHub.
  - Exemplo: `ghssh`

## SSH

- **`ssha`** (🌐 Ambos)
  - Comando: `ssh-add`
  - Descrição: Adiciona chave SSH ao agente.
  - Exemplo: `ssha ~/.ssh/id_ed25519`

- **`sshal`** (🌐 Ambos)
  - Comando: `ssh-add -l`
  - Descrição: Lista chaves carregadas no agente SSH.
  - Exemplo: `sshal`

- **`sshkeys`** (🌐 Ambos)
  - Comando: `ls -la ~/.ssh/`
  - Descrição: Lista todos os arquivos de chaves SSH.
  - Exemplo: `sshkeys`

- **`sshconfig`** (🌐 Ambos)
  - Comando: `nano ~/.ssh/config`
  - Descrição: Edita o arquivo de configuração do SSH.
  - Exemplo: `sshconfig`

- **`keygen`** (🌐 Ambos)
  - Comando: `ssh-keygen -t ed25519 -C`
  - Descrição: Gera nova chave SSH Ed25519.
  - Exemplo: `keygen 'email@x.com'`

## Docker

- **`d`** (🌐 Ambos)
  - Comando: `docker`
  - Descrição: Atalho para o comando docker.
  - Exemplo: `d ps`

- **`dc`** (🌐 Ambos)
  - Comando: `docker compose`
  - Descrição: Atalho para o docker compose.
  - Exemplo: `dc up -d`

- **`dps`** (🌐 Ambos)
  - Comando: `docker ps`
  - Descrição: Lista containers em execução.
  - Exemplo: `dps`

- **`dpsa`** (🌐 Ambos)
  - Comando: `docker ps -a`
  - Descrição: Lista todos os containers incluindo parados.
  - Exemplo: `dpsa`

- **`dimg`** (🌐 Ambos)
  - Comando: `docker images`
  - Descrição: Lista imagens Docker disponíveis localmente.
  - Exemplo: `dimg`

- **`dlog`** (🌐 Ambos)
  - Comando: `docker logs -f`
  - Descrição: Segue os logs de um container.
  - Exemplo: `dlog meu-container`

- **`dex`** (🌐 Ambos)
  - Comando: `docker exec -it`
  - Descrição: Executa comando interativo em container.
  - Exemplo: `dex app bash`

- **`dstart`** (🌐 Ambos)
  - Comando: `docker start`
  - Descrição: Inicia um container parado.
  - Exemplo: `dstart meu-container`

- **`dstop`** (🌐 Ambos)
  - Comando: `docker stop`
  - Descrição: Para um container em execução.
  - Exemplo: `dstop meu-container`

- **`drm`** (🌐 Ambos)
  - Comando: `docker rm`
  - Descrição: Remove um container.
  - Exemplo: `drm meu-container`

- **`drmi`** (🌐 Ambos)
  - Comando: `docker rmi`
  - Descrição: Remove uma imagem.
  - Exemplo: `drmi minha-imagem`

- **`dpull`** (🌐 Ambos)
  - Comando: `docker pull`
  - Descrição: Baixa imagem do registry.
  - Exemplo: `dpull nginx:alpine`

- **`dbuild`** (🌐 Ambos)
  - Comando: `docker build -t`
  - Descrição: Constrói imagem com tag.
  - Exemplo: `dbuild app:latest .`

- **`dstats`** (🌐 Ambos)
  - Comando: `docker stats`
  - Descrição: Monitora CPU/memória dos containers em tempo real.
  - Exemplo: `dstats`

- **`dins`** (🌐 Ambos)
  - Comando: `docker inspect`
  - Descrição: Inspeciona detalhes de container ou imagem.
  - Exemplo: `dins app`

- **`dip`** (🌐 Ambos)
  - Comando: `docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}'`
  - Descrição: IP do container.
  - Exemplo: `dip app`

- **`dnet`** (🌐 Ambos)
  - Comando: `docker network ls`
  - Descrição: Lista redes Docker disponíveis.
  - Exemplo: `dnet`

- **`dvol`** (🌐 Ambos)
  - Comando: `docker volume ls`
  - Descrição: Lista volumes Docker criados.
  - Exemplo: `dvol`

- **`dprune`** (🌐 Ambos)
  - Comando: `docker system prune -af --volumes`
  - Descrição: Remove todos os recursos Docker não utilizados.
  - Exemplo: `dprune`

- **`dcup`** (🌐 Ambos)
  - Comando: `docker compose up -d`
  - Descrição: Sobe os serviços em background.
  - Exemplo: `dcup`

- **`dcdown`** (🌐 Ambos)
  - Comando: `docker compose down`
  - Descrição: Para e remove os containers do compose.
  - Exemplo: `dcdown`

- **`dcstop`** (🌐 Ambos)
  - Comando: `docker compose stop`
  - Descrição: Para os serviços sem remover containers.
  - Exemplo: `dcstop`

- **`dcrestart`** (🌐 Ambos)
  - Comando: `docker compose restart`
  - Descrição: Reinicia todos os serviços do compose.
  - Exemplo: `dcrestart`

- **`dcps`** (🌐 Ambos)
  - Comando: `docker compose ps`
  - Descrição: Lista os serviços do compose e seus estados.
  - Exemplo: `dcps`

- **`dclog`** (🌐 Ambos)
  - Comando: `docker compose logs -f`
  - Descrição: Segue os logs de todos os serviços do compose.
  - Exemplo: `dclog`

- **`dclogs`** (🌐 Ambos)
  - Comando: `docker compose logs --tail=100`
  - Descrição: Exibe as últimas 100 linhas dos logs do compose.
  - Exemplo: `dclogs`

- **`dcbuild`** (🌐 Ambos)
  - Comando: `docker compose build --no-cache`
  - Descrição: Reconstrói as imagens sem cache.
  - Exemplo: `dcbuild`

- **`dcpull`** (🌐 Ambos)
  - Comando: `docker compose pull`
  - Descrição: Atualiza imagens dos serviços do compose.
  - Exemplo: `dcpull`

- **`dcexec`** (🌐 Ambos)
  - Comando: `docker compose exec`
  - Descrição: Executa comando em serviço.
  - Exemplo: `dcexec app bash`

## Gerenciadores de Pacotes

- **`update`** (🌐 Ambos)
  - Comando: `brew update && brew upgrade` (macOS) / `sudo apt update...` (Linux)
  - Descrição: Atualiza o sistema e gerenciadores de pacotes.
  - Exemplo: `update`

- **`apti`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `sudo apt install`
  - Descrição: Instala um pacote via APT.
  - Exemplo: `apti htop`

- **`aptr`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `sudo apt remove`
  - Descrição: Remove um pacote via APT.
  - Exemplo: `aptr htop`

- **`apts`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `apt search`
  - Descrição: Busca pacotes nos repositórios APT.
  - Exemplo: `apts nginx`

- **`aptshow`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `apt show`
  - Descrição: Exibe detalhes de um pacote APT.
  - Exemplo: `aptshow git`

- **`aptls`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `dpkg -l | grep`
  - Descrição: Filtra pacotes instalados.
  - Exemplo: `aptls nginx`

- **`brewup`** (🖥️ Desktop / ☁️ Server se instalado)
  - Comando: `brew update && brew upgrade && brew cleanup`
  - Descrição: Atualiza Homebrew e remove versões antigas.
  - Exemplo: `brewup`

- **`brewls`** (🖥️ Desktop / ☁️ Server se instalado)
  - Comando: `brew list`
  - Descrição: Lista todos os pacotes instalados via Homebrew.
  - Exemplo: `brewls`

- **`brewinfo`** (🖥️ Desktop / ☁️ Server se instalado)
  - Comando: `brew info`
  - Descrição: Exibe informações sobre um pacote.
  - Exemplo: `brewinfo git`

- **`brewsearch`** (🖥️ Desktop / ☁️ Server se instalado)
  - Comando: `brew search`
  - Descrição: Busca pacotes no Homebrew.
  - Exemplo: `brewsearch ripgrep`

## Linguagens & Frameworks (🖥️ Desktop)

### Laravel / PHP
- **`art`** (🖥️ Desktop)
  - Comando: `php artisan`
  - Descrição: Atalho para o PHP Artisan.
  - Exemplo: `art list`

- **`artm`** (🖥️ Desktop)
  - Comando: `php artisan migrate`
  - Descrição: Executa as migrations pendentes.
  - Exemplo: `artm`

- **`artmf`** (🖥️ Desktop)
  - Comando: `php artisan migrate:fresh`
  - Descrição: Recria todas as tabelas do zero.
  - Exemplo: `artmf`

- **`artmfs`** (🖥️ Desktop)
  - Comando: `php artisan migrate:fresh --seed`
  - Descrição: Recria as tabelas e popula com seeders.
  - Exemplo: `artmfs`

- **`arts`** (🖥️ Desktop)
  - Comando: `php artisan serve`
  - Descrição: Inicia o servidor de desenvolvimento do Laravel.
  - Exemplo: `arts`

- **`artq`** (🖥️ Desktop)
  - Comando: `php artisan queue:work`
  - Descrição: Inicia o worker de filas.
  - Exemplo: `artq`

- **`artc`** (🖥️ Desktop)
  - Comando: `php artisan cache:clear && php artisan config:clear && php artisan route:clear && php artisan view:clear`
  - Descrição: Limpa todos os caches do Laravel.
  - Exemplo: `artc`

- **`artt`** (🖥️ Desktop)
  - Comando: `php artisan test`
  - Descrição: Executa a suíte de testes do Laravel.
  - Exemplo: `artt`

- **`artmake`** (🖥️ Desktop)
  - Comando: `php artisan make`
  - Descrição: Atalho para geração de código.
  - Exemplo: `artmake:controller UserController`

- **`artr`** (🖥️ Desktop)
  - Comando: `php artisan route:list`
  - Descrição: Lista todas as rotas da aplicação.
  - Exemplo: `artr`

- **`arttink`** (🖥️ Desktop)
  - Comando: `php artisan tinker`
  - Descrição: Abre o REPL interativo do Laravel.
  - Exemplo: `arttink`

- **`artkey`** (🖥️ Desktop)
  - Comando: `php artisan key:generate`
  - Descrição: Gera uma nova chave de aplicação.
  - Exemplo: `artkey`

- **`artopt`** (🖥️ Desktop)
  - Comando: `php artisan optimize:clear`
  - Descrição: Limpa todos os caches e otimizações.
  - Exemplo: `artopt`

- **`artschedule`** (🖥️ Desktop)
  - Comando: `php artisan schedule:work`
  - Descrição: Inicia o worker de tarefas agendadas.
  - Exemplo: `artschedule`

- **`artdb`** (🖥️ Desktop)
  - Comando: `php artisan db`
  - Descrição: Abre conexão interativa com o banco de dados.
  - Exemplo: `artdb`

- **`artmodel`** (🖥️ Desktop)
  - Comando: `php artisan make:model`
  - Descrição: Cria um Model.
  - Exemplo: `artmodel Post -m`

- **`artjob`** (🖥️ Desktop)
  - Comando: `php artisan make:job`
  - Descrição: Cria um Job para filas.
  - Exemplo: `artjob ProcessPayment`

- **`artevent`** (🖥️ Desktop)
  - Comando: `php artisan event:list`
  - Descrição: Lista todos os eventos e listeners registrados.
  - Exemplo: `artevent`

- **`ci`** (🖥️ Desktop)
  - Comando: `composer install`
  - Descrição: Instala dependências do composer.json.
  - Exemplo: `ci`

- **`cu`** (🖥️ Desktop)
  - Comando: `composer update`
  - Descrição: Atualiza dependências para versões permitidas.
  - Exemplo: `cu`

- **`creq`** (🖥️ Desktop)
  - Comando: `composer require`
  - Descrição: Adiciona um pacote.
  - Exemplo: `creq vendor/pacote`

- **`creqd`** (🖥️ Desktop)
  - Comando: `composer require --dev`
  - Descrição: Adiciona pacote como dev-dependency.
  - Exemplo: `creqd phpunit/phpunit`

- **`cdump`** (🖥️ Desktop)
  - Comando: `composer dump-autoload`
  - Descrição: Regenera o autoload do Composer.
  - Exemplo: `cdump`

- **`crun`** (🖥️ Desktop)
  - Comando: `composer run`
  - Descrição: Executa um script do composer.json.
  - Exemplo: `crun dev`

### Node / JavaScript
- **`ni`** (🌐 Ambos)
  - Comando: `npm install`
  - Descrição: Instala todas as dependências do package.json.
  - Exemplo: `ni`

- **`nid`** (🌐 Ambos)
  - Comando: `npm install --save-dev`
  - Descrição: Instala pacote como dependência de desenvolvimento.
  - Exemplo: `nid typescript`

- **`nr`** (🌐 Ambos)
  - Comando: `npm run`
  - Descrição: Executa script do package.json.
  - Exemplo: `nr build`

- **`nrd`** (🌐 Ambos)
  - Comando: `npm run dev`
  - Descrição: Inicia o servidor de desenvolvimento.
  - Exemplo: `nrd`

- **`nrb`** (🌐 Ambos)
  - Comando: `npm run build`
  - Descrição: Executa o build de produção.
  - Exemplo: `nrb`

- **`nrt`** (🌐 Ambos)
  - Comando: `npm run test`
  - Descrição: Executa os testes.
  - Exemplo: `nrt`

- **`nx`** (🌐 Ambos)
  - Comando: `npx`
  - Descrição: Executa pacote Node sem instalar globalmente.
  - Exemplo: `nx create-react-app my-app`

- **`bi`** (🌐 Ambos)
  - Comando: `bun install`
  - Descrição: Instala dependências com Bun.
  - Exemplo: `bi`

- **`br`** (🌐 Ambos)
  - Comando: `bun run`
  - Descrição: Executa script com Bun.
  - Exemplo: `br dev`

- **`brd`** (🌐 Ambos)
  - Comando: `bun run dev`
  - Descrição: Inicia o dev server com Bun.
  - Exemplo: `brd`

- **`brb`** (🌐 Ambos)
  - Comando: `bun run build`
  - Descrição: Build de produção com Bun.
  - Exemplo: `brb`

- **`bx`** (🌐 Ambos)
  - Comando: `bunx`
  - Descrição: Executa pacote sem instalar, via Bun.
  - Exemplo: `bx cowsay hello`

- **`pn`** (🖥️ Desktop)
  - Comando: `pnpm`
  - Descrição: Atalho para o pnpm.
  - Exemplo: `pn add axios`

- **`pni`** (🖥️ Desktop)
  - Comando: `pnpm install`
  - Descrição: Instala dependências com pnpm.
  - Exemplo: `pni`

- **`pnr`** (🖥️ Desktop)
  - Comando: `pnpm run`
  - Descrição: Executa script do package.json via pnpm.
  - Exemplo: `pnr build`

- **`pnd`** (🖥️ Desktop)
  - Comando: `pnpm run dev`
  - Descrição: Inicia o dev server com pnpm.
  - Exemplo: `pnd`

- **`pnb`** (🖥️ Desktop)
  - Comando: `pnpm run build`
  - Descrição: Build de produção com pnpm.
  - Exemplo: `pnb`

- **`pnt`** (🖥️ Desktop)
  - Comando: `pnpm run test`
  - Descrição: Executa os testes com pnpm.
  - Exemplo: `pnt`

- **`pnx`** (🖥️ Desktop)
  - Comando: `pnpm dlx`
  - Descrição: Executa pacote sem instalar via pnpm.
  - Exemplo: `pnx create-next-app`

- **`pnadd`** (🖥️ Desktop)
  - Comando: `pnpm add`
  - Descrição: Adiciona dependência com pnpm.
  - Exemplo: `pnadd axios`

- **`pnaddd`** (🖥️ Desktop)
  - Comando: `pnpm add -D`
  - Descrição: Adiciona dev-dependency com pnpm.
  - Exemplo: `pnaddd vitest`

### Python / uv
- **`py`** (🖥️ Desktop)
  - Comando: `python3`
  - Descrição: Atalho para Python 3.
  - Exemplo: `py main.py`

- **`pyv`** (🖥️ Desktop)
  - Comando: `python3 --version`
  - Descrição: Exibe a versão ativa do Python.
  - Exemplo: `pyv`

- **`uvi`** (🖥️ Desktop)
  - Comando: `uv pip install`
  - Descrição: Instala pacote Python com uv.
  - Exemplo: `uvi requests`

- **`uvs`** (🖥️ Desktop)
  - Comando: `uv run`
  - Descrição: Executa script com uv.
  - Exemplo: `uvs main.py`

- **`venv`** (🖥️ Desktop)
  - Comando: `python3 -m venv .venv && source .venv/bin/activate`
  - Descrição: Cria e ativa virtualenv local.
  - Exemplo: `venv`

- **`activate`** (🖥️ Desktop)
  - Comando: `source .venv/bin/activate`
  - Descrição: Ativa o virtualenv local do diretório.
  - Exemplo: `activate`

### Ruby / rbenv
- **`rbv`** (🖥️ Desktop)
  - Comando: `rbenv versions`
  - Descrição: Lista versões do Ruby instaladas via rbenv.
  - Exemplo: `rbv`

- **`rblocal`** (🖥️ Desktop)
  - Comando: `rbenv local`
  - Descrição: Define versão do Ruby para o diretório atual.
  - Exemplo: `rblocal 3.2.0`

- **`rbglobal`** (🖥️ Desktop)
  - Comando: `rbenv global`
  - Descrição: Define a versão global do Ruby.
  - Exemplo: `rbglobal 3.2.0`

- **`be`** (🖥️ Desktop)
  - Comando: `bundle exec`
  - Descrição: Executa comando no contexto do Bundler.
  - Exemplo: `be rails s`

- **`binstall`** (🖥️ Desktop)
  - Comando: `bundle install`
  - Descrição: Instala gems do Gemfile.
  - Exemplo: `binstall`

- **`bupdate`** (🖥️ Desktop)
  - Comando: `bundle update`
  - Descrição: Atualiza gems do Gemfile.
  - Exemplo: `bupdate`

### Rust / Cargo
- **`cb`** (🖥️ Desktop)
  - Comando: `cargo build`
  - Descrição: Compila o projeto Rust em modo debug.
  - Exemplo: `cb`

- **`cbr`** (🖥️ Desktop)
  - Comando: `cargo build --release`
  - Descrição: Compila em modo release otimizado.
  - Exemplo: `cbr`

- **`crun2`** (🖥️ Desktop)
  - Comando: `cargo run`
  - Descrição: Compila e executa o projeto Rust.
  - Exemplo: `crun2`

- **`ct`** (🖥️ Desktop)
  - Comando: `cargo test`
  - Descrição: Executa os testes do projeto.
  - Exemplo: `ct`

- **`ccheck`** (🖥️ Desktop)
  - Comando: `cargo check`
  - Descrição: Verifica erros sem gerar o binário.
  - Exemplo: `ccheck`

- **`clippy`** (🖥️ Desktop)
  - Comando: `cargo clippy`
  - Descrição: Executa o linter do Rust.
  - Exemplo: `clippy`

- **`cfmt`** (🖥️ Desktop)
  - Comando: `cargo fmt`
  - Descrição: Formata o código com rustfmt.
  - Exemplo: `cfmt`

- **`cadd`** (🖥️ Desktop)
  - Comando: `cargo add`
  - Descrição: Adiciona dependência ao projeto Rust.
  - Exemplo: `cadd serde`

- **`crem`** (🖥️ Desktop)
  - Comando: `cargo remove`
  - Descrição: Remove dependência do projeto Rust.
  - Exemplo: `crem serde`

- **`cupdate`** (🖥️ Desktop)
  - Comando: `cargo update`
  - Descrição: Atualiza todas as dependências do Cargo.lock.
  - Exemplo: `cupdate`

- **`cdoc`** (🖥️ Desktop)
  - Comando: `cargo doc --open`
  - Descrição: Gera e abre a documentação do projeto no browser.
  - Exemplo: `cdoc`

### Go
- **`gobuild`** (🖥️ Desktop)
  - Comando: `go build ./...`
  - Descrição: Compila todos os pacotes do projeto Go.
  - Exemplo: `gobuild`

- **`gorun`** (🖥️ Desktop)
  - Comando: `go run .`
  - Descrição: Executa o pacote principal.
  - Exemplo: `gorun`

- **`gotest`** (🖥️ Desktop)
  - Comando: `go test ./...`
  - Descrição: Executa todos os testes do projeto.
  - Exemplo: `gotest`

- **`gomod`** (🖥️ Desktop)
  - Comando: `go mod tidy`
  - Descrição: Remove dependências não utilizadas do go.mod.
  - Exemplo: `gomod`

- **`govet`** (🖥️ Desktop)
  - Comando: `go vet ./...`
  - Descrição: Verifica problemas comuns no código Go.
  - Exemplo: `govet`

- **`gofmt`** (🖥️ Desktop)
  - Comando: `gofmt -w .`
  - Descrição: Formata todos os arquivos Go do diretório.
  - Exemplo: `gofmt`

- **`goget`** (🖥️ Desktop)
  - Comando: `go get`
  - Descrição: Adiciona dependência ao projeto Go.
  - Exemplo: `goget github.com/gin-gonic/gin`

- **`goclean`** (🖥️ Desktop)
  - Comando: `go clean -cache`
  - Descrição: Remove o cache de build do Go.
  - Exemplo: `goclean`

- **`gocover`** (🖥️ Desktop)
  - Comando: `go test ./... -coverprofile=coverage.out && go tool cover -html=coverage.out`
  - Descrição: Cobertura HTML.
  - Exemplo: `gocover`

- **`gowork`** (🖥️ Desktop)
  - Comando: `go work`
  - Descrição: Gerencia workspaces Go.
  - Exemplo: `gowork use ./pkg`

## DevOps & Sistema

- **`anp`** (🌐 Ambos)
  - Comando: `ansible-playbook`
  - Descrição: Executa um playbook.
  - Exemplo: `anp site.yml -i hosts`

- **`ani`** (🌐 Ambos)
  - Comando: `ansible-inventory --list`
  - Descrição: Exibe o inventário em formato JSON.
  - Exemplo: `ani`

- **`anping`** (🌐 Ambos)
  - Comando: `ansible all -m ping`
  - Descrição: Testa conectividade com todos os hosts.
  - Exemplo: `anping`

- **`anv`** (🌐 Ambos)
  - Comando: `ansible-vault`
  - Descrição: Gerencia arquivos criptografados com Vault.
  - Exemplo: `anv edit secrets.yml`

- **`anve`** (🌐 Ambos)
  - Comando: `ansible-vault encrypt`
  - Descrição: Criptografa um arquivo com Vault.
  - Exemplo: `anve secrets.yml`

- **`anvd`** (🌐 Ambos)
  - Comando: `ansible-vault decrypt`
  - Descrição: Descriptografa um arquivo com Vault.
  - Exemplo: `anvd secrets.yml`

- **`anvr`** (🌐 Ambos)
  - Comando: `ansible-vault rekey`
  - Descrição: Recriptografa com nova senha.
  - Exemplo: `anvr secrets.yml`

- **`ancheck`** (🌐 Ambos)
  - Comando: `ansible-playbook --check`
  - Descrição: Simula execução do playbook sem aplicar mudanças.
  - Exemplo: `ancheck site.yml`

- **`andiff`** (🌐 Ambos)
  - Comando: `ansible-playbook --check --diff`
  - Descrição: Simula e exibe diff das mudanças que seriam aplicadas.
  - Exemplo: `andiff site.yml`

- **`anfacts`** (🌐 Ambos)
  - Comando: `ansible all -m setup`
  - Descrição: Coleta facts de todos os hosts do inventário.
  - Exemplo: `anfacts`

### Monitoramento & Processos
- **`topc`** (🌐 Ambos)
  - Comando: `top -o cpu` (macOS) / `top -bn1 | head -20` (Linux)
  - Descrição: Monitora processos ordenados por uso de CPU.
  - Exemplo: `topc`

- **`topm`** (🖥️ Desktop macOS)
  - Comando: `top -o mem`
  - Descrição: Monitora processos ordenados por uso de memória.
  - Exemplo: `topm`

- **`psg`** (🌐 Ambos)
  - Comando: `ps aux | grep`
  - Descrição: Busca processos por nome.
  - Exemplo: `psg nginx`

- **`df`** (🌐 Ambos)
  - Comando: `df -h`
  - Descrição: Uso de disco com tamanhos legíveis.
  - Exemplo: `df`

- **`meminfo`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `free -h`
  - Descrição: Exibe uso de memória RAM e swap.
  - Exemplo: `meminfo`

- **`diskinfo`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `df -h`
  - Descrição: Exibe uso de disco de todas as partições.
  - Exemplo: `diskinfo`

- **`cpuinfo`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `lscpu`
  - Descrição: Exibe informações detalhadas sobre a CPU.
  - Exemplo: `cpuinfo`

- **`sysinfo`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `hostnamectl`
  - Descrição: Exibe informações do sistema operacional e hostname.
  - Exemplo: `sysinfo`

### Systemd (Linux)
- **`sstatus`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `sudo systemctl status`
  - Descrição: Exibe o status de um serviço.
  - Exemplo: `sstatus nginx`

- **`sstart`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `sudo systemctl start`
  - Descrição: Inicia um serviço.
  - Exemplo: `sstart nginx`

- **`sstop`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `sudo systemctl stop`
  - Descrição: Para um serviço.
  - Exemplo: `sstop nginx`

- **`srestart`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `sudo systemctl restart`
  - Descrição: Reinicia um serviço.
  - Exemplo: `srestart nginx`

- **`senable`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `sudo systemctl enable`
  - Descrição: Habilita um serviço para iniciar no boot.
  - Exemplo: `senable nginx`

- **`sdisable`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `sudo systemctl disable`
  - Descrição: Desabilita um serviço no boot.
  - Exemplo: `sdisable nginx`

- **`slogs`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `sudo journalctl -u`
  - Descrição: Exibe logs de um serviço específico.
  - Exemplo: `slogs nginx`

- **`syslog`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `sudo journalctl -f`
  - Descrição: Segue o log do sistema em tempo real.
  - Exemplo: `syslog`

## Rede & Web

- **`myip`** (🌐 Ambos)
  - Comando: `curl -s ifconfig.me`
  - Descrição: Exibe o IP público da máquina.
  - Exemplo: `myip`

- **`localip`** (🌐 Ambos)
  - Comando: `ipconfig getifaddr en0` (macOS) / `hostname -I...` (Linux)
  - Descrição: Exibe o IP local principal da máquina.
  - Exemplo: `localip`

- **`ports`** (🌐 Ambos)
  - Comando: `lsof -iTCP -sTCP:LISTEN -n -P` (macOS) / `ss -tulnp` (Linux)
  - Descrição: Lista todas as portas em escuta.
  - Exemplo: `ports`

- **`wholistening`** (☁️ Server / 🖥️ Desktop Linux)
  - Comando: `ss -tulnp`
  - Descrição: Alias alternativo para listar portas em escuta.
  - Exemplo: `wholistening`

- **`flush`** (🌐 Ambos)
  - Comando: `dscacheutil...` (macOS) / `sudo systemd-resolve...` (Linux)
  - Descrição: Limpa o cache de DNS.
  - Exemplo: `flush`

### cURL / HTTP
- **`get`** (🌐 Ambos)
  - Comando: `curl -s`
  - Descrição: GET request simples.
  - Exemplo: `get https://api.github.com`

- **`post`** (🌐 Ambos)
  - Comando: `curl -s -X POST -H 'Content-Type: application/json'`
  - Descrição: POST JSON simples.
  - Exemplo: `post url -d '{"key":"val"}'`

- **`headers`** (🌐 Ambos)
  - Comando: `curl -sI`
  - Descrição: Exibe apenas os headers HTTP da resposta.
  - Exemplo: `headers google.com`

- **`httpcode`** (🌐 Ambos)
  - Comando: `curl -o /dev/null -s -w '%{http_code}\n'`
  - Descrição: Exibe somente o código HTTP da resposta.
  - Exemplo: `httpcode google.com`

- **`timing`** (🌐 Ambos)
  - Comando: `curl -o /dev/null -s -w 'dns:%{time_namelookup}s...'`
  - Descrição: Latência detalhada.
  - Exemplo: `timing google.com`

### JSON / YAML
- **`jpp`** (🌐 Ambos)
  - Comando: `python3 -m json.tool`
  - Descrição: Formata e valida JSON.
  - Exemplo: `cat data.json | jpp`

- **`jsonf`** (🌐 Ambos)
  - Comando: `jq .`
  - Descrição: Formata JSON com cores via jq.
  - Exemplo: `cat data.json | jsonf`

### Segurança & Certs
- **`certinfo`** (🌐 Ambos)
  - Comando: `openssl x509 -text -noout -in`
  - Descrição: Exibe detalhes de um certificado .pem.
  - Exemplo: `certinfo cert.pem`

- **`certexpiry`** (🌐 Ambos)
  - Comando: `openssl x509 -enddate -noout -in`
  - Descrição: Exibe a data de expiração de um certificado.
  - Exemplo: `certexpiry cert.pem`

- **`sslcheck`** (🌐 Ambos)
  - Comando: `openssl s_client -connect`
  - Descrição: Inspeciona TLS de um host.
  - Exemplo: `sslcheck google.com:443`

- **`genpass`** (🌐 Ambos)
  - Comando: `openssl rand -base64 32`
  - Descrição: Gera uma senha aleatória segura de 32 bytes.
  - Exemplo: `genpass`

### Ambiente
- **`envls`** (🌐 Ambos)
  - Comando: `env | sort`
  - Descrição: Lista todas as variáveis de ambiente ordenadas.
  - Exemplo: `envls`

- **`envg`** (🌐 Ambos)
  - Comando: `env | grep`
  - Descrição: Filtra variáveis de ambiente.
  - Exemplo: `envg PATH`

- **`dotenv`** (🌐 Ambos)
  - Comando: `export $(cat .env | grep -v '^#' | xargs)`
  - Descrição: Carrega variáveis do arquivo .env atual.
  - Exemplo: `dotenv`

---
> Follow the formatting guide: [Markdown Format Guide](.claude/commands/markdown-format.md)
