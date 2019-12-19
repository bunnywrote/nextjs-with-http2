# Customized HTTP2 server example

## How to use

Create the public and private keys:

```bash
openssl req -x509 -newkey rsa:2048 -nodes -sha256 -subj '/CN=localhost' \
  -keyout localhost-privkey.pem -out localhost-cert.pem
```

Install it and run:

```bash
npm install
npm run dev
# or
yarn
yarn dev
```