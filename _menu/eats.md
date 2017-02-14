---
title: Eats
layout: menu
sidebar_order: 1
is_public: true
is_alcohol: false
subcategories:
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
  - name: The Burger
    items:
      - name: Single Patty
        description: Proprietary Blend of chuck, short rib, and brisket. 5.5oz patties. Served with lettuce, tomato, onion, House Pickles, Secret Sauce, sesame bun. Add cheese +$1. Veggie patty available upon request
        price: 10.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Meat cooked to
            options: "Rare|Medium-rare|Medium|Medium-well|Well"
            required: true
          - name: Substitute Veggie Patty
            options: "No|Yes"
            required: false
          - name: Add House American Cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add Swiss Cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add cheddar cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add bleu cheese +$1
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
        description: Red cabbage slaw, BBQ sauce
        price: 12.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Pastrami
        description: Mustard, house pickle, rye bread. Add $2 for half lb. Add $1 for Swiss Cheese
        price: 12.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Half-lb carve +$2
            options: "No|Yes[+2.00]"
            required: false
          - name: Add Swiss Cheese +$1
            options: "No|Yes[+1.00]"
            required: false
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Pickle Brine Fried Chicken
        description: Coleslaw, buttermilk aioli, pickles, tomato, sesame bun
        price: 10.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Fried Green Tomato
        description: Marinara, eggplant caponata, mozzarella
        price: 9.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
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
          - name: Add North Country Bacon +$3
            options: "No|Yes[+3.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Spaghetti and Meatballs
        description: Marinara sauce, Reggiano. Add extra meatball $2
        price: 10.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Add meatball +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Bison Chili
        description: Onions, cheddar, sour cream, Texas Toast
        price: 12.00
        image_path:
        stackable: true
        orderable: true      
  - name: Salads
    items:
      - name: Simple Greens (half portion)
        description: House cut greens, cranberry, sunflower, almonds, grapes, reggiano, white balsamic vinaigrette. Whole portion +$5
        price: 4.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Whole portion +$5
            options: "No|Yes[+5.00]"
            required: false
      - name: Harlowe's Caesar (half portion)
        description: House cut romaine, baby kale, fried croutons, reggiano, roasted garlic Caesar dressing. Whole portion +$6
        price: 4.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Whole portion +$6
            options: "No|Yes[+6.00]"
            required: false
      - name: Beet Salad
        description: Oranges, French Feta, pistachio, shallot
        price: 11.00
        image_path:
        stackable: true
        orderable: true
      - name: Little Gem "Cobb"
        description: Bleu cheese, bacon, avocado, egg, tomato, red onion, Green Goddess dressing
        price: 12.00
        image_path:
        stackable: true
        orderable: true
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
      - name: Shrimp Cocktail
        description: House Cocktail Sauce, cucumber, red onion, avocado
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
        description: House ketchup
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
      - name: Red Cabbage Slaw
        description:
        price: 3.00
        image_path:
        stackable: true
        orderable: true
      - name: Bleu Cheese Slaw
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
      - name: House Dill Pickles
        description:
        price: 2.00
        image_path:
        stackable: true
        orderable: true
      - name: Bread & Butter Pickles
        description:
        price: 2.00
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
      - name: Bread Pudding
        description: Vanilla bean gelato, salted caramel, candied hazelnuts
        price: 7.00
        image_path:
        stackable: true
        orderable: true
      - name: Chocolate Tort
        description: Black n Blue sauce, maple whipped cream
        price: 7.00
        image_path:
        stackable: true
        orderable: true
---
