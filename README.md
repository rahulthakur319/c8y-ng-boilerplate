# EAI NG Backbone

### Prerequisites
This code is tested on node version v12.20.0

### Configuration Steps

1. Replace in all files `c8y-ng-boilerplate` with the name of the project
2. Replace the urls in proxy conf and package json
3. `npm install`
4. Copy `environments.ts` (in `src/environments`) to `environments.local.ts` and insert your c8y credentials & tenant.
5. `npm start`

### To deploy

```
npm run build && npm run deploy
```