# Your-life-site
40. Individual project called "Just od it"

# repo -> https://github.com/MichalAW/Your-life-site.git

# link -> 

# Script
1. Download repository
2. Launch script "watch" to visit site

# Package.json scripts
1. "prewatch": "npm run clean",
2. "watch": "parcel src/index.html --open --no-autoinstall --port 8080",
3. "sass": "node-sass src/sass/ -o src/css/",
4. "prebuild": "npm run clean",
5. "build": "parcel build src/index.html --out-dir docs --public-url /Just-do-it",
6. "clean": "rimraf dist",
7. "code-quality": "npm run format && npm run lint",
8. "format": "prettier --write \"src/**/*.{js,html,scss}\""
# Design bought