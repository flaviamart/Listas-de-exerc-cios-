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

let primeiraTarefa= tarefas.shift()

//splice substitui 
tarefas.splice(0,2, 'fazer cafe da manhã', 'organizar a mesa')

//slice seleciona
let tarefasSelecionadas = tarefas.slice(1,4)
console.log(tarefasSelecionadas)

let tarefasCompletas = tarefas.concat('Ver um filme ', 'descansar')



console.log("lista original de tarefas", tarefas);
console.log('última tarefa removida', ultimaTarefa);
console.log('primeira tarefa removida', primeiraTarefa);
console.log('tarefas selecionadas', tarefasSelecionadas);
console.log('lista final de tarefas', tarefasCompletas);

// arrays
//length- quantos itens tem na lista 
let cores = ['azul', 'branco', 'laranja', 'preto']
console.log(cores.length)
let ultimoElemento =[cores.length -1]
console.log(ultimoElemento)

// adicionar elementos 
const notas =[10, 7, 6, 9]

//push adiciona no final 
notas.push(3)
console.log(notas)

//unshift adiciona no início 
notas.unshift(4)
console.log(notas)

//deletando intens 
//pop deleta o ultimo 
notas.pop()
console.log(notas)

//shift deleta o primeiro 
notas.shift()
console.log(notas)
 

