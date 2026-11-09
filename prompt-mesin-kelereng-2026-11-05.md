# Prompt Google Flow: Mesin Kelereng (Loop ASMR)

Referensi: `C:\Users\LENOVO\Downloads\WhatsApp Image 2026-11-05 at 22.10.20.jpeg`
Hasil: 1 scene, 8 detik, vertikal 9:16, kamera diam, mesin diam, hanya kelereng yang bergerak, suara ASMR, siap di-loop.

## Cara pakai (Frames to Video, Veo 3.1, 9:16)
1. Pilih mode **Frames to Video**.
2. **Frame awal**: foto mesin yang sudah Anda upload di Flow.
3. **Frame akhir**: foto yang sama (supaya bisa di-loop). Kalau kolom ini tidak ada, lewati saja.
4. Tempel prompt di bawah, lalu generate.

```
Vertical 9:16, photorealistic smartphone footage of a real handmade plastic marble run machine on a light grey foam surface, exactly as in the first frame. One single continuous shot. Locked-off static camera on a tripod, the framing stays exactly identical to the first frame for the entire video: no zoom, no pan, no tilt, no dolly, no shake, no cuts, no change of angle. The machine itself stays completely still; the gears, the step lifter, the bowls and the chutes do not move. Only the marbles move.
Action: a slow, calm, relaxing and endless flow of colorful glass marbles, everything moves gently and unhurried. Marbles roll slowly one after another down the curved cream chute from the top, with wide gaps between them, and gently drop into the top funnel bowl. In each of the three bowls, one or two marbles circle slowly and lazily around the inside, taking several seconds to spiral inward, then softly drop through the center hole into the bowl below, and finally roll slowly out along the lower exit chute. The flow is slow, constant and rhythmic from start to end, with the same number of marbles on screen at all times, so the last frame looks the same as the first frame.
Audio: close-mic ASMR recording, crisp and detailed, very satisfying. A soft, slow, low hollow rolling of glass marbles around the plastic bowls, rising gently in pitch as they spiral toward the center. Well-spaced, unhurried drops with calm pauses between them. Each time a marble drops through a hole, a clear satisfying "tok" of glass hitting hard plastic, followed by a small bouncing rattle "tik-tik-tik" before it starts rolling again. A soft rolling rumble on the chute and a light glassy "ting" when two marbles touch. The marble drop sound is the loudest and clearest sound. Steady, even sound level from start to end, perfectly in sync with each marble on screen. No music, no speech, no motor noise.
Realism: natural daylight, true-to-life colors, accurate physics with marbles following gravity, slow gentle circular motion that only slightly speeds up near the center, realistic glass reflections and soft shadows, slightly imperfect handmade plastic with dust and small scratches.
Avoid: fast motion, rushing marbles, time-lapse, sped-up footage, any camera movement, zoom, reframing, cuts, moving gears, moving machine parts, light changes, text, watermark, logo, user interface, hands, people, marbles floating, marbles passing through walls, marbles rolling uphill, marbles appearing or disappearing, parts changing shape.
```

## Loop di CapCut
- Pilih 1 dari 4 output yang gerakannya paling mulus dan bunyi "tok"-nya paling pas.
- Kalau gerakan melambat di awal atau akhir, buang ±0,5 detik di bagian itu.
- Di sambungan, beri crossfade 0,3–0,5 detik dan fade audio 0,2 detik.
- Duplikat klip sesuai durasi yang dibutuhkan (8 kali ≈ 1 menit).
- Pakai suara asli Veo tanpa musik, naikkan volume ±20–30%, dan matikan noise reduction.

## Troubleshooting
| Masalah | Solusi |
|---|---|
| Teks atau UI YouTube dari foto ikut muncul | Crop fotonya sampai hanya mesin yang terlihat, lalu upload ulang |
| Sambungan loop terlihat "lompat" | Isi frame akhir dengan foto yang sama, lalu tambahkan crossfade |
| Kelereng masih terlalu cepat | Di CapCut: Kecepatan → 0,7×–0,8× (jangan di bawah 0,7× karena suara jadi berat dan gambar patah-patah). Atau tambahkan `in gentle slow motion` di kalimat Action |
| Kelereng berhenti di akhir video | Tambahkan `the marbles keep moving at the same speed until the very last frame` |
| Kamera masih bergerak | Pastikan frame akhir diisi foto yang sama |
| Roda gigi atau tangga ikut bergerak | Tambahkan `the gears are frozen and never rotate, the lifter plates never move` |
| Kelereng melayang / menembus dinding | Tambahkan `marbles always touching a surface except while falling` |
| Suara tidak pas dengan gambar | Generate ulang, atau tempel efek suara "marble drop" dari CapCut |
| Muncul musik atau suara orang | Tambahkan `no background music, no voices, no whispering` |
