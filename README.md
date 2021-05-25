# Discuss

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Install Node.js dependencies with `npm install` inside the `assets` directory
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.


## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix


# Landing Page that lists all topics, with out signing in the user can only view and comment on topics

<img src="https://i.imgur.com/K3oM4nz.png" alt="landing page with user signed out" />


# Landing Page that lists all topics, only the user that created a topic has the option to edit or delete a topic

<img src="https://i.imgur.com/gXpnPLB.png" alt="landing page with user signed in" />

# When a single topic is clicked the user will be brought to the topic page which uses websockets to update the comments in real time.

<img src="https://i.imgur.com/ecAXheD.png" alt="topic page with comments" />

# The user that created a topic can edit the title of the topic when signed in

<img src="https://i.imgur.com/Gw0SbDB.png" alt="topic edit page" />

# Users that are not signed in can still interact with the website, they're comments will just show "Anonymous" as the author.

<img src="https://i.imgur.com/Gw0SbDB.png" alt="signed out user commenting on post" />
