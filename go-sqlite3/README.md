### Building
`go build -tags "linux"`

### Attestation Generation

`witness run -o test-att.json --step build -- go build -tags "linux"`

#### With network-trace support

`witness run -a network-trace -o test-att.json --step build -- go build -tags "linux"`

