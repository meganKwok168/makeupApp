Many people like using makeup, but an upcoming concern with cosmetic usage is the toxicity of mainstream makeup products.  People are turning to "natural" cosmetics but find that they aren't actually organic.

I'm going to build an app that scans a product/ingredient-label and gives the user the problems with the ingredients (with evidence) and recommends a professionally-reviewed natural recipe that will make a similar cosmetic product.

Tech stack list:
- flutter (for mobile app development)
- database: sql
- written in python
- APIs: Flask
- use EU CosIng for ingredient information


Milestone list:
1. create a list of popular mainstream makeup products (store by name, brand, category, ingredient list, image)
2. create flutter project and create home, search, and results screens
3. be able to pull from EU CosIng for ingredient information
4. use a text recognition tool & be able to identify ingredient-list section from extracted text
5. create product analysis results screen
6. find a DIY makeup recipes that covers the list from step 1
7. develop DIY recipe recommendation algorithm (pulls from step 6)
