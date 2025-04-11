//lista de objetos 
const carro = {
  marca: 'Honda',
  modelo: 'suv',
  ano:  2023
}
console.log(carro.marca)
console.log(carro.modelo)
console.log(carro.ano)

//remover propriedades 
const usuário = {
  nome: 'Fernanda',
  email: 'fernanda@gmail.com',
  idade: 25
}
delete usuário.email
console.log(usuário)

// trocar propriedades 
const pessoa = {
  nome: 'Carlos',
  idade: 29
}
console.log(pessoa.idade)
pessoa.idade= {
  idade: 40
}
console.log(pessoa.idade)

//lista de array
let tarefas = ['estudar', 'lavar a louça', 'fazer exercícios']
tarefas.push('comprar pão', 'ler um livro')

let ultimaTarefa= tarefas.pop()

tarefas.unshift('acordar cedo', 'tomar café')
