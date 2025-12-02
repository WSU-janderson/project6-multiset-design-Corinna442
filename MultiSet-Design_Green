# MultiSet Design

**Corinna Green**
CS-3100-01
12/5/2025

## Introduction
- My design models an enemy loot table where certain items drop when the enemy is killed. 
- There will be different items along with quantities per each. 
- The items will be classified as strings and built atop HashTable<string, unsigned int>.

## Design Philosophy
### Qualities of Design
- **Efficiency:** Finding items must be fast during gameplay, preferring O(1) time complexity for inserting, removing, or looking for an item.
- **Simplicity:** Interface should be easy for other game code accessibility, such as other methods/classes interworking like getters, setters, addItem(), removeItem(), etc.
- **Extensibility:** Interface/other design choices should allow extensions to be added/incorporated easily for future features.
- **Readability:** Code should be organized clearly so that developers can easily understand how the structure works without needing to know the inner workings of hashing.
### Identify the Client
- The client will be the **game system** responsible for generating enemy-dropped-items
- The users are **other developers** responsible for calling functions from the MultiSet to change or get item quantities.

## Core Operations
