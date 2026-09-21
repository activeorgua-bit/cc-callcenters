# Шахрайські колцентри: дії правоохоронців — статичний дашборд

Статична збірка дашборда cc.ppl.watch для GitHub Pages: усі фільтри й агрегації рахуються в браузері
над знімком даних `data/cc_static.json` (дописи офіційних Telegram-каналів органів правопорядку, кейси,
канали, помісячні обсяги). Еталон (ручне кодування) — лише для читання.

Оновлення: на сервері `python cc_static_export.py` → `cc-web/public/data/cc_static.json` →
`VITE_STATIC=1 VITE_BASE=/cc-callcenters/ VITE_OUTDIR=dist-static npx vite build` → закомітити `dist-static` у гілку `gh-pages`.
