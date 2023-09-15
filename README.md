# trabalho-final
const tarefa = [];

function criarTarefa () {
    const tituloTarefa = (' ');
    const descricao = (' ');

    const statusDaTarefa = {
        titulo: tituloTarefa,
        Descricao: descricao,
        status: 'pendente',
    };
    tarefa.push(statusDaTarefa);
}

function listarTarefa () {
    console.log(tarefa)
}

