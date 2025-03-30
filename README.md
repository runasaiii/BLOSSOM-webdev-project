💅 **Fashion Closet - Virtual Wardrobe**

Fashion Closet is a virtual wardrobe application designed to help users organize their clothing, create stylish outfits, and plan looks for different occasions. The app offers personalized outfit suggestions based on the weather or upcoming events.


💖 **Team Members**

Aruna Karagulova

Dariya Kapuzaeva

Nazerke Zheken


✨ **Features**

Frontend

Upload and manage clothing items with details such as category, style, color, and season.

Create and save outfits using selected clothing items.

Plan outfits based on dates and events with a built-in planner.

Filter clothing items by category, style, season, and color using [(ngModel)].

Interactive UI with OnClick events for adding, editing, and deleting items.

JWT-based authentication with user profiles.

Routing for seamless navigation.

Directives: ngFor, ngIf for dynamic rendering.

HTTP interceptor for token management.



Backend

Models:

User: Manages user profiles with JWT-based authentication.

ClothingItem: Represents clothing items with properties like name, photo, category, style, color, season, and owner.

Outfit: Combines clothing items into outfits, owned by users.

Planner: Plans outfits for specific dates or events.

CRUD operations for clothing items, outfits, and plans.

Token-based authentication with login and logout.

Serialization with at least 2 serializers using serializer.Serializer and 2 using serializer.ModelSerializer.

Two FBV DRF views (e.g., login and logout).

Two CBV APIViews for advanced functionality.

Association between models using ForeignKey and ManyToMany relationships.

Additional Features
Weather-based outfit recommendations.
Style tips and outfit suggestions.
Statistics to track clothing usage.
"Random Outfit" feature for spontaneous styling.
Social sharing options for outfits.
