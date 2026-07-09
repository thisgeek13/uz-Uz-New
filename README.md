# Özbekça yangi klaviatura tartibi (Uzbek New Latin Keyboard Layout)

Bu repozitoriy özbek lotin alifbosidagi maxsus harflar (**ğ, ö, ş, ç**) uchun möljallangan Windows klaviatura tartibini öz ichiga oladi. Tartib standart QWERTY (ANSI) joylaşuviga asoslangan bölib, faqat 4 ta tugma özbekça harflarga moslaştirilgan — qolgan barcha tugmalar odatdagidek işlaydi.

![Uzbek keyboard layout](uzbek_keyboard.svg)

## Nega kerak?

Rasmiy özbek lotin alifbosida `sh`, `ch`, `g'`, `o'` kabi digraflar (ikki belgidan iborat harflar) mavjud. Ushbu tartib ularning har birini bitta tugma bilan, bitta harf sifatida yoziş imkonini beradi:

| Digraf | Maxsus harf |
|:---:|:---:|
| `sh` | **ş** |
| `ch` | **ç** |
| `g'` | **ğ** |
| `o'` | **ö** |

## Nima özgargan?

Odatiy inglizcha (US) tartibdagi törtta belgi tugmasi özbekça harflarga almaştirilgan. Almaştirilgan asl belgilar yöqolib qolmagan — ular **Ctrl** va **Ctrl+Alt (AltGr)** qatlamlariga köçirilgan:

| Tugma (fizik joyi) | Oddiy | Shift | Ctrl | Ctrl+Alt |
|---|:---:|:---:|:---:|:---:|
| `[` örnida | **ğ** | **Ğ** | `[` | `{` |
| `]` örnida | **ö** | **Ö** | `]` | `}` |
| `;` örnida | **ş** | **Ş** | `;` | `:` |
| `\` örnida | **ç** | **Ç** | `\` | `\|` |

Qolgan barcha tugmalar (harflar, raqamlar, tiniş belgilari, `'`, `` ` `` va h.k.) standart US tartibi bilan bir xil işlaydi.

## Örnatish

Ushbu tartib [Microsoft Keyboard Layout Creator (MSKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134) yordamida yaratilgan `.klc` fayli asosida tuzilgan.

1. `.klc` faylini MSKLC dasturida oçing.
2. **Project → Build DLL and Setup Package** tugmasini bosing — bu `setup.exe` örnatuvçi faylini yaratadi.
3. `setup.exe` faylini işga tuşirib, tartibni tizimga örnating.
4. **Sozlamalar → Vaqt va til → Til → Klaviatura** bölimidan **"Uzbek new layout"** ni qöşing va faollaştiring.

## Til va litsenziya

- **Til:** Özbek tili (lotin yozuvi), `uz-UZ` (LCID `00000443`)
- **Muallif:** thisgeek
- **Litsenziya:** © 2026 thisgeek

## Hissa qöşiş

Xatolik topsangiz yoki takliflaringiz bölsa — Issue oçing yoki Pull Request yuboring.
