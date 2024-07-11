# Serve with this command

npm run start

# To make TitleComponent standalone:

1. Add `standalone: true` to title.component.ts
2. Import it in AppModule

# To change from NgModules to standalone everything:

1. Make TitleComponent standalone
2. Make AppComponent standalone
3. Add app.config.ts with all the routes
4. Change main.ts to bootstrap AppComponent
5. Remove AppModule and AppRoutingModule
