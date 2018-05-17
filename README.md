# Tus.Cache.Redis

A plugin for the Tus https://hex.pm/packages/tus server.
Provides a cache backend based on Redis.


## Installation

The package can be installed by adding `tus_cache_redis` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:tus, "~> 0.1.0"},
    {:tus_cache_redis, "~> 0.1.0"},
  ]
end
```

## Configuration

- `cache`:
	Set it as `Tus.Cache.Redis`.

- `redis_host`:
	Optional.

- `redis_port`:
	Optional. 
