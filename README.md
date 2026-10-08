# Organograma PhizChat

Organograma interativo das BUs PhizChat (Brasil e China), publicado pelo GitHub Pages.

O conteúdo é protegido por frase-chave. O `index.html` deste repositório guarda os dados cifrados (AES-256-GCM, chave derivada por PBKDF2-SHA256 com 600 mil iterações). Sem a frase, o arquivo só mostra a tela de acesso, e o código-fonte não expõe nomes, cargos nem a estrutura.

## Como abrir

Acesse o endereço do GitHub Pages deste repositório e digite a frase-chave.

## Como atualizar

1. Abra o organograma (pelo site ou pelo artefato no claude.ai) e faça as edições.
2. Clique em **Baixar versão protegida** (no site) ou em **Exportar → Versão protegida para o GitHub** (no claude.ai). No site a frase já usada para abrir é mantida.
3. Substitua o `index.html` deste repositório pelo arquivo baixado: **Add file → Upload files**, arraste o `index.html` e confirme o commit.
4. Em um ou dois minutos o site mostra a nova versão.

## Cuidados

- Nunca suba para cá uma versão sem cifragem do organograma. O histórico do git guarda tudo, inclusive versões antigas.
- Use sempre a mesma frase-chave combinada. Se ela vazar, gere uma nova versão protegida com outra frase e substitua o `index.html`.
- Quem tem a frase consegue abrir e repassar o conteúdo. Compartilhe só com quem precisa.
