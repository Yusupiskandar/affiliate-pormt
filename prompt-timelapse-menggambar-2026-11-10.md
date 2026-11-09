# Prompt Time-lapse Menggambar 8 Detik — Google Flow (Veo 3.1)

Referensi contoh: sketsa pensil gadis anime berambut pendek berseragam pelaut di buku sketsa Moleskine, di atas meja kayu dengan latte, tanaman, kuas, dan tangan bersweter cokelat bata.

Prompt ini umum: gambar apa pun yang Anda upload akan menjadi objek yang digambar.

---

## 1. Cara pakai di Google Flow

1. **Mode yang disarankan: Frames to Video.** Taruh gambar upload sebagai **frame terakhir (end frame)**. Dengan begitu video pasti berakhir persis di gambar jadi Anda.
   - Frame awal boleh dikosongkan. Kalau mau lebih rapi, buat dulu gambar yang sama tapi halamannya masih kosong, lalu pakai sebagai frame awal.
2. **Durasi:** 8 detik, sesuai panjang satu klip Veo 3.1 di Flow. Tidak perlu Extend.

---

## 2. Prompt utama

```
A realistic overhead time-lapse video of an artist drawing in a sketchbook. The camera is completely locked off and static, top-down at a slight angle, matching the exact composition, framing, lighting and props of the reference image. The final frame must look exactly like the reference image.

The drawing being created is exactly the artwork shown on the open sketchbook page in the reference image — same subject, same pose, same line style, same proportions, same pencil shading. Nothing else is drawn.

Time-lapse progression, sped up, continuous:
- 0–1.5s: blank page, the hand quickly sketches light, loose construction lines and basic shapes of the subject.
- 1.5–4s: clean confident outlines appear — face, hair, body and main shapes take form.
- 4–6.5s: details are added rapidly — eyes, facial features, hair strands, clothing folds.
- 6.5–8s: soft graphite shading and final touches; the hand lifts slightly and the drawing is complete, identical to the reference.

The artist's right hand moves fast and naturally in time-lapse style, holding the pencil with a correct grip; the left hand rests still on the page holding the sketchbook. Pencil lines appear exactly where the pencil tip touches the paper. Everything else on the desk stays still: same objects, same positions, warm soft natural window light, cozy aesthetic. Subtle light flicker typical of time-lapse is fine, but no camera movement.

Photorealistic, 4K, shallow depth of field, natural skin texture, cozy art-studio mood.

Audio: fast, crisp pencil scratching on paper (ASMR style), faint paper rustle. No music, no voice.

Avoid: camera movement, zoom, morphing drawing, drawing a different subject or style, colored ink, text or watermark appearing, extra fingers, distorted hands, pencil floating, lines appearing away from the pencil tip, objects moving on the desk.
```

---

## 3. Tips supaya hasilnya cocok dengan gambar Anda

- **Gambar Anda adalah adegan lengkap** (meja dan tangan, seperti contoh): pakai prompt utama apa adanya, dengan gambar sebagai end frame.
- **Gambar Anda hanya karakter atau artwork saja** (tanpa meja): pakai mode **Ingredients to Video** dan ganti kalimat pertama di paragraf kedua menjadi:
  > The drawing being created is exactly the character/artwork from the uploaded reference image, rendered as a graphite pencil sketch on the sketchbook page.
- **Gambar berwarna** (cat air atau marker): ganti `soft graphite shading` dengan alat yang sesuai, contohnya `watercolor washes` atau `alcohol marker coloring`, lalu hapus `colored ink` dari daftar Avoid.
