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

<del>It wasn't straightforward to get this work in codespace, but in the end this is quite normal ubuntu. Claude Sonnet 3.5 was very helpful, albait I did do litle googling too. 

<del>- install with `asdf` newest erlang and elixir.
<del>- install newer PostgresSQL to get new things to work
<del>- create psql new role `codespace` with password and chanege `config.exs` credientals
<del>- use `sudo su` when you need to use `sudo` commands. If you are asked `sudo` password

Those above is commands I did when I used this platform more like normal server... well ofcourse what I did did not last... 

Next night I RTFM and used what devcontainer-plugins gave me like elixir, erlang, postgresql. Some trial and errors there, but I got elixir via `asdf`. And postgress. With postgres I next time try code that installs that via `apt`. Only problem is that in codespace there is now only version 12 to be installed (in this ubuntu/debian image?) so one have to install repo for newer packages. If you install postgress via asdf, you have to init it self to working order and put it to `service`. From `apt` it does that automatically. Well it was good to know how to do that, so it was this time good learning. Also that learn difference with systemctl and service. 

Now (next night) we try if I can start the program... yes. Lets examine code. Last night there were fails in githubs CI -prosess and also `mix test` did not pass.


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
