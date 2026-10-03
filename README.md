# Оқу кеңістігі — GitHub Pages

## Жариялау
1. github.com сайтына кіріп, аккаунтыңызға кіріңіз.
2. `+` → **New repository** таңдаңыз.
3. Repository name: `oku-kitap`; **Public** таңдаңыз; **Create repository** басыңыз.
4. Репозиторийде **Add file → Upload files** басыңыз.
5. Осы ZIP-тен шығарылған `index.html` мен `README.md` файлдарын терезеге сүйреп апарыңыз.
6. Төменнен **Commit changes** басыңыз.
7. **Settings → Pages** ашыңыз.
8. **Build and deployment** бөлімінде Source: **Deploy from a branch**; Branch: `main`; Folder: `/ (root)` таңдаңыз; **Save** басыңыз.
9. 1–5 минуттан соң Pages бетінде көрсетілген сілтемені ашыңыз: `https://USERNAME.github.io/oku-kitap/`.

## Word файлдарын сайтқа енгізу
Word (.docx) файлын GitHub-қа жүктеу оның мәтінін автоматты түрде кітап бетіне айналдырмайды. Қарапайым әдіс: Word-та мәтінді белгілеу (Ctrl+A), көшіру (Ctrl+C), ал `index.html` ішіндегі `items` массивінен тиісті бөлімнің `title` және `content` мәндерін ауыстыру. Сақтап, GitHub-та жаңартылған файлды қайта жүктеп, **Commit changes** басыңыз.

## PDF
Сайттағы PDF сақтау батырмасы браузердің басып шығару терезесін ашады. Destination/Printer ішінен **Save as PDF** таңдаңыз.
