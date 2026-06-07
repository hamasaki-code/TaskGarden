# TaskGarden

TaskGarden is a Ruby on Rails task management app that organizes tasks by genre
and visualizes completed work as a GitHub-style grass graph.

## Tech Stack

- Ruby 3.1.7
- Ruby on Rails 7.2
- PostgreSQL
- Tailwind CSS via `tailwindcss-rails`
- Hotwire with Turbo and Stimulus

## Setup

Install Ruby 3.1.7 and PostgreSQL before running the app.

```sh
bundle install
bin/rails db:create
bin/rails db:migrate
```

The default development database configuration uses the PostgreSQL role
`postgres` on `localhost`.

## Development

Run the Rails server and Tailwind watcher together:

```sh
bin/dev
```

Then open:

```txt
http://localhost:3000
```

## Test

Run the Rails test suite:

```sh
bin/rails test
```

## Documentation

Project requirements and implementation order are managed in `docs/`.

- `docs/requirements.md`
- `docs/design.md`
- `docs/implementation-rules.md`
- `docs/issues.md`
