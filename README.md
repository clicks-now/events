# clicks — events

Event records, host packages, and post-mortems for Clicks — a city-wide partner meetup series for the Shopify ecosystem.

## Structure

```
events/
  host-package/          # Everything a host needs to run a Clicks event
    README.md            # Host package overview
    run-of-show.md       # Run-of-show template
  cities/                # One folder per city, one subfolder per event
    toronto/
      2026-05/
        post-mortem.md
  templates/
    post-mortem.md       # Post-mortem template
```

## Running an event in your city

1. Read the [host package](./host-package/README.md)
2. Open an issue using the Event Proposal template
3. Run the event
4. Submit a post-mortem PR to `cities/your-city/YYYY-MM/`

## License

[CC BY 4.0](./LICENSE) — use it, fork it, share it.
