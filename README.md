# The Holy Quran

Minimal, no JavaScript, Amiri Quran font based rendering of the Holy Quran.

## GitHub Pages based Website

Visit <https://shakeel.github.io/quran> to view the HTML pages from this repository
hosted via GitHub pages.

Learn more about how to enable your own GitHub repository to start serving your website <https://pages.github.com/>.

## PageSpeed Insights

In order to reduce any overhead in rendering the website and to get the best performance possible,
I have tried to eliminate any usage of JavaScript frameworks, images, and limited usage of network
calls.

Without spending any time on improving the performance the initial performance result for the desktop
looks very promising.

* <https://pagespeed.web.dev/report?url=https%3A%2F%2Fshakeel.github.io%2Fquran%2F&form_factor=desktop>
* <https://pagespeed.web.dev/report?url=https%3A%2F%2Fshakeel.github.io%2Fquran%2Fsurah%2F002.html&form_factor=desktop>

There is still room for improvement on mobile platforms.

* <https://pagespeed.web.dev/report?url=https%3A%2F%2Fshakeel.github.io%2Fquran%2F&form_factor=mobile>
* <https://pagespeed.web.dev/report?url=https%3A%2F%2Fshakeel.github.io%2Fquran%2Fsurah%2F002.html&form_factor=mobile>

## How were there HTML files created?

All credit is due to [aliftype](https://github.com/aliftype/) aka [Khaled Hosny](https://github.com/khaledhosny) 
for creating the [Amiri Font](https://www.amirifont.org/), the [Reem Kufi font](https://github.com/aliftype/reem-kufi),
the [Qahiri Font](https://aliftype.com/qahiri/) and most importantly for the [quran-data](https://github.com/aliftype/quran-data)
which has the Quran as UTF-8 encoded plain text files, following the best Unicode practices as possible (no more font specific hacks, no repurposing of totally unrelated code points and so one), plus some tools to convert it into other document formats.

I forked the [quran-data](https://github.com/aliftype/quran-data) repository to modify the Python script to generate HTML files.

This forked repo [shakeel/quran-data](https://github.com/shakeel/quran-data) has the generated HTML files.

This [repo](https://github.com/shakeel/quran) has the hand generated index.html file for a table of contents of the Surah names. I made sure that the HTML files work as intended on mobile platforms too.

## Is this work done?

* No, I plan to create Juz 1..30 for an easier reading experience.
* Additional plans are to create a page based layout for each Juz.
* Create SQLite database for each verse of the Quran from the UTF-8 encoded text files.
* Create n-grams for the entire Quran.
* Link each word to the Quran Corpus website for grammatical analysis.
* Add Islamic Classes notes for tafseer of Surah al Fatiha and the beginning verses of Surah al Baqarah.

All contributions are welcomed.
