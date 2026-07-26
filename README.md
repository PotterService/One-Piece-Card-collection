# Bow One Piece Collection Manager — GitHub Pages v1

A no-install One Piece Card Game collection manager that runs entirely in the browser.

## Features

- Browse One Piece Card Game sets using OPTCG API
- View regular cards, parallel cards, and alternate artwork variants
- Card images, set IDs, rarity, color, type, and market pricing
- Track quantity, condition, language, purchase price, value, favorites, trade cards, and notes
- Wishlist
- Owned, missing, and parallel filters
- IndexedDB browser storage
- JSON backup export and import
- CSV export
- API response and image caching
- Mobile-friendly design
- Scanner page marked Work in Progress
- Basic PWA support

## GitHub Pages

1. Create a public GitHub repository.
2. Upload all files from this folder.
3. Open Settings → Pages.
4. Choose Deploy from a branch.
5. Select `main` and `/ (root)`.
6. Save.

No PHP, XAMPP, Composer, database server, account, or download is required.

## API usage

The OPTCG API is community-run and asks users not to make excessive requests.

This site reduces requests by:

- Caching the set list for 48 hours
- Caching each set's card data for 24 hours
- Caching loaded card images through the service worker
- Reusing cached data on repeat visits

## Storage

Collection information stays in each visitor's browser. Users should export backups regularly.

This project is not affiliated with or endorsed by Bandai, Eiichiro Oda, Shueisha, Toei Animation, or OPTCG API.
