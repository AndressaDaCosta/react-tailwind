# React com TailwindCSS - Alura Newsletter

- npx tailwindcss -o build.css --minify

module.exports = {
plugins: {
tailwindcss: {},
autoprefixer: {},
...(process.env.NODE_ENV === 'production' ? { cssnano: {} } : {})
},
}
- npm run build