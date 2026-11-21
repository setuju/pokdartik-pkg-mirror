# pokdartik-pkg-mirror

Arsip berkas paket terverifikasi dan materi referensi (`pkg-64e2888849d6/`) beserta manifes integritas `SHA256SUMS.txt` untuk mirror dokumen PokdarTIK.

## Isi Direktori Terkini (`pkg-64e2888849d6/`)

- `pkg-64e2888849d6/eBook _ _Belajar Pemrograman Python_.pdf`
- `pkg-64e2888849d6/eBook _ _Belajar Pemrograman Python Tingkat Menengah_.pdf`
- `pkg-64e2888849d6/eBook _ _Belajar Pemrograman Python Tingkat Mahir_.pdf`
- `pkg-64e2888849d6/eBook _ _Dasar-dasar Pemrograman Nodejs_.pdf`
- `pkg-64e2888849d6/eBook _ _Kamus Istilah Pemrograman Komputer_.pdf`
- `pkg-64e2888849d6/WiTiGemma-CPU-Setup-Win.zip` *(Git LFS — installer Windows x64 CPU-only, lolos `unzip -t`)*
- `pkg-64e2888849d6/witi-ai-linux-qnm-gemma-1.0.tar.gz` *(Git LFS — arsip Linux `.tar.gz`, lolos `gzip -t` & `tar -tzf`)*
- `pkg-64e2888849d6/witi-ai-linux-qnm-gemma_1.0_amd64.deb` *(Git LFS — paket Debian/Ubuntu `amd64`, lolos `control.tar.xz` & `data.tar.xz`)*
- `pkg-64e2888849d6/witi-ai-linux-qnm-gemma-1.0-1.x86_64.rpm` *(Git LFS — paket RPM `x86_64`, lolos dekompresi penuh payload `gzip`)*
- `SHA256SUMS.txt`

## Verifikasi Integritas Berkas

Setelah mengunduh berkas (dan menarik objek Git LFS jika menggunakan `git lfs`), verifikasi *checksum* SHA-256 dengan:

```bash
sha256sum -c SHA256SUMS.txt

```

## Catatan Status & Sumber

* Sumber utama (`pokdartik.or.id`) sempat mengalami kendala akses/DNS (`SERVFAIL`), dan salinan arsip awal `.zip`, `.deb`, serta `.rpm` ditemukan mengalami kerusakan pada bagian isi/kompresi meskipun *hash* lamanya cocok.
* Berkas paket yang dipublikasikan di mirror ini adalah salinan yang telah diuji integritas kompresi/payload-nya dan dicocokkan ulang pada `SHA256SUMS.txt`.
