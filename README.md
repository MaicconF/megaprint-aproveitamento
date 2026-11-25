# Aproveitamento MegaPrint

Calculadora de aproveitamento para os computadores da gráfica.

1. Escolha a medida do material (A4, A3, meio metro DTF, 1 m²).
2. Digite a largura e a altura da peça em centímetros.
3. Aperte **Calcular**: o pop-up mostra a quantidade total, quantas cabem na largura e na altura.

Espaçamento padrão de 1 cm entre as peças e em todas as bordas. A calculadora testa a peça normal e girada e mostra a que rende mais.
**Várias medidas juntas:** no passo 3 dá pra colocar várias medidas com quantidade (ex.: 3×3, 10×15 e 20×30 no DTF) e ver quantas folhas/metros precisa, com o desenho da montagem.

As medidas podem ser editadas na própria página (ficam salvas no navegador de cada computador).

É um arquivo só (`index.html`), sem instalação. Publicado pelo GitHub Pages.

## Montagem de fotos na A4 (`montagem.html`)

Sobe as fotos, escolhe a medida (10×15 sai 10×14,6, 3×4, 5×7, 13×18, 15×21...) e a quantidade.
No quadro de cada foto dá pra arrastar pra ajustar o corte, usar o zoom e o botão Girar foto.
As fotos são montadas nas folhas A4 (margem da impressora de 0,25 cm) e saem em PDF ou direto pra impressão.
Tudo roda no navegador, as fotos não saem do computador.

## Montagem de livreto (`livreto.html`)

Sobe as páginas do livro (JPEG ou PNG) na ordem: capa, miolo e contracapa. A página completa até múltiplo de 4 com páginas extras (em branco, ou com uma imagem avulsa em cada uma), sempre antes da contracapa.
Gera o PDF de impressão frente e verso (A4 deitado com páginas A5, A3 com páginas A4 ou medida própria), já na ordem certa para dobrar ao meio e encaixar, sem folha em branco sobrando.
Também baixa um PDF na ordem de leitura para conferência. Dá para dividir ao meio imagens que trazem duas páginas lado a lado, mudar a ordem com as setas e escolher virar pela borda curta ou longa.
JPEG entra no PDF sem recompressão (a arte não é alterada). Tudo roda no navegador, nada é enviado.

