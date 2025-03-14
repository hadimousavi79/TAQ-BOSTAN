


# 🚀 پروژه‌ی طاق‌بستان (TAQ-BOSTAN)
### غیرقابل شناسایی ترین تونل برای دور زدن فیلترینگ

---

دستور اجرای اسکریپت:

```bash
bash <(curl -Ls https://raw.githubusercontent.com/ParsaKSH/TAQ-BOSTAN/main/script.sh)
```
## 🌟 معرفی پروژه
پروژه‌ی **طاق‌بستان** یک راهکار جامع برای ایجاد تونل‌های امن اینترنتی و IPv6 لوکال است. این پروژه شامل سه بخش اصلی می‌شود:

- [🔒 ساخت تونل امن و سریع با Hysteria2](#بخش-اول-تونل-امن-و-سریع-با-hysteria2)
- [🌐 ایجاد IPv6 لوکال با SIT](#بخش-دوم-ایجاد-ipv6-لوکال-با-sit)
- [🛡 ایجاد IPv6 لوکال با WireGuard](#بخش-سوم-ایجاد-ipv6-لوکال-با-wireguard)

---

## 📌 نکات بسیار مهم
- اگر سرور شما IPv6 ندارد، ابتدا باید با **SIT** یا **WireGuard** یک IPv6 لوکال ایجاد کنید.
- اسکریپت‌ها تمامی مراحل نصب و تنظیمات را برای شما انجام می‌دهند.

---

## 🔒 بخش اول: تونل امن و سریع با Hysteria2
<details>
<summary>✅ مشاهده توضیحات و آموزش استفاده</summary>

### 📌 مزایا:
- تونل رمزنگاری‌شده **TLS 1.3 + QUIC**
- انتقال تمام ترافیک از طریق یک کانکشن واحد UDP
- جلوگیری کامل از مشکوک شدن سرور توسط ایران اکسس
- رفتار ترافیک مشابه HTTPS عادی (بدون ریسک شناسایی)
- بدون نیاز به دامنه (استفاده از SSL خودامضا)

### 🚀 نصب آسان:
اسکریپت را در هر دو سرور ایران و خارجی اجرا کنید.

- به سوالات به‌ترتیب پاسخ دهید تا نصب به‌راحتی انجام شود.

</details>

---

## 🌐 بخش دوم: ایجاد IPv6 لوکال با SIT
<details>
<summary>✅ مشاهده توضیحات و آموزش استفاده</summary>

### 📌 مزایا:
- بسیار سریع و سبک (بدون رمزنگاری اضافی)
- پشتیبانی مستقیم توسط هسته لینوکس (کرنل)
- نصب و راه‌اندازی آسان

**نحوه اجرا روی سرور ایران:**
- نوع سرور را **IRAN** انتخاب کنید.
- IP سرور ایران و تعداد سرورهای خارجی را وارد کنید.
- به‌ترتیب IP سرورهای خارجی را وارد کرده و سرور را ریبوت کنید.

**نحوه اجرا روی سرور خارجی:**
- نوع سرور را **FOREIGN** انتخاب کنید.
- IP سرور خارجی و IP سرور ایران را وارد کنید.
- شماره سرور خارجی (که در سرور ایران وارد کردید) را مشخص کنید.
- سرور را ریبوت کنید.

</details>

---

## 🛡 بخش سوم: ایجاد IPv6 لوکال با WireGuard
<details>
<summary>✅ مشاهده توضیحات و آموزش استفاده</summary>

### 📌 مزایا:
- امنیت بالا و رمزنگاری قوی
- تونل کردن همه ترافیک‌ها در یک کانکشن واحد UDP
- قابل استفاده روی سرورهای فیلتر شده


- نوع سرور (ایران یا خارجی) را مشخص کنید.
- IP عمومی سرورها و کلید عمومی WireGuard را وارد کنید.
- فایل‌های کانفیگ خودکار ساخته شده و سرویس فعال می‌شود.
- سرور را ریبوت کنید.

</details>

---

## 📞 پشتیبانی و راهنمایی

هرگونه سؤال یا مشکل خود را فقط با تگ کردن من در گروه اپ ایران مطرح کنید:
لطفا سوال خود را در پیوی مطرح نکنید، پاسخ داده نمی‌شود.

- 👤 **تلگرام من:** [@ParsaA_KSH](https://t.me/ParsaA_KSH)  
- 💬 **گروه اپ‌ایران:** [OPIranClub](https://t.me/OPIranClub)

---

## ❤️ حمایت مالی از پروژه

اگر پروژه برای شما مفید بود، برای حمایت مالی می‌توانید از آدرس‌های زیر استفاده کنید:

| شبکه | آدرس والت |
|-------|------------|
| **Tron** | `TD3vY9Drpo3eLi8z2LtGT9Vp4ESuF2AEgo` |
| **USDT** | `UQAm3obHuD5kWf4eE4JmAO_5rkQdZPhaEpmRWs6Rk8vGQJog` |
| **TON** | `bc1qaquv5vg35ua7qnd3wlueytw0fugpn8qkkuq9r2` |
| **BTC** | `0x800680F566A394935547578bc5599D98B139Ea22` |

از حمایت شما ممنونم ❤️

---

## 📝 لایسنس پروژه

پروژه‌ی طاق‌بستان تحت لایسنس **Apache** منتشر شده است.  
آزادانه از آن استفاده کنید؛ تنها نام من (Parsa) و لینک پروژه را ذکر نمایید.

---

## ⭐️ ستاره دادن به پروژه

اگر این پروژه برایتان مفید بود، حتماً به آن ستاره بدهید. این باعث می‌شود افراد بیشتری از آن استفاده کنند.

---

امیدوارم پروژه طاق‌بستان بتواند امنیت و سرعت اینترنت شما را افزایش دهد.  
با آرزوی موفقیت برای شما 🚀✨



![image](https://github.com/user-attachments/assets/f9f4e79a-0dd4-47ca-862a-8af8504a355a)
ایران، کرمانشاه
