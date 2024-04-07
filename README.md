    
   </head><body>  <header>
     <h1>Instalação do Rust no Kali Linux</h1>
       </header>
    <section>
        <h2>Passos para instalar o Rust no Kali Linux</h2>
        <ol>
            <li>Atualize o sistema Kali Linux:
                <pre>sudo apt update && sudo apt upgrade</pre>
            </li>
            <li>Instale o Rust usando `rustup`:
                <pre>curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh</pre>
            </li>
            <li>Adicione o diretório do Cargo ao seu PATH:
                <pre>source $HOME/.cargo/env</pre>
            </li>
            <li>Verifique se a instalação foi bem-sucedida:
                <pre>rustc --version && cargo --version</pre>
            </li>
        </ol>
    </section>
