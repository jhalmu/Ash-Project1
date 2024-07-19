# Elixir-Ash-Auth-Example
- Example Example app from Ash github-pages (working example there)

1. install Elixir, brew in mac is great
2. Install hex and installer following your choise of tutorial
3. Have Postgress. I use Postgress App 'cos that just works... in mac.
4. clone repo
5. mix gen.deps
6. Uh... actually tutorial where I copied commands is included as getting-started.md... I mean there you get commands to get postgress up
7. happy mix phx.server

- What else. I continue from here and hopefully get something I have wanted to do for a long time.  

===============================

It wasn't straightforward to get this work in codespace, but in the end this is quite normal ubuntu. Claude Sonnet 3.5 was very helpful, albait I did do litle googling too. 

- install with `asdf` newest erlang and elixir.
- install newer PostgresSQL to get new things to work
- create psql new role `codespace` with password and chanege `config.exs` credientals
- use `sudo su` when you need to use `sudo` commands. If you are asked `sudo` password

Well. I took while in here nightshift and I dont know id I dear to do anything else... or...



================================



# Example

To start your Phoenix server:

  * Run `mix setup` to install and setup dependencies
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix
