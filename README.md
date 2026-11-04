Resumo do ProjetoO objetivo atual é implementar um sistema de seleção e carregamento dinâmico de personagens para um jogo HTML5 em JavaScript (Canvas) baseado em Dragon Ball.Módulos e Alterações Implementadas
Menu de Seleção (HTML):Estruturação da tag <select id="hero"> no index.html para permitir a escolha entre Goku, Vegeta, Trunks (Criança), Gogeta e Golden Frieza.   
Mapeamento de Recursos (manifest):Organização das sub-listas de caminhos das imagens recortadas para cada lutador (animações de idle, ataques e dano/pulo).   
Atributos e Efeitos Visuais (PCOL e FORMDATA):Configuração do array names com a lista atualizada de lutadores.Definição de esquemas de cores para os projéteis de Ki no objeto PCOL (ex: azul para Kamehameha, roxo para Galick Gun/Supernova, dourado para Golden Frieza).   
Mapeamento de formas alternativas e transformações no objeto FORMDATA (SSJ, SSJ Blue, Majin Vegeta, Golden Frieza).  
Lógica de Atualização Dinâmica:Criação de um event listener associado ao menu <select> para recarregar os sprites e atualizar os dados do Canvas sempre que o utilizador altera o personagem escolhido.
https://jgawps.github.io/Dragon-Pixells/
