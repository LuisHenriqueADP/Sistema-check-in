const participante = {
nome: "mayk brito",
email: "mayk@gmail.com",
dataInscricao: new Date(2024, 2, 22, 19, 20),
dataCheckIn: new Date(2024, 2, 25, 22, 00)
}
let participantes =[
  {
nome: "mayk brito",
email: "mayk@gmail.com",
dataInscricao: new Date(2024, 2, 22, 19, 20),
dataCheckIn: new Date(2024, 2, 25, 22, 00)
}
]
for(let participante of participantes) {
    output = output + criarNovoParticipante(participante)
  } // faça alguma coisa aqui enquanto tiver pessoas nessa lista
  
 