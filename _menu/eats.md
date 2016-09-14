---
title: Eats
layout: menu
sidebar_order: 1
is_public: true
is_alcohol: false
subcategories:
  - name: Oysters
    items:
      - name: Oysters, Raw (6)
        description: Dozen Oysters $29
        price: 16.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Dozen Oysters +$13
            options: "No|Yes[+13.00]"
            required: false
      - name: Oysters, Grilled (6)
        description: Dozen Oysters $29
        price: 16.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Dozen Oysters +$13
            options: "No|Yes[+13.00]"
            required: false
      - name: Oysters, Fried (6)
        description: Dozen Oysters $29
        price: 16.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Dozen Oysters +$13
            options: "No|Yes[+13.00]"
            required: false
  - name: Bar Bites
    items:
      - name: Shrimp Cocktail (6)
        description: Jumbo shrimp, cocktail sauce, Old Bay Aioli and lemon. Dozen Shrimp $29
        price: 16.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Dozen Shrimp +$13
            options: "No|Yes[+13.00]"
            required: false
      - name: Fried Chicken Wings
        description: Sweet and Spicy sauce
        price: 6.00
        image_path:
        stackable: true
        orderable: true
      - name: Beer Cheese
        description: Fried garlic bread mops
        price: 8.00
        image_path:
        stackable: true
        orderable: true
      - name: Harlowe's Texas Toast
        description: Bone marrow, garlic, parmesan, parsley
        price: 4.00
        image_path:
        stackable: true
        orderable: true
      - name: Smokey Deviled Eggs
        description: “La Fin du Mustard”,  shallot, chives
        price: 4.00
        image_path:
        stackable: true
        orderable: true
  - name: Sides
    items:
      - name: Salt Brine Kennebec Fries
        description: With house ketchup
        price: 5.00
        image_path:
        stackable: true
        orderable: true
      - name: Garnet Yam Fries
        description: Soy caramel, ginger salt
        price: 5.00
        image_path:
        stackable: true
        orderable: true
      - name: Yukon Potato Salad
        description:
        price: 3.00
        image_path:
        stackable: true
        orderable: true
      - name: Red Cabbage or Blue Cheese Slaw
        description:
        price: 3.00
        image_path:
        stackable: true
        orderable: true
      - name: Fried Onions w/ BBQ Sauce
        description:
        price: 5.00
        image_path:
        stackable: true
        orderable: true
      - name: House Dill or B&B Pickles
        description:
        price: 2.00
        image_path:
        stackable: true
        orderable: true
  - name: Salads
    items:
      - name: Simple Greens
        description: House cut greens, cranberry, sunflower, almonds, grapes, white balsamic vinaigrette
        price: 9.00
        image_path:
        stackable: true
        orderable: true
      - name: Harlowe's Caesar
        description: House cut romaine, baby kale, fried croutons, reggiano, roasted garlic dressing
        price: 10.00
        image_path:
        stackable: true
        orderable: true
      - name: Marinated Tomatoes
        description: Red onions, cucumber, oregano, Valbreso feta, red wine vinaigrette
        price: 11.00
        image_path:
        stackable: true
        orderable: true
      - name: Little Gem Lettuce and Avocado
        description: Green Goddess, cured egg yolk, Shaft Bleu, North Country Bacon
        price: 12.00
        image_path:
        stackable: true
        orderable: true
  - name: The Dips
    items:
      - name: The Beef Dip
        description: Beef au jus, side horseradish, 4.5oz carve
        price: 9.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: 6oz carve +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: The Slow Roasted Pork Dip
        description: Smoked Ham au jus, “La Fin du Mustard”, 4.5oz carve
        price: 8.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: 6oz carve +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: The Turkey Dip
        description: Bacon-Turkey au jus, garlic parmesan butter, 4.5oz carve
        price: 8.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: 6oz carve +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: The Braised Lamb Dip
        description: Lamb au jus, House Labneh, 4.5oz carve
        price: 10.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: 6oz carve +$2
            options: "No|Yes[+2.00]"
            required: false
  - name: Burgers
    items:
      - name: Beef
        description: House-ground 5.5oz patty, served with lettuce, tomato, onion, House Pickles, Secret Sauce, sesame bun
        price: 10.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Meat cooked to
            options: "Rare|Medium-rare|Medium|Medium-well|Well"
            required: true
          - name: Add cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Turkey
        description: House-ground 5.5oz patty, served with lettuce, tomato, onion, House Pickles, Secret Sauce, sesame bun
        price: 9.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Veggie
        description: House-ground 5.5oz patty, served with lettuce, tomato, onion, House Pickles, Secret Sauce, sesame bun
        price: 8.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
  - name: Signatures
    items:
      - name: Slow Braised BBQ Short Rib
        description: Choice of slaw, BBQ sauce
        price: 12.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Pastrami
        description: Mustard, house pickle, rye. Add $2 for half lb.
        price: 12.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Pickle Brine Fried Chicken
        description: Coleslaw, buttermilk aioli, pickles, sesame bun
        price: 10.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Tomato Parmigiano
        description: Fried heirloom tomato, mozzarella, marinara, basil
        price: 9.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Shrimp Po' Boy
        description: Cajun fried shrimp, coleslaw, remoulade
        price: 13.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Harlowe's Grilled Cheese
        description: Ciabatta loaf, Harlowe’s American Cheese, sea salt
        price: 8.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Meatball Marinara
        description: House beef and pork blend, mozzarella, marinara
        price: 10.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Spaghetti and Meatballs
        description: Marinara sauce, Reggiano. Add meatball $2
        price: 10.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add meatball +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Pheasant Sausage
        description: Black lentils, corn poblano rajas
        price: 9.00
        image_path:
        stackable: true
        orderable: true
      - name: Bison Chili
        description: Onions, cheddar, sour cream, Texas Toast
        price: 12.00
        image_path:
        stackable: true
        orderable: true
  - name: Dessert
    items:
      - name: Beignets
        description: Cinnamon sugar, caramel and chocolate sauces
        price: 7.00
        image_path:
        stackable: true
        orderable: true
      - name: Chocolate Tort
        description: Black n blue sauce, maple whipped cream
        price: 7.00
        image_path:
        stackable: true
        orderable: true
      - name: Bread Pudding
        description: Vanilla bean gelato, salted caramel, candied hazelnuts
        price: 7.00
        image_path:
        stackable: true
        orderable: true
---
