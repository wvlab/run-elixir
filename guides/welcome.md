# Welcome to Elixir!

[Elixir](https://elixir-lang.org) is a dynamic, functional programming language created by [José Valim](https://github.com/josevalim). It is great for building scalable and maintainable applications. It puts the FUN into **FUN**ctional programming! This guide will walk you through its basics in less than 30 minutes.

*This guide was written by [Peter Ullrich](https://peterullrich.com). Please submit any comments on [GitHub](https://github.com/PJUllrich/run-elixir/discussions). If you want to support me, please consider buying my courses ([one](https://indiecourses.com/catalog/build-an-mvp-with-elixir-6i4V9yOqLL54GuG0HkV9HR) and [two](https://indiecourses.com/catalog/building-forms-with-phoenix-liveview-2OPYIqaekkZwrpgLUZOyZV)) or my [book](https://pragprog.com/titles/puphoe/building-table-views-with-phoenix-liveview/) 💜.*

## Install Elixir

Let's first install Elixir and Erlang. You can find instructions in the [official installation guide](https://elixir-lang.org/install.html).

However, a fast way to install the language on `macOS` and `linux` is to use the [asdf](https://asdf-vm.com/) version manager:

```bash
# Install the elixir and erlang plugins
asdf plugin add elixir
asdf plugin add erlang

# Now install erlang
asdf install erlang latest
asdf set -u erlang latest

# And Elixir
asdf install elixir latest
asdf set -u elixir latest

# You can check that Elixir is installed with:
elixir -v
```

## Run the Code

If you want to run the following code yourself, there are three options:

1. **Recommended**: Install [Livebook](https://livebook.dev/) (see the link for instructions) and simply click the `Run in Livebook` button above each file to open it in an interactive notebook. The files will open on your local computer.
1. Start an Elixir REPL with `iex` and copy and paste the code into the command line.
1. Copy and paste the code into an Elixir script file, like `script.exs`, and run `mix run script.exs`.

## Let's begin!

> #### Tip {: .tip}
>
> You can navigate through the pages with the `left` and `right` arrow

Let's begin: [Learn how to write 'Hello World'](guides/01-basics/hello-world.livemd)
