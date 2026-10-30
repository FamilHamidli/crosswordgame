# Kəlmə — gündəlik Azərbaycan krossvordu

Bu qovluqda saytın bütün faylları var:

- `index.html` — oyunun özü
- `puzzles.json` — redaktorda planlaşdırdığınız krossvordlar

`puzzles.json`-da həmin gün üçün krossvord yoxdursa, oyun özündəki 8 hazır krossvorddan birini göstərir.

## GitHub Pages-də yayımlamaq (bir dəfə)

1. GitHub-da yeni repozitoriya yaradın, məsələn `kelme`. **Public** seçin.
2. Repozitoriyada **Add file → Upload files** basın, `index.html`, `puzzles.json` və `README.md` fayllarını sürükləyib atın, **Commit changes** basın.
3. **Settings → Pages** bölməsinə keçin. **Source** üçün **Deploy from a branch**, branch üçün **main** və **/ (root)** seçin, **Save** basın.
4. 1–2 dəqiqədən sonra sayt `https://İSTİFADƏÇİ-ADINIZ.github.io/kelme/` ünvanında açılacaq.

## Yeni krossvordları əlavə etmək (hər həftə)

1. Claude-dakı redaktorda növbəti günlərin krossvordlarını yaradın.
2. **puzzles.json yüklə** düyməsini basın.
3. GitHub-da `puzzles.json` faylını açın, qələm işarəsinə (Edit) basın, köhnə məzmunu silib yenisini yapışdırın və ya **Add file → Upload files** ilə yeni faylı yükləyin. **Commit changes** basın.

Bir neçə dəqiqəyə sayt yenilənir.

## Öz domeninizi qoşmaq (istəyə görə)

Domen aldıqdan sonra **Settings → Pages → Custom domain** bölməsinə domeni yazın və domen satıcısının panelində GitHub-ın göstərdiyi DNS qeydlərini əlavə edin.
