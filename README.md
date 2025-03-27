# Home System Server

A docker compose configuration consisting of services I like.

## Configuration

### .env

I've provided an example with all recommended variables at `/.env.example`

### Nextcloud

#### `config.php`

-   `‘filesystem_check_changes’ => 1` so changes to user files are detected
