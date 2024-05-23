# desafio-DIO

function classificarHeroi() {
    var nome = prompt("Digite o nome do herói:");
    let xp
    var nivel;

    if (xp < 1000) {
        nivel = "Ferro";
    } else if (xp >= 1001 && xp <= 2000) {
        nivel = "Bronze";
    } else if (xp >= 2001 && xp <= 5000) {
        nivel = "Prata";
    } else if (xp >= 5001 && xp <= 7000) {
        nivel = "Ouro";
    } else if (xp >= 7001 && xp <= 8000) {
        nivel = "Platina";
    } else if (xp >= 8001 && xp <= 9000) {
        nivel = "Ascendente";
    } else if (xp >= 9001 && xp <= 10000) {
        nivel = "Imortal";
    } else if (xp >= 10001){ // XP maior ou igual a 10001
        nivel = "Radiante";
    }

    // Exibindo a mensagem final com o nome e o nível do herói
    print("O Herói de nome " + nome + " está no nível de " + nivel);
}

// Chamar a função principal para executar o programa
classificarHeroi();
