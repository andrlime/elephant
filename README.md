## Contributing
Fork from the `dev` branch only. Merges to `main` are pushes to prod, which for now will not happen for a while.

## Tech used
Python, Taskfile, Poetry

## Poetry Usage for This Package
When using this package at all:
`poetry shell`
Run `deactivate` when context switching.

After cloning locally: `task init`

Build file x:
`poetry build x`

Run tests:
`task test`

Add new package:
`poetry add <pip-dependency>`
