# Paper Clip

___Edit PDF document metadata___

Edit the title, author, keywords and more details of your PDF documents

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing

```
flatpak install flathub io.github.diegoivan.pdf_metadata_editor
flatpak run io.github.diegoivan.pdf_metadata_editor
```

## Building

```
git clone git@github.com:yakushabb/io.github.diegoivan.pdf_metadata_editor.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.github.diegoivan.pdf_metadata_editor.json
```

---

**Technologies**: GNOME, GTK4, Libadwaita, Poppler, Libexempi, Vala
