# AngularCliToMigrate

npx nx@latest init => project.json is created
npx nx init --integrated => (apps + libs folder; hence monorepo)

new:
npx create-nx-workspace@latest =>

- standalone
- integrated monorepo

# Use Nx cli

npx nx serve
npx nx build
npx nx test --watch=false

- if you invoke the build or test command multiple times, without changing code, nx caching comes in to play and is fast
