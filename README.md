# D.pro
tem uma interface visual em React + Vite + Three.js + shaders GLSL (o "rosto" holográfico). Um cérebro baseado no Claude Code da Anthropic (rodando de forma headless)
Você diz "Hey D", ele acorda, escuta e executa tarefas reais usando as ferramentas que você tiver configuradas. 
O que ele consegue fazer
 * Busca informações na web
 * Gerar imagens
 * Controla o celular (via Android)
 * Ler e-mails
 * controlar o próprio navegador
 * manipular a interface holográfica (cores, efeitos, painéis, etc.)
Como funciona
São dois processos:
 1. Browser-» interface + voz (microfone e fala)
 2. Bridge (Node.js) -»conecta com o Claude Code e excuta as ferramentas
Tudo roda localmente. A única assinatura necessária é a do Claude Code. O Elevebtabs é opcional (melhora a voz eo reconhecimento de fala).   
