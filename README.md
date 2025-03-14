# What is the Egyptian Pages?

An open source database (a JSON file :D) of business/services owned by egyptians abroad to easily discover and support them.
Anyone is welcomed to contribute to the project by forking the repo and adding their business/services or any other business they know of.
If you are providing a service even individually (e.g translation, handy work, training) you are welcomed to add it to the directory.

# To get the list of businesses/services as a json, simply make a curl request:

```bash
curl https://raw.githubusercontent.com/tarek-eg/egyptianpages/main/src/data/data.json
```

## How to run

Nodejs v >= 22 is required

```bash
npm install
npm run test
```

## Contribution Guide

- Business should be abroad and owned by an Egyptian
- Business should be legal
- Add your business to the json file in src/data/data.json following the scheme defined in scheme.ts
- Run npm run test to make sure the data is valid
- Create a pull request
- Wait for the PR to be reviewed and merged
- Done!
