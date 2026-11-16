# Otimização-Deadlock
Mods de otimização que eu considero úteis e essenciais para Deadlock. Apresentarei cada um dos mods, o que eles fazem, sua página oficial de download, seu autor, imagens demonstrando exemplos e, logo após, no final do texto, dividirei quais mods eu recomendo para cada tipo de máquina.
<br>
<br>

## [Gameinfo](https://github.com/Sqooky/OptimizationLock/#table)

**Recomendações:**
* [Sqooky's Config/Optimizationlock Default](https://github.com/Sqooky/OptimizationLock/blob/main/Sqooky's%20.gi/gameinfo.gi): Para maior performance sem perdas visuais.
* [Sqooky's Max FPS Config](https://github.com/Sqooky/OptimizationLock/blob/main/maximumfps%20or%20minimum%20spec%20config%20and%20resources%20here/gameinfo.gi): Configuração focada em FPS, porém ainda mantém o jogo com uma aparência aceitável.
* [Kaizuchaneru's Minimum Spec](https://github.com/Sqooky/OptimizationLock/blob/main/kaizuchanerus%20minimum%20spec/gameinfo.gi): Focada em FPS acima de tudo, fazendo a aparência do jogo diferir muito do original.
<br>

# Mods de Partículas
<br>

## [Clutter Be Gone](https://gamebanana.com/mods/722853) by [@laund](https://github.com/laundmo)
<img width="1920" height="1080" alt="Credits Laund" src="https://github.com/user-attachments/assets/fa94d4d6-4ddb-4b8e-8fac-1d8fb2725315" />
O que ele faz: Remove as partículas e efeitos de tela desnecessários para a gameplay sem remover as informações que você precisa, assim reduzindo quedas de FPS durante fights com uso simultâneo de várias habilidades ao mesmo tempo.<br>
Link para a página de download do mod: https://gamebanana.com/mods/722853
<br>
<br>

## [Brighter lighting](https://deadlockconfig.com/#o-brighterlighting) By BreadRollius
<img width="1920" height="1080" alt="Mais brilhante" src="https://github.com/user-attachments/assets/f1aa40ba-7cfe-4add-bbf2-c0b660f606d6" /><br>
O que ele faz: Vignette, exposição local e bloom são processamentos aplicados à tela inteira, abrangendo cada pixel em cada quadro. Um mapeamento de tons (tonemap) reajustado mantém a imagem brilhante, e nuvens em funil menores; todas essas modificações resultam em menos elementos renderizados com transparência, somadas ao tonemap feito pelo autor do mod, deixando a imagem mais brilhante.<br>
Link para a página de download do mod: https://deadlockconfig.com/#o-brighterlighting<br>
<br>
<br>

# Mods de Texturas
<br>

## [Low detail map](https://deadlockconfig.com/#o-lowdetailmap) By jcStani

| Stock (Original) | Low Detail Map (Modificado) |
| :---: | :---: |
| <img width="1920" height="1080" alt="Texturas antes" src="https://github.com/user-attachments/assets/3e0de8f3-3566-4665-8847-e3b3feaff1b9" /> | <img width="1920" height="1080" alt="Texturas Depois" src="https://github.com/user-attachments/assets/994879c4-d5cc-478b-9a49-d7662149e87e" /> |

O que ele faz: Reduz a qualidade das texturas sem comprometer a iluminação e os detalhes importantes; é uma solução menos extrema que o Potatolock e o Texture Downscaler Mod apresentado abaixo.<br>
Página de download do mod: https://deadlockconfig.com/#o-lowdetailmap
<br>
<br>

## [Sinner Light Fix Mod](https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Sinner%20Light%20Fix%20Mod) By HoppCX
<img width="1280" height="720" alt="p3lhjkxqvizh1" src="https://github.com/user-attachments/assets/16f71deb-e0ec-4ff9-97d4-68142518dcad" /><br>
O que ele faz: Se você baixar a qualidade das texturas usando r_texture_stream_mip_bias para um valor acima de 4, as luzes dos Sinners param de aparecer corretamente para você; este mod faz com que as luzes apareçam novamente, independentemente do valor que você configurar para suas texturas.<br>
Página de download do mod: https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Sinner%20Light%20Fix%20Mod
<br>
<br>

## [Texture downscaler Mod](https://gamebanana.com/dl/1865013) By Sqooky
<img width="3438" height="1440" alt="screenshot_20261003_130328-region" src="https://github.com/user-attachments/assets/cc40782d-2eda-46b8-9326-1ace2da74a0f" />
O que ele faz: Reduz as texturas do jogo a um estado que reduz o consumo de VRAM do jogo ao menor possível. Suas vantagens em relação a outros mods semelhantes, como o Potatolock, que tentam fazer isso manipulando mipmaps — uma abordagem que, por vezes, é ineficaz, já que algumas texturas ignoram os mipmaps e acabam sendo carregadas em alta resolução de qualquer maneira.<br>
Página de download do mod: https://gamebanana.com/dl/1865013<br>
<br>
<br>

# Mods de HUD
<br>

## [HUD++](https://deadlockconfig.com/) By HoppCX and jcStani
<img width="789" height="828" alt="image" src="https://github.com/user-attachments/assets/48a6ec6d-d216-4c9d-b1a3-fe36d58c6896" /><br>
O que ele faz: Transforma animações do HUD, como a de cooldown de Ults, itens e habilidades, que ficam carregando no sentido horário, em somente um número que vai mudando, para que esse elemento do HUD não precise ser desenhado novamente a cada frame.<br>
**Modificações bônus pelo próprio autor do mod:**
* timer de buffs
* Minimap maior e transparente
* Diferença de souls em porcentagem<br>

Página de download do mod: https://deadlockconfig.com/
<br>
<br>

## [jcStani's HP Bars](https://deadlockconfig.com/#o-hpbars) By jcStani
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f7d431bd-0a22-4349-a33e-f1a1cbd3a2bb" />
O que ele faz: Simplifica a barra de vida em um estilo plano, como uma folha de papel, sem scripts, fazendo o jogo renderizar como as barras de vida originais do começo do jogo. No meio de uma fight com muitos heróis na tela e barras de vida atualizando toda hora com debuffs e indicadores de stamina muito complicados, isso faz diferença principalmente em reduzir o quanto seu FPS cai durante uma grande luta, em vez de aumentá-lo, devido ao seu maior peso em desempenho ser em lutas com muitos jogadores em uma só área.<br>
Página de download do mod: https://deadlockconfig.com/#o-hpbars
<br>
<br>

## [Blur Disabler](https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Blur%20Disabler) By Sqooky and Bytenode
<img width="1920" height="1080" alt="BLUR3" src="https://github.com/user-attachments/assets/48a4ff52-c26f-4a09-8f12-39055f9440fb" /><br>
O que ele faz: Desativa todo o desfoque presente nos elementos da interface, o que reduz significativamente (no meu caso, Sqooky) as travadas. Para mim, Silent7s também reduziu o tempo de abertura da tela de configuração e do menu de builds.<br>
Página de download do mod: https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Blur%20Disabler<br>
<br>
<br>

# Mods de Engine
<br>

## [Sound stack update cap](https://deadlockconfig.com/#o-soundcap) by HoppCX: *A reprodução de sons é atualizada cerca de 60 vezes por segundo, em vez de a cada quadro.*
<img width="1360" height="784" alt="Gemini_Generated_Image_yk567lyk567lyk56" src="https://github.com/user-attachments/assets/488639f0-d312-4983-b92c-d83fa3b4ca29" />
Descrição traduzida: Cada som tem um lugar no mundo: a intensidade com que ele é ouvido em cada ouvido depende da sua localização e da posição em que você se encontra. O jogo realiza esse cálculo para cada som em reprodução a cada quadro (frame) — e, em uma luta de equipe, cerca de 80 sons podem estar sendo reproduzidos simultaneamente. Para evitar sobrecarga, o processamento de cada som ocorre em intervalos de 15 a 17 ms — uma frequência próxima da frequência com que o servidor envia as posições (64 vezes por segundo) —, utilizando um temporizador aleatório individual para distribuir a carga de processamento entre os quadros. Vale ressaltar que os sons começam a ser reproduzidos exatamente no momento em que são acionados.<br>
<br>
<br>

# Qualidade de Vida
<br>

## [Better Builds](https://gamebanana.com/mods/725437) By Paul Lock
<img width="2496" height="1664" alt="6ac7915f606d1" src="https://github.com/user-attachments/assets/4ef2788b-2198-4701-97d8-15c82f6ea817" /><br>
O que ele faz: Traz uma **nova aba** ao menu de builds, onde você pode separar as builds por *Trusted Players*, *Top 100* e *DLNS*, além de poder ordenar por mais usadas e ver quais são as mais favoritadas.<br>
Página de download do mod: https://gamebanana.com/mods/725437
