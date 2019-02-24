# cne


# 環境構築

```
docker-compose build
docker-compose run --rm client /bin/bash  
docker-compose run --rm server /bin/bash  
```

# client

```
get started:
    npm run dev

To build & start for production:
    npm run build
    npm start
```

# server
https://elixirschool.com/ja/lessons/basics/basics/

```
We are almost there! The following steps are missing:

    $ cd hello
    $ cd assets && npm install && node node_modules/webpack/bin/webpack.js --mode development

Then configure your database in config/dev.exs and run:

    $ mix ecto.create

Start your Phoenix app with:

    $ mix phx.server

You can also run your app inside IEx (Interactive Elixir) as:

    $ iex -S mix phx.server
```