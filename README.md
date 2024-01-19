# AngularCliToMigrate

npx nx@latest init => project.json is created
npx nx init --integrated => (apps + libs folder; hence monorepo)

new:
npx create-nx-workspace@latest =>

- package based (not an option anymore?) => pure repo, do what you want
- standalone => contains all nx features, but is not a monorepo, useful for building single apps
- integrated monorepo => preconfigured open for multiple apps and libs
- migration: migrate existing app to nx

# Use Nx cli

npx nx serve
npx nx build
npx nx test --watch=false

- if you invoke the build or test command multiple times, without changing code, nx caching comes in to play and is fast

# create apps or libs

nx g @nx/angular:app appName
nx g @nx/angular:lib libName
