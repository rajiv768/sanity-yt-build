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

To run sanity studio server(backend server), open another command window & cd sanityyoutube
sanity login
sanity start
Now we have 2 apps running which is sanity-yt-build(front-end) at localhost:3000 & sanityyoutube at http://localhost:3333

open 3rd command prompt & run npm i next-sanity

http://localhost:3333/desk
http://localhost:3000/post/rajiv-arora
ISR - Incremental Static Regeneration
npm i react-portable-text

npm install react-hook-form
npm i @sanity/client
https://www.sanity.io/manage
https://www.sanity.io/manage/personal/project/04gd9482
https://www.sanity.io/manage/personal/project/04gd9482/api
https://www.sanity.io/manage/personal/project/04gd9482/api#tokens
Add API token with Name Youtube Sanity & Editor selection, Save & Copy the token