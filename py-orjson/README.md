### Building
`maturin build --release --strip`

### Attestation Generation

`witness run -o test-att.json --step build -- maturin build --release --strip`

#### With network-trace support

`witness run -a network-trace -o test-att.json --step build -- maturin build --release --strip`

