# Adaylar

Burası [Adaylar](https://adaylar.org)'un mdbook reposudur. Servis edilmeye hazır dosyaları `/docs` dizininde görebilirsiniz.

# Notlar

- Yerel makinede test etmek için:

      mdbook serve

- Daha sonra tarayıcınızdan şu adrese gidin:

      http://localhost:3000/

- `docs/` dizinini ve commitini hazırlayın:

      rm -rf docs/ && mdbook build -d docs/ && echo -n "adaylar.org" > docs/CNAME && git add docs/ && git commit -m "docs dizinini oluştur"

- mdbook yazılımını macOS işletim sisteminde şu şekilde yükleyebilirsiniz:

      brew install mdbook

- Parti logoları yaklaşık olarak 4096 piksel boyutlarında eklenmiştir. Bu çevirileri aşağıdaki komut ile sağlayabilirsiniz.

      for f in *.png; do convert $f -resize 4096@ $f; done

# Lisans

- İçeriklerin sunulmasında kullanılan [mdBook](https://github.com/rust-lang/mdBook) yazılımı [Mozilla Public License Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/) ile lisanslıdır.
  - Ayrıca çeşitli yazıtiplerinin lisanslarını GitHub reposunun ilgili dizinlerinde görebilirsiniz.

# Yazar
Kıvanç Yazan <kyzn at cpan dot org>
