# coffee-ranking

Coffee Ranking is an API in NestJS (using typescript and typeORM) in which it's possible to add coffee brands and rank them.

#### Users will be able to:
- Create requests for adding a new coffee to the database;
- Edit said requests;
- Cancel said requests;
- Vote on approved coffees;
- Write a review on approved coffees;

#### Admins will be able to:
- Add coffees to the database directly;
- Accept or refuse user requests;

#### Coffees include:
- A photo
- A name
- A description
- Rating (0 to 5 stars)
- Reviews[] // they work like comments, but unique per user
