# Rust å¥é¨åäº« ð¦

---

## ä¸ºä»ä¹å­¦ä¹  Rustâ

-----

1. è¿ç»­ä¸å¹´æä¸ºå¨ä¸çæåæ¬¢è¿çè¯­è¨

<!-- rustæ¥æ¥ï¼<a href="https://rustcc.cn/article?id=8cfed228-a988-4186-9692-dc44e36baed9#:~:text=Rust%20%E8%BF%9E%E7%BB%AD%E7%AC%AC%207%20%E5%B9%B4%E6%88%90%E4%B8%BA%E6%9C%80%E5%8F%97%E5%96%9C%E7%88%B1%E7%9A%84%E8%AF%AD%E8%A8%80%20Rust%20%E5%9C%A8%202022%20%E5%B9%B4%E7%9A%84,StackOverflow%20%E8%B0%83%E6%9F%A5%E4%B8%AD%E8%BF%9E%E7%BB%AD%E7%AC%AC%207%20%E5%B9%B4%E6%88%90%E4%B8%BA%E6%9C%80%E5%8F%97%E5%96%9C%E7%88%B1%E7%9A%84%E8%AF%AD%E8%A8%80%E3%80%82%20Rust%20%E4%BD%9C%E4%B8%BA%E6%9C%80%E5%8F%97%E5%96%9C%E7%88%B1%E7%9A%84%E8%AF%AD%E8%A8%80%E5%B7%B2%E7%BB%8F%E8%B5%B0%E8%BF%87%E4%BA%86%E7%AC%AC%E4%B8%83%E4%B8%AA%E5%B9%B4%E5%A4%B4%EF%BC%8C%2087%25%20%E7%9A%84%E5%BC%80%E5%8F%91%E8%80%85%E8%A1%A8%E7%A4%BA%E4%BB%96%E4%BB%AC%E6%83%B3%E7%BB%A7%E7%BB%AD%E4%BD%BF%E7%94%A8%E5%AE%83%E3%80%82">rust æ¥æ¥</a> -->

<a href="https://survey.stackoverflow.co/2022/?utm_source=so-owned&utm_medium=announcement-banner&utm_campaign=dev-survey-2022&utm_content=results#most-loved-dreaded-and-wanted-language-want">stackoverflow survey</a>

-----

2. æ²¡æ GC ä¹æ éæå¨åå­ç®¡ç

<div style="font-size: 20px; color: #666;">
<ul>
<li>åå¾åæ¶æºå¶(GC)ï¼å¨ç¨åºè¿è¡æ¶ä¸æ­å¯»æ¾ä¸åä½¿ç¨çåå­ï¼å¸åä»£è¡¨ï¼JavaãGo</li>
<li>æå¨ç®¡çåå­çåéåéæ¾, å¨ç¨åºä¸­ï¼éè¿å½æ°è°ç¨çæ¹å¼æ¥ç³è¯·åéæ¾åå­ï¼å¸åä»£è¡¨ï¼C++</li>
<li>éè¿ææææ¥ç®¡çåå­ï¼ç¼è¯å¨å¨ç¼è¯æ¶ä¼æ ¹æ®ä¸ç³»åè§åè¿è¡æ£æ¥</li>
</ul>
</div>

```rust
{                      // s å¨è¿éæ æï¼å®å°æªå£°æ
    let s = "hello";   // ä»æ­¤å¤èµ·ï¼s æ¯ææç

    // ä½¿ç¨ s
}                      // æ­¤ä½ç¨åå·²ç»æï¼sä¸åææ
```

-----

3. è·¨å¹³å°ï¼å¯ä»¥ç¼è¯ä¸ºåç³»ç»çå¯æ§è¡æä»¶

<!-- .slide: data-background-image="https://miro.medium.com/max/851/1*TLqYA0gwLrLAfXMGoTWFlQ.png" data-background-opacity="0.1" data-background-size="contain" -->
<a href="https://zhuanlan.zhihu.com/p/128626720" target="_blank">äº¤åç¼è¯</a>

-----

<!-- .slide: data-background="https://media.bitdegree.org/storage/media/images/2019/11/Rust-vs-C.jpg" data-background-opacity="0.1" data-background-size="contain" -->
4. <a href="https://www.jianshu.com/p/95884d1d04aa">æ§è½æ¯è© C++/C è¿è½ç´æ¥è°ç¨å®ä»¬çä»£ç ãå®å¨æ§æé«</a>

-----

<!-- .slide: data-background="https://oscimg.oschina.net/oscnet/up-933d6cb2a65d5d7694422048292cdbd7ce5.jpg" data-background-opacity="0.1" data-background-size="contain" -->
5. Rust å°æ¥å¯è½ä¼æä¸º Linux åæ ¸å¼åçç¬¬äºè¯­è¨

