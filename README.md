# Sales Dashboard 2026 (view only)
Static site: index.html + data.json. Viewers can filter but cannot upload or change data.

## Deploy ke Vercel
1. npm i -g vercel
2. cd folder ini, lalu jalankan: vercel --prod
   (atau push folder ke GitHub lalu Import di vercel.com/new, Framework: Other, tanpa build command)

## Update bulanan
Ganti data.json dengan versi terbaru lalu deploy ulang. data.json dibuat dari RD + RD Own Store
(format: {"tx":[...],"own":[...]}). Minta saya generate ulang setiap bulan dengan file terbaru.
