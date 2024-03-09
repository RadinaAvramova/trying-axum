# trying-axum

## Requirements

Rust and `sqlx` (`cargo install sql`)

## How to run

Clone the repo and then execute

```bash
export DATABASE_URL="sqlite:data.db"
sqlx db create
cargo run
```

You should now have the server running locally at [localhost:3000](http://localhost:3000).

## Endpoints

The endpoints developed for now are:

- `POST /note`: create a new note (based on the string passed as body payload)
- `GET /note/:id`: gets a note by ID

