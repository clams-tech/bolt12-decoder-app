## BOLT12 Offer Decoder

[Demo](https://bolt12.surge.sh/)

## Description

A web application that facilitates the decoding of BOLT12 offers using the [bolt12-decoder](https://github.com/lnbc1QWFyb24/bolt12-decoder) npm package.

Users can paste an encoded offer into the designated text area and receive the corresponding decoded JSON representation in another text area.

## Features

- Decode BOLT12 offers into JSON format.
- Handle errors during the decoding process.
- Pre-fill the encoded input field with an `offer` query param from the URL like so: [https://bolt12.surge.sh/?offer=lno1qgsqvgnwgcg35z6ee2h3yczraddm72xrfua9uve2rlrm9deu7xyfzrc2q42xjurnyyfqys2zzcssx06thlxk00g0epvynxff5vj46p3en8hz8ax9uy4ckyyfuyet8eqg](https://bolt12.surge.sh/?offer=lno1qgsqvgnwgcg35z6ee2h3yczraddm72xrfua9uve2rlrm9deu7xyfzrc2q42xjurnyyfqys2zzcssx06thlxk00g0epvynxff5vj46p3en8hz8ax9uy4ckyyfuyet8eqg)

## Getting Started

### Install Dependencies:

```bash
npm i
```

### Run the app:

```bash
npm run dev
```
