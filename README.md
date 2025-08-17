
<video src="./show.mp4" controls loop muted autoplay width="100%"></video>

# JellyfinTheme

[Ultrachromic](https://github.com/CTalvio/Ultrachromic), [Glassmorphism](https://github.com/alexyle/jellyfin-theme), [Scyfin](https://github.com/loof2736/scyfin), [JellyTheme](https://github.com/alexyle/jellyfin-theme) ve [Zombie](https://github.com/MakD/zombie-release/tree/main) temalarından esinlenerek oluşturulmuş, Jellyfin için minimalist ve zarif bir tema.


---
(GEREKLİ) **BU TEMAYI BU EKLENTİLER İLE BERABER KULLANIN!**
<img src="./images/eklentiler.png" alt="eklentiler" width="100%"/>
---
### **Ekran Görüntüleri:**

<img src="./images/home.png" alt="home" width="100%"/>
<img src="./images/nice-guys.png" alt="movies" width="100%"/>
<img src="./images/avatar.jpg" alt="tv-shows" width="100%"/>
<img src="./images/player.jpg" alt="player" width="100%"/>
<img src="./images/genres.png" alt="genres" width="100%"/>

Two login wallpaper options: Minimal and Stylish.

<img src="./images/login.png" alt="login" width="100%"/>

**Mobile:**

<img src="./images/phone.jpg" alt="phone" width="100%"/>

---

## Kurulum

Benim kullandığım temayı Jellyfin'e eklemek için aşağıdaki satırı Dashboard > General > Custom CSS bölümüne kopyalayın:

```
@import url('https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/round-icons.css');
@import url('https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/theme.css');
@import url('https://fonts.googleapis.com/icon?family=Material+Icons');
@import url('https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/colorschemes/gray.css');

.adminDrawerLogo img {
  content: url(https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/affine-light.webp) !important;
}

imgLogoIcon {
  content: url(https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/affine-light.webp) !important;
}

.pageTitleWithLogo {
  background-image: url(https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/affine-light.webp) !important;
}

```

Daha sonra, eğer yapmadıysanız, bu temayı kullanacak _her_ cihaz için Arka Planları etkinleştirin (Ayarlar > Görüntü > Arka Planlar).¹

## Renk Şemaları

Varsayılan renkleri aşağıdaki ön ayarlardan birine değiştirmek isterseniz (isteğe bağlı) aşağıdaki @import satırlarından **birini** ekleyin:

### Açık Mavi
<img src="./images/colorschemes/cyan.png" alt="default" width="30%"/>

Varsayılan renk şeması.

<details>
 <summary>Önizleme</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-cyan.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/cyan.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Mavi

<img src="./images/colorschemes/blue.png" alt="blue" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/colorschemes/blue.css');
```

<details>
 <summary>Önizleme</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-blue.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/blue.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Mercan

<img src="./images/colorschemes/coral.png" alt="coral" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/colorschemes/coral.css');
```

<details>
 <summary>Önizleme</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-coral.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/coral.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Gri

<img src="./images/colorschemes/gray.png" alt="gray" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/colorschemes/gray.css');
```

<details>
 <summary>Önizleme</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-gray.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/gray.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Yeşil

<img src="./images/colorschemes/green.png" alt="green" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/colorschemes/green.css');
```

<details>
 <summary>Önizleme</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-green.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/green.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Mor

<img src="./images/colorschemes/purple.png" alt="purple" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/colorschemes/purple.css');
```

<details>
 <summary>Önizleme</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-purple.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/purple.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Kırmızı

<img src="./images/colorschemes/red.png" alt="red" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/colorschemes/red.css');
```

<details>
 <summary>Önizleme</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-red.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/red.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Sarı

<img src="./images/colorschemes/yellow.png" alt="yellow" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/colorschemes/yellow.css');
```

<details>
 <summary>Önizleme</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-yellow.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/yellow.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>
<br>


### Alternatif Giriş Ekranı Duvar Kağıdı
Son olarak, alternatif (şık) giriş ekranı duvar kağıdını kullanmak isterseniz, aşağıdaki satırı Özel CSS'nize ekleyin:

```css
@import url('https://cdn.jsdelivr.net/gh/ArdaYILDIZ-DEV/JellyfinTheme@latest/login-alt.css');
```

Bu, minimalist (varsayılan) ve şık giriş ekranı duvar kağıdı versiyonları arasındaki bir karşılaştırmadır:

<details>
 <summary>Mavi</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-blue.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-blue.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Mercan</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-coral.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-coral.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Açık Mavi</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-cyan.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-cyan.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Gri</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-gray.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-gray.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Yeşil</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-green.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-green.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Mor</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-purple.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-purple.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Kırmızı</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-red.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-red.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Sarı</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-yellow.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-yellow.jpg" alt="default" width="100%"/>
 </div>
</details>

---

### Notlar:

¹ Bu temayı kullanmayı planladığınız *her* cihazda Arka Planları etkinleştirmeniz gerekir, aksi takdirde tema bozuk görünecektir.

Bu tema, içeriği sağa eğimli arka plan resimleriyle en iyi görünür. [Burada gösterildiği gibi](./images/extras/bg-guide.jpg).

Canlı TV özelliğini ve Müzik Videolarını kullanmıyorum, bu yüzden tema orada bozuk görünebilir. Temalandırmaya karşı değilim, ancak kullanmadığım için zor...

TV modunu (Ayarlar > Görüntü > Görüntü Modu > TV) yakında temalandırmayı planlıyorum. Şu anda bozuk görünüyor.

---

### Yasal Uyarı:

Tema yalnızca 1080p (16:9) çözünürlükte, hem uygulamada hem de web arayüzünde test edilmiştir. Bu nedenle 720p, 2K ve 4K ekranlarda veya farklı ekran oranlarında bozuk görünebilir. Lütfen herhangi bir sorunu bildirin.

Tema hala **WIP** (Yapım Aşamasında) ve bazı alanlarda bozuk görünebilir. Lütfen herhangi bir sorunu bildirin.

CSS konusunda bilgili değilim, ancak sonuç istediğim gibi görünüyorsa, kod ne kadar karmaşık veya dağınık olursa olsun, bu benim için bir kazançtır... PR'lar (Pull Request'ler) kabul edilir.

---
