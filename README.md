🔧 Development
Start the development server on http://localhost:3000:

bash
Copy
Edit
# npm
npm run dev

# yarn
yarn dev

# pnpm
pnpm dev

# bun
bun run dev
📦 Production
Build the application for production:

bash
Copy
Edit
# npm
npm run build

# yarn
yarn build

# pnpm
pnpm build

# bun
bun run build
🔍 Preview Production Build
bash
Copy
Edit
# npm
npm run preview

# yarn
yarn preview

# pnpm
pnpm preview

# bun
bun run preview
📚 Install Required Libraries
✅ Tailwind CSS
bash
Copy
Edit
npm install -D @nuxtjs/tailwindcss
Then add it to your nuxt.config.ts:

ts
Copy
Edit
export default defineNuxtConfig({
  modules: ['@nuxtjs/tailwindcss']
})
✅ GSAP (for animation)
bash
Copy
Edit
npm install gsap
Use it in any Vue component:

ts
Copy
Edit
import gsap from 'gsap'
🪄 Features
🔤 Dual-language support (Khmer & English)

🖼️ Upload and preview personal photos

🎨 Department-based gradient card themes

🖋️ Khmer font support (Moul, Siemreap)

🧠 Smooth GSAP animations

📱 Responsive layout with Tailwind CSS

🧩 Easy to customize and extend

🚀 Deployment
Check out Nuxt’s official deployment guide:
📘 https://nuxt.com/docs/getting-started/deployment

📝 License
MIT — feel free to modify, contribute, or fork.

👤 Author
Akari Kenn

yaml
Copy
Edit
