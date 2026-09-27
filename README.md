# woo-sync — نسخه‌ها

فایل نصب هر نسخهٔ woo-sync (پنل همگام‌سازی قیمت و موجودی ووکامرس با لیست اکسل).

- **دانلود:** از بخش [Releases](https://github.com/P3R6/woo-sync-releases/releases)، فایل `woo-sync-setup-<نسخه>.exe`.
- برنامه روزی یک بار همین‌جا را نگاه می‌کند و نسخهٔ تازه را خبر می‌دهد؛ برگشت به نسخه‌های قبلی هم از داخل برنامه است: **تنظیمات ← نسخه و به‌روزرسانی**.
- `releases.json` فهرست نسخه‌هاست، امضاشده با کلید سازنده. برنامه نسخه‌ای را نصب می‌کند که امضای این فهرست درست باشد و فایل نصبش بایت‌به‌بایت با آن بخواند؛ چیز دیگری نه.

---

Installers for woo-sync. `releases.json` is the signed list of the versions the
program offers, each Setup named by size and SHA-256. The program checks the
signature against the public key built into it and installs nothing else.
Do not edit `releases.json` by hand: an edited file no longer verifies, and
every copy ignores it.
