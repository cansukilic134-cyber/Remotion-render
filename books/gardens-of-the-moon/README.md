# gardens-of-the-moon

> Bu kitabın **hub klasörü**. Kitaba dair her şey (config, meta, prompt, upload pack) burada; render çıktıları `public/` ve `out/` altında, aşağıda linkli.

## Dosyalar

| | Konum | Not |
|---|---|---|
| 🎬 Final video | `out/gardens-of-the-moon.mp4` _(yok)_ | render çıktısı |
| 🖼️ Thumbnail | `out/thumbnail-gardens-of-the-moon.png` _(yok)_ | YouTube kapak |
| 📝 YouTube pack | `books/gardens-of-the-moon/youtube.md` _(yok)_ | başlık/açıklama/tag/bölümler |
| 💬 Captions (CC) | `public/captions/gardens-of-the-moon.clean.vtt` _(yok)_ | YouTube'a "With timing" yükle |
| 💬 Captions (ham) | [`public/captions/gardens-of-the-moon.vtt`](../../public/captions/gardens-of-the-moon.vtt) | kelime-zamanlı (karaoke kaynağı) |
| 🎙️ Audio | `public/audio/gardens-of-the-moon.m4a` _(yok)_ | NotebookLM sesi |
| 🖼️ Scene images | `public/scenes/gardens-of-the-moon/` _(yok)_ | Flux görselleri |
| ✍️ NotebookLM prompt | [`books/gardens-of-the-moon/prompt.notebooklm.md`](prompt.notebooklm.md) | orijinal analiz açısı |
| 📖 Manifest | [`books/gardens-of-the-moon/book.json`](book.json) | book.json (slug/başlık/engine) |
| ⚙️ Vox config | `books/gardens-of-the-moon/config.vox.json` _(yok)_ | render config (beats/captions) |
| ⚙️ YouTube meta | `books/gardens-of-the-moon/youtube-meta.json` _(yok)_ | SEO/meta + thumbnail brief |
| 🎞️ Render chunks | `out_Vox-gardens-of-the-moon_chunks/` _(yok)_ | ara mp4 parçaları + parts.txt |

## Yükleme sırası
1. `out/gardens-of-the-moon.mp4` yükle
2. Başlık + açıklama (bölümler tıklanabilir olur) + tag → [youtube.md](youtube.md)
3. Thumbnail → `out/thumbnail-gardens-of-the-moon.png`
4. CC → `gardens-of-the-moon.clean.vtt` ("With timing")
5. **Altered content = Yes** (sentetik ses)

## Yeniden üretmek
```bash
node scripts/make-book.js --slug=gardens-of-the-moon --title="gardens-of-the-moon"
```
