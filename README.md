# MyMonorepo

## Run Cypress Browserstack

Change your creds in browserstack.json

https://github.com/RutvikChandla/demo-monorepo/blob/0052b8bb2325a3bf62d18198a897787b5e19a5cb/browserstack.json#L2-L5

Then run below commands to run cypress tests on browserstack
```sh
nvm install 20
nvm use 20
npm install
browserstack-cypress run
```

## For any issues regarding cypress config file for any external users please check below

- Browserstack.json should be on root level
- Path for home directory and cypress config should be relative to home directory and correct.

https://github.com/RutvikChandla/demo-monorepo/blob/4c7493b210076a35a0410b0023f865d153f78fa2/browserstack.json#L16-L17
