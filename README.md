
# <h1 align="center">TUBE STIMA</h1>

##  Deskripsi

<p align="justify">
  
</p>

## Bahasa Yang Digunakan

<ol>
    <li> Python</li>
</ol>

## Cara menjalankan bot
<p>1. Pastikan sudah mendownload python dan jika belum installer di https://www.python.org/
      dan centang opsi “Add Python to PATH” saat instalasi</p>
<p>2. Dowloan file game engine [klik disini](https://github.com/haziqam/tubes1-IF2211-game-engine/releases/tag/v1.1.0)</p>

<p>3. Download file bot starter pack [klik disini](https://github.com/16-197-M-Rafiq-Ridho/Tubes-Stima)</p>

<p>4. download [Node.js](https://nodejs.org/en) dan [docker](https://www.docker.com/products/docker-desktop/)</p>

## Buka CMD lalu
1. Masuk direktori game engine
   ```
   cd ./tubes1-IF2110-game-engine
   ```
3. Install dependencies

   ```
   yarn
   ```

4. Setup default environment variables

   For windows

   ```
   ./scripts/copy-env.bat
   ```

   For Linux /(possibly) macOS

   ```
   chmod +x ./scripts/copy-env.sh
   ./scripts/copy-env.sh
   ```

5. Setup local database

   ```
   docker compose up -d database
   ```

   For windows

   ```
   ./scripts/setup-db-prisma.bat
   ```

   For Linux /(possibly) macOS

   ```
   chmod +x ./scripts/setup-db-prisma.sh
   ./scripts/setup-db-prisma.sh
   ```

6. Build

   ```
   npm run build
   ```

## How to Run 💻

```
npm run start
```

<p>and Enjjooyyyy.........walaupun bekum optimal</p>


## Contributors

| Nama                        | NIM       | Link Github                                                                            |
| ----------------------------| --------- | -------------------------------------------------------------------------------------- |
| Maxavier Girvanus Manurung  | 123140191 | [@01-191-MaxavierGirvanusManurung](https://github.com/01-191-MaxavierGirvanusManurung) |
| Gilang Surya Agung          | 123140187 | [@15-187-GilangSuryaAgung](https://github.com/15-187-GilangSuryaAgung)                 |
| Muhammad Rafiq Ridho        | 123140197 | [@16-197-M-Rafiq-Ridho](https://github.com/16-197-M-Rafiq-Ridho)                       |

