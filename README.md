<p align="center">
  <img src="https://raw.githubusercontent.com/0vergrown/Origins-Dietary-Delights/main/pack.png" alt="Dietary Delights cover"/>
</p>

# Dietary Delights
**Dietary Delights** extends and refines the functionality of LuaDotExe's "We Have the Meats" by expanding compatibility between the Origins mod and a comprehensive list of other food-related mods. This pack introduces detailed item tags for various diets, facilitating the creation of unique Origin traits based on dietary preferences and restrictions.
## Target Audience
This pack is designed primarily for developers looking to enhance or create custom Origins with specific dietary needs. It is also beneficial for those in the modding community looking to standardize dietary tags across various mods.
## Key Features
- **Expanded Meat Category:** Incorporates modded items into the 'meat' category, ensuring compatibility with Origins’ dietary systems.
- **New Dietary Tags:** Introduces categories like **Ketogenic**, **Organic**, **Vegan**, **Pescatarian**, and **Vegetarian**, allowing for the creation of Origins with unique dietary-based abilities or restrictions.
## Supported Mods
Dietary Delights works with the following mods:

01. (Let's Do) Bakery  
02. (Let's Do) Beachparty  
03. (Let's Do) Brewery  
04. (Let's Do) Candlelight  
05. (Let's Do) Farm & Charm  
06. (Let's Do) Meadow  
07. (Let's Do) Vinery  
08. AdventureZ  
09. Aether Delight  
10. Alaska Native Craft  
11. Anthropophagy  
12. Aquaculture Delight  
13. Ars Nouveau  
14. Autovw's Burger Mod/Burger Mod Fabricated  
15. Better Animals Plus  
16. Better Nether  
17. Biome Makeover  
18. Born In Chaos  
19. Bountiful Fares  
20. Brewin' And Chewin'  
21. Chest Cavity  
22. Chirpy's Wildlife  
23. Corn Delight  
24. Croptopia  
25. Cultural Delights  
26. Deep Aether  
27. Delightful  
28. Ecologics  
29. End's Delight  
30. End's Phantasm  
31. Ender's Delight  
32. Expanded Delight  
33. Farmer's Delight  
34. Farmer's Respite  
35. Fish of Thieves  
36. Food+  
37. Galosphere  
38. Golden Steak  
39. Immersive Weathering  
40. Jellyfishing  
41. Kentucky Fried Axolotls (KFA)  
42. Midas Hunger  
43. Naturalist  
44. Nears  
45. Nether Additions  
46. Nether Depths Upgrade  
47. Nether's Delight  
48. Ocean's Delight  
49. Pam's HarvestCraft 2 - Food Core  
50. Promenade  
51. Quality Crops  
52. Quality's Delight  
53. Rotten Leather  
54. Silent's Delight  
55. Snowpig  
56. Spawn  
57. Spit Splat  
58. The Aether  
59. The Aether: Redux  
60. Twilight Forest  
61. Twilight's Flavors & Delight  
62. Turkish Delight  
63. Unusual Delight (Hostile Delight)  
64. Unusual Fish Mod  
65. ValleyCraft  
66. Vampire's Delight  
67. Vampirism  
68. Vegan Delight  
69. Vietnam's Delight  
70. You've Goat to be Kidding Me
71. More Delight
72. Crabber's Delight
73. My Nether's Delight (Meat Tag Only)
## Implementation Guide
### Specific Dietary Tag
To apply a specific dietary tag, such as Pescatarian, use the following JSON structure:
```json
"item_condition": {
    "type": "origins:ingredient",
    "ingredient": {
        "tag": "origins:pescatarian"
    }
}
```
This setup ensures that the Origin can utilize only items tagged as Pescatarian.
### General Meat Category
For Origins designed to consume any type of meat, the simplified `origins:meat` tag can be utilized:
```json
"item_condition": {
    "type": "origins:meat"
}
```
This configuration allows the Origin to use any item classified under the expanded Meat category.
### Organic Tag
The `organic` tag has been broadly defined to encompass all possible items from supported mods plus vanilla foods, aligning with the literal definition of "organic" in a non-chemical context in Minecraft.
