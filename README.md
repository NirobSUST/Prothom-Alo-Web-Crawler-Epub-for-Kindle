# 📰 Daily Prothom Alo Newspaper to e-Book (EPUB) Converter

Turn today's news from Prothom Alo into a clean, easy-to-read e-book for your Kindle, Kobo, or mobile e-reader!

---

## 🌟 What Does This Project Do?

This tool automatically visits **[Prothom Alo](https://www.prothomalo.com)** (one of the largest news portals in Bangladesh), collects all of today's published articles, and compiles them into a single, beautifully organized **EPUB e-book file**.

### Why use it?
* **Read Offline:** Download your daily newspaper once and read it anywhere—on a flight, commute, or offline.
* **Eye-Friendly Reading:** Transfer the e-book to your Kindle, Kobo, reMarkable, or tablet for a distraction-free, screen-friendly reading experience.
* **Organized & Clickable:** Includes a interactive Table of Contents sorted by topics (National, World, Sports, Entertainment, Opinion, Business, etc.).

---

## 🚀 How It Works (In Simple Terms)

1. **Scans Categories:** The script starts by visiting the main sections and topic pages on Prothom Alo.
2. **Finds Today's News:** It checks the publication timestamp of every article to make sure only stories published **today** (in Bangladesh standard time) are collected.
3. **Extracts Article Content:** It cleanly extracts headlines, categories, publication dates, and full story text while ignoring distracting ads and popups.
4. **Builds an E-Book:** It combines all articles into a single, organized `.epub` file saved directly to your Google Drive or computer.

---

## ⚙️ How to Run It (Step-by-Step)

You don't need to install anything complicated on your computer! You can run this easily using **Google Colab** in your web browser.

### Option 1: Run on Google Colab (Recommended)

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a **New Notebook**.
3. Copy the Python script into a code cell.
4. Click the **Play button** (▶) on the left side of the code cell to start.
5. If prompted, allow access to mount your Google Drive (so the output e-book file can be saved).
6. Wait for the process to complete—your fresh daily e-book will be saved directly inside your Google Drive!

---

## 📱 How to Read the EPUB File

Once the script generates your file (e.g., `Prothom_Alo_2026-08-08.epub`):

* **On Kindle:** Send the file to your Kindle email address using Amazon's [Send to Kindle](https://www.amazon.com/sendtokindle) service.
* **On Android:** Open the file using Google Play Books, ReadEra, or Moon+ Reader.
* **On iPhone / iPad / Mac:** Open the file directly in Apple Books.
* **On Kobo / Nook:** Connect your device via USB and copy the `.epub` file over.

---

## 🧰 Requirements (For Tech Users running locally)

If you prefer running this script on your own computer terminal, ensure you have Python 3.8+ installed along with these libraries:

```bash
pip install requests beautifulsoup4 ebooklib python-dateutil pytz
```

---

## 📄 License

This project is open-source and intended for personal reading and offline access only.
