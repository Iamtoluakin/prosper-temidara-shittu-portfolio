# Prosper Temidara Shittu — Artist Portfolio

A Vite-powered, responsive portfolio built from the artist’s original 2026 PDF. All art images are taken from the PDF, not generated.

## Deploy to Vercel
1. Unzip the project and upload the folder to a GitHub repository.
2. In Vercel, select **Add New → Project** and import the repository.
3. Framework: **Vite**; Build command: `npm run build`; Output directory: `dist`.
4. Click **Deploy**. Vercel will provide a public `.vercel.app` URL.

## Local preview
`npm install` then `npm run dev`.

## Before publishing
- Ask the artist to approve the selected images and descriptions.
- Add the artist’s preferred contact method in the Contact section of `src.js`.
- Some photos show other people; confirm permission to display them publicly.
- The original PDF is 355 MB and is not included in the website bundle. If a PDF download is desired, upload an optimized version separately and add its URL.
