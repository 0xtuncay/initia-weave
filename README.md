# İnitia-weave

# 1. GO'yu Yüklüyoruz.

```
cd $HOME && \
ver="1.23.3" && \
wget "https://golang.org/dl/go$ver.linux-amd64.tar.gz" && \
sudo rm -rf /usr/local/go && \
sudo tar -C /usr/local -xzf "go$ver.linux-amd64.tar.gz" && \
rm "go$ver.linux-amd64.tar.gz" && \
echo "export PATH=$PATH:/usr/local/go/bin:$HOME/go/bin" >> $HOME/.bash_profile && \
source $HOME/.bash_profile && \
go version
```

# 2. Weave'yi Yüklüyoru.

```
git clone https://github.com/initia-labs/weave.git
cd weave
git checkout tags/v0.1.1
make install
```

version 0.1.1 olacak.

```
weave version
```

0.1.1 Olaacak.
```
weave version
```

# 3. Weaveyi Başlatıyoruz.

```
weave init
```
