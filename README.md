# 🍽️ IGiulia's Recipes in Cooklang

Welcome to my personal collection of **(mostly) Italian recipes** structured using [Cooklang](https://cooklang.org/)! This repository helps me organize, manage, and generate shopping lists for my favorite dishes.

## 📂 Folder Structure

This repository is structured by **recipe categories**:

```
.
├── Antipasti        # Starters
├── Beverages        # Drinks & Cocktails
├── Dolci            # Desserts
├── Piatti_unici     # One-dish meals
├── Primi            # Pasta & Risotto
├── Secondi          # Main courses (Meat, Fish, etc.)
├── meal-plans/      # Weekly meal plans (optional)
├── shopping-lists/  # Auto-generated shopping lists (optional)
├── images/          # Recipe images
│   ├── original-recipes  # Raw photos
│   └── results-recipes   # Final plated dishes
└── README.md        # This guide
```

---

## 🍳 How to Use These Recipes

### 🛠 Requirements
To make the most of these recipes, install **Cooklang CLI**:

```sh
# Install Cooklang CLI (if not already installed)
brew install cooklang/cook/cli  # macOS/Linux
scoop install cooklang-cli       # Windows
```

### 📚 Viewing Recipes
Each recipe is stored as a `.cook` file in **Cooklang format**. You can view them with:

```sh
cook read Antipasti/bruschetta.cook
```

### 🛍️ Generating a Shopping List
To create a shopping list from multiple recipes:

```sh
cook shopping-list Primi/carbonara.cook Secondi/ossobuco.cook
```

### 🗓️ Meal Planning
You can create **weekly meal plans** using `.cook` files in the `meal-plans/` folder.

Example:

```sh
cook plan meal-plans/week-1-meal-plan.cook
```

---

## 📝 Best Practices (from [Cooklang](https://cooklang.org/docs/best-practices/)

1. **Keep ingredient names consistent**  
   - Example: Use `@olive oil{2%tbsp}` instead of `@extra virgin olive oil`
  
2. **Use scalable portions**  
   - Write recipes to support different servings (e.g., `@spaghetti{100%g}` instead of `100g spaghetti`)

3. **Organize images**  
   - Store raw photos in `images/original-recipes/`  
   - Save final plated dishes in `images/results-recipes/`  

---

## 🐟 License

Feel free to use and modify these recipes for personal use! 🍕🍝
