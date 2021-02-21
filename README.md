* capacitor and svelte

code ran:

npx degit sveltejs/template svelte-app
cd svelte-app
npm i
npm run build
npm install @capacitor/core @capacitor/cli
npx cap init
change output dir to public instead of www (capacitor config)
npx cap add android
npx cap open android
