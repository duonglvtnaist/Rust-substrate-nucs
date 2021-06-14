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
5. How to use the git
git clone https://github.com/duonglvtnaist/Rust-substrate-nucs.git\
git remote add upstream https://github.com/duonglvtnaist/Rust-substrate-nucs\
git checkout -b \<yourbranch\>\
vim \<filename to update\>\
git add \<filename\>\
git git commit -m "Commit name"\
git push --set-upstream upstream \<yourbranch\>\
--> Input\
 username: duonglvtnaist\
 password: \*\*\*\*\*\*\*\*\*\*\*\*\
--> Go to the git to add and merge pull request\
6. SSH information:
NUC001 ip: 163.221.183.93\
NUC002 ip: 163.221.124.43\
ssh hong@address
pass: user1comparch
ssh luan@address
pass: user2comparch
ssh dung@address\
pass: user3comparch\
ssh chuong@address\
pass: user4comparch\
ssh dai@address\
pass: user5comparch
to change password please run a command: "passwd" after you log in the NUC00x
7. Teamviewer configuration
NUC001:
ID: 146 102 706
Pass: nuc001
ID: 195 481 088
Pass: nuc002teamview