<img src="https://img14.360buyimg.com/imagetools/jfs/t1/142432/15/29758/94664/633c00c2E794b0c01/5b372bed032485ef.png">

-----

<!-- .slide: data-background="https://www.shuttle.rs/images/blog/ferris-error-handling.png" data-background-opacity="0.1" data-background-size="contain" -->
6. æå¶ä¸¥æ ¼çç±»åæ ¡éª

<div class="fragment fade-in" style="margin-top: 1em;">
çè³æ¯ä»£ç åªè¦è½è·èµ·æ¥æèç¼è¯éè¿äºï¼å°±è¯´æä½ çä»£ç è´¨éå·²ç»å¾ä¸éäº
</div>

-----

<!-- .slide: data-background="https://www.rust-lang.org/static/images/wasm-ferris.png" data-background-opacity="0.1" data-background-size="contain" -->
7. å¯ä»¥ç¼å <a href="https://github.com/chenxiaochun/blog/blob/master/article/%E7%BC%96%E8%AF%91Rust%E4%B8%BAWebAssembly.md" target="_blank">webAssembly</a>

-----

<!-- .slide: data-background="https://img14.360buyimg.com/imagetools/jfs/t1/184097/14/32232/11986/633bf6d3Efa88ab3f/bbb7c32f21f04be8.png" data-background-opacity="0.1" -->
<a href="https://www.infoq.cn/article/ihlljbyidfxwkq17r_kq" target="_blank">8. æ¯æ npm çæ ¸å¿èº«ä»½éªè¯æå¡</a>

<p class="fragment" style="font-size: 20px; margin-top: 1em; text-align: left;">
npm çèº«ä»½éªè¯æå¡æ²¡é£ä¹å¤æï¼ä»¥ Node.js éååªè±äºä¸ä¸ªå°æ¶ãå¦ä¸æ¹é¢ï¼Go éè¦ 2 å¤©ï¼ä½ä»¥ Rust éåè±äºæ´æ´ä¸ä¸ªææï¼ä¸»è¦æ¯å ä¸º Rust çå­¦ä¹ æ²çº¿æ´å é¡å³­ä»¥åè¯¥è¯­è¨çåå¨å¤ææ§<br /><br/>
ââ Chris Dickinson è¿æ ·è§£éè¯´
</p>

-----

<!-- .slide: data-background="https://img12.360buyimg.com/imagetools/jfs/t1/91779/10/31396/399571/6343f5faE44b5c5df/78cacf9bca4a6d9a.png" data-background-opacity="0.1" data-background-size="contain" -->
9. èåè®¾è®¡å·¥å· <a href="https://www.figma.com/files/recent?fuid=841590831032294578" target="_blank">figma</a> ç½é¡µççè¿è¡å®ç°

-----

<!-- .slide: data-background="https://img12.360buyimg.com/imagetools/jfs/t1/170748/16/31022/1383394/6344c25bE13d54838/32b61c89f9f4ca13.gif" data-background-opacity="0.1" data-background-size="contain" -->
10. å¾®ä¿¡èå¤©éçãð£ï¸ð©ãåè½æ®è¯´æ¯ç¨ webAssembly å®ç°ç

-----

11. æ´å¤...

https://github.com/i5ting/rust-fe

---

## ç¯å¢å®è£

-----

å¨ Linux æ macOS ä¸å®è£ rust

```
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```

-----

å¨ Windows ä¸å®è£ rustï¼éè¦ä¾èµäº C++ ç¯å¢

<a href="https://course.rs/first-try/installation.html#%E5%9C%A8-windows-%E4%B8%8A%E5%AE%89%E8%A3%85-rustup" target="_blank">å®è£æç¨</a>

-----

æ£æ¥æ¯å¦å®è£æå

```
$ rustc -V
rustc 1.58.0 (02072b482 2022-01-11)
```

---

## ç¼è¾å¨æä»¶å®è£ð 

-----

### VSCode æä»¶

-----

ð« ä¸æ¨èå®æ¹ç rust æä»¶ï¼å·²ç»åæ­¢ç»´æ¤

<img src="./images/02.png">

-----

â æ´æ¨èç±ç¤¾åºé©±å¨ç»´æ¤ç rust æä»¶

<img src="./images/03.png">

-----

å°±åå¶å®è¯­è¨æä»¶ä¸æ ·ï¼æä¾äºä»¥ä¸ç¹æ§ï¼

```
1. ä»£ç èªå¨å®ææç¤º
2. ä»£ç é´çèªå¨è·³è½¬
3. è¯­æ³é«äº®åä»£ç æ£æ¥
4. ....
```

-----

### Vim æä»¶

-----

```
Plugin 'rust-analyzer/rust-analyzer'
Plugin 'rust-lang/rust.vim'
```

```
let g:rustfmt_autosave = 1
```

