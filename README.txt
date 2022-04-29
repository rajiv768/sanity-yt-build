npx create-next-app --example with-tailwindcss sanity-yt-build
cd sanity-yt-build
code .
https://www.sanity.io/
Create a new project with our command line
npm install -g @sanity/cli
sanity init or 
sanity init --coupon sonny2022	-- initialize sanity studio inside this directory
login with google
project name: sanityyoutube
default dataset configuration: Y
This gives us the backend with some data associated with it
Project output path: Enter
Select project template: Blog schema
Now we have a new project sanityyoutube in https://www.sanity.io/
npm run dev

git remote add origin https://github.com/rajiv768/sanity-yt-build.git
git add .
git commit -m 'first commit'
git push -u origin main