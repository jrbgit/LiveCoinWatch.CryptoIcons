# LiveCoinWatch.CryptoIcons

A complete download off all cryptocurrency token icons from the LiveCoinWatch API. (I did not include the .webp files in this repo due to the size, however the script will download any or all of the 4 available formats.

### Folder Structure

- `icons/`
  - `32x32/`
    - `png`
    - `webp`
  - `64x64/`
    - `png`
    - `webp`

### File Formats

TICKER.png

TICKER.webp

- PNG 32
- PNG 64
- Webp 32
- Webp 64

### Example

- `icons/png/32x32/ADA.png`
- `icons/png/64x64/ADA.png`
- `icons/webp/32x32/ADA.webp`
- `icons/webp/64x64/ADA.webp`

### Source Code

I will upload the source code that built this dataset shortly. Right now the coin URLS are being pulled from a SQL database that already contains the LiveCoinWatch API Data. When I release the code, I would like to make it an all-in-one script that grabs the coin image URLs directly from the API.

### Examples

#### PNG 32x32

![ADA PNG 32x32](icons/32x32/png/ADA.png)
![MATIC Polygon PNG 32x32](icons/32x32/png/MATIC.png)
![Cosmos PNG 32x32](icons/32x32/png/ATOM.png)
![GLQ PNG 32x32](icons/32x32/png/GLQ.png)
![XRP PNG 32x32](icons/32x32/png/XRP.png)

#### PNG 64x64

![ADA PNG 64x64](icons/64x64/png/ADA.png)
![MATIC Polygon PNG 64x64](icons/64x64/png/MATIC.png)
![Cosmos PNG 64x64](icons/64x64/png/ATOM.png)
![GLQ PNG 64x64](icons/64x64/png/GLQ.png)
![XRP PNG 64x64](icons/64x64/png/XRP.png)
