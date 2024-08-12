# Pingo-Ponga
unction setup() {

  createCanvas(800, 600); // Cria uma tela de 800x600 pixels

}

// Função de desenho, chamada repetidamente para desenhar na tela

function draw() {

  background(220); // Limpa a tela com uma cor cinza claro

  

  let x = mouseX; // Obtém a posição X do cursor do mouse

  let y = mouseY; // Obtém a posição Y do cursor do mouse

  

  fill(255, 0, 0); // Define a cor de preenchimento como vermelho

  noStroke(); // Remove o contorno do círculo

  

  ellipse(x, y, 50, 50); // Desenha um círculo de 50x50 pixels na posição do mouse

}



}


}
