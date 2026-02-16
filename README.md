# Product Images

This repository contains product images for an e-commerce dataset.

## Structure

Images are organized by category group and subcategory:

```
├── WomensClothing/
│   ├── dresses/
│   ├── tops/
│   ├── ethnic-dresses/
│   └── ... (17 subcategories)
├── MensClothing/
│   ├── sherwani/
│   └── ... (4 subcategories)
├── UnisexClothing/
│   ├── shirts/
│   ├── jeans/
│   └── ... (11 subcategories)
├── Footwear/
│   ├── sports-shoes/
│   └── ... (8 subcategories)
├── BagsAndWallets/
├── Jewelry/
├── WatchesAndEyewear/
├── BeautyAndPersonalCare/
├── FashionAccessories/
├── HomeAndLiving/
├── Electronics/
└── SportsAndFitness/
```

## Category Groups

| Group | Subcategories | Products |
|-------|---------------|----------|
| WomensClothing | 17 | 349 |
| UnisexClothing | 11 | 307 |
| Footwear | 8 | 119 |
| Jewelry | 3 | 38 |
| BagsAndWallets | 7 | 34 |
| HomeAndLiving | 16 | 32 |
| BeautyAndPersonalCare | 11 | 15 |
| WatchesAndEyewear | 2 | 14 |
| MensClothing | 4 | 9 |
| FashionAccessories | 4 | 7 |
| Electronics | 2 | 4 |
| SportsAndFitness | 1 | 1 |

## Usage

Images are hosted via GitHub Pages and can be accessed at:

```
https://pazhanir.github.io/product-images/{category_group}/{subcategory}/{product_id}_{image_number}.jpg
```

Example:
```
https://pazhanir.github.io/product-images/WomensClothing/dresses/21664722_1.jpg
```

## Dataset

The `product_datasets.csv` file contains product information with the following columns:
- `category_group` - Main category group (e.g., WomensClothing, Footwear)
- `subcategory` - Specific product category (e.g., dresses, sports-shoes)
- `github_images` - GitHub Pages URLs for product images

## Statistics

- **Total Products:** 929
- **Total Images:** 5,322
- **Category Groups:** 12
- **Subcategories:** 86
