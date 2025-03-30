💅 **Fashion Closet - Virtual Wardrobe**

Fashion Closet is a virtual wardrobe application designed to help users organize their clothing, create stylish outfits, and plan looks for different occasions. The app offers personalized outfit suggestions based on the weather or upcoming events.


💖 **Team Members**

Aruna Karagulova

Dariya Kapuzaeva

Nazerke Zheken



✨ **Features**  

### **Frontend**
- Manage clothing items with details (category, style, color, season).  
- Create and save outfits, plan looks for specific dates and events.  
- Filter items by category, style, season, and color.  
- Interactive UI with click events for adding, editing, and deleting.  
- JWT authentication and user profiles.  
- Seamless navigation with routing and dynamic rendering using ngFor, ngIf.  
- HTTP interceptor for token management.  

---

**Backend**
- **Models:**  
  - **User:** Manages profiles with JWT authentication.  
  - **ClothingItem:** Stores clothing details.  
  - **Outfit:** Combines items into looks.  
  - **Planner:** Plans outfits for events.  
- CRUD for clothing items, outfits, and plans.  
- Token-based authentication for login/logout.  
- Serialization with DRF (using Serializer and ModelSerializer).  
- Two FBV views (e.g., login, logout) and two CBV APIViews.  
- Relationships with ForeignKey and ManyToMany.  

**Additional Features**
- Weather-based outfit suggestions.  
- Style tips and outfit recommendations.  
- Usage statistics and a "Random Outfit" feature.  
- Social sharing options.  
