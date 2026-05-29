# agrinho
jogo agrinho tema sobre o agro do brasil 


FEITO POR ANDRE DE FRANCA ROBERTO 1D CIDADE GAUCHA PR 

Tecnologias Principais
HTML5: Cria a estrutura da tela e os textos da interface (HUD).

CSS3: Estiliza o design da interface (cores escuras, bordas verdes e caixas de texto).

JavaScript + Three.js: Motor gráfico que renderiza todo o jogo em 3D usando WebGL.

Recursos e Funções do Código
THREE.WebGLRenderer e Scene: Criam o motor gráfico, a iluminação (Sol), as sombras e a névoa do ambiente.

THREE.InstancedMesh: Desenha milhares de pés de milho na plantação consumindo pouca memória (otimização de performance).

genTex (Canvas 2D): Cria as texturas de grama, solo arado e placas desenhando-as via código, sem precisar carregar imagens externas.

PointerLock: Prende o ponteiro do mouse na tela para permitir que você gire a câmera livremente.

colisoresMundo: Array que calcula as coordenadas das paredes, silos e árvores para criar o sistema de colisão física (impedir que o jogador atravesse objetos).

Funções Procedurais (criarCasa / criarPredio): Geram automaticamente os quarteirões da cidade e prédios com janelas iluminadas.

Mapeamento de Teclas: Prepara o código para alternar os modos de jogo (Trator, Carro, Colhedora e Drone) e funções como reabastecer e vender a safra nos silos.
