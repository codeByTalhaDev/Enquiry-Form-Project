```md
# Front-End
```
```md
# 1-Create Vite Project

npm create vite
cd foldername
npm install
```

```md 
#2-Install Tailwind

#Step 1:

npm install tailwindcss @tailwindcss/vite

#Step 2:

#In => vite.config.js

import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'
export default defineConfig({
  plugins: [
    tailwindcss(),
  ],
})

#Step 3:

In => index.css

@import "tailwindcss";
```
```md
# 3-Import Flowbite

# Step 1:

npx flowbite-react@latest init

# Step 2:

npm install flowbite-react@latest flowbite@latest
```


```md
# Deployment

# The Rule of Thumb
# Stage	                      MongoDB Type	         Notes
Development (local)	        MongoDB Compass	     Works only on your machine
Deployment (online)	        MongoDB Atlas	       Must be cloud, your server cannot access local DB
Someone else downloading	  Local or Cloud	     They choose; your code only gives the models & connection variable
```