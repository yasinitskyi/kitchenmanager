# kitchenmanager
Kitchen manager

## Requirements
### System
- Keep track of groceries at home
- Add, modify, and delete recipes
  - Recipes have:
    - ingredients ("groceries") and amounts ("units"?)
    - instructions
    - comments (心得)
- Look up what recipes can be made using the groceries at home
- Generate a shopping list based on a set of recipes (which groceries need to be purchased if we want to complete a given set of recipes)
- Support multiple users (multiple people can log into the same server)
- Support multiple kitchens (multiple users can share a kitchen)
  - Kitchens have:
    - groceries
    - recipes
    - one head chef (主廚)
    - many sous chefs (副主廚)
- Simple kitchen-based permission scheme (everyone belonging to a kitchen can do anything in that kitchen)
  - head chef can add or remove sous chefs to a kitchen
  - sous chefs can do everything head chefs can do, except add or remove other chefs

### Interface
- Desktop browser support
- Mobile browser support
- Advanced features:
  - support simultaneous editing + autosave
  - push notifications
- UI
  - tabbed approach?
  - react (for v1?)
  - typescript?
