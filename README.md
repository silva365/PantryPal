# PantyPal

PantryPal
Your kitchen, intelligently organized. Scan groceries. Track freshness. Discover meals. Shop smarter.

A clickable product prototype for an AI-powered, mobile-first kitchen app (iOS + Android). Open index.html in a browser. No build step.

Screens
Home Dashboard: pantry totals, items needing attention, suggested meals, and a prominent Scan Groceries action.
My Kitchen: inventory by fridge, freezer, pantry and custom locations. Search, edit quantities, adjust dates.
AI Scanner: photograph groceries, scan a barcode, import a receipt, or add manually. Every scan ends in a review screen.
Cook With What I Have: recipes ranked by available ingredients, dietary preferences, time, and items to use soon.
Shopping List: missing ingredients, recurring essentials and household needs. Purchased items can be added to inventory.
Principles
Human confirmation is part of scanning. A model can recognize a carton of eggs but can't count the eggs inside or read an unreadable date. The scanner suggests; the user confirms before anything is saved.
Scanning is optional. Manual entry and barcode scanning are always available.
Freshness uses recorded dates and general guidance. The app never claims a photo proves food is safe.
Meal images are labelled as AI-generated serving suggestions, never shown as photos of the user's food.
AI features
Feature	Release
Grocery photo recognition	MVP
Receipt scanning	MVP
Personalized recipe generation	MVP
AI meal images	Proposed
Freshness intelligence	Second release
AI meal planning	Later
About the prototype
The camera, AI results and barcode lookups use sample data. Changes are saved in the browser's local storage. Only the salmon meal image is a real AI-generated image (img/salmon.jpg); the others are drawn placeholders. Image prompts for the remaining meals are in the page's "Meal image style" section.
