---
title: Eats
layout: menu
sidebar_order: 1
is_public: true
is_alcohol: false
is_breakfast: false
subcategories:
  - name: The Dips
    items:
      - name: The Roast Beef Dip
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
        price: 11.00
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
        description: Proprietary Blend of chuck, short rib, and brisket. 7oz patties. Served with lettuce, tomato, onion, House Pickles, Secret Sauce, sesame bun. Add Cheese +$1. House American, Swiss, cheddar, bleu. Add Bacon, Avocado, Fried Egg +$2 each.
        price: 11.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Meat cooked to
            options: "Rare|Medium-rare|Medium|Medium-well|Well"
            required: true
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
          - name: Add North Country Bacon +$2
            options: "No|Yes[+2.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
          - name: Add fried egg +$2
            options: "No|Yes[+2.00]"
            required: false
      - name: Portobello Mushroom
        description: Served with lettuce, tomato, onion, House Pickles, Secret Sauce, sesame bun. Add Cheese +$1. House American, Swiss, cheddar, bleu. Add Bacon, Avocado, Fried Egg +$2 each.
        price: 9.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
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
          - name: Add North Country Bacon +$2
            options: "No|Yes[+2.00]"
            required: false
          - name: Add 1/2 avocado +$2
            options: "No|Yes[+2.00]"
            required: false
          - name: Add fried egg +$2
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
      - name: Filet O' Today
        description: Crispy catfish, tartar sauce, lettuce, tomato, red onion
        price: 11.00
        image_path:
        stackable: true
        orderable: true
      - name: Andy's PBLT
        description: Pork belly, lettuce, tomato
        price: 10.00
        image_path:
        stackable: true
        orderable: true
      - name: Spaghetti & Meatballs
        description: Fresh pasta, reggiano, marinara
        price: 15.00
        image_path:
        stackable: true
        orderable: true
      - name: Scottish Organic Salmon
        description: Baby summer squashes, tomato relish
        price: 19.00
        image_path:
        stackable: true
        orderable: true
      - name: Flat Iron Pub Steak
        description: Sautéed spinach, salt brine fries. (8 oz. Prime)
        price: 21.00
        image_path:
        stackable: true
        orderable: true
      - name: 1/2 Rack Baby Back Ribs
        description: Corn, Slaw, Potato Salad
        price: 23.00
        image_path:
        stackable: true
        orderable: true
  - name: Salads
    items:
      - name: Simple Greens
        description: House cut greens, cranberry, sunflower, almonds, grapes, Point Reyes bleu cheese, balsamic vinaigrette. Whole portion +$5
        price: 4.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Whole portion +$5
            options: "No|Yes[+5.00]"
            required: false
      - name: Harlowe's Caesar
        description: House cut romaine, fried croutons, reggiano, roasted garlic Caesar dressing. Whole portion +$6
        price: 4.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Whole portion +$6
            options: "No|Yes[+6.00]"
            required: false
      - name: Japanese Tomatoes
        description: White miso dressing, green onions, watermelon togarashi croutons, shisho
        price: 11.00
        image_path:
        stackable: true
        orderable: true
      - name: "Wedgie"
        description: Bacon, avocado, tomato, blue cheese, green onion, roasted garlic
        price: 12.00
        image_path:
        stackable: true
        orderable: true
  - name: Oysters
    items:
      - name: Oysters of the Day (half-dozen)
        description: Dozen Oysters $28
        price: 15.00
        image_path:
        stackable: false
        orderable: true
        custom_fields:
          - name: Dozen Oysters +$13
            options: "No|Yes[+13.00]"
            required: false
  - name: Bar Bites
    items:
      - name: Roasted Eggplant Dip
        description: Grilled flatbread, EVOO, Aleppo chili flake
        price: 6.00
        image_path:
        stackable: true
        orderable: true
      - name: Maryland Crispy Calamari
        description: House tartar sauce, lemon
        price: 9.00
        image_path:
        stackable: true
        orderable: true
      - name: Fried Chicken Drumsticks
        description: Buttermilk aioli, soy apricot sauce
        price: 6.00
        image_path:
        stackable: true
        orderable: true
      - name: Grilled Corn on the Cob
        description: Mayo, cotija, lime, chipotle flake
        price: 5.00
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
        description: “La Fin du Mustard”, shallot, chives
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
      - name: Little Donuts
        description: Cinnamon sugar, caramel sauce
        price: 6.00
        image_path:
        stackable: true
        orderable: true
      - name: Bread Pudding
        description: Vanilla ice cream, caramel sauce, hazelnuts
        price: 6.00
        image_path:
        stackable: true
        orderable: true
      - name: Harlowe's Brownie Sundae
        description: Chocolate sauce, peanuts, bourbon cherries, ice cream
        price: 6.00
        image_path:
        stackable: true
        orderable: true
---
