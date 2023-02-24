# MarkDown Dokuman

#### MarkDown ile navigation oluşturmak
```
input

- [MarkDown ile Döküman](#markdown-dokuman)
  - [Başlık Oluşturma](#basliklar-olusturma)
  - [Paragraf Oluşturma](#paragraf-olusturma)
  - [Liste Oluşturma](#liste-olusturma)
  - [Link Oluşturma](#link-olusturma)
  - [Resim Ekleme](#resim-ekleme)
```

Output
- [MarkDown ile Döküman](#markdown-dokuman)
  - [Başlık Oluşturma](#basliklar-olusturma)
  - [Paragraf Oluşturma](#paragraf-olusturma)
  - [Liste Oluşturma](#liste-olusturma)
  - [Tablo Oluşturma](#tablo-olusturma)
  - [Link Oluşturma](#link-olusturma)
  - [Resim Ekleme](#resim-ekleme)

## Basliklar Olusturma

```
Girdi (input)

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
```

Çıktı (output)

# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6


## Use Case MarkDown

```
| ✅ Do this         | ❌ Don't do this  | ❌ Don't do this  |
| ------------------ | ----------------- | ----------------- |
| # Here's a Heading | #Here's a Heading | #Here's a Heading |
| # Here's a Heading | #Here's a Heading | #Here's a Heading |
```

| ✅ Do this         | ❌ Don't do this  | ❌ Don't do this  |
| ------------------ | ----------------- | ----------------- |
| # Here's a Heading | #Here's a Heading | #Here's a Heading |
| # Here's a Heading | #Here's a Heading | #Here's a Heading |

***

# Paragraf Olusturma

MarkDown'da syntax olmadan olmadan yazılabilir

#### Kalın(Bold) Yazmak

```
Input
I just love **bold text**.
```

Output

I just love **bold text**.

#### Eğik Yazmak

```
Input
Italicized text is the *cat's meow*.
```

Output

Italicized text is the _cat's meow_.

#### Hem Eğik hem kalın

```
Input
This text is ***really important***.
```

Output

This text is **_really important_**.

#### Blok Alıntı

```
Input
> Dorothy followed her through many of the beautiful rooms in her castle.
```

Output

> Dorothy followed her through many of the beautiful rooms in her castle.

İçiçe Blok Alıntı (Blockquotes with Other Elements)

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>   _Everything_ is going according to **plan**.

***

## Liste Olusturma

Liste oluştururken direk kendi sayı vermekte 1,1,1,1 veya 3,5,6,8 gibi verseler de

```
Input
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
        1. Item Test
            1. Item in test
            2. Test two
4. Fourth item
```

Output

1. First item
2. Second item
3. Third item
   1. Indented item
   2. Indented item
      1. Item Test
         1. Item in test
         2. Test two
4. Fourth item

Hepsinin Çıktısı Aynı Olur ( \* , - , + üçüde aynı çıktıyı verir)

```
Inputs
* First item
* Second item
* Third item
* Fourth item

- First item
- Second item
- Third item
- Fourth item

+ First item
+ Second item
+ Third item
+ Fourth item

```

Output

- First item
  - Second item
- Third item
- Fourth item



```
Input

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
```

Output

- First item
- Second item
- Third item
  - Indented item
  - Indented item
- Fourth item

Listedeki Kaçınma Karakteri \ (Unordered List)

```
Input

- 1968\. A great year!
- I think 1969 was second best.
```


Output

- 1968\. A great year!
- I think 1969 was second best.

| ✅ Do this         | ❌ Don't do this  |
| ------------------ | ----------------- |
| - First item | - First item |
| - First item | + First item |
| - First item | * First item |
| - First item | + First item |

***

## Tablo Olusturma

| Sütun 1 | Sütun 2   | Sütun  3  |
| ------- | --------- | ----------|
| satır 1 | satır 1-2 | satır 1-3 |
| satır 2 | satır 2-2 | satır 2-3 |
```

| ✅ Do this         | ❌ Don't do this  | ❌ Don't do this  |
| ------------------ | ----------------- | ----------------- |
| # Here's a Heading | #Here's a Heading | #Here's a Heading |
| # Here's a Heading | #Here's a Heading | #Here's a Heading |

## Yatay Çizgi (Horizontal Rules)
```
Input
***

---
___
```

Output

***
---
___

## Link Olusturma

```
Input
My favorite search engine is [Google](https://google.com).
```

Output

My favorite search engine is [Google](https://google.com).

#### Linke Açıklama Ekleme

üstüne gelince yazar

```
Input
My favorite search engine is [Google](https://google.com "https://google.com").
```

Output

My favorite search engine is [Google](https://google.com "https://google.com").


#### URL veya Mail Ekleme

My favorite search engine is <https://www.google.com>

<fake@example.com>

```
My favorite search engine is <https://www.google.com>

<fake@example.com>
```

#### Link Formatını Değiştirme

```
Input
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).
```

Output

I love supporting the **[EFF](https://eff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

See the section on [`code`](#code).

## Resim Ekleme
```
Input
![Test Image](/github-temp.png "Github Temp Test")
```
Output
![Test Image](/github-temp.png "Github Temp Test")

Link ve resim birlikte verilmek istenirse

```
Input
[![Bu bir link ve resimdir](/github-temp.png )](https://www.google.com "Google.com")
```

