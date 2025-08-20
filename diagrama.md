// Interface do Reprodutor Musical
public interface IReprodutor {
    void tocar();
    void pausar();
    void selecionarMusica(String musica);
}

// Interface do Aparelho Telefônico
public interface ITelefone {
    void ligar(String numero);
    void atender();
    void iniciarCorreioVoz();
}

// Interface do Navegador
public interface INavegador {
    void exibirPagina(String url);
    void adicionarNovaAba();
    void atualizarPagina();
}
