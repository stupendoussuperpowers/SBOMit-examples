### Building
`npm install && npm run build`

### Attestation Generation

`witness run -o test-att.json --step build -- npm install && npm run build`

#### With network-trace support

`witness run -a network-trace -o test-att.json --step build -- npm install && npm run build`
