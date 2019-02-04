# Mango

To start your Phoenix server:

* Install dependencies with `mix deps.get`
* Create and migrate your database with `mix ecto.create && mix ecto.migrate`
* Install Node.js dependencies with `cd assets && npm install`
* Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Run test

Test code requires a running instance of Phantomjs for the Acceptance tests. Run the following command on one of the terminal windows

```bash
phantomjs --wd
```

and in another terminal window, run the test

```bash
mix test
```
