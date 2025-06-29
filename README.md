# Slax

To start your Phoenix server:

  * Run `mix setup` to install and setup dependencies
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Commands

  * `docker-compose up -d`: Start Docker container
  * `mix setup`: Install and setup dependencies
  * `mix phx.server`: Start Phoenix endpoint
  * `iex -S mix phx.server`: Start Phoenix endpoint inside IEx
  * `mix phx.gen.schema {schema name} {database name} [columns {name:type}]`: Generate a schema
    * Eg: `mix phx.gen.schema Chat.Room rooms name:text topic:text`
  * `mix ecto.migrate`: Run database migrations
  * `mix ecto.rollback`: Rollback database migrations
  * `mix ecto.dump`: Dump database schema

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix
