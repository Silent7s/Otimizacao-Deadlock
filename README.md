# Otimização-Deadlock
Mods de Otimização que eu considero uteis e essenciais para Deadlock, Apresentarei cada um dos mods o que eles fazem, sua pagina oficial de download, seu autor, Imagens demonstrando exemplos e logo após no final do texto dividir em que mods eu recomendo para cada tipo de Maquina.


# Particulas

## [Clutter Be Gone](https://gamebanana.com/mods/722853) by [@laund](https://github.com/laundmo)
<img width="1920" height="1080" alt="Credits Laund" src="https://github.com/user-attachments/assets/fa94d4d6-4ddb-4b8e-8fac-1d8fb2725315" />
O que ele faz: Remove as partículas e efeitos de tela desnecessários para a gameplay sem remover as informações que você precisa, assim reduzindo quedas de fps durante fights com uso simultaneo de varias habilidades ao mesmo tempo.<br>
Link para a pagina de download do mod: https://gamebanana.com/mods/722853


## [Brighter lighting](https://deadlockconfig.com/#o-brighterlighting) By BreadRollius
<img width="666" height="375" alt="deadlockconfig com_ (3)" src="https://github.com/user-attachments/assets/2e171b70-db01-4f19-b786-89736c625267" /><br>
O que ele faz: Vignette, exposição local e bloom são processamentos aplicados à tela inteira, abrangendo cada pixel em cada quadro. Um mapeamento de tons (tonemap) reajustado mantém a imagem brilhante, e nuvens em funil menores todas essas modificações resultam em menos elementos renderizados com transparência; somado ao tonemap feito pelo autor do mod deixando a imagem mais brilhante.<br>
Link para a pagina de download do mod: https://deadlockconfig.com/#o-brighterlighting

# Texturas

## [Low detail map](https://deadlockconfig.com/#o-lowdetailmap) By jcStani
<img width="623" height="350" alt="deadlockconfig com_" src="https://github.com/user-attachments/assets/f33cd5a6-12d5-4fec-8c77-cee3a6795135"/><br>
O que ele faz: Reduz a qualidade das Texturas sem comprometer a Iluminação e os detalhes Importantes uma solução menos extrema que potatolock e o Texture Downscaler Mod apresentado abaixo.<br>
Pagina de Download do mod: https://deadlockconfig.com/#o-lowdetailmap


## [Sinner Light Fix Mod](https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Sinner%20Light%20Fix%20Mod)
<img width="1280" height="720" alt="p3lhjkxqvizh1" src="https://github.com/user-attachments/assets/16f71deb-e0ec-4ff9-97d4-68142518dcad" /><br>
O que ele faz: se você baixar a qualidade das texturas usando r_texture_stream_mip_bias para um valor acima de 4 as luzes dos sinners param de aparecer corretamente para você esse mod faz com que as luzes apareçam novamente independente de que valor você configurar suas texturas.<br>
Pagina de Download do mod: https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Sinner%20Light%20Fix%20Mod

## [Texture downscaler Mod](https://gamebanana.com/dl/1865013) By Sqooky
<img width="3438" height="1440" alt="screenshot_20261003_130328-region" src="https://github.com/user-attachments/assets/cc40782d-2eda-46b8-9326-1ace2da74a0f" />
O que ele faz: Reduz as texturas do jogo a um estado a reduzir o consumo de vram do jogo ao menor possivel suas vantagens em relação a outros mods semelhantes, como o potatolock, que tentam fazer isso manipulando mipmaps — uma abordagem que, por vezes, é ineficaz, já que algumas texturas ignoram os mipmaps e acabam sendo carregadas em alta resolução de qualquer maneira.<br>
Pagina de Download do mod: https://gamebanana.com/dl/1865013

# HUD


## [HUD++](https://deadlockconfig.com/) By HoppCX and jcStani
<img width="789" height="828" alt="image" src="https://github.com/user-attachments/assets/48a6ec6d-d216-4c9d-b1a3-fe36d58c6896" /><br>
O que ele faz: transforma animações do hud como a de cooldown de Ults, Itens e habilidades que fica carregando no sentido horario em somente um numero que vai mudando para que esse elemento do hud não precisar ser desenhado novamente a cada frame.<br>
**Modificações bonus pelo propio autor do mod:**
* timer de buffs
* Minimap maior e transparente
* Diferença de souls em porcentagem<br>

Pagina de Download do mod: https://deadlockconfig.com/

## [jcStani's HP Bars](https://deadlockconfig.com/#o-hpbars) By jcStani
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f7d431bd-0a22-4349-a33e-f1a1cbd3a2bb" />
O que ele faz: Simplifica a barra de vida em um estilo plano de uma folha de papel sem script fazendo o jogo a renderizar como as barras de vida originais do começo do jogo, no meio de uma fight com muitos herois na tela e barras de vida atualizando toda hora com debuff e indicadores de stamina muito complicados isso faz diferença em grande parte em reduzir o quanto seu fps cai durante uma grande luta do que os aumentar devido a seu maior peso em desempenho ser em lutas com muitos jogadores em uma só area.<br>
Pagina de Download do mod: https://deadlockconfig.com/#o-hpbars


## [Blur Disabler](https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Blur%20Disabler) By Sqooky and Bytenode

O que ele faz: Este mod desativa todo o desfoque presente nos elementos da interface, o que reduz significativamente (no meu caso(Sqooky)) as travadas.
Pagina de Download do mod: https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Blur%20Disabler

# Engine


## [Sound stack update cap](https://deadlockconfig.com/#o-soundcap) by HoppCX: *A reprodução de sons é atualizada cerca de 60 vezes por segundo, em vez de a cada quadro.*
<img width="1360" height="784" alt="Gemini_Generated_Image_yk567lyk567lyk56" src="https://github.com/user-attachments/assets/488639f0-d312-4983-b92c-d83fa3b4ca29" />
Descrição traduzida: Cada som tem um lugar no mundo: a intensidade com que ele é ouvido em cada ouvido depende da sua localização e da posição em que você se encontra. O jogo realiza esse cálculo para cada som em reprodução a cada quadro (frame) — e, em uma luta de equipe, cerca de 80 sons podem estar sendo reproduzidos simultaneamente. Para evitar sobrecarga, o processamento de cada som ocorre em intervalos de 15 a 17 ms — uma frequência próxima à com que o servidor envia as posições (64 vezes por segundo) —, utilizando um temporizador aleatório individual para distribuir a carga de processamento entre os quadros. Vale ressaltar que os sons começam a ser reproduzidos exatamente no momento em que são acionados.


