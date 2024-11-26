npm install
npm run dev

npx vite build --watch

package.json змінити значення прапора --base=/<vite-sass-starter-murkup-template>/, для команди build, замінивши <vite-sass-starter-murkup-template> на назву свого репозиторію.

Settings > Actions > General - в секції «Workflow permissions» обери опцію «Read and write permissions» і постав галочку в чекбоксі. Це необхідно для автоматизації процесу деплою проекту.
Settings > Pages - виставити роздачу продакшн версії файлів з папки /root гілки gh-pages, якщо це не було зроблено автоматично.
