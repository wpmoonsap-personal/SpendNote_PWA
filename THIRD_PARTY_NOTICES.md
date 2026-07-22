# SpendNote Third-Party Notices

© 2026 Watcharaporn Moonsap (maqmoq). Contact: wp.moonsap@gmail.com.

This file lists third-party libraries, tools, fonts, and services currently used by SpendNote. These licenses apply to the respective third-party components only. They do not change the license of SpendNote itself.

## Runtime Components

- **Tesseract OCR / Tesseract.js** - Apache License 2.0
  - Used for receipt text recognition in the web/PWA build.
  - License files are included in `web/vendor/tesseract/`.

- **Google ML Kit Text Recognition** - Google ML Kit terms and documentation
  - Used for receipt OCR in the Android app.

- **AndroidX Core** - Apache License 2.0
  - Android support/runtime functionality.

- **AndroidX WebKit** - Apache License 2.0
  - Android WebView support functionality.

- **Prompt Font** - SIL Open Font License 1.1
  - Used as the primary app font.
  - License file is included at `web/fonts/OFL-Prompt.txt`.

- **Frankfurter API** - External exchange-rate API
  - Used when the user taps to fetch exchange rates.
  - Requests send currency-pair queries, not personal financial data.

## Build Tools

- **esbuild** - MIT License
  - Used to build/minify the web/PWA assets.

- **javascript-obfuscator** - BSD-2-Clause License
  - Used to make public JavaScript builds harder to reverse-engineer.

- **Android Gradle Plugin / Android build tools** - Android/Google terms
  - Used to build the Android app.

## Thai Note

รายการข้างต้นเป็นใบอนุญาตหรือเงื่อนไขของไลบรารี เครื่องมือ ฟอนต์ และบริการภายนอกที่ SpendNote ใช้เท่านั้น ไม่ใช่ใบอนุญาตของโปรเจกต์ SpendNote เอง โค้ด ดีไซน์ โลโก้ ชื่อ SpendNote และไฟล์ประกอบของโปรเจกต์ยังอยู่ภายใต้ข้อกำหนดและสิทธิ์การใช้งานของ SpendNote เว้นแต่ระบุไว้เป็นอย่างอื่น