```[7]
let g:ale_linters = {
\   'html': ['tidy'],
\   'less': ['stylelint'],
\   'javascript': ['eslint'],
\   'typescript': ['tsserver', 'eslint'],
\   'markdown': ['markdownlint'],
\   'rust': ['analyzer']
\}
```

---

## è®¤è¯ Cargo

<p class="fragment fade-up">ä¸ä¸ªä¼ç§çåç®¡çå¨éå¸¸éè¦ ð¦</p>

-----

åå»ºé¡¹ç®

```
cargo new hello_world
```

<div class="fragment fade-up">
è¿è¡é¡¹ç®

```
cargo run
```
</div>


<div class="fragment fade-up">
ç¼è¯é¡¹ç®

```shell
cargo build
```
</div>

-----

<div>
å®è£ä¾èµ

```
cargo install pkgName
```
</div>

<div class="fragment fade-up">
è¿è¡ååæµè¯

```shell
cargo test
```
</div>

<div class="fragment fade-up">
é¡¹ç®æ£æ¥

<div style="font-size: 16px;">
å½é¡¹ç®å¤§äºåï¼cargo run å cargo build ä¸å¯é¿åçä¼åæ¢ï¼å¯ä»¥æ´å¿«çæ¥éªè¯ä»£ç çæ­£ç¡®æ§
</div>

```shell
cargo check
```
</div>

---

## ä¸ä¸ªæ®éç rust é¡¹ç®

-----

åºç¡ç®å½ç»æ

```
.
âââ Cargo.lock
âââ Cargo.toml
âââ hello.txt
âââ src
âÂ Â  âââ main.rs
âÂ Â  âââ multiplication_table.rs
âââ target
    âââ CACHEDIR.TAG
    âââ debug
        âââ build
        âââ deps
```

-----

Cargo.toml

```toml
[package]
name = "hello_world"
version = "0.1.0"
edition = "2021"

# See more keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html

[dependencies]

```

-----

Cargo.lock

```
# This file is automatically @generated by Cargo.
# It is not intended for manual editing.
version = 3

[[package]]
name = "hello_world"
version = "0.1.0"
```

---

## ä¸è½½ä¾èµå¤ªæ¢äºï¼

-----

å¨`$HOME/.cargo/config.toml`æ·»å ä»¥ä¸åå®¹ï¼

```toml
[source.crates-io]
replace-with = 'ustc'

[source.ustc]
registry = "git://mirrors.ustc.edu.cn/crates.io-index"
```

---

## Rust è¯­è¨å­¦ä¹ 

-----

ä»ç°å¨å¼å§çæ­£è¿å¥ rust ä¸çï¼<br />ä½ ä¼æ¥è§¦å°å¾å¤æ°çæ¦å¿µð

-----

* æææãå¼ç¨ãåç¨
* å¤åç±»å
* æ³ååç¹å¾
* æ¨¡å¼å¹é
* ç±»åè½¬æ¢
* å®ç¼ç¨
* çå½å¨æ
* æºè½æé
* ååæ¨¡å
* ...

-----

ä½æ¯ï¼ä¸è¦å®³æï¼

-----

<div class="fragment grow">
ä»¥ä¸ééä¸è®²ï¼æä»¬åªè®²ç¹å¿åºç¡ç¥è¯ï¼<br/>å ä¸ºæä¹ä¸ä¼ð¤ª
</div>

-----

