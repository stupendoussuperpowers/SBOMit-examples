### Building
`make release`

### Attestation Generation

`witness run -o test-att.json --step build -- make release`

#### With network-trace support

`witness run -a network-trace -o test-att.json --step build -- make release`

