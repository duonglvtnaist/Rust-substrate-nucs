# Rust-substrate-nucs

1. Install ssh
sudo apt-get install ssh\
systemctl start sshd\
2. Check IP
ip addr show\
inet 192.168.10.14/24 brd 192.168.10.255 scope global dynamic noprefixroute wlp3s0\
--> Ip address is 192.168.10.14\
3. Connect to ssh through
ssh -X username@ipaddress\
--> type your pass\
4. Install Rust
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh\
Necessary info:\
To get started you may need to restart your current shell.\
This would reload your PATH environment variable to include\
Cargo's bin directory ($HOME/.cargo/bin).\

To configure your current shell, run:\
source $HOME/.cargo/env\


