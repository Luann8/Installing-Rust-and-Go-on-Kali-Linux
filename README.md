<header>
    <h1>Installing Rust on Kali Linux</h1>
</header>

<section>
    <h2>Steps to Install Rust on Kali Linux</h2>
    <ol>
        <li>Update Kali Linux system:</li>
        <pre>sudo apt update && sudo apt upgrade</pre>
        <li>Install Rust using `rustup`:</li>
        <pre>curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh</pre>
        <li>Add Cargo directory to your PATH:</li>
        <pre>source $HOME/.cargo/env</pre>
        <li>Verify if the installation was successful:</li>
        <pre>rustc --version && cargo --version</pre>
    </ol>
</section>

<footer>
    <p>For more information, see the <a href="https://www.rust-lang.org/tools/install">official Rust installation documentation</a>.</p>
</footer>

<img src="https://raw.githubusercontent.com/Luann8/Rust-install-kali-linux/main/Apresenta%C3%A7%C3%A3o1.png" alt="Presentation1">
