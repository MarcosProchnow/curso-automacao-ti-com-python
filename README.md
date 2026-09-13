# Automação de TI com Python — do script ao servidor

Código do curso gratuito do canal **[Professor Prochnow](https://www.youtube.com/@ProfessorProchnowTI)**.
Aula nova toda **terça, 20h**.

> Você já sabe qual tarefa te toma tempo. Nesse curso a gente escreve o script que faz ela por você.

Nenhuma aula ensina Python com lista de compras. Cada aula automatiza uma tarefa que quem
trabalha com infraestrutura faz na mão hoje: baixar a config de doze equipamentos, procurar
IP no log, manter a planilha de inventário, conferir se o serviço subiu.

## O projeto: Sentinela, o robô de plantão

Uma base de código só, que cresce da aula 1 à 17 e nunca é reescrita:

```
aula  1  →  um script que apaga backup velho
aula  4  →  o log vira relatório que o chefe lê
aula  6  →  config de N equipamentos, baixada e datada
aula 11  →  inventário que se atualiza sozinho
aula 13  →  alerta no celular quando o disco passa de 85%
aula 15  →  roda todo dia às 6h, sem ninguém clicar
aula 16  →  sentinela backup | varrer | inventario
aula 17  →  sentinela explicar — o log da madrugada, em português
```

## Como acompanhar a partir de qualquer aula

**Você não precisa ter visto as aulas anteriores.** Cada aula tem uma tag com o estado do
projeto no fim dela. Para começar da aula 11, baixe a tag da aula 10:

```bash
git clone https://github.com/MarcosProchnow/curso-automacao-ti-com-python
cd curso-automacao-ti-com-python
git checkout aula-10
```

A branch `main` está sempre no estado final do curso.

## As aulas

| Aula | Título | Tag | Vídeo |
|---:|---|---|---|
| 01 | O primeiro script que apaga backup velho sozinho | `aula-01` | *em breve* |
| 02 | Achando no log quem está tentando entrar no seu servidor | `aula-02` | *em breve* |
| 03 | Expressão regular no log de verdade (IP, data, usuário) | `aula-03` | *em breve* |
| 04 | Do log bruto ao relatório diário em CSV | `aula-04` | *em breve* |
| 05 | Rodando comando no servidor por SSH, sem abrir o PuTTY | `aula-05` | *em breve* |
| 06 | Backup automático da configuração dos seus equipamentos | `aula-06` | *em breve* |
| 07 | netmiko — o mesmo backup em switch e firewall de verdade | `aula-07` | *em breve* |
| 08 | Tirando a senha de dentro do script (e o que fazer no lugar) | `aula-08` | *em breve* |
| 09 | Varrendo 254 IPs em segundos para saber quem está ligado | `aula-09` | *em breve* |
| 10 | Porta aberta e serviço de pé — a checagem de saúde | `aula-10` | *em breve* |
| 11 | Inventário que se atualiza sozinho | `aula-11` | *em breve* |
| 12 | Consumindo API REST com requests (e tratando o erro de verdade) | `aula-12` | *em breve* |
| 13 | Alerta no Telegram e por e-mail quando o disco encher | `aula-13` | *em breve* |
| 14 | O script que não morre calado — log, erro e rastro | `aula-14` | *em breve* |
| 15 | Agendando de verdade — Agendador do Windows, cron e systemd timer | `aula-15` | *em breve* |
| 16 | Empacotando o Sentinela — CLI, arquivo de configuração e Git | `aula-16` | *em breve* |
| 17 | O script que pede ajuda para uma LLM para explicar o log | `aula-17` | *em breve* |

## O que você precisa

- **Python 3.13** ([python.org](https://www.python.org/downloads/)) — a aula 1 instala do zero
- Um computador com 8 GB de RAM
- **Não precisa** de servidor nem de hardware: o laboratório é criado de graça na aula 5

Bibliotecas usadas ao longo do curso, cada uma apresentada na aula em que aparece:

```bash
python -m pip install -r requirements.txt
```

## Pré-requisito de gente, não de máquina

Você sabe o que é IP, porta, SSH e log. **Não precisa saber programar** — o curso assume
zero linha de Python escrita antes.

## Licença

[MIT](LICENSE) — use no trabalho, copie, modifique. Se ajudou, deixa uma estrela e um
comentário no vídeo contando o que você automatizou.
