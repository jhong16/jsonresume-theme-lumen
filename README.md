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

## Install, Build, Deploy (Local)
```
git clone <jsonresume-theme-lumen>

cd jsonresume-theme-lumen

npm install resume-cli@3.1.2

npx resume-cli --version
# Sanity Check 3.1.2

npx resume-cli validate --schema schema.json resume.json

sudo npm link

npx resume-cli export examples/resume/resume.html --theme .
```

## TODO:
- Actual Schema and Content on Projects Section
- Actual Schema and Content on Publications Section
- Actual Schema and Content on Awards Section
- Actual Schema and Content on References Section
- Actual Schema and Content on Languages Section