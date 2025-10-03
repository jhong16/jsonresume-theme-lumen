# jsonresume-theme-lumen
A JSON Resume Theme

This was a learning exercise and an outcome of a resume format to optimize maximize readability 

## Feature Set:
- Custom Schema
    - Necessary for sub-bulleting
- Compiled the formatting tips from across various internets:
    - Subtle lining and separation
    - Maintaining font ratios to 1.33
    - A smaller sectioning of Certificates, Skills, and Interests
- Printable from HTML to PDF

## Install (Github, Recommended)
```
npm install github:jhong16/jsonresume-theme-lumen --save-dev
```

## Install and Build (Bootstrapped)
```
git clone <jsonresume-theme-lumen>
cd jsonresume-theme-lumen

node --version # v20.19.2
npm --version # 9.2.0

npm install path/<jsonresume-theme-lumen> --save-dev
npm link jsonresume-theme-lumen
```

### Deploy with resume-cli
```
npm install resume-cli --save-dev
npx resume-cli --version # 3.1.2

npx resume-cli validate --schema schema.json resume.json
npx resume-cli export examples/resume/resume.html --theme .
```

## Deploy with resumed
There's no abilty to validate on a custom schema it seems. But it exports okay.
```
npm install resumed --save-dev
npx resumed --version # resumed, 6.1.0

npx resumed render resume.json --output examples/resume/resume.html --theme jsonresume-theme-lumen
```


## TODO:
- Actual Schema and Content on Projects Section
- Actual Schema and Content on Publications Section
- Actual Schema and Content on Awards Section
- Actual Schema and Content on References Section
- Actual Schema and Content on Languages Section