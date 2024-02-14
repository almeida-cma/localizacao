# localizacao
Exemplo de geolocalização.

Neste exemplo:

A página de isca apresenta uma oferta especial com base na localização do usuário.
A função getLocation() é chamada quando a página é carregada para obter a localização do usuário.
A função showPosition(position) é chamada quando a localização do usuário é obtida com sucesso, e exibe a latitude e longitude do usuário no console do navegador. Você pode enviar essas informações para um servidor para obter ofertas personalizadas com base na localização do usuário.
A oferta especial inclui uma imagem ilustrativa, detalhes da oferta (como nome do produto ou serviço, desconto e validade) e instruções para aproveitar a oferta.
O conteúdo da oferta é apresentado em um contêiner centralizado na página, com estilos CSS para melhor apresentação.
Lembre-se de substituir offer_image.jpg pela imagem real da sua oferta especial e personalizar os detalhes da oferta de acordo com a sua campanha publicitária. Além disso, certifique-se de implementar o código no servidor para processar a localização do usuário e fornecer ofertas personalizadas.

Um footer foi adicionado à página, e dentro dele há um parágrafo para exibir a localização obtida através da geolocalização.

A função showPosition(position) foi modificada para atualizar o conteúdo do elemento HTML com o id location com as coordenadas de latitude e longitude do usuário.

Com isso, ao carregar a página, o footer exibirá a localização atual do usuário.
