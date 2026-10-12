# Resume Customizer - Frontend

Next.js app: upload a resume, paste a job description, get a tailored resume and download it as PDF/DOCX.

Backend repo: https://github.com/divyacoder01/resume_backend (full documentation is in its README).

## Run locally
```
npm install
echo NEXT_PUBLIC_API_URL=http://localhost:8000 > .env.local
npm run dev
```

## Deploy (Vercel)
Import this repo, add env var `NEXT_PUBLIC_API_URL` = your Render backend URL.
