# cujo

> Bu kitabın **hub klasörü**. Kitaba dair her şey (config, meta, prompt, upload pack) burada; render çıktıları `public/` ve `out/` altında, aşağıda linkli.

## Dosyalar

| | Konum | Not |
|---|---|---|
| 🎬 Final video | `out/cujo.mp4` _(yok)_ | render çıktısı |
| 🖼️ Thumbnail | `out/thumbnail-cujo.png` _(yok)_ | YouTube kapak |
| 📝 YouTube pack | `books/cujo/youtube.md` _(yok)_ | başlık/açıklama/tag/bölümler |
| 💬 Captions (CC) | `public/captions/cujo.clean.vtt` _(yok)_ | YouTube'a "With timing" yükle |
| 💬 Captions (ham) | [`public/captions/cujo.vtt`](../../public/captions/cujo.vtt) | kelime-zamanlı (karaoke kaynağı) |
| 🎙️ Audio | `public/audio/cujo.m4a` _(yok)_ | NotebookLM sesi |
| 🖼️ Scene images | `public/scenes/cujo/` _(yok)_ | Flux görselleri |
| ✍️ NotebookLM prompt | [`books/cujo/prompt.notebooklm.md`](prompt.notebooklm.md) | orijinal analiz açısı |
| 📖 Manifest | [`books/cujo/book.json`](book.json) | book.json (slug/başlık/engine) |
| ⚙️ Vox config | `books/cujo/config.vox.json` _(yok)_ | render config (beats/captions) |
| ⚙️ YouTube meta | `books/cujo/youtube-meta.json` _(yok)_ | SEO/meta + thumbnail brief |
| 🎞️ Render chunks | `out_Vox-cujo_chunks/` _(yok)_ | ara mp4 parçaları + parts.txt |

## Yükleme sırası
1. `out/cujo.mp4` yükle
2. Başlık + açıklama (bölümler tıklanabilir olur) + tag → [youtube.md](youtube.md)
3. Thumbnail → `out/thumbnail-cujo.png`
4. CC → `cujo.clean.vtt` ("With timing")
5. **Altered content = Yes** (sentetik ses)

## Yeniden üretmek
```bash
node scripts/make-book.js --slug=cujo --title="cujo"
```
