# React com TailwindCSS - Alura Newsletter

-   npx tailwindcss -o build.css --minify

module.exports = {
plugins: {
tailwindcss: {},
autoprefixer: {},
...(process.env.NODE_ENV === 'production' ? { cssnano: {} } : {})
},
}

-   npm run build

[π©π»βπ Certificado ](https://cursos.alura.com.br/certificate/a971714f-bef5-4294-a68a-0aab51e1d909)
[π PΓ‘gina ](https://react-tailwind-andressadacosta.vercel.app/)