```rust[1-2|3-6|8-9|11-14|16-17|19-20|22-25|28-32]
// Rust ç¨åºå¥å£å½æ°ï¼è·å¶å®è¯­è¨ä¸æ ·ï¼é½æ¯ mainï¼è¯¥å½æ°ç®åæ è¿åå¼
fn main() {
   // ä½¿ç¨letæ¥å£°æåéï¼è¿è¡ç»å®ï¼aæ¯ä¸å¯åç
   // æ­¤å¤æ²¡ææå®açç±»åï¼ç¼è¯å¨ä¼é»è®¤æ ¹æ®açå¼ä¸ºaæ¨æ­ç±»åï¼i32ï¼æç¬¦å·32ä½æ´æ°
   // è¯­å¥çæ«å°¾å¿é¡»ä»¥åå·ç»å°¾
   let a = 10;

   // ä¸»å¨æå®bçç±»åä¸ºi32
   let b: i32 = 20;

   // è¿éæä¸¤ç¹å¼å¾æ³¨æï¼
   // 1. å¯ä»¥å¨æ°å¼ä¸­å¸¦ä¸ç±»å:30i32è¡¨ç¤ºæ°å¼æ¯30ï¼ç±»åæ¯i32
   // 2. cæ¯å¯åçï¼mutæ¯mutableçç¼©å
   let mut c = 30i32;

   // è¿è½å¨æ°å¼åç±»åä¸­é´æ·»å ä¸ä¸ªä¸åçº¿ï¼è®©å¯è¯»æ§æ´å¥½
   let d = 30_i32;

   // è·å¶å®è¯­è¨ä¸æ ·ï¼å¯ä»¥ä½¿ç¨ä¸ä¸ªå½æ°çè¿åå¼æ¥ä½ä¸ºå¦ä¸ä¸ªå½æ°çåæ°
   let e = add(add(a, b), add(c, d));

   // println!æ¯å®è°ç¨ï¼çèµ·æ¥åæ¯å½æ°ä½æ¯å®è¿åçæ¯å®å®ä¹çä»£ç å
   // è¯¥å½æ°å°æå®çæ ¼å¼åå­ç¬¦ä¸²è¾åºå°æ åè¾åºä¸­(æ§å¶å°)
   // {}æ¯å ä½ç¬¦ï¼å¨å·ä½æ§è¡è¿ç¨ä¸­ï¼ä¼æeçå¼ä»£å¥è¿æ¥
   println!("( a + b ) + ( c + d ) = {}", e);
}

// å®ä¹ä¸ä¸ªå½æ°ï¼è¾å¥ä¸¤ä¸ªi32ç±»åç32ä½æç¬¦å·æ´æ°ï¼è¿åå®ä»¬çå
fn add(i: i32, j: i32) -> i32 {
  // è¿åç¸å å¼ï¼è¿éå¯ä»¥çç¥return
  i + j
}
```

-----

å­ç¬¦ç±»å(char)

```rust
fn main() {
    let c = 'z';
    let z = 'â¤';
    let g = 'å½';
    let heart_eyed_cat = 'ð»';
}
```

-----

å¸å°ç±»å(bool)

```rust
fn main() {
    let t = true;

    let f: bool = false; // ä½¿ç¨ç±»åæ æ³¨,æ¾å¼æå®fçç±»å
}
```

-----

è¯­å¥åè¡¨è¾¾å¼

```rust
fn main() {
  fn add_with_extra(x: i32, y: i32) -> i32 {
      let x = x + 1; // è¯­å¥
      let y = y + 5; // è¯­å¥
      x + y // è¡¨è¾¾å¼ãç»å°¾æ²¡æåå·ï¼ç¸å½äº return x + y;
  }
}
```

-----

å½æ°

```rust
fn main() {
    another_function(5, 6.1);
}

fn another_function(x: i32, y: f32) {
    println!("The value of x is: {}", x);
    println!("The value of y is: {}", y);
}
```

---

## ä¸¾å ä¸ªä¾å­ð°

-----

ð°æ¬å°`hello_world`ç¤ºä¾

-----

èªå¨ç­æ´æ°

```shell
cargo install cargo-watch
```

```shell
cargo watch -x run
```

-----

å®è£ä¾èµåæ¶ï¼èªå¨å°ä¿¡æ¯å å¥å°`Cargo.toml`

<p style="font-size: 20px; text-align: left;">
é¦åéè¦å®è£`cargo-edit`ï¼ç¶åå°±ä¼è·å¾ä¸ä¸ªæ©å±å½ä»¤`cargo add`ãä»¥åä½¿ç¨å®å®è£ç¬¬ä¸æ¹ä¾èµï¼å°±è½å°ä¾èµä¿¡æ¯èªå¨åå¥`Cargo.toml`äº
</p>

```shell
cargo install cargo-edit
```

```shell
cargo add mycrate
```

-----

<a href="https://github.com/chenxiaochun/blog/blob/master/article/%E7%BC%96%E8%AF%91Rust%E4%B8%BAWebAssembly.md" target="_blank">
ð° Rust ç¼å webAssembly ç¤ºä¾
</a>

---

## ç¸å³æç¨ð

-----

* <a href="https://play.rust-lang.org/" target="_blank">rust playground</a>
* <a href="https://learn.microsoft.com/zh-cn/training/paths/rust-first-steps/" target="_blank">rust å¾åäºé¡¹å°åºç¨</a>
* <a href="https://github.com/chenxiaochun/blog/blob/master/article/%E7%BC%96%E8%AF%91Rust%E4%B8%BAWebAssembly.md" target="_blank">rust webAssembly</a>
* <a href="https://course.rs/about-book.html" target="_blank">Rust è¯­è¨å£ç»</a>

<div class="fragment zoom-in" style="margin-top: 20px;">é½æ¯å¥é¨çº§ç»ä¹ ï¼åªè¦æç§æ­¥éª¤åï¼ç»å¯¹è½æå âï¸</div>

---

## Rust å­¦ä¹ æ²çº¿ð

-----

<img src="./images/01.png" />

---

# ð

æ¬æ¬¡ä»å¥é¨å°æ¾å¼ï¼åäº«ç»æ