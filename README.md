## Website Parts 

1. Import Views 
    - Front: Home, Movies , Movie Details, TV Shows 
    - Dashboard: Home, CRUD Movies , CRUD Categories
    - Admin Auth: Login Only

2. Models & Migrations 
    - Migrations: Movies, Categories, TV Shows
      NOTE: By default ASP Has tables for Auth (Admin)  
    - Models: Movie, Category, TvShow, Admin 

3. Controllers 
    - CRUD Movies (Admin Only)
    - CRUD Categories (Admin Only)
    - FrontController (Responsible for the front-end pages)
      - HomePage() 
      - MoviesPage() 
      - MoviePage(movie_id)
      - ShowsPage() 
      - ShowPage(show_id) 

**We HAVE to mesure this arch agains SOLID Principles**

## Tools & API Used 
1. Disqus For Comments 
2. Google Analytics 
3. Valid Admin Dahsboard Template 
