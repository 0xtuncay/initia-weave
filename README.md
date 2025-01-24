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

# 4 Burada Bir Kaç Seçenek Çıkıyor Ne Yapmak İstediğinizi seçin. Ben Rollup Kurucam.
 Run an L1 node
  Launch a new rollup
  Run OPinit bots
  Run a relayer
![Screenshot_2025-01-24-15-36-06-316-edit_com server auditor ssh client](https://github.com/user-attachments/assets/01da2505-b03f-41c3-bbf5-6014152961af)

Devam Ediyoruz.
