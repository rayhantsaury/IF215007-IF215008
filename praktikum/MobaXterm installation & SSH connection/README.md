### Image 
![image](https://user-images.githubusercontent.com/86096057/209508933-7d5a41a6-00c9-45b6-a158-c3e2fecbb22d.png)
![image](https://user-images.githubusercontent.com/86096057/209509020-990c6ee4-7703-4216-98e9-9dc14e9ee66a.png)


#### Buat sesi baru, dan:
1. Tambahkan 192.168.0.100sebagai host jarak jauh Anda. Tentukan nama pengguna dan port jika perlu.
2. Di tab Pengaturan SSH lanjutan , centang Gunakan kunci pribadi dan masukkan kredensial untuk host target
3. Buka tab Pengaturan jaringan dan konfigurasikan jump host Anda dengan mengklik tombol SSH gateway (jump host).
4. Tambahkan 3.45.67.89jump host ke salah satu jump host tanpa melupakan kredensial jump host. Tentukan nama pengguna dan port.
5. Klik OK lalu OK lagi

### [MobaXterm] XServer display setting
-----------
* Change display offset as '11' in the MobaXTerm X Server setting
```Shell
echo $DISPLAY
export DISPLAY=:11
echo $DISPLAY
```

#### Reference
---------

* [Fixing Vim's Background Color Erase for 256-color tmux and GNU screen](http://sunaku.github.io/vim-256color-bce.html)
* [github](https://github.com/SeokjuLee/terminal-setup)
