
<header>
    <h1>Installing Rust and Go on Kali Linux</h1>
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

<section>
    <h2>Steps to Install Go (Golang) on Kali Linux</h2>
    <ol>
        <li>Download the Go binary distribution:</li>
        <pre>wget https://golang.org/dl/go1.17.linux-amd64.tar.gz</pre>
        <li>Extract the downloaded archive:</li>
        <pre>sudo tar -C /usr/local -xzf go1.17.linux-amd64.tar.gz</pre>
        <li>Add Go binary directory to your PATH:</li>
        <pre>echo "export PATH=$PATH:/usr/local/go/bin" >> ~/.bashrc</pre>
        <li>Reload your shell configuration:</li>
        <pre>source ~/.bashrc</pre>
        <li>Verify if the installation was successful:</li>
        <pre>go version</pre>
    </ol>
</section>


<img src="https://github.com/Luann8/Rust-install-kali-linux/blob/main/1.jpg?raw=true" alt="Presentation1">
