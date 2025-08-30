# Recipe App Implementation Plan

## Overview

A recipe app with the following pages and features:

- Home page (`/`)
- Ingredients page (`/ingredients`)
  - Add ingredient (`/ingredients/add`)
  - Edit ingredient (`/ingredients/edit/[id]`)
- Recipes page (`/recipes`)
  - Add recipe (`/recipes/add`)
  - Edit recipe (`/recipes/edit/[id]`)
  - Recipe detail (`/recipes/[id]`)

## Tech Stack

- Next.js App Router
- shadcn/ui
- Aceternity UI
- Tailwind CSS (and other CSS libraries as needed)

---

## Pages & Routes

### Home Page (`/`)
- Hero section (Aceternity UI)
- Navigation bar (shadcn/ui or custom)
- Links to Recipes and Ingredients

### Ingredients

- **List Page** (`/ingredients`)
  - List all ingredients
  - Actions: Add, Edit, Delete

- **Add Ingredient** (`/ingredients/add`)
  - Form to add new ingredient (shadcn/ui form components)

- **Edit Ingredient** (`/ingredients/edit/[id]`)
  - Form prefilled with ingredient data

### Recipes

- **List Page** (`/recipes`)
  - List all recipes
  - Actions: Add, Edit, Delete, View

- **Add Recipe** (`/recipes/add`)
  - Form to add new recipe (shadcn/ui form components)

- **Edit Recipe** (`/recipes/edit/[id]`)
  - Form prefilled with recipe data

- **Recipe Detail** (`/recipes/[id]`)
  - Show recipe details, ingredients, instructions

---

## Components

- Navbar
- HeroSection (Aceternity UI)
- RecipeCard
- IngredientCard
- Forms (shadcn/ui)
- Modals/Dialogs (shadcn/ui)

---

## Data

- Ingredient model: id, name, quantity, unit, etc.
- Recipe model: id, name, description, ingredients[], instructions, etc.

---

## Tasks

1. Set up Next.js App Router structure
2. Create shared UI components (Navbar, HeroSection, etc.)
3. Implement Ingredients pages and forms
4. Implement Recipes pages and forms
5. Connect forms to data (local state, API, or database)
6. Add styling using shadcn/ui, Aceternity UI, and Tailwind CSS
7. Add navigation and routing
8. Test all flows (add, edit, view, delete)
9. Polish UI/UX

---

## References

- [Next.js App Router Documentation](https://nextjs.org/docs/app)
- [shadcn/ui Documentation](https://ui.shadcn.com/)
- [Aceternity UI](https://ui.aceternity.com/)