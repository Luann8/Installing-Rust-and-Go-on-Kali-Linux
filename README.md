
 <header>
        <h1>Instalação do Rust no Kali Linux</h1>
    </header>

 <section>
        <h2>Passos para instalar o Rust no Kali Linux</h2>
        <ol>
            <li>Atualize o sistema Kali Linux:</li>
            <pre>sudo apt update && sudo apt upgrade</pre>
            <li>Instale o Rust utilizando `rustup`:</li>
            <pre>curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh</pre>
            <li>Adicione o diretório do Cargo ao seu PATH:</li>
            <pre>source $HOME/.cargo/env</pre>
            <li>Verifique se a instalação foi bem-sucedida:</li>
            <pre>rustc --version && cargo --version</pre>
        </ol>
    </section>

<footer>
        <p>Para mais informações, consulte a <a href="https://www.rust-lang.org/tools/install">documentação oficial de instalação do Rust</a>.</p>
    </footer>
