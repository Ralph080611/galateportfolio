# Ralph Andrei D. Galate - Portfolio

Built with **React 18 + Vite + Tailwind CSS**.

## Run
```
npm install
npm run dev      # open the local URL
npm run build    # production build in /dist
```

## Edit
- `src/data.js` -> all your content (email, socials, education, certifications, hobbies, roles)
- `src/assets/photo.jpg` -> your photo
- `src/components/` -> one file per section
- `src/index.css` -> theme colors and animations

## Projects
- Edit the `projects` list in `src/data.js` (title `t`, description `d`, category `cat`, tags, `github`, optional `demo`, year `y`).
- Entries with `sample:true` show a "Sample" tag. Remove the flag once a project is real.
- The filter buttons are built automatically from the `cat` values.

## Deploy (Vercel)
Push the WHOLE folder to GitHub, including `src/` (with `src/assets/photo.jpg`), `index.html` and `package-lock.json`. Vercel auto-detects Vite: build `npm run build`, output `dist`.
